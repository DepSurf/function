# Function: <code>swp_offset_pfn</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135f967)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/filemap.c:migration_entry_wait_on_locked
```
```
In mm/memory.c (ffffffff813b8e08)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mprotect.c (ffffffff813ce58f)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff813d2fc2)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/hugetlb.c (ffffffff8141280e)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/ksm.c (ffffffff81421ae8)
Location: include/linux/swapops.h:117
Inline: True
```
```
In mm/migrate_device.c (ffffffff81438f7c)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81440420)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/memcontrol.c (ffffffff814501aa)
Location: include/linux/swapops.h:117
Inline: True
```
```
In mm/memory-failure.c (ffffffff8145f08e)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/hmm.c (ffffffff814705d7)
Location: include/linux/swapops.h:117
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8152fcf8)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
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
In mm/filemap.c (ffffffff81390937)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/filemap.c:migration_entry_wait_on_locked
```
```
In mm/memory.c (ffffffff813e9580)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/memory.c:pfn_swap_entry_to_page
```
```
In mm/mprotect.c (ffffffff81402ec8)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81407c1e)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/hugetlb.c (ffffffff81445e1c)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/ksm.c (ffffffff8145688c)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate_device.c (ffffffff8146f824)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81475f36)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81485c0a)
Location: include/linux/swapops.h:117
Inline: True
```
```
In mm/memory-failure.c (ffffffff8149503e)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/hmm.c (ffffffff814a4db2)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/proc/task_mmu.c (ffffffff81567c09)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
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
In mm/filemap.c (ffffffff813ba5b7)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/filemap.c:migration_entry_wait_on_locked
```
```
In mm/memory.c (ffffffff814144c0)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/memory.c:pfn_swap_entry_to_page
```
```
In mm/mprotect.c (ffffffff8142f492)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff814342e2)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/hugetlb.c (ffffffff8147f854)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/ksm.c (ffffffff81491382)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate_device.c (ffffffff8149e24f)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a57ca)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/memcontrol.c (ffffffff814b45ba)
Location: include/linux/swapops.h:117
Inline: True
```
```
In mm/memory-failure.c (ffffffff814c493e)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/hmm.c (ffffffff814d5d88)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/proc/task_mmu.c (ffffffff8159fda6)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
