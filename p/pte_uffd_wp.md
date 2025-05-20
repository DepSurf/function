# Function: <code>pte_uffd_wp</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81290ef0)
Location: arch/x86/include/asm/pgtable.h:319
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
```
```
In mm/rmap.c (ffffffff812a57cb)
Location: arch/x86/include/asm/pgtable.h:319
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812e4668)
Location: arch/x86/include/asm/pgtable.h:319
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff812f2d87)
Location: arch/x86/include/asm/pgtable.h:319
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
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
In mm/memory.c (ffffffff8129b97c)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
```
```
In mm/rmap.c (ffffffff812b0b8a)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812f0348)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff812fd3ba)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
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
In mm/memory.c (ffffffff812a0a75)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffffffff812b6273)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff812f5cc2)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff8130410e)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
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
In mm/memory.c (ffffffff812e1b95)
Location: arch/x86/include/asm/pgtable.h:289
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffffffff812f8bc8)
Location: arch/x86/include/asm/pgtable.h:289
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/migrate.c (ffffffff8133fe87)
Location: arch/x86/include/asm/pgtable.h:289
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff8134de3e)
Location: arch/x86/include/asm/pgtable.h:289
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81421e79)
Location: arch/x86/include/asm/pgtable.h:289
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
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
In mm/gup.c (ffffffff81338883)
Location: arch/x86/include/asm/pgtable.h:292
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813429cb)
Location: arch/x86/include/asm/pgtable.h:292
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_present_pte
```
```
In mm/rmap.c (ffffffff8135f1aa)
Location: arch/x86/include/asm/pgtable.h:292
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81392bef)
Location: arch/x86/include/asm/pgtable.h:292
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate_device.c (ffffffff813b7420)
Location: arch/x86/include/asm/pgtable.h:292
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff813c709e)
Location: arch/x86/include/asm/pgtable.h:292
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8149944e)
Location: arch/x86/include/asm/pgtable.h:292
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
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
In mm/gup.c (ffffffff813b0048)
Location: arch/x86/include/asm/pgtable.h:293
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813baa47)
Location: arch/x86/include/asm/pgtable.h:293
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_present_pte
```
```
In mm/mprotect.c (ffffffff813cdd83)
Location: arch/x86/include/asm/pgtable.h:293
Inline: True
Inline callers:
  - mm/mprotect.c:can_change_pte_writable
```
```
In mm/rmap.c (ffffffff813da062)
Location: arch/x86/include/asm/pgtable.h:293
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81411590)
Location: arch/x86/include/asm/pgtable.h:293
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate_device.c (ffffffff81438f66)
Location: arch/x86/include/asm/pgtable.h:293
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff8144af19)
Location: arch/x86/include/asm/pgtable.h:293
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8152e6e1)
Location: arch/x86/include/asm/pgtable.h:293
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
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
In mm/gup.c (ffffffff813e4674)
Location: arch/x86/include/asm/pgtable.h:299
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813ef557)
Location: arch/x86/include/asm/pgtable.h:299
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_present_pte
```
```
In mm/mprotect.c (ffffffff81402743)
Location: arch/x86/include/asm/pgtable.h:299
Inline: True
Inline callers:
  - mm/mprotect.c:can_change_pte_writable
```
```
In mm/rmap.c (ffffffff8140e7a5)
Location: arch/x86/include/asm/pgtable.h:299
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81444a5c)
Location: arch/x86/include/asm/pgtable.h:299
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate_device.c (ffffffff8146f7ca)
Location: arch/x86/include/asm/pgtable.h:299
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff8147ec53)
Location: arch/x86/include/asm/pgtable.h:299
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff815669f1)
Location: arch/x86/include/asm/pgtable.h:299
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
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
In mm/gup.c (ffffffff8140f01c)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff814199b7)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_present_pte
```
```
In mm/mprotect.c (ffffffff8142ed73)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - mm/mprotect.c:can_change_pte_writable
```
```
In mm/rmap.c (ffffffff8143afac)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8147eabd)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate_device.c (ffffffff8149e544)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff814af92d)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/task_mmu.c (ffffffff815a0881)
Location: arch/x86/include/asm/pgtable.h:389
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_scan_pmd_entry
  - fs/proc/task_mmu.c:pagemap_scan_pmd_entry
  - fs/proc/task_mmu.c:pagemap_hugetlb_category
  - fs/proc/task_mmu.c:pagemap_page_category
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
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
