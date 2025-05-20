# Function: <code>hstate_vma</code>

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
In mm/mmap.c (ffffffff811c5447)
Location: include/linux/hugetlb.h:376
Inline: True
```
```
In mm/pagewalk.c (ffffffff811d0156)
Location: include/linux/hugetlb.h:376
Inline: True
```
```
In mm/hugetlb.c (ffffffff811dacc6)
Location: include/linux/hugetlb.h:376
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:linear_hugepage_index
  - mm/hugetlb.c:vma_mmu_pagesize
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/mempolicy.c (ffffffff811dfe1c)
Location: include/linux/hugetlb.h:376
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:huge_zonelist
```
```
In mm/migrate.c (ffffffff811f0dfa)
Location: include/linux/hugetlb.h:376
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:migration_entry_wait_huge
```
```
In fs/proc/task_mmu.c (ffffffff81278163)
Location: include/linux/hugetlb.h:376
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/mmap.c (ffffffff811e12a8)
Location: include/linux/hugetlb.h:372
Inline: True
```
```
In mm/pagewalk.c (ffffffff811ed2e9)
Location: include/linux/hugetlb.h:372
Inline: True
```
```
In mm/hugetlb.c (ffffffff811fc919)
Location: include/linux/hugetlb.h:372
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:vma_mmu_pagesize
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff812007f1)
Location: include/linux/hugetlb.h:372
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_zonelist
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff812119bc)
Location: include/linux/hugetlb.h:372
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:remove_migration_pte
```
```
In fs/proc/task_mmu.c (ffffffff812a4a7e)
Location: include/linux/hugetlb.h:372
Inline: True
Inline callers:
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
In mm/mmap.c (ffffffff811f1268)
Location: include/linux/hugetlb.h:372
Inline: True
```
```
In mm/pagewalk.c (ffffffff811f76d9)
Location: include/linux/hugetlb.h:372
Inline: True
```
```
In mm/hugetlb.c (ffffffff8120d403)
Location: include/linux/hugetlb.h:372
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:vma_mmu_pagesize
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff81212151)
Location: include/linux/hugetlb.h:372
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_zonelist
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff81223b66)
Location: include/linux/hugetlb.h:372
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:remove_migration_pte
```
```
In fs/proc/task_mmu.c (ffffffff812ba3ee)
Location: include/linux/hugetlb.h:372
Inline: True
Inline callers:
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
In mm/mmap.c (ffffffff811fcc48)
Location: include/linux/hugetlb.h:394
Inline: True
Inline callers:
  - mm/mmap.c:__split_vma
