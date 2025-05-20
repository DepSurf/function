# Function: <code>radix_enabled</code>

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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/process.c (c000000000020e5c)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - arch/powerpc/kernel/process.c:start_thread
  - arch/powerpc/kernel/process.c:copy_thread_tls
  - arch/powerpc/kernel/process.c:arch_setup_new_exec
  - arch/powerpc/kernel/process.c:__switch_to
```
```
In arch/powerpc/kernel/setup_64.c (c000000000031114)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup_64.c:early_setup_secondary
  - arch/powerpc/kernel/setup_64.c:early_setup
```
```
In arch/powerpc/kernel/machine_kexec_64.c (c00000000007187c)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - arch/powerpc/kernel/machine_kexec_64.c:default_machine_kexec
```
```
In arch/powerpc/mm/fault.c (c0000000000861c0)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - arch/powerpc/mm/fault.c:__do_page_fault
```
```
In arch/powerpc/mm/pgtable.c (c000000000087b40)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable.c:__find_linux_pte
  - arch/powerpc/mm/pgtable.c:huge_ptep_set_access_flags
  - arch/powerpc/mm/pgtable.c:huge_ptep_set_access_flags
  - arch/powerpc/mm/pgtable.c:ptep_set_access_flags
  - arch/powerpc/mm/pgtable.c:ptep_set_access_flags
  - arch/powerpc/mm/pgtable.c:set_pte_at
  - arch/powerpc/mm/pgtable.c:set_pte_at
```
```
In arch/powerpc/mm/mmap.c (c000000000088828)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - arch/powerpc/mm/mmap.c:arch_pick_mmap_layout
```
```
In arch/powerpc/mm/init_64.c (c000000000088de0)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - arch/powerpc/mm/init_64.c:vmemmap_free
  - arch/powerpc/mm/init_64.c:vmemmap_populate
```
```
In arch/powerpc/mm/ioremap.c (c00000000008961c)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - arch/powerpc/mm/ioremap.c:early_ioremap_range
```
```
In arch/powerpc/mm/mmu_context.c (c00000000008a168)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - arch/powerpc/mm/mmu_context.c:switch_mm_irqs_off
```
```
In arch/powerpc/mm/book3s64/hash_pgtable.c (c00000000008c018)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_pgtable.c:hash__pmdp_huge_get_and_clear
```
```
In arch/powerpc/mm/book3s64/hash_utils.c (c00000000008dc24)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_utils.c:update_mmu_cache
```
```
In arch/powerpc/mm/book3s64/mmu_context.c (c000000000090680)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/mmu_context.c:arch_exit_mmap
  - arch/powerpc/mm/book3s64/mmu_context.c:destroy_context
  - arch/powerpc/mm/book3s64/mmu_context.c:init_new_context
```
```
In arch/powerpc/mm/book3s64/pgtable.c (c000000001356134)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/pgtable.c:setup_disable_tlbie
  - arch/powerpc/mm/book3s64/pgtable.c:pmd_move_must_withdraw
  - arch/powerpc/mm/book3s64/pgtable.c:ptep_modify_prot_commit
  - arch/powerpc/mm/book3s64/pgtable.c:ptep_modify_prot_start
  - arch/powerpc/mm/book3s64/pgtable.c:arch_report_meminfo
  - arch/powerpc/mm/book3s64/pgtable.c:remove_section_mapping
  - arch/powerpc/mm/book3s64/pgtable.c:create_section_mapping
  - arch/powerpc/mm/book3s64/pgtable.c:mmu_cleanup_all
  - arch/powerpc/mm/book3s64/pgtable.c:update_mmu_cache_pmd
  - arch/powerpc/mm/book3s64/pgtable.c:pmdp_invalidate
  - arch/powerpc/mm/book3s64/pgtable.c:pmdp_invalidate
  - arch/powerpc/mm/book3s64/pgtable.c:pmdp_test_and_clear_young
  - arch/powerpc/mm/book3s64/pgtable.c:pmdp_set_access_flags
  - arch/powerpc/mm/book3s64/pgtable.c:pmdp_set_access_flags
```
```
In arch/powerpc/mm/book3s64/hash_tlb.c (c000000000091e70)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_tlb.c:flush_tlb_pmd_range
  - arch/powerpc/mm/book3s64/hash_tlb.c:flush_tlb_pmd_range
  - arch/powerpc/mm/book3s64/hash_tlb.c:__flush_hash_table_range
  - arch/powerpc/mm/book3s64/hash_tlb.c:__flush_hash_table_range
```
```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000095b84)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:pmd_free_pte_page
  - arch/powerpc/mm/book3s64/radix_pgtable.c:pmd_set_huge
  - arch/powerpc/mm/book3s64/radix_pgtable.c:pud_free_pmd_page
  - arch/powerpc/mm/book3s64/radix_pgtable.c:pud_set_huge
  - arch/powerpc/mm/book3s64/radix_pgtable.c:arch_ioremap_pmd_supported
  - arch/powerpc/mm/book3s64/radix_pgtable.c:arch_ioremap_pud_supported
  - arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable
