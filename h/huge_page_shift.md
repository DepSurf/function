# Function: <code>huge_page_shift</code>

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
In mm/hugetlb.c (0)
Location: include/linux/hugetlb.h:400
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/hugetlb.h:400
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/hugetlb.h:400
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff812f37d1)
Location: include/linux/hugetlb.h:400
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/hugetlb.c (ffffffff811fdd09)
Location: include/linux/hugetlb.h:396
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault_mutex_hash
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:vma_mmu_pagesize
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff8120080a)
Location: include/linux/hugetlb.h:396
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_zonelist
```
```
In mm/migrate.c (0)
Location: include/linux/hugetlb.h:396
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff81328af1)
Location: include/linux/hugetlb.h:396
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
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
In mm/hugetlb.c (ffffffff8120e807)
Location: include/linux/hugetlb.h:396
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault_mutex_hash
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:vma_mmu_pagesize
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff8121216a)
Location: include/linux/hugetlb.h:396
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_zonelist
```
```
In mm/migrate.c (0)
Location: include/linux/hugetlb.h:396
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff8133e831)
Location: include/linux/hugetlb.h:396
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
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
In mm/hugetlb.c (ffffffff8121a127)
Location: include/linux/hugetlb.h:418
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault_mutex_hash
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff8121d52d)
Location: include/linux/hugetlb.h:418
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
```
```
In mm/migrate.c (0)
Location: include/linux/hugetlb.h:418
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff8135340e)
Location: include/linux/hugetlb.h:418
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
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
In mm/hugetlb.c (ffffffff812351f7)
Location: include/linux/hugetlb.h:412
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault_mutex_hash
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff81238721)
Location: include/linux/hugetlb.h:412
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
```
```
In mm/migrate.c (0)
Location: include/linux/hugetlb.h:412
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff81378032)
Location: include/linux/hugetlb.h:412
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
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
In mm/page_alloc.c (0)
Location: include/linux/hugetlb.h:425
Inline: True
```
```
In mm/hugetlb.c (ffffffff81257fd1)
Location: include/linux/hugetlb.h:425
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault_mutex_hash
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff8125bc41)
Location: include/linux/hugetlb.h:425
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/hugetlb.h:425
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/hugetlb.h:425
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff813a6a62)
Location: include/linux/hugetlb.h:425
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
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
Location: include/linux/hugetlb.h:436
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/page_alloc.c (0)
Location: include/linux/hugetlb.h:436
Inline: True
```
```
In mm/mprotect.c (ffffffff8124d9f5)
Location: include/linux/hugetlb.h:436
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124f4b4)
Location: include/linux/hugetlb.h:436
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff81251f16)
Location: include/linux/hugetlb.h:436
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff812538a9)
Location: include/linux/hugetlb.h:436
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8126b460)
Location: include/linux/hugetlb.h:436
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault_mutex_hash
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff81270501)
Location: include/linux/hugetlb.h:436
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/hugetlb.h:436
Inline: True
```
```
In mm/migrate.c (ffffffff812830be)
Location: include/linux/hugetlb.h:436
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8128b37f)
Location: include/linux/hugetlb.h:436
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In fs/hugetlbfs/inode.c (ffffffff813bf888)
Location: include/linux/hugetlb.h:436
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
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
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mprotect.c (ffffffff8126000d)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81261809)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff8126425c)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_collapse_flush
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff81265af1)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (0)
Location: include/linux/hugetlb.h:424
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128673b)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff8128be04)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
```
```
In mm/migrate.c (0)
Location: include/linux/hugetlb.h:424
Inline: True
```
```
In mm/huge_memory.c (ffffffff812a5f8f)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/hmm.c (ffffffff812c3187)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_fault
  - mm/hmm.c:hmm_range_snapshot
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/hugetlbfs/inode.c (ffffffff813ea0c0)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
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
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mprotect.c (ffffffff8126e8fd)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8126ffc7)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff81272acc)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_collapse_flush
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff81274410)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (0)
Location: include/linux/hugetlb.h:424
Inline: True
```
```
In mm/hugetlb.c (ffffffff81296320)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff8129b9d4)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
```
```
In mm/migrate.c (ffffffff812aeb0d)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812b7451)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In fs/hugetlbfs/inode.c (ffffffff81404160)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
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
Location: include/linux/hugetlb.h:573
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mprotect.c (ffffffff8129f128)
Location: include/linux/hugetlb.h:573
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8129fea5)
Location: include/linux/hugetlb.h:573
Inline: True
Inline callers:
  - mm/mremap.c:move_normal_pmd