```
```
In mm/pagewalk.c (ffffffff8120256d)
Location: include/linux/hugetlb.h:394
Inline: True
```
```
In mm/hugetlb.c (ffffffff812192ad)
Location: include/linux/hugetlb.h:394
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff8121d514)
Location: include/linux/hugetlb.h:394
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff8122f4a6)
Location: include/linux/hugetlb.h:394
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/userfaultfd.c (ffffffff8124b713)
Location: include/linux/hugetlb.h:394
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:394
Inline: True
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
In mm/pagewalk.c (ffffffff8121b1dc)
Location: include/linux/hugetlb.h:388
Inline: True
```
```
In mm/hugetlb.c (ffffffff81234262)
Location: include/linux/hugetlb.h:388
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_split
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff81238704)
Location: include/linux/hugetlb.h:388
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff8124cda6)
Location: include/linux/hugetlb.h:388
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/userfaultfd.c (ffffffff8126ba35)
Location: include/linux/hugetlb.h:388
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:388
Inline: True
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
In mm/pagewalk.c (ffffffff8123d28e)
Location: include/linux/hugetlb.h:401
Inline: True
```
```
In mm/hugetlb.c (ffffffff81257192)
Location: include/linux/hugetlb.h:401
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_split
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff8125bc24)
Location: include/linux/hugetlb.h:401
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff812708a5)
Location: include/linux/hugetlb.h:401
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/userfaultfd.c (ffffffff8129051a)
Location: include/linux/hugetlb.h:401
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:401
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
In arch/x86/mm/pgtable.c (ffffffff8108314a)
Location: include/linux/hugetlb.h:412
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mprotect.c (ffffffff8124d9f5)
Location: include/linux/hugetlb.h:412
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124f4b4)
Location: include/linux/hugetlb.h:412
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812518b1)
Location: include/linux/hugetlb.h:412
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81251f16)
Location: include/linux/hugetlb.h:412
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff812538a9)
Location: include/linux/hugetlb.h:412
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8126b802)
Location: include/linux/hugetlb.h:412
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_split
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff812704e4)
Location: include/linux/hugetlb.h:412
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff812830be)
Location: include/linux/hugetlb.h:412
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff8128b37f)
Location: include/linux/hugetlb.h:412
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/userfaultfd.c (ffffffff812a54f0)
Location: include/linux/hugetlb.h:412
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:412
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
In arch/x86/mm/pgtable.c (ffffffff81086ddb)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mprotect.c (ffffffff8126000d)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81261809)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81263b81)
Location: include/linux/hugetlb.h:400
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff8126425c)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_collapse_flush
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff81265af1)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81286afa)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_split
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff8128bde7)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff8129f535)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff812a5f8f)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/userfaultfd.c (ffffffff812c093b)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812c3187)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_fault
  - mm/hmm.c:hmm_range_snapshot
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:400
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
In arch/x86/mm/pgtable.c (ffffffff81087acb)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mprotect.c (ffffffff8126e8fd)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8126ffc7)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81272384)
Location: include/linux/hugetlb.h:400
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81272acc)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_collapse_flush
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff81274410)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff812966fa)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_split
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff8129b9b7)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff812aeb0d)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff812b7451)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/userfaultfd.c (ffffffff812d2a53)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812d59ec)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:400
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
In arch/x86/mm/pgtable.c (ffffffff81089f07)
Location: include/linux/hugetlb.h:549
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mprotect.c (ffffffff8129f128)
Location: include/linux/hugetlb.h:549
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8129fea5)
Location: include/linux/hugetlb.h:549
Inline: True
Inline callers:
  - mm/mremap.c:move_normal_pmd
```
```
In mm/pagewalk.c (ffffffff812a2315)
Location: include/linux/hugetlb.h:549
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_hugetlb_range
```
```
In mm/pgtable-generic.c (ffffffff812a3824)
Location: include/linux/hugetlb.h:549
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff812a56bb)
Location: include/linux/hugetlb.h:549
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff812c9c77)
Location: include/linux/hugetlb.h:549
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_split
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff812cf5ab)
Location: include/linux/hugetlb.h:549
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:vma_migratable
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff812e43eb)
Location: include/linux/hugetlb.h:549
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff812ec5f1)
Location: include/linux/hugetlb.h:549
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/hmm.c (ffffffff8130b659)
Location: include/linux/hugetlb.h:549
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c3e6)
Location: include/linux/hugetlb.h:549
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/proc/task_mmu.c (ffffffff813b7bb3)
Location: include/linux/hugetlb.h:549
Inline: True
Inline callers:
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
In arch/x86/mm/pgtable.c (ffffffff8108a187)
Location: include/linux/hugetlb.h:547
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mprotect.c (ffffffff812aa4e8)
Location: include/linux/hugetlb.h:547
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812ab0dc)
Location: include/linux/hugetlb.h:547
Inline: True
```
```
In mm/pagewalk.c (ffffffff812adc55)
Location: include/linux/hugetlb.h:547
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_hugetlb_range
```
```
In mm/pgtable-generic.c (ffffffff812af104)
Location: include/linux/hugetlb.h:547
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff812b0c24)
Location: include/linux/hugetlb.h:547
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff812d58b7)
Location: include/linux/hugetlb.h:547
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_split
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff812db07b)
Location: include/linux/hugetlb.h:547
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:vma_migratable
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff812efded)
Location: include/linux/hugetlb.h:547
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff812f7669)
Location: include/linux/hugetlb.h:547
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/hmm.c (ffffffff81317519)
Location: include/linux/hugetlb.h:547
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/mapping_dirty_helpers.c (ffffffff81318326)
Location: include/linux/hugetlb.h:547
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/proc/task_mmu.c (ffffffff813c9640)
Location: include/linux/hugetlb.h:547
Inline: True
Inline callers:
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
In arch/x86/mm/pgtable.c (ffffffff8108ade7)
Location: include/linux/hugetlb.h:660
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mprotect.c (ffffffff812af928)
Location: include/linux/hugetlb.h:660
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812b05dc)
Location: include/linux/hugetlb.h:660
Inline: True
```
```
In mm/pagewalk.c (ffffffff812b3c72)
Location: include/linux/hugetlb.h:660
Inline: True
Inline callers:
  - mm/pagewalk.c:__walk_page_range
