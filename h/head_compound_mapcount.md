# Function: <code>head_compound_mapcount</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81271197)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/debug.c (ffffffff81be74e5)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/swapfile.c (ffffffff812c81fb)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/huge_memory.c (ffffffff812f8f0a)
Location: include/linux/mm.h:810
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:follow_trans_huge_pmd
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
In mm/vmscan.c (ffffffff81275cf4)
Location: include/linux/mm.h:833
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/debug.c (ffffffff81bd9370)
Location: include/linux/mm.h:833
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/swapfile.c (ffffffff812cec73)
Location: include/linux/mm.h:833
Inline: True
Inline callers:
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/huge_memory.c (ffffffff812ff54d)
Location: include/linux/mm.h:833
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:follow_trans_huge_pmd
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
In mm/vmscan.c (ffffffff812b39ee)
Location: include/linux/mm.h:836
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/debug.c (ffffffff81cbbdb2)
Location: include/linux/mm.h:836
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/swapfile.c (ffffffff81314203)
Location: include/linux/mm.h:836
Inline: True
Inline callers:
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/huge_memory.c (ffffffff8134915d)
Location: include/linux/mm.h:836
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:follow_trans_huge_pmd
```
</details>
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
In mm/filemap.c (ffffffff81359a7f)
Location: include/linux/mm.h:842
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/debug.c (ffffffff813ade78)
Location: include/linux/mm.h:842
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff813bc920)
Location: include/linux/mm.h:842
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:zap_pte_range
```
```
In mm/rmap.c (ffffffff813d8f21)
Location: include/linux/mm.h:842
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_referenced
```
```
In mm/madvise.c (ffffffff813f4e2f)
Location: include/linux/mm.h:842
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff814107ab)
Location: include/linux/mm.h:842
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_wp
```
```
In mm/mempolicy.c (ffffffff81416362)
Location: include/linux/mm.h:842
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff814218b7)
Location: include/linux/mm.h:842
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff8143629a)
Location: include/linux/mm.h:842
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
```
```
In mm/migrate_device.c (ffffffff8143829b)
Location: include/linux/mm.h:842
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
```
```
In mm/khugepaged.c (ffffffff8144a918)
Location: include/linux/mm.h:842
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memory-failure.c (ffffffff81462c47)
Location: include/linux/mm.h:842
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/task_mmu.c (ffffffff8152dacd)
Location: include/linux/mm.h:842
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
In fs/proc/page.c (ffffffff81547a61)
Location: include/linux/mm.h:842
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
```
</details>
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