```
```
In mm/pgtable-generic.c (ffffffff812a3824)
Location: include/linux/hugetlb.h:573
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff812a56bb)
Location: include/linux/hugetlb.h:573
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff812b4027)
Location: include/linux/hugetlb.h:573
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff812c98a1)
Location: include/linux/hugetlb.h:573
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:dequeue_huge_page_vma
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff812cf5ab)
Location: include/linux/hugetlb.h:573
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:vma_migratable
```
```
In mm/migrate.c (ffffffff812e43eb)
Location: include/linux/hugetlb.h:573
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/huge_memory.c (ffffffff812ec5f1)
Location: include/linux/hugetlb.h:573
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c3e6)
Location: include/linux/hugetlb.h:573
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/hugetlbfs/inode.c (ffffffff81451fa0)
Location: include/linux/hugetlb.h:573
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
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
Location: include/linux/hugetlb.h:571
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mprotect.c (ffffffff812aa4e8)
Location: include/linux/hugetlb.h:571
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812ab0dc)
Location: include/linux/hugetlb.h:571
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812af104)
Location: include/linux/hugetlb.h:571
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff812b0c24)
Location: include/linux/hugetlb.h:571
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff812bfabc)
Location: include/linux/hugetlb.h:571
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff812d542f)
Location: include/linux/hugetlb.h:571
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:allowed_mems_nr
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:dequeue_huge_page_vma
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff812db07b)
Location: include/linux/hugetlb.h:571
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:vma_migratable
```
```
In mm/migrate.c (ffffffff812efded)
Location: include/linux/hugetlb.h:571
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/huge_memory.c (ffffffff812f7669)
Location: include/linux/hugetlb.h:571
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff81318326)
Location: include/linux/hugetlb.h:571
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/hugetlbfs/inode.c (ffffffff8146e4e0)
Location: include/linux/hugetlb.h:571
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
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
Location: include/linux/hugetlb.h:684
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mprotect.c (ffffffff812af928)
Location: include/linux/hugetlb.h:684
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812b05dc)
Location: include/linux/hugetlb.h:684
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812b45b3)
Location: include/linux/hugetlb.h:684
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff812b6763)
Location: include/linux/hugetlb.h:684
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff812c521c)
Location: include/linux/hugetlb.h:684
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff812dea01)
Location: include/linux/hugetlb.h:684
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:restore_reserve_on_error
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff812e28e7)
Location: include/linux/hugetlb.h:684
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:vma_migratable
```
```
In mm/migrate.c (ffffffff812f573c)
Location: include/linux/hugetlb.h:684
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/huge_memory.c (ffffffff812fdb28)
Location: include/linux/hugetlb.h:684
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131e516)
Location: include/linux/hugetlb.h:684
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/hugetlbfs/inode.c (ffffffff81473b20)
Location: include/linux/hugetlb.h:684
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
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
Location: include/linux/hugetlb.h:707
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mprotect.c (ffffffff812f1170)
Location: include/linux/hugetlb.h:707
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812f2ca1)
Location: include/linux/hugetlb.h:707
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff812f6193)
Location: include/linux/hugetlb.h:707
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff812f897a)
Location: include/linux/hugetlb.h:707
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff81309769)
Location: include/linux/hugetlb.h:707
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff81325de6)
Location: include/linux/hugetlb.h:707
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff81329c4f)
Location: include/linux/hugetlb.h:707
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:vma_migratable
```
```
In mm/migrate.c (ffffffff8133fd38)
Location: include/linux/hugetlb.h:707
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/huge_memory.c (ffffffff813476c8)
Location: include/linux/hugetlb.h:707
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
```
```
In mm/memory-failure.c (ffffffff8135ec37)
Location: include/linux/hugetlb.h:707
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_hugetlb_range
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136b8f6)
Location: include/linux/hugetlb.h:707
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/hugetlbfs/inode.c (ffffffff814ca751)
Location: include/linux/hugetlb.h:707
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_size_to_hpages
  - fs/hugetlbfs/inode.c:hugetlbfs_size_to_hpages
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In drivers/dma-buf/udmabuf.c (ffffffff818ab580)
Location: include/linux/hugetlb.h:707
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
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
Location: include/linux/hugetlb.h:737
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mremap.c (ffffffff81356970)
Location: include/linux/hugetlb.h:737
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff8135a1a4)
Location: include/linux/hugetlb.h:737
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff8135ef5f)
Location: include/linux/hugetlb.h:737
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81394b51)
Location: include/linux/hugetlb.h:737
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:dequeue_huge_page_vma
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff81399087)
Location: include/linux/hugetlb.h:737
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:vma_migratable
```
```
In mm/migrate.c (ffffffff813b17bd)
Location: include/linux/hugetlb.h:737
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/migrate_device.c (ffffffff813b7124)
Location: include/linux/hugetlb.h:737
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813bda30)
Location: include/linux/hugetlb.h:737
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
```
```
In mm/memory-failure.c (ffffffff813d90c7)
Location: include/linux/hugetlb.h:737
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_hugetlb_range
```
```
In mm/page_isolation.c (ffffffff813ddd4e)
Location: include/linux/hugetlb.h:737
Inline: True
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9a8b)
Location: include/linux/hugetlb.h:737
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/hugetlbfs/inode.c (ffffffff81556706)
Location: include/linux/hugetlb.h:737
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_size_to_hpages
  - fs/hugetlbfs/inode.c:hugetlbfs_size_to_hpages
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In drivers/dma-buf/udmabuf.c (ffffffff819f5f86)
Location: include/linux/hugetlb.h:737
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
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
Location: include/linux/hugetlb.h:776
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mremap.c (ffffffff813d0f3a)
Location: include/linux/hugetlb.h:776
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff813d4c24)
Location: include/linux/hugetlb.h:776
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff813d9e08)
Location: include/linux/hugetlb.h:776
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8140de24)
Location: include/linux/hugetlb.h:776
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:dequeue_huge_page_vma
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff81418f07)
Location: include/linux/hugetlb.h:776
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:vma_migratable
```
```
In mm/migrate.c (ffffffff81432b23)
Location: include/linux/hugetlb.h:776
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/migrate_device.c (ffffffff814391b1)
Location: include/linux/hugetlb.h:776
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8144024a)
Location: include/linux/hugetlb.h:776
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
```
```
In mm/memory-failure.c (ffffffff8145f0e7)
Location: include/linux/hugetlb.h:776
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_hugetlb_range
```
```
In mm/page_isolation.c (ffffffff814649f2)
Location: include/linux/hugetlb.h:776
Inline: True
```
```
In mm/mapping_dirty_helpers.c (ffffffff81471acb)
Location: include/linux/hugetlb.h:776
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/hugetlbfs/inode.c (ffffffff815f8205)
Location: include/linux/hugetlb.h:776
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_size_to_hpages
  - fs/hugetlbfs/inode.c:hugetlbfs_size_to_hpages
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81b73551)
Location: include/linux/hugetlb.h:776
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
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
Location: include/linux/hugetlb.h:804
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mremap.c (ffffffff814059af)
Location: include/linux/hugetlb.h:804
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff8140967a)
Location: include/linux/hugetlb.h:804
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff8140e521)
Location: include/linux/hugetlb.h:804
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81441201)
Location: include/linux/hugetlb.h:804
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_hugetlb_folio_vma
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:dequeue_hugetlb_folio_vma
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff8144c3d7)
Location: include/linux/hugetlb.h:804
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:vma_migratable
  - mm/mempolicy.c:vma_migratable