```
```
In mm/pgtable-generic.c (ffffffff812b45b3)
Location: include/linux/hugetlb.h:660
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff812b6763)
Location: include/linux/hugetlb.h:660
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff812de81a)
Location: include/linux/hugetlb.h:660
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_split
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff812e28e7)
Location: include/linux/hugetlb.h:660
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:vma_migratable
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff812f573c)
Location: include/linux/hugetlb.h:660
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff812fdb28)
Location: include/linux/hugetlb.h:660
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/hmm.c (ffffffff8131d219)
Location: include/linux/hugetlb.h:660
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131e516)
Location: include/linux/hugetlb.h:660
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/proc/task_mmu.c (ffffffff813d0745)
Location: include/linux/hugetlb.h:660
Inline: True
Inline callers:
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
In arch/x86/mm/pgtable.c (ffffffff8109a387)
Location: include/linux/hugetlb.h:683
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mprotect.c (ffffffff812f1170)
Location: include/linux/hugetlb.h:683
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812f2ca1)
Location: include/linux/hugetlb.h:683
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812f5832)
Location: include/linux/hugetlb.h:683
Inline: True
Inline callers:
  - mm/pagewalk.c:__walk_page_range
```
```
In mm/pgtable-generic.c (ffffffff812f6193)
Location: include/linux/hugetlb.h:683
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff812f897a)
Location: include/linux/hugetlb.h:683
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81325be9)
Location: include/linux/hugetlb.h:683
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_split
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff81329c4f)
Location: include/linux/hugetlb.h:683
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:vma_migratable
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff8133fd38)
Location: include/linux/hugetlb.h:683
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff813476c8)
Location: include/linux/hugetlb.h:683
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
```
```
In mm/memory-failure.c (ffffffff8135ec37)
Location: include/linux/hugetlb.h:683
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_hugetlb_range
```
```
In mm/hmm.c (ffffffff8136a5a9)
Location: include/linux/hugetlb.h:683
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136b8f6)
Location: include/linux/hugetlb.h:683
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/proc/task_mmu.c (ffffffff81421b41)
Location: include/linux/hugetlb.h:683
Inline: True
Inline callers:
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
In arch/x86/mm/pgtable.c (ffffffff810ad4e7)
Location: include/linux/hugetlb.h:713
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mremap.c (ffffffff813575e8)
Location: include/linux/hugetlb.h:713
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff813585c0)
Location: include/linux/hugetlb.h:713
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813596fc)
Location: include/linux/hugetlb.h:713
Inline: True
Inline callers:
  - mm/pagewalk.c:__walk_page_range
```
```
In mm/pgtable-generic.c (ffffffff8135a1a4)
Location: include/linux/hugetlb.h:713
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff8135ef5f)
Location: include/linux/hugetlb.h:713
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81375459)
Location: include/linux/hugetlb.h:713
Inline: True
```
```
In mm/hugetlb.c (ffffffff81394939)
Location: include/linux/hugetlb.h:713
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_split
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff81399087)
Location: include/linux/hugetlb.h:713
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:vma_migratable
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff813b4c2a)
Location: include/linux/hugetlb.h:713
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/migrate_device.c (ffffffff813b7124)
Location: include/linux/hugetlb.h:713
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813bda30)
Location: include/linux/hugetlb.h:713
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
```
```
In mm/memory-failure.c (ffffffff813d90c7)
Location: include/linux/hugetlb.h:713
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_hugetlb_range
```
```
In mm/hmm.c (ffffffff813e816c)
Location: include/linux/hugetlb.h:713
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9a8b)
Location: include/linux/hugetlb.h:713
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/proc/task_mmu.c (ffffffff8149af52)
Location: include/linux/hugetlb.h:713
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In arch/x86/mm/pgtable.c (ffffffff810c7627)
Location: include/linux/hugetlb.h:752
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mremap.c (ffffffff813d1b29)
Location: include/linux/hugetlb.h:752
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff813d2d28)
Location: include/linux/hugetlb.h:752
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813d3fa2)
Location: include/linux/hugetlb.h:752
Inline: True
Inline callers:
  - mm/pagewalk.c:__walk_page_range
