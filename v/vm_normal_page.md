# Function: <code>vm_normal_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *vm_normal_page(struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bd490)
Location: mm/memory.c:750
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:__get_user_pages
  - mm/memory.c:unmap_page_range
  - mm/memory.c:do_wp_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:copy_page_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mprotect.c:change_protection_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:can_gather_numa_stats
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff811bd490-ffffffff811bd52c: vm_normal_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *vm_normal_page(struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d8210)
Location: mm/memory.c:752
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mprotect.c:change_protection_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
**Symbols:**

```
ffffffff811d8210-ffffffff811d82ac: vm_normal_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *vm_normal_page(struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e7ee0)
Location: mm/memory.c:754
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mprotect.c:change_protection_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
**Symbols:**

```
ffffffff811e7ee0-ffffffff811e7f76: vm_normal_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *vm_normal_page(struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f3080)
Location: mm/memory.c:820
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:copy_page_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mprotect.c:change_protection_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
**Symbols:**

```
ffffffff811f3080-ffffffff811f3116: vm_normal_page (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *vm_normal_page(struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81250270)
Location: mm/memory.c:574
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mprotect.c:change_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81250270-ffffffff8125033d: vm_normal_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *vm_normal_page(struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125e820)
Location: mm/memory.c:574
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mprotect.c:change_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff8125e820-ffffffff8125e8ed: vm_normal_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *vm_normal_page(struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8128eb10)
Location: mm/memory.c:592
Inline: False
Direct callers:
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_one_pte
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mprotect.c:change_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:mc_handle_present_pte
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
**Symbols:**

```
ffffffff8128eb10-ffffffff8128ebdd: vm_normal_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *vm_normal_page(struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812996c0)
Location: mm/memory.c:594
Inline: False
Direct callers:
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mprotect.c:change_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
**Symbols:**

```
ffffffff812996c0-ffffffff8129978d: vm_normal_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *vm_normal_page(struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129e8e0)
Location: mm/memory.c:606
Inline: False
Direct callers:
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mprotect.c:change_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
**Symbols:**

```
ffffffff8129e8e0-ffffffff8129e9b1: vm_normal_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *vm_normal_page(struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812dfb20)
Location: mm/memory.c:605
Inline: False
Direct callers:
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mprotect.c:change_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
**Symbols:**

```
ffffffff812dfb20-ffffffff812dfbf1: vm_normal_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *vm_normal_page(struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813400a0)
Location: mm/memory.c:612
Inline: False
Direct callers:
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_present_pte
  - mm/mlock.c:mlock_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
**Symbols:**

```
ffffffff813400a0-ffffffff81340194: vm_normal_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *vm_normal_page(struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813b8010)
Location: mm/memory.c:565
Inline: False
Direct callers:
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_present_pte
  - mm/mlock.c:mlock_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:can_change_pte_writable
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
**Symbols:**

```
ffffffff813b8010-ffffffff813b811f: vm_normal_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *vm_normal_page(struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813ecde0)
Location: mm/memory.c:584
Inline: False
Direct callers:
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:vm_normal_folio
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:can_change_pte_writable
  - mm/ksm.c:break_ksm_pmd_entry
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:get_mctgt_type
  - mm/hmm.c:hmm_vma_handle_pte
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
**Symbols:**

```
ffffffff813ecde0-ffffffff813eceef: vm_normal_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page *vm_normal_page(struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81418340)
Location: mm/memory.c:582
Inline: False
Direct callers:
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_present_pte
  - mm/mprotect.c:can_change_pte_writable
  - mm/ksm.c:break_ksm_pmd_entry
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:get_mctgt_type
  - mm/hmm.c:hmm_vma_handle_pte
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_page_category
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
**Symbols:**

```
ffffffff81418340-ffffffff8141844f: vm_normal_page (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct page *vm_normal_page(struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f6230)
Location: mm/memory.c:574
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mprotect.c:change_protection_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffff8000102f6230-ffff8000102f6304: vm_normal_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *vm_normal_page(struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c05183f4)
Location: mm/memory.c:574
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/memory.c:do_wp_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mprotect.c:change_protection_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
**Symbols:**

```
c05183f4-c05184bc: vm_normal_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *vm_normal_page(struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003bdbb0)
Location: mm/memory.c:574
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mprotect.c:change_protection_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
c0000000003bdbb0-c0000000003bdce8: vm_normal_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *vm_normal_page(struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe0002073d6)
Location: mm/memory.c:574
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mprotect.c:change_protection_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffe0002073d6-ffffffe000207476: vm_normal_page (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct page *vm_normal_page(struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81256e70)
Location: mm/memory.c:574
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mprotect.c:change_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81256e70-ffffffff81256f3d: vm_normal_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *vm_normal_page(struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812497c0)
Location: mm/memory.c:574
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mprotect.c:change_protection_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff812497c0-ffffffff8124987b: vm_normal_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *vm_normal_page(struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81254c10)
Location: mm/memory.c:574
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mprotect.c:change_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81254c10-ffffffff81254cdd: vm_normal_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *vm_normal_page(struct vm_area_struct *vma, long unsigned int addr, pte_t pte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81264690)
Location: mm/memory.c:574
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mprotect.c:change_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
**Symbols:**

```
ffffffff81264690-ffffffff8126475d: vm_normal_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
