# Function: <code>migration_entry_to_page</code>

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
In mm/memory.c (ffffffff811bdae8)
Location: include/linux/swapops.h:122
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/migrate.c (ffffffff811f0cda)
Location: include/linux/swapops.h:122
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:__migration_entry_wait
```
```
In fs/proc/task_mmu.c (ffffffff81278194)
Location: include/linux/swapops.h:122
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/memory.c (ffffffff811d908a)
Location: include/linux/swapops.h:122
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/migrate.c (ffffffff81211832)
Location: include/linux/swapops.h:122
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In fs/proc/task_mmu.c (ffffffff812a5033)
Location: include/linux/swapops.h:122
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/memory.c (ffffffff811e8523)
Location: include/linux/swapops.h:122
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/page_vma_mapped.c (ffffffff811f6c77)
Location: include/linux/swapops.h:122
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/migrate.c (ffffffff812239f2)
Location: include/linux/swapops.h:122
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In fs/proc/task_mmu.c (ffffffff812ba998)
Location: include/linux/swapops.h:122
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/memory.c (ffffffff811f76b5)
Location: include/linux/swapops.h:122
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/page_vma_mapped.c (ffffffff81201b57)
Location: include/linux/swapops.h:122
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/migrate.c (ffffffff8122f352)
Location: include/linux/swapops.h:122
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In fs/proc/task_mmu.c (ffffffff812c86e4)
Location: include/linux/swapops.h:122
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/memory.c (ffffffff8120a95f)
Location: include/linux/swapops.h:207
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff8121ad12)
Location: include/linux/swapops.h:207
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/migrate.c (ffffffff8124cf2c)
Location: include/linux/swapops.h:207
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In fs/proc/task_mmu.c (ffffffff812ec533)
Location: include/linux/swapops.h:207
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/memory.c (ffffffff8122b7e8)
Location: include/linux/swapops.h:207
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff8123cb43)
Location: include/linux/swapops.h:207
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/migrate.c (ffffffff81270a31)
Location: include/linux/swapops.h:207
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In fs/proc/task_mmu.c (ffffffff81319b74)
Location: include/linux/swapops.h:207
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/memory.c (ffffffff8123ebb0)
Location: include/linux/swapops.h:203
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81251019)
Location: include/linux/swapops.h:203
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/migrate.c (ffffffff81285051)
Location: include/linux/swapops.h:203
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In fs/proc/task_mmu.c (ffffffff81330c4d)
Location: include/linux/swapops.h:203
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/memory.c (ffffffff8125092e)
Location: include/linux/swapops.h:188
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81263305)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/migrate.c (ffffffff8129f6c0)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In fs/proc/task_mmu.c (ffffffff81358a6e)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/memory.c (ffffffff8125eede)
Location: include/linux/swapops.h:188
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81271ab5)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/migrate.c (ffffffff812b0a60)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In fs/proc/task_mmu.c (ffffffff81370cbe)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/memory.c (ffffffff8128fb66)
Location: include/linux/swapops.h:190
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_one_pte
  - mm/memory.c:copy_one_pte
```
```
In mm/page_vma_mapped.c (ffffffff812a20e8)
Location: include/linux/swapops.h:190
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/migrate.c (ffffffff812e6ba0)
Location: include/linux/swapops.h:190
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In fs/proc/task_mmu.c (ffffffff813b875d)
Location: include/linux/swapops.h:190
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/memory.c (ffffffff8129a42b)
Location: include/linux/swapops.h:190
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812ada2d)
Location: include/linux/swapops.h:190
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/migrate.c (ffffffff812f1ef0)
Location: include/linux/swapops.h:190
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In fs/proc/task_mmu.c (ffffffff813ca18d)
Location: include/linux/swapops.h:190
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/memory.c (ffffffff8129f62e)
Location: include/linux/swapops.h:197
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812b2eae)
Location: include/linux/swapops.h:197
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/migrate.c (ffffffff812f822b)
Location: include/linux/swapops.h:197
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812fb992)
Location: include/linux/swapops.h:197
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813d0d6f)
Location: include/linux/swapops.h:197
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
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
In mm/memory.c (ffff8000102f7058)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/swapops.h:188
Inline: False
```
```
In mm/migrate.c (ffff800010350d6c)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In fs/proc/task_mmu.c (ffff800010439768)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/memory.c (c0519158)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/swapops.h:188
Inline: False
```
```
In mm/migrate.c (c0552448)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In fs/proc/task_mmu.c (c06013b4)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In mm/memory.c (c0000000003bf170)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/page_vma_mapped.c (c0000000003d60d0)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/migrate.c (c000000000436ff0)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In fs/proc/task_mmu.c (c00000000054cb38)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/memory.c (ffffffe000207610)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/swapops.h:188
Inline: False
```
```
In mm/migrate.c (ffffffe00023f73e)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
```
```
In fs/proc/task_mmu.c (ffffffe0002d353e)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/memory.c (ffffffff8125752e)
Location: include/linux/swapops.h:188
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff8126a105)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/migrate.c (ffffffff812a9040)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In fs/proc/task_mmu.c (ffffffff8136929e)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/memory.c (ffffffff8124a556)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff8125c2f7)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/migrate.c (ffffffff8129a9b3)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In fs/proc/task_mmu.c (ffffffff81359549)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/memory.c (ffffffff812552ce)
Location: include/linux/swapops.h:188
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81267ea5)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/migrate.c (ffffffff812a6e50)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In fs/proc/task_mmu.c (ffffffff81366d6e)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/memory.c (ffffffff81264d82)
Location: include/linux/swapops.h:188
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81277827)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/migrate.c (ffffffff812b7182)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In fs/proc/task_mmu.c (ffffffff8137a3be)
Location: include/linux/swapops.h:188
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
</details>
</li>
</ul>

## Differences