```
```
In mm/pgtable-generic.c (ffffffff813d4c24)
Location: include/linux/hugetlb.h:752
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff813d9e08)
Location: include/linux/hugetlb.h:752
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff813f338c)
Location: include/linux/hugetlb.h:752
Inline: True
```
```
In mm/hugetlb.c (ffffffff8140dc80)
Location: include/linux/hugetlb.h:752
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_split
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff81418f07)
Location: include/linux/hugetlb.h:752
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:vma_migratable
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff81433dc9)
Location: include/linux/hugetlb.h:752
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/migrate_device.c (ffffffff814391b1)
Location: include/linux/hugetlb.h:752
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8144024a)
Location: include/linux/hugetlb.h:752
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
```
```
In mm/memory-failure.c (ffffffff8145f0e7)
Location: include/linux/hugetlb.h:752
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_hugetlb_range
```
```
In mm/hmm.c (ffffffff81470079)
Location: include/linux/hugetlb.h:752
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/mapping_dirty_helpers.c (ffffffff81471acb)
Location: include/linux/hugetlb.h:752
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/proc/task_mmu.c (ffffffff8152f990)
Location: include/linux/hugetlb.h:752
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In fs/hugetlbfs/inode.c (ffffffff815f65b5)
Location: include/linux/hugetlb.h:752
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
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
In arch/x86/mm/pgtable.c (ffffffff810cad77)
Location: include/linux/hugetlb.h:780
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mremap.c (ffffffff814066c5)
Location: include/linux/hugetlb.h:780
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81407aba)
Location: include/linux/hugetlb.h:780
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8140897f)
Location: include/linux/hugetlb.h:780
Inline: True
Inline callers:
  - mm/pagewalk.c:__walk_page_range
```
```
In mm/pgtable-generic.c (ffffffff8140967a)
Location: include/linux/hugetlb.h:780
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff8140e521)
Location: include/linux/hugetlb.h:780
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81426ddf)
Location: include/linux/hugetlb.h:780
Inline: True
```
```
In mm/hugetlb.c (ffffffff81441040)
Location: include/linux/hugetlb.h:780
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_split
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff8144c3d7)
Location: include/linux/hugetlb.h:780
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:vma_migratable
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/migrate.c (ffffffff81469671)
Location: include/linux/hugetlb.h:780
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/migrate_device.c (ffffffff8146f550)
Location: include/linux/hugetlb.h:780
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814759b6)
Location: include/linux/hugetlb.h:780
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
```
```
In mm/memory-failure.c (ffffffff81495097)
Location: include/linux/hugetlb.h:780
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_hugetlb_range
```
```
In mm/hmm.c (ffffffff814a4849)
Location: include/linux/hugetlb.h:780
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a641a)
Location: include/linux/hugetlb.h:780
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/proc/task_mmu.c (ffffffff815681b5)
Location: include/linux/hugetlb.h:780
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In fs/hugetlbfs/inode.c (ffffffff8162e675)
Location: include/linux/hugetlb.h:780
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
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
In arch/x86/mm/pgtable.c (ffffffff810d32c7)
Location: include/linux/hugetlb.h:801
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mremap.c (ffffffff81432dd4)
Location: include/linux/hugetlb.h:801
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff814340cc)
Location: include/linux/hugetlb.h:801
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8143509f)
Location: include/linux/hugetlb.h:801
Inline: True
Inline callers:
  - mm/pagewalk.c:__walk_page_range
