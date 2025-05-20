# Function: <code>pmd_trans_huge</code>

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
In mm/gup.c (ffffffff811ba90e)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811bd36e)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811c2737)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811c8772)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811c94e9)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811ca8f6)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/pagewalk.c (ffffffff811cffb1)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
```
```
In mm/madvise.c (ffffffff811d14dd)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff811d433d)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff811e0037)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff811f5dba)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:page_check_address_pmd
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memcontrol.c (ffffffff811faf91)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
```
In mm/userfaultfd.c (ffffffff81207939)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
```
```
In fs/userfaultfd.c (ffffffff8125afb7)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff812782c6)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/filemap.c (ffffffff811a16b4)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (ffffffff811d5261)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811dac11)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811de294)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811e4a18)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811e5be3)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811e77f3)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:mm_find_pmd
```
```
In mm/pagewalk.c (ffffffff811ecf37)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
```
```
In mm/madvise.c (ffffffff811eea86)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff811f2133)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff811ff25b)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff81215ea5)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81220f9f)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff8122d7b4)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/userfaultfd.c (ffffffff81283b7d)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff812a54f7)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/filemap.c (ffffffff811b152b)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (ffffffff811e527c)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811ea7d4)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811ee0a4)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811f4a03)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f5e63)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff811f6f2f)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff811f7327)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
```
```
In mm/rmap.c (ffffffff811f8b83)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (ffffffff811ff3c6)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81202b2b)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff81210567)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff812284c4)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812336f3)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff8123fcf2)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/userfaultfd.c (ffffffff81297770)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff8129c99b)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff812bae47)
Location: arch/x86/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/filemap.c (ffffffff811b77cb)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (ffffffff811f09eb)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
```
```
In mm/memory.c (ffffffff811f57cd)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811f90ab)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811ff8b0)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81200c5b)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81201e27)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8120277a)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
```
```
In mm/rmap.c (ffffffff81203b30)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (ffffffff8120a07d)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8120dba0)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff8121bf53)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff812348c9)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8123efb3)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff8124bb3a)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/userfaultfd.c (ffffffff812a50a9)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff812aaf6d)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
```
```
In fs/proc/task_mmu.c (ffffffff812c7fc7)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_trans_huge(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cbd4b)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (ffffffff812055ac)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:follow_pmd_mask
Direct callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff8120e885)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff8121148f)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81217e8d)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81219167)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8121a784)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8121b54e)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
```
```
In mm/rmap.c (ffffffff8121c85c)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (ffffffff81223285)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81228e0f)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff81237358)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8124b5c8)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812527f9)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8125ebe2)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff8126be7e)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff8126e565)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff812c84f3)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff812ce7e7)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
```
```
In fs/proc/task_mmu.c (ffffffff812eb991)
Location: arch/x86/include/asm/pgtable.h:227
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81204f70-ffffffff81204f94: pmd_trans_huge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_trans_huge(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ecf5e)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (ffffffff81226a28)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff8123003f)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff8123222d)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81239c25)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
  - mm/mprotect.c:change_protection
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8123ab08)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8123c6a0)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8123d14d)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
```
```
In mm/rmap.c (ffffffff8123e623)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (ffffffff81246116)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8124a0fa)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff8125a899)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8126e34f)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81276c2f)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81282f4c)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff8129096b)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff81293177)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff812f1879)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff812f8e17)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81318e4f)
Location: arch/x86/include/asm/pgtable.h:237
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81225e70-ffffffff81225e96: pmd_trans_huge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_trans_huge(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fd051)
Location: arch/x86/include/asm/pgtable.h:239
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (ffffffff81239b05)
Location: arch/x86/include/asm/pgtable.h:239
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff81241d29)
Location: arch/x86/include/asm/pgtable.h:239
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff812459fd)
Location: arch/x86/include/asm/pgtable.h:239
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8124d5ef)
Location: arch/x86/include/asm/pgtable.h:239
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124ed14)
Location: arch/x86/include/asm/pgtable.h:239
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81250abd)
Location: arch/x86/include/asm/pgtable.h:239
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8125161d)
Location: arch/x86/include/asm/pgtable.h:239
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81252bb3)
Location: arch/x86/include/asm/pgtable.h:239
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (ffffffff8125a536)
Location: arch/x86/include/asm/pgtable.h:239
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8125e73a)
Location: arch/x86/include/asm/pgtable.h:239
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff8126e75f)
Location: arch/x86/include/asm/pgtable.h:239
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812831dd)
Location: arch/x86/include/asm/pgtable.h:239
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8128bb6a)
Location: arch/x86/include/asm/pgtable.h:239
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81298f9c)
Location: arch/x86/include/asm/pgtable.h:239
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff812a594c)
Location: arch/x86/include/asm/pgtable.h:239
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812a7567)
Location: arch/x86/include/asm/pgtable.h:239
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81306239)
Location: arch/x86/include/asm/pgtable.h:239
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff8130d453)
Location: arch/x86/include/asm/pgtable.h:239
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8132feff)
Location: arch/x86/include/asm/pgtable.h:239
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff812395e0-ffffffff81239606: pmd_trans_huge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_trans_huge(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812154cb)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (ffffffff8124ad4f)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff81254693)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff81257b52)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8125fd4e)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8126106a)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81262d9d)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812638e4)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81264f33)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (ffffffff81275613)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8127b993)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff81289db4)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff812a6799)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812b437e)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff812c1043)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812c4697)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81327794)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff8133565d)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81357d31)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff8124a640-ffffffff8124a666: pmd_trans_huge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_trans_huge(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812228f4)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (ffffffff8125923f)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff81262bf3)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff81266062)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8126e5f8)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8126f803)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8127154d)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81271dda)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
```
```
In mm/rmap.c (ffffffff812737c3)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (ffffffff812845e3)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8128b473)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff81299924)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812aed96)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812b7c72)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812c5c9e)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff812d2f93)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812d60ef)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff8133a574)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff8134925d)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8136ff61)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81258af0-ffffffff81258b16: pmd_trans_huge (STB_LOCAL)
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
In mm/filemap.c (ffffffff8124ffe4)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (ffffffff81288d3a)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
```
```
In mm/memory.c (ffffffff81294af8)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault_around
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff812963b2)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8129e4a5)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812a036c)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812a1c02)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812a2850)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
```
```
In mm/rmap.c (ffffffff812a4993)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (ffffffff812b6793)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812bde9d)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/mempolicy.c (ffffffff812cecf1)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812e439b)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812ece65)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812fb98e)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff81308d82)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff8130b30e)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c8d0)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff813723bd)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
```
```
In fs/dax.c (ffffffff8138f544)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/proc/task_mmu.c (ffffffff813b7f8c)
Location: arch/x86/include/asm/pgtable.h:261
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/filemap.c (ffffffff8125a238)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (ffffffff81292a1a)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
```
```
In mm/memory.c (ffffffff8129f378)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault_around
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
```
```
In mm/mincore.c (ffffffff812a1322)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812a9865)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812ab88d)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812ad630)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812ae190)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
```
```
In mm/rmap.c (ffffffff812b0123)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (ffffffff812c29e3)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812c99c1)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/mempolicy.c (ffffffff812da631)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812f001a)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812f80df)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff813075de)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff81314b8d)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff813171ce)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff81318810)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff8138020d)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
```
```
In fs/dax.c (ffffffff813a0bc8)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/proc/task_mmu.c (ffffffff813c9e4c)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/filemap.c (ffffffff8125f9ad)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff8129a8b3)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff812a4408)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_pmd_range
```
```
In mm/mincore.c (ffffffff812a6b1b)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812aecf5)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812b0c85)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812b2822)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812b357f)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
```
```
In mm/rmap.c (ffffffff812b571c)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (ffffffff812c9863)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812d062d)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff812e1ea1)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812f5aaf)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812fe660)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8130dd5c)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff8131ad3a)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff8131d4c7)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131ea00)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff81387594)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
```
```
In fs/dax.c (ffffffff813a7d5f)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/proc/task_mmu.c (ffffffff813d14ac)
Location: arch/x86/include/asm/pgtable.h:260
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/filemap.c (ffffffff8129c31d)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff812db269)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff812e55b2)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_pmd_range
```
```
In mm/mincore.c (ffffffff812e7ffb)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812f04e5)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812f26bc)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812f4447)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812f511a)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
```
```
In mm/rmap.c (ffffffff812f73b0)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (ffffffff8130e883)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81315b77)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff81328f81)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff81340073)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81348201)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81358bbc)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8135f3b4)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/userfaultfd.c (ffffffff8136812a)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff8136a867)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136bde0)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff813d486b)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
```
```
In fs/dax.c (ffffffff813f7757)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/proc/task_mmu.c (ffffffff814229ac)
Location: arch/x86/include/asm/pgtable.h:231
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/filemap.c (ffffffff812f34bb)
Location: arch/x86/include/asm/pgtable.h:234
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff8133ae26)
Location: arch/x86/include/asm/pgtable.h:234
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff813478f0)
Location: arch/x86/include/asm/pgtable.h:234
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_p4d_range
```
```
In mm/mincore.c (ffffffff8134930c)
Location: arch/x86/include/asm/pgtable.h:234
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff8134c5f0)
Location: arch/x86/include/asm/pgtable.h:234
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff81353a1a)
Location: arch/x86/include/asm/pgtable.h:234
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff813566fc)
Location: arch/x86/include/asm/pgtable.h:234
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81358438)
Location: arch/x86/include/asm/pgtable.h:234
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81358ff5)
Location: arch/x86/include/asm/pgtable.h:234
Inline: True
```
```
In mm/rmap.c (ffffffff8135c9cd)
Location: arch/x86/include/asm/pgtable.h:234
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (ffffffff81376706)
Location: arch/x86/include/asm/pgtable.h:234
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81381171)
Location: arch/x86/include/asm/pgtable.h:234
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff813981ee)
Location: arch/x86/include/asm/pgtable.h:234
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate_device.c (ffffffff813b75e4)
Location: arch/x86/include/asm/pgtable.h:234
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813be43c)
Location: arch/x86/include/asm/pgtable.h:234
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff813d2df0)
Location: arch/x86/include/asm/pgtable.h:234
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff813d9a4d)
Location: arch/x86/include/asm/pgtable.h:234
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/userfaultfd.c (ffffffff813e595d)
Location: arch/x86/include/asm/pgtable.h:234
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff813e8a6e)
Location: arch/x86/include/asm/pgtable.h:234
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9ff9)
Location: arch/x86/include/asm/pgtable.h:234
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff8145fd19)
Location: arch/x86/include/asm/pgtable.h:234
Inline: True
```
```
In fs/dax.c (ffffffff8146a5bf)
Location: arch/x86/include/asm/pgtable.h:234
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/proc/task_mmu.c (ffffffff81499ac9)
Location: arch/x86/include/asm/pgtable.h:234
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/filemap.c (ffffffff8135d80b)
Location: arch/x86/include/asm/pgtable.h:235
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/vmscan.c (ffffffff8137f9ed)
Location: arch/x86/include/asm/pgtable.h:235
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/gup.c (ffffffff813b0471)
Location: arch/x86/include/asm/pgtable.h:235
Inline: True
```
```
In mm/memory.c (ffffffff813bfc7e)
Location: arch/x86/include/asm/pgtable.h:235
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_p4d_range
```
```
In mm/mincore.c (ffffffff813c16d6)
Location: arch/x86/include/asm/pgtable.h:235
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff813c5173)
Location: arch/x86/include/asm/pgtable.h:235
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff813cdeba)
Location: arch/x86/include/asm/pgtable.h:235
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff813d0cf2)
Location: arch/x86/include/asm/pgtable.h:235
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff813d2a6b)
Location: arch/x86/include/asm/pgtable.h:235
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813d376b)
Location: arch/x86/include/asm/pgtable.h:235
Inline: True
```
```
In mm/madvise.c (ffffffff813f4054)
Location: arch/x86/include/asm/pgtable.h:235
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff813ff908)
Location: arch/x86/include/asm/pgtable.h:235
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff81417f74)
Location: arch/x86/include/asm/pgtable.h:235
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff8141ef1d)
Location: arch/x86/include/asm/pgtable.h:235
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate_device.c (ffffffff814391d3)
Location: arch/x86/include/asm/pgtable.h:235
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81440c9c)
Location: arch/x86/include/asm/pgtable.h:235
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81447499)
Location: arch/x86/include/asm/pgtable.h:235
Inline: True
Inline callers:
  - mm/khugepaged.c:find_pmd_or_thp_or_none
```
```
In mm/memcontrol.c (ffffffff814585f0)
Location: arch/x86/include/asm/pgtable.h:235
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8145fdfa)
Location: arch/x86/include/asm/pgtable.h:235
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/userfaultfd.c (ffffffff8146d434)
Location: arch/x86/include/asm/pgtable.h:235
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff814709ee)
Location: arch/x86/include/asm/pgtable.h:235
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff814720a8)
Location: arch/x86/include/asm/pgtable.h:235
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff814ef605)
Location: arch/x86/include/asm/pgtable.h:235
Inline: True
```
```
In fs/dax.c (ffffffff814fb06f)
Location: arch/x86/include/asm/pgtable.h:235
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/proc/task_mmu.c (ffffffff8152dcff)
Location: arch/x86/include/asm/pgtable.h:235
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/filemap.c (ffffffff8138f8a0)
Location: arch/x86/include/asm/pgtable.h:236
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/vmscan.c (ffffffff813b0f1a)
Location: arch/x86/include/asm/pgtable.h:236
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/gup.c (ffffffff813e76c1)
Location: arch/x86/include/asm/pgtable.h:236
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff813f4945)
Location: arch/x86/include/asm/pgtable.h:236
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_p4d_range
```
```
In mm/mincore.c (ffffffff813f6689)
Location: arch/x86/include/asm/pgtable.h:236
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff813f95fc)
Location: arch/x86/include/asm/pgtable.h:236
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff81403247)
Location: arch/x86/include/asm/pgtable.h:236
Inline: True
```
```
In mm/mremap.c (ffffffff8140572f)
Location: arch/x86/include/asm/pgtable.h:236
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff814077ab)
Location: arch/x86/include/asm/pgtable.h:236
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81408214)
Location: arch/x86/include/asm/pgtable.h:236
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff814097cb)
Location: arch/x86/include/asm/pgtable.h:236
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/madvise.c (ffffffff814277fb)
Location: arch/x86/include/asm/pgtable.h:236
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff8144b5e3)
Location: arch/x86/include/asm/pgtable.h:236
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/ksm.c (ffffffff81453b59)
Location: arch/x86/include/asm/pgtable.h:236
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate_device.c (ffffffff8146f364)
Location: arch/x86/include/asm/pgtable.h:236
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81476540)
Location: arch/x86/include/asm/pgtable.h:236
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8147cb69)
Location: arch/x86/include/asm/pgtable.h:236
Inline: True
Inline callers:
  - mm/khugepaged.c:find_pmd_or_thp_or_none
```
```
In mm/memcontrol.c (ffffffff8148e447)
Location: arch/x86/include/asm/pgtable.h:236
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff814955f9)
Location: arch/x86/include/asm/pgtable.h:236
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/userfaultfd.c (ffffffff814a1e43)
Location: arch/x86/include/asm/pgtable.h:236
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/hmm.c (ffffffff814a4f3a)
Location: arch/x86/include/asm/pgtable.h:236
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a6919)
Location: arch/x86/include/asm/pgtable.h:236
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff81524dd6)
Location: arch/x86/include/asm/pgtable.h:236
Inline: True
```
```
In fs/dax.c (ffffffff815324c2)
Location: arch/x86/include/asm/pgtable.h:236
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/proc/task_mmu.c (ffffffff81566166)
Location: arch/x86/include/asm/pgtable.h:236
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/filemap.c (ffffffff813b92ce)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/vmscan.c (ffffffff813da491)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/gup.c (ffffffff8141233f)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
```
In mm/memory.c (ffffffff81420f79)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_p4d_range
```
```
In mm/mincore.c (ffffffff81422339)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff814251a4)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff8142f7d7)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
```
```
In mm/mremap.c (ffffffff81431c69)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81433e39)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81434934)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff8143600a)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/madvise.c (ffffffff81460fdc)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81484fcf)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/ksm.c (ffffffff8148e39c)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate_device.c (ffffffff8149d1f7)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a5dd0)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814ac209)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
Inline callers:
  - mm/khugepaged.c:find_pmd_or_thp_or_none
