# Function: <code>pfn_swap_entry_to_page</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct page *pfn_swap_entry_to_page(swp_entry_t entry);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e06fb)
Location: include/linux/swapops.h:250
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/page_vma_mapped.c (ffffffff812f4a56)
Location: include/linux/swapops.h:250
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/migrate.c (ffffffff8133ff54)
Location: include/linux/swapops.h:250
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff813457ac)
Location: include/linux/swapops.h:250
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81352226)
Location: include/linux/swapops.h:250
Inline: True
```
```
In mm/hmm.c (ffffffff8136a50f)
Location: include/linux/swapops.h:250
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81422559)
Location: include/linux/swapops.h:250
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
**Symbols:**

```
ffffffff812dd090-ffffffff812dd0c8: pfn_swap_entry_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct page *pfn_swap_entry_to_page(swp_entry_t entry);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f59c3)
Location: include/linux/swapops.h:370
Inline: True
Inline callers:
  - mm/filemap.c:migration_entry_wait_on_locked
```
```
In mm/memory.c (ffffffff81340ddb)
Location: include/linux/swapops.h:370
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mprotect.c (ffffffff813540e5)
Location: include/linux/swapops.h:370
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff81390ffa)
Location: include/linux/swapops.h:370
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/migrate_device.c (ffffffff813b7242)
Location: include/linux/swapops.h:370
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813bb918)
Location: include/linux/swapops.h:370
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/memcontrol.c (ffffffff813ce74a)
Location: include/linux/swapops.h:370
Inline: True
```
```
In mm/hmm.c (ffffffff813e86a6)
Location: include/linux/swapops.h:370
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8149b1f2)
Location: include/linux/swapops.h:370
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
**Symbols:**

```
ffffffff8133cd90-ffffffff8133cdd5: pfn_swap_entry_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct page *pfn_swap_entry_to_page(swp_entry_t entry);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135f967)
Location: include/linux/swapops.h:462
Inline: True
Inline callers:
  - mm/filemap.c:migration_entry_wait_on_locked
```
```
In mm/memory.c (ffffffff813b8e08)
Location: include/linux/swapops.h:462
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mprotect.c (ffffffff813ce58f)
Location: include/linux/swapops.h:462
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff8141280e)
Location: include/linux/swapops.h:462
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/ksm.c (ffffffff81421ae8)
Location: include/linux/swapops.h:462
Inline: True
```
```
In mm/migrate_device.c (ffffffff81438f7c)
Location: include/linux/swapops.h:462
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81440420)
Location: include/linux/swapops.h:462
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff814501aa)
Location: include/linux/swapops.h:462
Inline: True
```
```
In mm/hmm.c (ffffffff814705d7)
Location: include/linux/swapops.h:462
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8152fcf8)
Location: include/linux/swapops.h:462
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
**Symbols:**

```
ffffffff813b4960-ffffffff813b49c0: pfn_swap_entry_to_page (STB_LOCAL)
ffffffff8143c040-ffffffff8143c0ca: pfn_swap_entry_to_page (STB_LOCAL)
ffffffff8152d740-ffffffff8152d7ca: pfn_swap_entry_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct page *pfn_swap_entry_to_page(swp_entry_t entry);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81390937)
Location: include/linux/swapops.h:453
Inline: True
Inline callers:
  - mm/filemap.c:migration_entry_wait_on_locked
```
```
In mm/memory.c (ffffffff813e9580)
Location: include/linux/swapops.h:453
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mprotect.c (ffffffff81402ec8)
Location: include/linux/swapops.h:453
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff81445e1c)
Location: include/linux/swapops.h:453
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/ksm.c (ffffffff8145688c)
Location: include/linux/swapops.h:453
Inline: True
Inline callers:
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate_device.c (ffffffff8146f824)
Location: include/linux/swapops.h:453
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81475f36)
Location: include/linux/swapops.h:453
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff81485c0a)
Location: include/linux/swapops.h:453
Inline: True
```
```
In mm/hmm.c (ffffffff814a4db2)
Location: include/linux/swapops.h:453
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/proc/task_mmu.c (ffffffff81567c09)
Location: include/linux/swapops.h:453
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
**Symbols:**

```
ffffffff813e9580-ffffffff813e95dc: pfn_swap_entry_to_page (STB_LOCAL)
ffffffff81471b60-ffffffff81471be6: pfn_swap_entry_to_page (STB_LOCAL)
ffffffff81565b70-ffffffff81565bf6: pfn_swap_entry_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct page *pfn_swap_entry_to_page(swp_entry_t entry);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813ba5b7)
Location: include/linux/swapops.h:458
Inline: True
Inline callers:
  - mm/filemap.c:migration_entry_wait_on_locked
```
```
In mm/memory.c (ffffffff814144c0)
Location: include/linux/swapops.h:458
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mprotect.c (ffffffff8142f492)
Location: include/linux/swapops.h:458
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff8147f854)
Location: include/linux/swapops.h:458
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/ksm.c (ffffffff81491382)
Location: include/linux/swapops.h:458
Inline: True
Inline callers:
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate_device.c (ffffffff8149e24f)
Location: include/linux/swapops.h:458
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a57ca)
Location: include/linux/swapops.h:458
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff814b45ba)
Location: include/linux/swapops.h:458
Inline: True
```
```
In mm/hmm.c (ffffffff814d5d88)
Location: include/linux/swapops.h:458
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/proc/task_mmu.c (ffffffff815a0050)
Location: include/linux/swapops.h:458
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_entry
Direct callers:
  - fs/proc/task_mmu.c:pagemap_thp_category
  - fs/proc/task_mmu.c:pagemap_page_category
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
**Symbols:**

```
ffffffff814144c0-ffffffff8141451c: pfn_swap_entry_to_page (STB_LOCAL)
ffffffff814a1360-ffffffff814a13e3: pfn_swap_entry_to_page (STB_LOCAL)
ffffffff8159d670-ffffffff8159d6f3: pfn_swap_entry_to_page (STB_LOCAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