```
```
In mm/pgtable-generic.c (ffffffff81435e6a)
Location: include/linux/hugetlb.h:801
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff8143ad20)
Location: include/linux/hugetlb.h:801
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff814600af)
Location: include/linux/hugetlb.h:801
Inline: True
```
```
In mm/hugetlb.c (ffffffff8147b170)
Location: include/linux/hugetlb.h:801
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_split
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_hugetlb_folio
```
```
In mm/mempolicy.c (ffffffff81485680)
Location: include/linux/hugetlb.h:801
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:vma_migratable
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/migrate.c (ffffffff814985a1)
Location: include/linux/hugetlb.h:801
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8149e051)
Location: include/linux/hugetlb.h:801
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a5386)
Location: include/linux/hugetlb.h:801
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
```
```
In mm/memory-failure.c (ffffffff814c4997)
Location: include/linux/hugetlb.h:801
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_hugetlb_range
```
```
In mm/hmm.c (ffffffff814d5879)
Location: include/linux/hugetlb.h:801
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d736a)
Location: include/linux/hugetlb.h:801
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/proc/task_mmu.c (ffffffff8159d483)
Location: include/linux/hugetlb.h:801
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_scan_hugetlb_entry
  - fs/proc/task_mmu.c:pagemap_scan_hugetlb_entry
  - fs/proc/task_mmu.c:pagemap_scan_pmd_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In fs/hugetlbfs/inode.c (ffffffff81667b45)
Location: include/linux/hugetlb.h:801
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
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
In arch/arm64/mm/hugetlbpage.c (ffff8000100b116c)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - arch/arm64/mm/hugetlbpage.c:arch_make_huge_pte
```
```
In virt/kvm/arm/mmu.c (ffff8000100caeb0)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:user_mem_abort
```
```
In mm/pagewalk.c (ffff800010307ba0)
Location: include/linux/hugetlb.h:400
Inline: True
```
```
In mm/hugetlb.c (ffff80001033373c)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_split
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffff80001033a958)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffff800010350e94)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/userfaultfd.c (ffff800010378780)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffff80001037b250)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:400
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (0)
Location: include/linux/hugetlb.h:634
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
In arch/powerpc/mm/pgtable.c (c0000000000880e0)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable.c:huge_ptep_set_access_flags
```
```
In mm/pagewalk.c (c0000000003d6488)
Location: include/linux/hugetlb.h:400
Inline: True
```
```
In mm/hugetlb.c (c00000000040faec)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_split
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (c0000000004152d4)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (c000000000436e40)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/userfaultfd.c (c00000000046b2a4)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (c00000000046fac8)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:400
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
In mm/pagewalk.c (ffffffe000212b60)
Location: include/linux/hugetlb.h:400
Inline: True
```
```
In mm/hugetlb.c (ffffffe000230c3c)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_split
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/migrate.c (0)
Location: include/linux/hugetlb.h:400
Inline: True
```
```
In mm/userfaultfd.c (ffffffe000250132)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (0)
Location: include/linux/hugetlb.h:400
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:400
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
In arch/x86/mm/pgtable.c (ffffffff81086acb)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mprotect.c (ffffffff81266f4d)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81268617)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8126a9d4)
Location: include/linux/hugetlb.h:400
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff8126b11c)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_collapse_flush
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff8126ca60)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8128ecda)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_split
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff81293f97)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff812a70ed)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff812afa31)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/userfaultfd.c (ffffffff812cb033)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812cdfcc)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:400
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
In arch/x86/mm/pgtable.c (ffffffff8107575b)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mprotect.c (ffffffff8125906d)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8125a8c9)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8125cb34)
Location: include/linux/hugetlb.h:400
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff8125d12c)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_collapse_flush
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff8125eac0)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81280a5d)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_split
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff81285ba7)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff81298b16)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff812a0f0f)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/userfaultfd.c (ffffffff812bbf91)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812bee39)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:400
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
In arch/x86/mm/pgtable.c (ffffffff81086a7b)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mprotect.c (ffffffff81264ced)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812663b7)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81268774)
Location: include/linux/hugetlb.h:400
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81268ebc)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_collapse_flush
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff8126a800)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8128caea)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_split
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff81291da7)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff812a4efd)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff812ad841)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/userfaultfd.c (ffffffff812c8e43)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812cbddc)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:400
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
In arch/x86/mm/pgtable.c (ffffffff81088bab)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mprotect.c (ffffffff81274687)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81275d48)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81278104)
Location: include/linux/hugetlb.h:400
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff8127884c)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_collapse_flush
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff8127a17c)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8129c8ba)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_split
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff812a1bb7)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff812b5a57)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff812bdbbd)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/userfaultfd.c (ffffffff812d9b3f)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812dcb3a)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:400
Inline: True
```
</details>
</li>
</ul>

## Differences