```
```
In mm/memcontrol.c (ffffffff814bdcb4)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff814c4dd9)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/userfaultfd.c (ffffffff814d3577)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/hmm.c (ffffffff814d5ffa)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d7999)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff81558a67)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
```
```
In fs/dax.c (ffffffff815673b2)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/proc/task_mmu.c (ffffffff8159e15f)
Location: arch/x86/include/asm/pgtable.h:272
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (0)
Location: include/asm-generic/pgtable.h:885
Inline: True
```
```
In mm/gup.c (0)
Location: include/asm-generic/pgtable.h:885
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:885
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:885
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:885
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/asm-generic/pgtable.h:885
Inline: True
```
```
In mm/rmap.c (0)
Location: include/asm-generic/pgtable.h:885
Inline: True
```
```
In mm/madvise.c (0)
Location: include/asm-generic/pgtable.h:885
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:885
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/pgtable.h:885
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/pgtable.h:885
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/pgtable.h:885
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_trans_huge(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/pgtable.c (c000000000087aa0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1211
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable.c:__find_linux_pte
```
```
In arch/powerpc/mm/book3s64/subpage_prot.c (c00000000009f6f0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1211
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/subpage_prot.c:subpage_walk_pmd_entry
```
```
In mm/filemap.c (c000000000364f28)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1211
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (c0000000003b6990)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1211
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
Direct callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (c0000000003c3eb0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1211
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (c0000000003c8470)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1211
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (c0000000003d20d0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1211
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0000000003d409c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1211
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (c0000000003d57f0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1211
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (c0000000003d6bf0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1211
Inline: True
```
```
In mm/rmap.c (c0000000003d87e0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1211
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (c0000000003f2e94)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1211
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (c0000000003fcfe4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1211
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (c000000000413230)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1211
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (c000000000434ee0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1211
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (c000000000440e14)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1211
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (c000000000456c10)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1211
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (c00000000046be1c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1211
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (c000000000470620)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1211
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (c000000000501ba8)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1211
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (c000000000515dd4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1211
Inline: True
```
```
In fs/proc/task_mmu.c (c00000000054d4e0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1211
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
c0000000003b5550-c0000000003b55f4: pmd_trans_huge (STB_LOCAL)
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
In mm/filemap.c (0)
Location: include/asm-generic/pgtable.h:885
Inline: True
```
```
In mm/gup.c (0)
Location: include/asm-generic/pgtable.h:885
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:885
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:885
Inline: True
```
```
In mm/mremap.c (0)
Location: include/asm-generic/pgtable.h:885
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/asm-generic/pgtable.h:885
Inline: True
```
```
In mm/rmap.c (0)
Location: include/asm-generic/pgtable.h:885
Inline: True
```
```
In mm/madvise.c (0)
Location: include/asm-generic/pgtable.h:885
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/pgtable.h:885
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/asm-generic/pgtable.h:885
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/pgtable.h:885
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/pgtable.h:885
Inline: True
```
```
In fs/dax.c (0)
Location: include/asm-generic/pgtable.h:885
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_trans_huge(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121af44)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (ffffffff8125188f)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff8125b243)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff8125e6b2)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81266c48)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81267e53)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81269b9d)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8126a42a)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
```
```
In mm/rmap.c (ffffffff8126be13)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (ffffffff8127cc33)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81283a53)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff81291f04)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a7376)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812b0252)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812be27e)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff812cb573)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812ce6cf)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81332b54)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff8134183d)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81368541)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81251140-ffffffff81251166: pmd_trans_huge (STB_LOCAL)
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
In mm/filemap.c (ffffffff8120e144)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (ffffffff8124476d)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff8124d3e1)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff81250b43)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81258b59)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8125a14a)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8125be59)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8125c8f0)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff8125de7f)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (ffffffff8126eaee)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812758ff)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff81283b50)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff81298dec)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812a16af)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812af3a5)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff812bc47c)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812bf44c)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff813234d0)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff813321d7)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81359881)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_trans_huge(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81218ce4)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (ffffffff8124f62f)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff81258fe3)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff8125c452)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812649e8)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81265bf3)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8126793d)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812681ca)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
```
```
In mm/rmap.c (ffffffff81269bb3)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (ffffffff8127a9d3)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81281863)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff8128fd14)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a5186)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812ae062)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812bc08e)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff812c9383)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812cc4df)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81330624)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff8133f30d)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81366011)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff8124eee0-ffffffff8124ef06: pmd_trans_huge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_trans_huge(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81227dd9)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (ffffffff8125ef9f)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
```
In mm/memory.c (ffffffff812689e3)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff8126be3b)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812743d6)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81275595)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812772d3)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81277b4a)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
```
```
In mm/rmap.c (ffffffff81279523)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (ffffffff8128a5b3)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81291591)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff8129f1af)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812b5cde)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812be3b7)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812cc85c)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff812da063)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812dd23f)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81342f72)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff813523da)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81379bfa)
Location: arch/x86/include/asm/pgtable.h:256
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff8125e850-ffffffff8125e876: pmd_trans_huge (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
