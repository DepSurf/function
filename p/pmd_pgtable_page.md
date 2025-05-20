# Function: <code>pmd_pgtable_page</code>

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
In mm/vmscan.c (ffffffff8137f487)
Location: include/linux/mm.h:2564
Inline: True
```
```
In mm/gup.c (ffffffff813b03dc)
Location: include/linux/mm.h:2564
Inline: True
```
```
In mm/memory.c (ffffffff813baf52)
Location: include/linux/mm.h:2564
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:pmd_install
```
```
In mm/mremap.c (ffffffff813d0316)
Location: include/linux/mm.h:2564
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff813d308d)
Location: include/linux/mm.h:2564
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff813d4b25)
Location: include/linux/mm.h:2564
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/hugetlb.c (ffffffff8140ddd6)
Location: include/linux/mm.h:2564
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81417bf7)
Location: include/linux/mm.h:2564
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff81433e85)
Location: include/linux/mm.h:2564
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/migrate_device.c (ffffffff8143898a)
Location: include/linux/mm.h:2564
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81440c58)
Location: include/linux/mm.h:2564
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81448fa2)
Location: include/linux/mm.h:2564
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (ffffffff81470267)
Location: include/linux/mm.h:2564
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff814f97db)
Location: include/linux/mm.h:2564
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_load_hole
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
In mm/vmscan.c (ffffffff813b09b7)
Location: include/linux/mm.h:2889
Inline: True
```
```
In mm/gup.c (ffffffff813e49ac)
Location: include/linux/mm.h:2889
Inline: True
```
```
In mm/memory.c (ffffffff813efa58)
Location: include/linux/mm.h:2889
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:pmd_install
```
```
In mm/mremap.c (ffffffff81405086)
Location: include/linux/mm.h:2889
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81407c50)
Location: include/linux/mm.h:2889
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff814094f5)
Location: include/linux/mm.h:2889
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/hugetlb.c (ffffffff814411b5)
Location: include/linux/mm.h:2889
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8144b1bc)
Location: include/linux/mm.h:2889
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/migrate.c (ffffffff814697d5)
Location: include/linux/mm.h:2889
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/migrate_device.c (ffffffff8146f0e9)
Location: include/linux/mm.h:2889
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814764fc)
Location: include/linux/mm.h:2889
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8147e73b)
Location: include/linux/mm.h:2889
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (ffffffff814a4a37)
Location: include/linux/mm.h:2889
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff81530c5e)
Location: include/linux/mm.h:2889
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_load_hole
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct page *pmd_pgtable_page(pmd_t *pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813d9ec7)
Location: include/linux/mm.h:2985
Inline: True
```
```
In mm/gup.c (ffffffff8140f20a)
Location: include/linux/mm.h:2985
Inline: True
```
```
In mm/memory.c (ffffffff8141b0aa)
Location: include/linux/mm.h:2985
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:pmd_install
```
```
In mm/mremap.c (ffffffff81431566)
Location: include/linux/mm.h:2985
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81434325)
Location: include/linux/mm.h:2985
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff81435ce5)
Location: include/linux/mm.h:2985
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/hugetlb.c (ffffffff8147b2e6)
Location: include/linux/mm.h:2985
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81484bc6)
Location: include/linux/mm.h:2985
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/migrate.c (ffffffff81498705)
Location: include/linux/mm.h:2985
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/migrate_device.c (ffffffff8149dbea)
Location: include/linux/mm.h:2985
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a5d8c)
Location: include/linux/mm.h:2985
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814acbff)
Location: include/linux/mm.h:2985
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_huge_page
Direct callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/hmm.c (ffffffff814d5a5f)
Location: include/linux/mm.h:2985
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff81565b3e)
Location: include/linux/mm.h:2985
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_load_hole
```
```
In fs/proc/task_mmu.c (ffffffff8159d5a2)
Location: include/linux/mm.h:2985
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_scan_hugetlb_entry
```
**Symbols:**

```
ffffffff814a8db0-ffffffff814a8df1: pmd_pgtable_page (STB_LOCAL)
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
</ul>
