# Function: <code>pte_unmap</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In arch/x86/mm/init.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In mm/mlock.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In mm/migrate_device.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/pgtable.h:109
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/pgtable.h:109
Inline: True
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
In arch/x86/kernel/ldt.c (ffffffff8105b521)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
```
In arch/x86/kernel/alternative.c (ffffffff81061a99)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81070d61)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init.c (ffffffff838eecb4)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - arch/x86/mm/init.c:poking_init
```
```
In kernel/events/core.c (ffffffff81396357)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In kernel/events/uprobes.c (ffffffff813aa44b)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff813b9834)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/vmscan.c (ffffffff813d7da2)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pte_range
  - mm/vmscan.c:walk_pte_range
```
```
In mm/gup.c (ffffffff8140e865)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8141541f)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:generic_access_phys
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:follow_pte
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:alloc_anon_folio
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__wp_page_copy_user
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff814224e0)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff8142536e)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff8142f2db)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff814311e3)
Location: include/linux/pgtable.h:111
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81434454)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff814346db)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pte_range
  - mm/pagewalk.c:walk_pte_range
```
```
In mm/pgtable-generic.c (ffffffff81436352)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map_lock
```
```
In mm/rmap.c (ffffffff8143b1bd)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_referenced_one
```
```
In mm/madvise.c (ffffffff8146136e)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81465f5e)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff8146b65f)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
```
```
In mm/mempolicy.c (ffffffff8148511c)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/ksm.c (ffffffff8148e534)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate.c (ffffffff81498496)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff8149d411)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a1abc)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/khugepaged.c (ffffffff814b069a)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff814bddb8)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff814c4e7a)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/userfaultfd.c (ffffffff814d2e23)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814d6338)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/userfaultfd.c (ffffffff81558b2d)
Location: include/linux/pgtable.h:111
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8159e255)
Location: include/linux/pgtable.h:111
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_scan_pmd_entry
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/fault.c (0)
Location: arch/arm64/include/asm/pgtable.h:496
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: arch/arm64/include/asm/pgtable.h:496
Inline: True
```
```
In mm/shmem.c (0)
Location: arch/arm64/include/asm/pgtable.h:496
Inline: True
```
```
In mm/gup.c (0)
Location: arch/arm64/include/asm/pgtable.h:496
Inline: True
```
```
In mm/memory.c (0)
Location: arch/arm64/include/asm/pgtable.h:496
Inline: True
```
```
In mm/mincore.c (0)
Location: arch/arm64/include/asm/pgtable.h:496
Inline: True
```
```
In mm/mlock.c (0)
Location: arch/arm64/include/asm/pgtable.h:496
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/arm64/include/asm/pgtable.h:496
Inline: True
```
```
In mm/mremap.c (0)
Location: arch/arm64/include/asm/pgtable.h:496
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: arch/arm64/include/asm/pgtable.h:496
Inline: True
```
```
In mm/pagewalk.c (0)
Location: arch/arm64/include/asm/pgtable.h:496
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/arm64/include/asm/pgtable.h:496
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/arm64/include/asm/pgtable.h:496
Inline: True
```
```
In mm/madvise.c (0)
Location: arch/arm64/include/asm/pgtable.h:496
Inline: True
```
```
In mm/swap_state.c (0)
Location: arch/arm64/include/asm/pgtable.h:496
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/arm64/include/asm/pgtable.h:496
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/arm64/include/asm/pgtable.h:496
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/arm64/include/asm/pgtable.h:496
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/arm64/include/asm/pgtable.h:496
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/arm64/include/asm/pgtable.h:496
Inline: True
```
```
In mm/khugepaged.c (0)
Location: arch/arm64/include/asm/pgtable.h:496
Inline: True
```
```
In mm/memcontrol.c (0)
Location: arch/arm64/include/asm/pgtable.h:496
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: arch/arm64/include/asm/pgtable.h:496
Inline: True
```
```
In mm/hmm.c (0)
Location: arch/arm64/include/asm/pgtable.h:496
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: arch/arm64/include/asm/pgtable.h:496
Inline: True
```
```
In fs/dax.c (0)
Location: arch/arm64/include/asm/pgtable.h:496
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/arm64/include/asm/pgtable.h:496
Inline: True
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
In arch/powerpc/mm/book3s64/subpage_prot.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1022
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1022
Inline: True
```
```
In mm/shmem.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1022
Inline: True
```
```
In mm/gup.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1022
Inline: True
```
```
In mm/memory.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1022
Inline: True
```
```
In mm/mincore.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1022
Inline: True
```
```
In mm/mlock.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1022
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1022
Inline: True
```
```
In mm/mremap.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1022
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1022
Inline: True
```
```
In mm/pagewalk.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1022
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1022
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1022
Inline: True
```
```
In mm/madvise.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1022
Inline: True
```
```
In mm/swap_state.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1022
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1022
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1022
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1022
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1022
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1022
Inline: True
```
```
In mm/khugepaged.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1022
Inline: True
```
```
In mm/memcontrol.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1022
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1022
Inline: True
```
```
In mm/hmm.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1022
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1022
Inline: True
```
```
In fs/dax.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1022
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1022
Inline: True
```
</details>
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
