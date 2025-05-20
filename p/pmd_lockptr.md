# Function: <code>pmd_lockptr</code>

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
In mm/gup.c (ffffffff811ba9a7)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811bd25f)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc
```
```
In mm/mprotect.c (ffffffff811c872c)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff811caa87)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - mm/rmap.c:__page_check_address
```
```
In mm/pgtable-generic.c (ffffffff811d04a6)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
```
```
In mm/hugetlb.c (ffffffff811dd92e)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_huge_pmd
```
```
In mm/mempolicy.c (ffffffff811dfec3)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff811f0e1c)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff811f50bd)
Location: include/linux/mm.h:1649
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:page_check_address_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
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
In mm/gup.c (ffffffff8122ec12)
Location: include/linux/mm.h:1765
Inline: True
```
```
In mm/memory.c (ffffffff811da276)
Location: include/linux/mm.h:1765
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/mprotect.c (ffffffff811e49cd)
Location: include/linux/mm.h:1765
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff811e7a57)
Location: include/linux/mm.h:1765
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:__page_check_address
```
```
In mm/pgtable-generic.c (ffffffff811ed726)
Location: include/linux/mm.h:1765
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/hugetlb.c (ffffffff811fde52)
Location: include/linux/mm.h:1765
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff811fec7e)
Location: include/linux/mm.h:1765
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812130f2)
Location: include/linux/mm.h:1765
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81215ddf)
Location: include/linux/mm.h:1765
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8121b486)
Location: include/linux/mm.h:1765
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
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
In mm/gup.c (ffffffff8124116d)
Location: include/linux/mm.h:1739
Inline: True
```
```
In mm/memory.c (ffffffff811e9da6)
Location: include/linux/mm.h:1739
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/mprotect.c (ffffffff811f49bf)
Location: include/linux/mm.h:1739
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff811f6f4a)
Location: include/linux/mm.h:1739
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff811f7b06)
Location: include/linux/mm.h:1739
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/rmap.c (ffffffff811f8ddd)
Location: include/linux/mm.h:1739
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:__page_check_address
```
```
In mm/hugetlb.c (ffffffff8120e93f)
Location: include/linux/mm.h:1739
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff812104ba)
Location: include/linux/mm.h:1739
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff81225462)
Location: include/linux/mm.h:1739
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812283fe)
Location: include/linux/mm.h:1739
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8122e3dd)
Location: include/linux/mm.h:1739
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/dax.c (ffffffff8129cd90)
Location: include/linux/mm.h:1739
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
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
In mm/gup.c (ffffffff811ef6d4)
Location: include/linux/mm.h:1792
Inline: True
```
```
In mm/memory.c (ffffffff811f1c60)
Location: include/linux/mm.h:1792
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/page_vma_mapped.c (ffffffff81201e42)
Location: include/linux/mm.h:1792
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff81202d06)
Location: include/linux/mm.h:1792
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/hugetlb.c (ffffffff8121a340)
Location: include/linux/mm.h:1792
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8121a9ea)
Location: include/linux/mm.h:1792
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff81230b3e)
Location: include/linux/mm.h:1792
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff81234816)
Location: include/linux/mm.h:1792
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812391db)
Location: include/linux/mm.h:1792
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff812ab7a9)
Location: include/linux/mm.h:1792
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
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
In mm/gup.c (ffffffff81206716)
Location: include/linux/mm.h:1894
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff812088c2)
Location: include/linux/mm.h:1894
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/page_vma_mapped.c (ffffffff8121a73f)
Location: include/linux/mm.h:1894
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff8121ba65)
Location: include/linux/mm.h:1894
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/hugetlb.c (ffffffff8123547c)
Location: include/linux/mm.h:1894
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81235c67)
Location: include/linux/mm.h:1894
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff8124b144)
Location: include/linux/mm.h:1894
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff81252729)
Location: include/linux/mm.h:1894
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81258c91)
Location: include/linux/mm.h:1894
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/dax.c (ffffffff812cef3d)
Location: include/linux/mm.h:1894
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
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
In mm/gup.c (ffffffff81225ec0)
Location: include/linux/mm.h:1983
Inline: True
```
```
In mm/memory.c (ffffffff812298fb)
Location: include/linux/mm.h:1983
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/page_vma_mapped.c (ffffffff8123c84c)
Location: include/linux/mm.h:1983
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff8123d815)
Location: include/linux/mm.h:1983
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/hugetlb.c (ffffffff8125839f)
Location: include/linux/mm.h:1983
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8125a6d9)
Location: include/linux/mm.h:1983
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff8126dd82)
Location: include/linux/mm.h:1983
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff81276b43)
Location: include/linux/mm.h:1983
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8127bb19)
Location: include/linux/mm.h:1983
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff812f96e6)
Location: include/linux/mm.h:1983
Inline: True
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
In mm/gup.c (ffffffff81239630)
Location: include/linux/mm.h:2053
Inline: True
```
```
In mm/memory.c (ffffffff8123ce2a)
Location: include/linux/mm.h:2053
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/mremap.c (ffffffff8124f3e9)
Location: include/linux/mm.h:2053
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81250c58)
Location: include/linux/mm.h:2053
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff81251dc5)
Location: include/linux/mm.h:2053
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/hugetlb.c (ffffffff8126ca6f)
Location: include/linux/mm.h:2053
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8126e55b)
Location: include/linux/mm.h:2053
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff81282bf2)
Location: include/linux/mm.h:2053
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff8128ba86)
Location: include/linux/mm.h:2053
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8128fe5b)
Location: include/linux/mm.h:2053
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8130e198)
Location: include/linux/mm.h:2053
Inline: True
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
In mm/gup.c (ffffffff8124c030)
Location: include/linux/mm.h:2048
Inline: True
```
```
In mm/memory.c (ffffffff8124ea94)
Location: include/linux/mm.h:2048
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/mremap.c (ffffffff8126173c)
Location: include/linux/mm.h:2048
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81262f38)
Location: include/linux/mm.h:2048
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff812640a5)
Location: include/linux/mm.h:2048
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/hugetlb.c (ffffffff81287e9a)
Location: include/linux/mm.h:2048
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81289b8d)
Location: include/linux/mm.h:2048
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff812a123c)
Location: include/linux/mm.h:2048
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff812a66be)
Location: include/linux/mm.h:2048
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812ab045)
Location: include/linux/mm.h:2048
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (ffffffff812c3e3a)
Location: include/linux/mm.h:2048
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff8133468d)
Location: include/linux/mm.h:2048
Inline: True
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
In mm/gup.c (ffffffff8125a519)
Location: include/linux/mm.h:2020
Inline: True
```
```
In mm/memory.c (ffffffff8125d03e)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/mremap.c (ffffffff8126fefa)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812716e8)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff81272915)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/hugetlb.c (ffffffff81297a9a)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff812996fd)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff812ae692)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff812b7b97)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812bc9de)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (ffffffff812d5b82)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff8134825d)
Location: include/linux/mm.h:2020
Inline: True
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
In mm/gup.c (ffffffff81288a2e)
Location: include/linux/mm.h:2291
Inline: True
```
```
In mm/memory.c (ffffffff8128d665)
Location: include/linux/mm.h:2291
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:do_set_pmd
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:__pte_alloc
```
```
In mm/mremap.c (ffffffff8129fdda)
Location: include/linux/mm.h:2291
Inline: True
Inline callers:
  - mm/mremap.c:move_normal_pmd
  - mm/mremap.c:move_normal_pmd