```
```
In mm/migrate.c (ffffffff814674a2)
Location: include/linux/hugetlb.h:804
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_hugetlbs
  - mm/migrate.c:migrate_hugetlbs
```
```
In mm/migrate_device.c (ffffffff8146f550)
Location: include/linux/hugetlb.h:804
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814759b6)
Location: include/linux/hugetlb.h:804
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
```
```
In mm/memory-failure.c (ffffffff81495097)
Location: include/linux/hugetlb.h:804
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_hugetlb_range
```
```
In mm/page_isolation.c (ffffffff8149a4f2)
Location: include/linux/hugetlb.h:804
Inline: True
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a641a)
Location: include/linux/hugetlb.h:804
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/hugetlbfs/inode.c (ffffffff81630185)
Location: include/linux/hugetlb.h:804
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_size_to_hpages
  - fs/hugetlbfs/inode.c:hugetlbfs_size_to_hpages
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
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
Location: include/linux/hugetlb.h:825
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mremap.c (ffffffff81431bf3)
Location: include/linux/hugetlb.h:825
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff81435e6a)
Location: include/linux/hugetlb.h:825
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff8143ad20)
Location: include/linux/hugetlb.h:825
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8147b38e)
Location: include/linux/hugetlb.h:825
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_pool_huge_folio
  - mm/hugetlb.c:dequeue_hugetlb_folio_vma