```
```
In arch/powerpc/mm/book3s64/radix_tlb.c (c000000000097d18)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix_kvm_prefetch_workaround
```
```
In arch/powerpc/mm/book3s64/hash_hugetlbpage.c (c00000000009e8cc)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_hugetlbpage.c:huge_ptep_modify_prot_commit
  - arch/powerpc/mm/book3s64/hash_hugetlbpage.c:huge_ptep_modify_prot_start
```
```
In arch/powerpc/mm/book3s64/subpage_prot.c (c00000000009fb6c)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/subpage_prot.c:__se_sys_subpage_prot
  - arch/powerpc/mm/book3s64/subpage_prot.c:__se_sys_subpage_prot
  - arch/powerpc/mm/book3s64/subpage_prot.c:subpage_walk_pmd_entry
  - arch/powerpc/mm/book3s64/subpage_prot.c:hpte_flush_range
  - arch/powerpc/mm/book3s64/subpage_prot.c:hpte_flush_range
  - arch/powerpc/mm/book3s64/subpage_prot.c:hpte_flush_range
```
```
In arch/powerpc/mm/hugetlbpage.c (c000000001357e70)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:hugetlbpage_init
  - arch/powerpc/mm/hugetlbpage.c:add_huge_page_size
  - arch/powerpc/mm/hugetlbpage.c:vma_mmu_pagesize
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
  - arch/powerpc/mm/hugetlbpage.c:alloc_bootmem_huge_page
```
```
In arch/powerpc/mm/copro_fault.c (c0000000000a67a8)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - arch/powerpc/mm/copro_fault.c:copro_handle_mm_fault
```
```
In arch/powerpc/platforms/powernv/setup.c (c00000000135ab94)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/setup.c:pnv_probe
  - arch/powerpc/platforms/powernv/setup.c:pnv_show_cpuinfo
```
```
In arch/powerpc/platforms/powernv/idle.c (c0000000000c7680)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/idle.c:power9_idle_stop
```
```
In arch/powerpc/platforms/powernv/vas-window.c (c0000000000e32e4)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/vas-window.c:init_winctx_regs
```
```
In arch/powerpc/platforms/pseries/lpar.c (c0000000000eb1d0)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/lpar.c:vpa_init
```
```
In arch/powerpc/platforms/pseries/setup.c (c0000000013623cc)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/setup.c:pSeries_setup_arch
  - arch/powerpc/platforms/pseries/setup.c:pSeries_show_cpuinfo
```
```
In arch/powerpc/xmon/xmon.c (c00000000010d518)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:show_pte
  - arch/powerpc/xmon/xmon.c:getvecname
  - arch/powerpc/xmon/xmon.c:getvecname
```
```
In kernel/fork.c (c0000000001373c0)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:dup_mmap
```
```
In mm/filemap.c (c000000000365050)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/shmem.c (c00000000038e6b0)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/percpu.c (c0000000003a1dbc)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/gup.c (c0000000003b6990)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003baef0)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mincore.c (c0000000003c86b4)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mmap.c (c0000000003cf0e0)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/mmu_gather.c (c0000000003d1a30)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mprotect.c (c0000000003d1ea0)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0000000003d409c)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (c0000000003d55d4)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/pagewalk.c (c0000000003d665c)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
```
```
In mm/pgtable-generic.c (c0000000003d73dc)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_clear_flush_young
  - mm/pgtable-generic.c:ptep_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush_young
  - mm/pgtable-generic.c:ptep_clear_flush_young
```
```
In mm/rmap.c (c0000000003d9e00)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (c0000000003e0ca8)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_page_range_noflush
  - mm/vmalloc.c:vunmap_page_range
  - mm/vmalloc.c:vunmap_page_range
  - mm/vmalloc.c:vunmap_page_range
  - mm/vmalloc.c:vunmap_page_range
  - mm/vmalloc.c:vunmap_page_range
```
```
In mm/madvise.c (c0000000003f32c0)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (c0000000003f7e14)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (c0000000003fd040)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (c00000000040fcd0)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (c000000000413230)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (c000000000eedbb0)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (c00000000041ac94)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (c000000000434ee0)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (c000000000444424)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:hugepage_init
```
```
In mm/khugepaged.c (c0000000004492f8)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (c000000000456c10)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (c00000000046bbd4)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (c00000000046c414)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In mm/hmm.c (c00000000046fb28)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (c000000000501668)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (c000000000514508)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
```
```
In fs/proc/task_mmu.c (c00000000054d4e0)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In drivers/nvdimm/pfn_devs.c (c000000000a15b70)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_devinit
  - drivers/nvdimm/pfn_devs.c:supported_alignments_show
  - drivers/nvdimm/pfn_devs.c:align_store
```
```
In lib/ioremap.c (c000000000eca274)
Location: arch/powerpc/include/asm/mmu.h:273
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
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