```
```
In mm/page_vma_mapped.c (ffffffff812a1bb5)
Location: include/linux/mm.h:2291
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff812a36d5)
Location: include/linux/mm.h:2291
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/hugetlb.c (ffffffff812cb130)
Location: include/linux/mm.h:2291
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff812cea39)
Location: include/linux/mm.h:2291
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff812e3cf2)
Location: include/linux/mm.h:2291
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff812ecd68)
Location: include/linux/mm.h:2291
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
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
In mm/khugepaged.c (ffffffff812f1180)
Location: include/linux/mm.h:2291
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (ffffffff8130b7da)
Location: include/linux/mm.h:2291
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff8138ecdd)
Location: include/linux/mm.h:2291
Inline: True
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
In mm/gup.c (ffffffff8129270e)
Location: include/linux/mm.h:2291
Inline: True
```
```
In mm/memory.c (ffffffff8129fb17)
Location: include/linux/mm.h:2291
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:do_set_pmd
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:__pte_alloc
```
```
In mm/mremap.c (ffffffff812ab244)
Location: include/linux/mm.h:2291
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812ad6b1)
Location: include/linux/mm.h:2291
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff812aefb5)
Location: include/linux/mm.h:2291
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/hugetlb.c (ffffffff812d6d40)
Location: include/linux/mm.h:2291
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff812da379)
Location: include/linux/mm.h:2291
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff812efa55)
Location: include/linux/mm.h:2291
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff812f7fb9)
Location: include/linux/mm.h:2291
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
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
In mm/khugepaged.c (ffffffff812fc892)
Location: include/linux/mm.h:2291
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (ffffffff813176c6)
Location: include/linux/mm.h:2291
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff813a03cc)
Location: include/linux/mm.h:2291
Inline: True
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
In mm/filemap.c (ffffffff8125fa3f)
Location: include/linux/mm.h:2299
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff812981d0)
Location: include/linux/mm.h:2299
Inline: True
```
```
In mm/memory.c (ffffffff812a5380)
Location: include/linux/mm.h:2299
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:finish_fault
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__pte_alloc
```
```
In mm/mremap.c (ffffffff812b0644)
Location: include/linux/mm.h:2299
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812b2cbf)
Location: include/linux/mm.h:2299
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff812b44e5)
Location: include/linux/mm.h:2299
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/hugetlb.c (ffffffff812de960)
Location: include/linux/mm.h:2299
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff812e1bd7)
Location: include/linux/mm.h:2299
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff812f53d5)
Location: include/linux/mm.h:2299
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff812fe569)
Location: include/linux/mm.h:2299
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813035ff)
Location: include/linux/mm.h:2299
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (ffffffff8131d3c3)
Location: include/linux/mm.h:2299
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff813a6aab)
Location: include/linux/mm.h:2299
Inline: True
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
In mm/filemap.c (ffffffff8129c3af)
Location: include/linux/mm.h:2328
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff812d8c0e)
Location: include/linux/mm.h:2328
Inline: True
```
```
In mm/memory.c (ffffffff812e68d5)
Location: include/linux/mm.h:2328
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:finish_fault
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__pte_alloc
```
```
In mm/mremap.c (ffffffff812f1f86)
Location: include/linux/mm.h:2328
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812f4882)
Location: include/linux/mm.h:2328
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff812f60c5)
Location: include/linux/mm.h:2328
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/hugetlb.c (ffffffff81325d45)
Location: include/linux/mm.h:2328
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81328cb1)
Location: include/linux/mm.h:2328
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff8133f9d5)
Location: include/linux/mm.h:2328
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff81348109)
Location: include/linux/mm.h:2328
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
In mm/khugepaged.c (ffffffff8134d369)
Location: include/linux/mm.h:2328
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (ffffffff8136a75d)
Location: include/linux/mm.h:2328
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff813f653b)
Location: include/linux/mm.h:2328
Inline: True
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
In mm/gup.c (ffffffff81338bcf)
Location: include/linux/mm.h:2406
Inline: True
```
```
In mm/memory.c (ffffffff81342fb0)
Location: include/linux/mm.h:2406
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:pmd_install
```
```
In mm/mremap.c (ffffffff81355ce5)
Location: include/linux/mm.h:2406
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81358982)
Location: include/linux/mm.h:2406
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff8135a0b5)
Location: include/linux/mm.h:2406
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/hugetlb.c (ffffffff81394ab0)
Location: include/linux/mm.h:2406
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
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
In mm/mempolicy.c (ffffffff81397f09)
Location: include/linux/mm.h:2406
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff813b4cd5)
Location: include/linux/mm.h:2406
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/migrate_device.c (ffffffff813b6e3d)
Location: include/linux/mm.h:2406
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813be3f8)
Location: include/linux/mm.h:2406
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
In mm/khugepaged.c (ffffffff813c3b0b)
Location: include/linux/mm.h:2406
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (ffffffff813e835c)
Location: include/linux/mm.h:2406
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff81468c3d)
Location: include/linux/mm.h:2406
Inline: True
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
In mm/vmscan.c (ffffffff8137f487)
Location: include/linux/mm.h:2570
Inline: True
```
```
In mm/gup.c (ffffffff813b03dc)
Location: include/linux/mm.h:2570
Inline: True
```
```
In mm/memory.c (ffffffff813baf52)
Location: include/linux/mm.h:2570
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:pmd_install
```
```
In mm/mremap.c (ffffffff813d0316)
Location: include/linux/mm.h:2570
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff813d308d)
Location: include/linux/mm.h:2570
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff813d4b25)
Location: include/linux/mm.h:2570
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/hugetlb.c (ffffffff8140ddd6)
Location: include/linux/mm.h:2570
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
Location: include/linux/mm.h:2570
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff81433e85)
Location: include/linux/mm.h:2570
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/migrate_device.c (ffffffff8143898a)
Location: include/linux/mm.h:2570
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81440c58)
Location: include/linux/mm.h:2570
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
Location: include/linux/mm.h:2570
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (ffffffff81470267)
Location: include/linux/mm.h:2570
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff814f97db)
Location: include/linux/mm.h:2570
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
Location: include/linux/mm.h:2895
Inline: True
```
```
In mm/gup.c (ffffffff813e49ac)
Location: include/linux/mm.h:2895
Inline: True
```
```
In mm/memory.c (ffffffff813efa58)
Location: include/linux/mm.h:2895
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:pmd_install
```
```
In mm/mremap.c (ffffffff81405086)
Location: include/linux/mm.h:2895
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81407c50)
Location: include/linux/mm.h:2895
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff814094f5)
Location: include/linux/mm.h:2895
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/hugetlb.c (ffffffff814411b5)
Location: include/linux/mm.h:2895
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
Location: include/linux/mm.h:2895
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/migrate.c (ffffffff814697d5)
Location: include/linux/mm.h:2895
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/migrate_device.c (ffffffff8146f0e9)
Location: include/linux/mm.h:2895
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814764fc)
Location: include/linux/mm.h:2895
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
Location: include/linux/mm.h:2895
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (ffffffff814a4a37)
Location: include/linux/mm.h:2895
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff81530c5e)
Location: include/linux/mm.h:2895
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_load_hole
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
In mm/vmscan.c (ffffffff813d9ec7)
Location: include/linux/mm.h:2996
Inline: True
```
```
In mm/gup.c (ffffffff8140f20a)
Location: include/linux/mm.h:2996
Inline: True
```
```
In mm/memory.c (ffffffff8141b0aa)
Location: include/linux/mm.h:2996
Inline: True
Inline callers:
  - mm/memory.c:do_set_pmd
  - mm/memory.c:pmd_install