```
```
In mm/mempolicy.c (ffffffff814847dc)
Location: include/linux/hugetlb.h:825
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
  - mm/mempolicy.c:vma_migratable
  - mm/mempolicy.c:alloc_migration_target_by_mpol
```
```
In mm/migrate.c (ffffffff8149662c)
Location: include/linux/hugetlb.h:825
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_hugetlbs
  - mm/migrate.c:migrate_hugetlbs
```
```
In mm/migrate_device.c (ffffffff8149e051)
Location: include/linux/hugetlb.h:825
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a5386)
Location: include/linux/hugetlb.h:825
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
```
```
In mm/memory-failure.c (ffffffff814c4997)
Location: include/linux/hugetlb.h:825
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_hugetlb_range
```
```
In mm/page_isolation.c (ffffffff814c9cd8)
Location: include/linux/hugetlb.h:825
Inline: True
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d736a)
Location: include/linux/hugetlb.h:825
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/proc/task_mmu.c (ffffffff8159d606)
Location: include/linux/hugetlb.h:825
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_scan_hugetlb_entry
  - fs/proc/task_mmu.c:pagemap_scan_pmd_entry
```
```
In fs/hugetlbfs/inode.c (ffffffff81669635)
Location: include/linux/hugetlb.h:825
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_size_to_hpages
  - fs/hugetlbfs/inode.c:hugetlbfs_size_to_hpages
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
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
In virt/kvm/arm/mmu.c (ffff8000100cb09c)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:user_mem_abort
```
```
In mm/hugetlb.c (ffff8000103356a0)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffff80001033a970)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
```
```
In fs/hugetlbfs/inode.c (ffff8000104e29c8)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable.c:huge_ptep_set_access_flags
```
```
In arch/powerpc/mm/book3s64/radix_hugetlbpage.c (c00000000009ec10)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_hugetlbpage.c:radix__flush_hugetlb_tlb_range
  - arch/powerpc/mm/book3s64/radix_hugetlbpage.c:radix__local_flush_hugetlb_page
  - arch/powerpc/mm/book3s64/radix_hugetlbpage.c:radix__flush_hugetlb_page
```
```
In arch/powerpc/mm/hugetlbpage.c (c0000000000a643c)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In mm/page_alloc.c (c0000000003ed490)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (c00000000040f714)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (c0000000004152f0)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
```
```
In mm/migrate.c (c000000000437530)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In fs/hugetlbfs/inode.c (c00000000061fb50)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
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
In mm/hugetlb.c (ffffffe000231afe)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:linear_hugepage_index
```
```
In fs/hugetlbfs/inode.c (ffffffe0003564ee)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
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
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mprotect.c (ffffffff81266f4d)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81268617)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff8126b11c)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_collapse_flush
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff8126ca60)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (0)
Location: include/linux/hugetlb.h:424
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128e900)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff81293fb4)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
```
```
In mm/migrate.c (ffffffff812a70ed)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812afa31)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In fs/hugetlbfs/inode.c (ffffffff813fc740)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
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
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mprotect.c (ffffffff8125906d)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8125a8c9)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff8125d12c)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_collapse_flush
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff8125eac0)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (0)
Location: include/linux/hugetlb.h:424
Inline: True
```
```
In mm/hugetlb.c (ffffffff812806a5)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff81285bc4)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
```
```
In mm/migrate.c (ffffffff81298b16)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812a0f0f)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In fs/hugetlbfs/inode.c (ffffffff813ed1c0)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
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
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mprotect.c (ffffffff81264ced)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812663b7)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff81268ebc)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_collapse_flush
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff8126a800)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (0)
Location: include/linux/hugetlb.h:424
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128c710)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff81291dc4)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
```
```
In mm/migrate.c (ffffffff812a4efd)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812ad841)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In fs/hugetlbfs/inode.c (ffffffff813f9ac0)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
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
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In mm/mprotect.c (ffffffff81274687)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81275d48)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff8127884c)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_collapse_flush
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
```
```
In mm/rmap.c (ffffffff8127a17c)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (0)
Location: include/linux/hugetlb.h:424
Inline: True
```
```
In mm/hugetlb.c (ffffffff8129c4f8)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:__vma_reservation_common
  - mm/hugetlb.c:linear_hugepage_index
```
```
In mm/mempolicy.c (ffffffff812a1bd4)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/mempolicy.c:huge_node
```
```
In mm/migrate.c (ffffffff812b5a57)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812bdbbd)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In fs/hugetlbfs/inode.c (ffffffff8140f710)
Location: include/linux/hugetlb.h:424
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
</details>
</li>
</ul>

## Differences
