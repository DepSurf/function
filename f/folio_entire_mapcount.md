# Function: <code>folio_entire_mapcount</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8130e976)
Location: include/linux/mm.h:786
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/util.c (ffffffff8131df34)
Location: include/linux/mm.h:786
Inline: True
Inline callers:
  - mm/util.c:folio_mapcount
```
```
In mm/debug.c (ffffffff81e6da2f)
Location: include/linux/mm.h:786
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/huge_memory.c (ffffffff813bbabc)
Location: include/linux/mm.h:786
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813808db)
Location: include/linux/mm.h:832
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
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
In mm/filemap.c (ffffffff8138b3c9)
Location: include/linux/mm.h:1100
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/vmscan.c (ffffffff813b1dc7)
Location: include/linux/mm.h:1100
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/debug.c (ffffffff813e235c)
Location: include/linux/mm.h:1100
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff813f1313)
Location: include/linux/mm.h:1100
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:zap_pte_range
```
```
In mm/rmap.c (ffffffff8140bbc3)
Location: include/linux/mm.h:1100
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_referenced
```
```
In mm/page_alloc.c (ffffffff8141afd9)
Location: include/linux/mm.h:1100
Inline: True
Inline callers:
  - mm/page_alloc.c:free_tail_page_prepare
```
```
In mm/madvise.c (ffffffff81427c56)
Location: include/linux/mm.h:1100
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff814494ff)
Location: include/linux/mm.h:1100
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_folio_add
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/ksm.c (ffffffff8145653e)
Location: include/linux/mm.h:1100
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff8146bd2b)
Location: include/linux/mm.h:1100
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
```
```
In mm/migrate_device.c (ffffffff8146df6b)
Location: include/linux/mm.h:1100
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
```
```
In mm/huge_memory.c (ffffffff81477f71)
Location: include/linux/mm.h:1100
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81480bd6)
Location: include/linux/mm.h:1100
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memory-failure.c (ffffffff81498a01)
Location: include/linux/mm.h:1100
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/task_mmu.c (ffffffff81565f04)
Location: include/linux/mm.h:1100
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff8157f681)
Location: include/linux/mm.h:1100
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
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
In mm/filemap.c (ffffffff813b4ef0)
Location: include/linux/mm.h:1183
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/vmscan.c (ffffffff813db333)
Location: include/linux/mm.h:1183
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/debug.c (ffffffff8140c9de)
Location: include/linux/mm.h:1183
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff8141beda)
Location: include/linux/mm.h:1183
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:zap_pte_range
```
```
In mm/rmap.c (ffffffff8143847a)
Location: include/linux/mm.h:1183
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_referenced
```
```
In mm/page_alloc.c (ffffffff81445dd6)
Location: include/linux/mm.h:1183
Inline: True
Inline callers:
  - mm/page_alloc.c:free_tail_page_prepare
```
```
In mm/madvise.c (ffffffff8146146e)
Location: include/linux/mm.h:1183
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81482f57)
Location: include/linux/mm.h:1183
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_folio_add
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/ksm.c (ffffffff81490fc2)
Location: include/linux/mm.h:1183
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff8149acdd)
Location: include/linux/mm.h:1183
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:add_page_for_migration
```
```
In mm/migrate_device.c (ffffffff8149e92f)
Location: include/linux/mm.h:1183
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
```
```
In mm/huge_memory.c (ffffffff814a76ec)
Location: include/linux/mm.h:1183
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814aebb0)
Location: include/linux/mm.h:1183
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memory-failure.c (ffffffff814c7f79)
Location: include/linux/mm.h:1183
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/task_mmu.c (ffffffff8159decf)
Location: include/linux/mm.h:1183
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff815b80bb)
Location: include/linux/mm.h:1183
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
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