```
```
In mm/mremap.c (ffffffff81431566)
Location: include/linux/mm.h:2996
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81434325)
Location: include/linux/mm.h:2996
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff81435ce5)
Location: include/linux/mm.h:2996
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/hugetlb.c (ffffffff8147b2e6)
Location: include/linux/mm.h:2996
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
Location: include/linux/mm.h:2996
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/migrate.c (ffffffff81498705)
Location: include/linux/mm.h:2996
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/migrate_device.c (ffffffff8149dbea)
Location: include/linux/mm.h:2996
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a5d8c)
Location: include/linux/mm.h:2996
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
Location: include/linux/mm.h:2996
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (ffffffff814d5a5f)
Location: include/linux/mm.h:2996
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff81565b3e)
Location: include/linux/mm.h:2996
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_load_hole
```
```
In fs/proc/task_mmu.c (ffffffff8159d5a2)
Location: include/linux/mm.h:2996
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_scan_hugetlb_entry
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
In mm/gup.c (ffff8000102f1fc8)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffff8000102f451c)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/page_vma_mapped.c (ffff8000103073a4)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffff8000103083c0)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/hugetlb.c (ffff800010335d9c)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffff800010338398)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffff800010352eb8)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffff800010358484)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffff80001035dc34)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (ffff80001037b37c)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/gup.c (0)
Location: include/linux/mm.h:2045
Inline: True
```
```
In mm/memory.c (c051b474)
Location: include/linux/mm.h:2045
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/mm.h:2045
Inline: True
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
In arch/powerpc/mm/book3s64/hash_pgtable.c (c00000000008baec)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_pgtable.c:hash__pgtable_trans_huge_withdraw
  - arch/powerpc/mm/book3s64/hash_pgtable.c:hash__pgtable_trans_huge_deposit
```
```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c0000000000953f0)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:radix__pgtable_trans_huge_withdraw
  - arch/powerpc/mm/book3s64/radix_pgtable.c:radix__pgtable_trans_huge_deposit
```
```
In arch/powerpc/mm/hugetlbpage.c (c0000000000a589c)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:huge_pte_alloc
```
```
In mm/gup.c (c0000000003b7ce0)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (c0000000003bb07c)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/page_vma_mapped.c (c0000000003d5970)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/hugetlb.c (c000000000410498)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (c0000000004111e0)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (c00000000043475c)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (c000000000440d38)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (c0000000004492b4)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (c00000000046fd40)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (c000000000514514)
Location: include/linux/mm.h:2020
Inline: True
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
In mm/gup.c (0)
Location: include/linux/mm.h:2045
Inline: True
```
```
In mm/memory.c (ffffffe000206682)
Location: include/linux/mm.h:2045
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:alloc_set_pte
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/mm.h:2045
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/mm.h:2045
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/mm.h:2045
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/mm.h:2045
Inline: True
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
In mm/gup.c (ffffffff81252b69)
Location: include/linux/mm.h:2020
Inline: True
```
```
In mm/memory.c (ffffffff8125568e)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/mremap.c (ffffffff8126854a)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81269d38)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff8126af65)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/hugetlb.c (ffffffff8129007a)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81291cdd)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff812a6c72)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff812b0177)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b4fbe)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (ffffffff812ce162)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff8134083d)
Location: include/linux/mm.h:2020
Inline: True
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
In mm/gup.c (ffffffff81245933)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff81247d8e)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/mremap.c (ffffffff8125a77a)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8125bfaa)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff8125cf95)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/hugetlb.c (ffffffff81281d3b)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81283926)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff81298718)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff812a1637)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812a5fec)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (ffffffff812bf015)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff81332f74)
Location: include/linux/mm.h:2020
Inline: True
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
In mm/gup.c (ffffffff81250909)
Location: include/linux/mm.h:2020
Inline: True
```
```
In mm/memory.c (ffffffff8125342e)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/mremap.c (ffffffff812662ea)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81267ad8)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff81268d05)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/hugetlb.c (ffffffff8128de8a)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8128faed)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff812a4a82)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff812adf87)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b2dce)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (ffffffff812cbf72)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff8133e30d)
Location: include/linux/mm.h:2020
Inline: True
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
In mm/gup.c (ffffffff8126028f)
Location: include/linux/mm.h:2020
Inline: True
```
```
In mm/memory.c (ffffffff81262e35)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/mremap.c (ffffffff81275c7b)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8127746e)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff81278695)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/hugetlb.c (ffffffff8129dc38)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8129e33b)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff812b55dd)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff812be2de)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812c320b)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (ffffffff812dcce6)
Location: include/linux/mm.h:2020
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff81352669)
Location: include/linux/mm.h:2020
Inline: True
```
</details>
</li>
</ul>

## Differences
