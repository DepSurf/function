# Function: <code>__phys_addr_nodebug</code>

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
In arch/x86/kernel/head64.c (ffffffff81f59222)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
  - arch/x86/kernel/head64.c:early_make_pgtable
```
```
In init/main.c (ffffffff81f59ee8)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81f5ccd6)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d191)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/pt.c (ffffffff81013356)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_config_buffer
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/xen/enlighten.c (ffffffff81f6074d)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_load_gdt_boot
  - arch/x86/xen/enlighten.c:xen_start_kernel
  - arch/x86/xen/enlighten.c:xen_start_kernel
  - arch/x86/xen/enlighten.c:xen_hvm_init_shared_info
```
```
In arch/x86/xen/setup.c (ffffffff81f61162)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu.c (ffffffff8101df31)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_get_user_pgd
  - arch/x86/xen/mmu.c:xen_pgd_alloc
  - arch/x86/xen/mmu.c:xen_pgd_alloc
  - arch/x86/xen/mmu.c:xen_pgd_alloc
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:xen_set_domain_pte
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_create_contiguous_region
  - arch/x86/xen/mmu.c:xen_create_contiguous_region
  - arch/x86/xen/mmu.c:__xen_set_pgd_hyper
  - arch/x86/xen/mmu.c:xen_set_pud
  - arch/x86/xen/mmu.c:xen_set_pmd
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/xen/mmu.c:xen_write_cr3
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:xen_set_pgd
  - arch/x86/xen/mmu.c:xen_set_pgd
  - arch/x86/xen/mmu.c:xen_reserve_special_pages
  - arch/x86/xen/mmu.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
```
```
In arch/x86/xen/p2m.c (ffffffff81024696)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
```
```
In arch/x86/xen/pmu.c (ffffffff81026595)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/smp.c (ffffffff8102b3e6)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:stop_self
  - arch/x86/xen/smp.c:xen_cpu_disable
  - arch/x86/xen/smp.c:xen_cpu_up
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In arch/x86/xen/efi.c (ffffffff81f65446)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
  - arch/x86/xen/efi.c:xen_efi_init
```
```
In arch/x86/realmode/init.c (ffffffff81f654b7)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:set_real_mode_permissions
  - arch/x86/realmode/init.c:setup_real_mode
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103461d)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/pci-dma.c (0)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103674c)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff8103e149)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_shutdown
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81f6d4e3)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff81f6fc86)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/kernel/mpparse.c (ffffffff81f705b9)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81f72f44)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105b998)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/pvclock.c (ffffffff81f749a8)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_init_vsyscall
```
```
In arch/x86/kernel/check.c (ffffffff81065408)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81066ce9)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81f76918)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff81f77061)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:free_tce_table
  - arch/x86/kernel/tce_64.c:tce_build
```
```
In arch/x86/mm/init.c (ffffffff81f77446)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff81f77961)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:ident_pud_init
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:vmemmap_populate
```
```
In arch/x86/mm/ioremap.c (ffffffff81f77e6b)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c20c)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wt
```
```
In arch/x86/mm/pat.c (ffffffff81070443)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff81070c8f)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:pgd_free
```
```
In arch/x86/mm/tlb.c (ffffffff81072517)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In arch/x86/mm/numa.c (ffffffff81f78996)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_reset_distance
```
```
In arch/x86/platform/efi/efi.c (ffffffff81f7a985)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81f7aee1)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
```
```
In kernel/fork.c (ffffffff8107d985)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/resource.c (ffffffff810867ba)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In kernel/sched/core.c (ffffffff8181fc49)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:idle_task_exit
```
```
In kernel/sched/wait.c (ffffffff810c36a5)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - kernel/sched/wait.c:bit_waitqueue
```
```
In kernel/power/snapshot.c (ffffffff810d04bc)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
```
```
In kernel/power/swap.c (ffffffff810d2935)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In kernel/profile.c (ffffffff818191e0)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:profile_cpu_callback
  - kernel/profile.c:profile_cpu_callback
  - kernel/profile.c:profile_cpu_callback
```
```
In kernel/kexec_core.c (ffffffff8110c96b)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_add_entry
  - kernel/kexec_core.c:paddr_vmcoreinfo_note
```
```
In kernel/kexec_file.c (ffffffff8110f369)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
```
```
In kernel/trace/trace.c (ffffffff8114d2a4)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/events/ring_buffer.c (ffffffff811851e5)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_free_page
  - kernel/events/ring_buffer.c:rb_irq_work
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
```
```
In mm/page_alloc.c (ffffffff81194475)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_page_frag
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:free_kmem_pages
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:__alloc_page_frag
```
```
In mm/swap.c (ffffffff8119d675)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/shmem.c (ffffffff811ab0e6)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In mm/mmu_context.c (ffffffff811afc76)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/percpu.c (ffffffff81f88bde)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_alloc_info
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:per_cpu_ptr_to_phys
```
```
In mm/list_lru.c (ffffffff811b8ee6)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_add
  - mm/list_lru.c:list_lru_add
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_del
```
```
In mm/workingset.c (ffffffff811b9cbf)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/gup.c (ffffffff811ba9aa)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff81f8a855)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/memory.c:init_zero_pfn
  - mm/memory.c:__pte_alloc
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
```
```
In mm/mprotect.c (ffffffff811c872f)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff811caa8a)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/rmap.c:__page_check_address
```
```
In mm/pgtable-generic.c (ffffffff811d04ad)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
```
```
In mm/memblock.c (ffffffff8181dbf9)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/memblock.c:get_allocated_memblock_reserved_regions_info
  - mm/memblock.c:get_allocated_memblock_memory_regions_info
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
```
```
In mm/hugetlb.c (ffffffff81f8bba4)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_bootmem_huge_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_huge_pmd
```
```
In mm/mempolicy.c (ffffffff811dfec6)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse.c (ffffffff81f8c617)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/sparse-vmemmap.c (ffffffff8181f276)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
```
In mm/slub.c (ffffffff811e8a5b)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/slub.c:ksize
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:kmem_cache_free_bulk
```
```
In mm/memory_hotplug.c (ffffffff811efe26)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff811f0e20)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff811f50cd)
Location: arch/x86/include/asm/page_64.h:12
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
```
In mm/zbud.c (ffffffff81204715)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/zbud.c:free_zbud_page
```
```
In mm/cma.c (ffffffff81f8e5c7)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In fs/exec.c (ffffffff812137a2)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In fs/direct-io.c (ffffffff8124af05)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/proc/kcore.c (ffffffff81286f78)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In fs/proc/vmcore.c (ffffffff81287b01)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In fs/ext4/crypto.c (ffffffff812e55bc)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_encrypted_zeroout
```
```
In fs/jbd2/journal.c (ffffffff812f2e72)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/crypto.c (ffffffff81305b4a)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81338fbb)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff8139ebf4)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_map_and_copy
```
```
In crypto/ablkcipher.c (ffffffff8139fa2c)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff813a14f6)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
```
```
In crypto/eseqiv.c (ffffffff813a2614)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - crypto/eseqiv.c:eseqiv_givencrypt
  - crypto/eseqiv.c:eseqiv_givencrypt
```
```
In block/bio.c (ffffffff813b29d4)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - block/bio.c:bio_map_kern
```
```
In block/blk-merge.c (ffffffff813c01ee)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-lib.c (ffffffff813c2a94)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
```
```
In block/bio-integrity.c (ffffffff813e795f)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
```
```
In lib/scatterlist.c (ffffffff813f9eef)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff813feb01)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In lib/swiotlb.c (ffffffff81412463)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_init_with_tbl
  - lib/swiotlb.c:swiotlb_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
```
```
In drivers/virtio/virtio_ring.c (ffffffff814bfacd)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
```
In drivers/virtio/virtio_mmio.c (ffffffff814c0c80)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff814c1870)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff814c32ac)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
```
In drivers/xen/grant-table.c (ffffffff814c5a92)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In drivers/xen/manage.c (ffffffff814c750c)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff81fa4a0a)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff814cab1a)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:init_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff814cb27e)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_map_ring
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_map_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81fa4c90)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff814d0c27)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
```
```
In drivers/xen/swiotlb-xen.c (ffffffff814d4409)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_set_dma_mask
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff814fef2f)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff815096aa)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/mem.c (ffffffff815112d5)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/agp/generic.c (ffffffff8151d4ed)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8151f511)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81521e85)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff8152d6e5)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:build_completion_wait
  - drivers/iommu/amd_iommu.c:build_completion_wait
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff815328fc)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
```
In drivers/iommu/dmar.c (ffffffff8153348a)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff81535a76)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_unmap
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
```
```
In drivers/iommu/intel-svm.c (ffffffff8153c30e)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8153c8b0)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/dma-mapping.c (ffffffff8155d8e5)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dma_common_get_sgtable
  - drivers/base/dma-mapping.c:dma_common_mmap
```
```
In drivers/spi/spi.c (ffffffff815e7811)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff815f1450)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:free_unused_bufs
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
```
```
In drivers/net/xen-netfront.c (ffffffff815fac46)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In drivers/usb/core/hcd.c (ffffffff8160d45c)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/devio.c (ffffffff8161c2c2)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816282be)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/md/dm-io.c (ffffffff816aab45)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/md/dm-io.c:km_get_page
```
```
In drivers/md/dm-kcopyd.c (ffffffff81fb3b66)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff816ca45e)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff81fb6282)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/memmap.c (ffffffff8181f67e)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In net/core/skbuff.c (ffffffff81705741)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:build_skb
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/netlink/af_netlink.c (ffffffff8174a9bb)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_mmap
```
```
In net/ipv4/tcp.c (ffffffff81766cb7)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/packet/af_packet.c (ffffffff81803575)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/kernel/head64.c (ffffffff81f8147a)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:early_make_pgtable
  - arch/x86/kernel/head64.c:reset_early_page_tables
```
```
In init/main.c (ffffffff81f81ec2)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/entry/vdso/vma.c (ffffffff8100420c)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d45e)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/pt.c (ffffffff81013f63)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/xen/enlighten.c (ffffffff81891bd6)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_hvm_init_shared_info
  - arch/x86/xen/enlighten.c:xen_start_kernel
  - arch/x86/xen/enlighten.c:xen_start_kernel
  - arch/x86/xen/enlighten.c:xen_load_gdt_boot
```
```
In arch/x86/xen/setup.c (ffffffff81f890c8)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu.c (ffffffff8101dda8)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
  - arch/x86/xen/mmu.c:xen_create_contiguous_region
  - arch/x86/xen/mmu.c:xen_create_contiguous_region
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_pgd_alloc
  - arch/x86/xen/mmu.c:xen_pgd_alloc
  - arch/x86/xen/mmu.c:xen_pgd_alloc
  - arch/x86/xen/mmu.c:xen_write_cr3
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:xen_set_pgd
  - arch/x86/xen/mmu.c:xen_set_pgd
  - arch/x86/xen/mmu.c:__xen_set_pgd_hyper
  - arch/x86/xen/mmu.c:xen_get_user_pgd
  - arch/x86/xen/mmu.c:xen_set_pud
  - arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pmd
  - arch/x86/xen/mmu.c:xen_set_domain_pte
  - arch/x86/xen/mmu.c:xen_reserve_special_pages
```
```
In arch/x86/xen/p2m.c (ffffffff8102469b)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/xen/pmu.c (ffffffff81025a43)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/smp.c (ffffffff8102a05f)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:stop_self
  - arch/x86/xen/smp.c:xen_cpu_disable
  - arch/x86/xen/smp.c:xen_cpu_up
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In arch/x86/xen/efi.c (ffffffff81f8d2cb)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
```
In arch/x86/realmode/init.c (ffffffff81f8d364)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:init_real_mode
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81f8f146)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/pci-dma.c (0)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103594a)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff8103df76)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_shutdown
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81f95894)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff81f9837c)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/kernel/mpparse.c (ffffffff81f98d0e)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81f9b76e)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bf0c)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/kernel/check.c (ffffffff810650ec)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81f9ddc2)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81f9f4a6)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff81067e97)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
  - arch/x86/kernel/tce_64.c:free_tce_table
```
```
In arch/x86/mm/init.c (ffffffff81f9ff3f)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:early_alloc_pgt_buf
```
```
In arch/x86/mm/init_64.c (ffffffff81896bed)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/ioremap.c (ffffffff81fa05e0)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff8106efbe)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:alloc_pte_page
```
```
In arch/x86/mm/pat.c (ffffffff810701b0)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff81070e08)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81072467)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/numa.c (ffffffff81fa113d)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_reset_distance
```
```
In arch/x86/mm/kaslr.c (ffffffff81896ed0)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/platform/efi/efi.c (ffffffff81fa326d)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107a779)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8107fe1f)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - kernel/fork.c:free_task
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/resource.c (ffffffff8108980d)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In kernel/sched/wait.c (ffffffff810c7037)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - kernel/sched/wait.c:bit_waitqueue
```
```
In kernel/power/snapshot.c (ffffffff810d6f7b)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
```
```
In kernel/power/swap.c (ffffffff810d76b0)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In kernel/profile.c (ffffffff810f13bc)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/kexec_core.c (ffffffff81115526)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - kernel/kexec_core.c:paddr_vmcoreinfo_note
  - kernel/kexec_core.c:kimage_add_entry
```
```
In kernel/kexec_file.c (ffffffff81116aa8)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
```
```
In kernel/trace/trace.c (ffffffff81155a75)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/events/ring_buffer.c (ffffffff8119823d)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_free_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page_alloc.c (ffffffff81fb1133)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:__free_page_frag
  - mm/page_alloc.c:__alloc_page_frag
```
```
In mm/swap.c (ffffffff811b1c01)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/shmem.c (ffffffff811c34ee)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In mm/percpu.c (ffffffff811caffc)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/list_lru.c (ffffffff811d39e2)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffff811d405e)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/gup.c (ffffffff8122ec21)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In mm/memory.c (ffffffff811da9bd)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:init_zero_pfn
```
```
In mm/mprotect.c (ffffffff811e49e4)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff811e7a6a)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:__page_check_address
```
```
In mm/pgtable-generic.c (ffffffff811ed73e)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/memblock.c (ffffffff8189885e)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:get_allocated_memblock_memory_regions_info
  - mm/memblock.c:get_allocated_memblock_reserved_regions_info
```
```
In mm/hugetlb.c (ffffffff811fde52)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff811fec91)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse.c (ffffffff81202316)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
```
```
In mm/sparse-vmemmap.c (ffffffff81fb67ad)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/slub.c (ffffffff81207bd2)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/memory_hotplug.c (ffffffff81fb6f70)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff81213109)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81215df6)
Location: arch/x86/include/asm/page_64.h:12
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
In mm/khugepaged.c (ffffffff8121b578)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/zbud.c (ffffffff812296b3)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/zbud.c:free_zbud_page
```
```
In mm/cma.c (ffffffff81fb8bc6)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In mm/usercopy.c (ffffffff8122e66c)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In fs/direct-io.c (ffffffff812737f6)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/crypto/crypto.c (ffffffff81288e1e)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_zeroout_range
```
```
In fs/proc/kcore.c (ffffffff812b417c)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In fs/proc/vmcore.c (ffffffff812b4e4d)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In fs/jbd2/journal.c (ffffffff8132083d)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/crypto.c (ffffffff81339e30)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8136e57e)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff813db9c6)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_map_and_copy
```
```
In crypto/ablkcipher.c (ffffffff813dcdfc)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff813dd695)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
```
```
In crypto/rsa-pkcs1pad.c (ffffffff813e0ef6)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sg_set_buf
```
```
In block/bio.c (ffffffff813f6172)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - block/bio.c:bio_map_kern
```
```
In block/blk-merge.c (ffffffff814042f6)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-lib.c (ffffffff814066ee)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:blkdev_issue_zeroout
```
```
In block/bio-integrity.c (ffffffff8142dbe8)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
```
```
In lib/scatterlist.c (ffffffff814410b5)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff81445d85)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In lib/swiotlb.c (ffffffff8145a1b4)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_init_with_tbl
  - lib/swiotlb.c:swiotlb_init_with_tbl
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
```
```
In drivers/pci/host/pcie-designware.c (ffffffff814a535d)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/pci/host/pcie-designware.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff8150f3d5)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81515fff)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In drivers/xen/manage.c (ffffffff81517da0)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff81fd0fcc)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8151ba00)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8151be56)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_map_ring
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_map_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81fd125e)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81521945)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81525067)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_set_dma_mask
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8154f751)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8155b665)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/mem.c (ffffffff8156389d)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/agp/generic.c (ffffffff81570484)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8157258e)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81574d0f)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff8158233d)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:build_completion_wait
  - drivers/iommu/amd_iommu.c:build_completion_wait
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff81587106)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
```
In drivers/iommu/dmar.c (ffffffff81587a2c)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158fe4c)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:domain_unmap
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel-svm.c (ffffffff81590e87)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8159146b)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/dma-mapping.c (ffffffff815b1bde)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dma_common_mmap
  - drivers/base/dma-mapping.c:dma_common_get_sgtable
```
```
In drivers/spi/spi.c (ffffffff81645867)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff816523d3)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:remove_vq_common
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
```
```
In drivers/net/xen-netfront.c (ffffffff8165ab38)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In drivers/usb/core/hcd.c (ffffffff8166d01a)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/devio.c (ffffffff8167c1bb)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8168f2fe)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816b963b)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/md/dm-io.c (ffffffff8170afe4)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/md/dm-io.c:km_get_page
```
```
In drivers/md/dm-kcopyd.c (ffffffff81fe0783)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff8172d411)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff81fe379e)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/memmap.c (ffffffff81899d89)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81760670)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In net/core/skbuff.c (ffffffff8177338c)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:build_skb
```
```
In net/ipv4/tcp.c (ffffffff817d31ab)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/packet/af_packet.c (ffffffff818782e4)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/kernel/head64.c (ffffffff81fbd47a)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:early_make_pgtable
  - arch/x86/kernel/head64.c:reset_early_page_tables
```
```
In init/main.c (ffffffff81fbdf10)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81003f8c)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d522)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/pt.c (ffffffff810140e8)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/xen/enlighten.c (ffffffff818c64e6)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_hvm_init_shared_info
  - arch/x86/xen/enlighten.c:xen_start_kernel
  - arch/x86/xen/enlighten.c:xen_start_kernel
  - arch/x86/xen/enlighten.c:xen_load_gdt_boot
```
```
In arch/x86/xen/setup.c (ffffffff81fc44bc)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/mmu.c (ffffffff8101e498)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
  - arch/x86/xen/mmu.c:xen_create_contiguous_region
  - arch/x86/xen/mmu.c:xen_create_contiguous_region
  - arch/x86/xen/mmu.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_zap_pfn_range
  - arch/x86/xen/mmu.c:xen_set_fixmap
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_pgd_alloc
  - arch/x86/xen/mmu.c:xen_pgd_alloc
  - arch/x86/xen/mmu.c:xen_pgd_alloc
  - arch/x86/xen/mmu.c:xen_write_cr3
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:__xen_pgd_walk
  - arch/x86/xen/mmu.c:xen_set_pgd
  - arch/x86/xen/mmu.c:xen_set_pgd
  - arch/x86/xen/mmu.c:__xen_set_pgd_hyper
  - arch/x86/xen/mmu.c:xen_get_user_pgd
  - arch/x86/xen/mmu.c:xen_set_pud
  - arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pmd
  - arch/x86/xen/mmu.c:xen_set_domain_pte
  - arch/x86/xen/mmu.c:xen_reserve_special_pages
```
```
In arch/x86/xen/p2m.c (ffffffff81024dcb)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/xen/pmu.c (ffffffff81026163)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/smp.c (ffffffff8102a7af)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:stop_self
  - arch/x86/xen/smp.c:xen_cpu_disable
  - arch/x86/xen/smp.c:xen_cpu_up
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In arch/x86/xen/efi.c (ffffffff81fc86df)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102bbb8)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_do_hypercall
  - arch/x86/hyperv/hv_init.c:hv_do_hypercall
```
```
In arch/x86/realmode/init.c (ffffffff81fc8778)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:init_real_mode
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81fca4d5)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/pci-dma.c (0)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103567a)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff8103d82a)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_shutdown
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff81fd3846)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/kernel/mpparse.c (ffffffff81fd41d7)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81fd6cb7)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ee8c)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/kernel/check.c (ffffffff8106861c)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81fd9345)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81fdaa08)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff8106bae7)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
  - arch/x86/kernel/tce_64.c:free_tce_table
```
```
In arch/x86/mm/init.c (ffffffff81fdb4a1)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:early_alloc_pgt_buf
```
```
In arch/x86/mm/init_64.c (ffffffff818cb2d8)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/ioremap.c (ffffffff81fdbb51)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81072c2e)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:alloc_pte_page
```
```
In arch/x86/mm/pat.c (ffffffff81073df0)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff81074988)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81075ff8)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/numa.c (ffffffff81fdc889)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_reset_distance
```
```
In arch/x86/mm/kaslr.c (ffffffff818cb5b9)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/platform/efi/efi.c (ffffffff81fdeafb)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107e5d3)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81084887)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/resource.c (ffffffff8108e75d)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff810ddafc)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
```
```
In kernel/power/swap.c (ffffffff810de220)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In kernel/profile.c (ffffffff810f8314)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/kexec_core.c (ffffffff8111cc46)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - kernel/kexec_core.c:paddr_vmcoreinfo_note
  - kernel/kexec_core.c:kimage_add_entry
```
```
In kernel/kexec_file.c (ffffffff8111e1e8)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
```
```
In kernel/trace/trace.c (ffffffff8115fed3)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/events/ring_buffer.c (ffffffff811a7c1d)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_free_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page_alloc.c (ffffffff81fed9d9)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap.c (ffffffff811c2261)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/shmem.c (ffffffff811d3567)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In mm/percpu.c (ffffffff811db131)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/list_lru.c (ffffffff811e38b2)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffff811e3f30)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/gup.c (ffffffff81241174)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In mm/memory.c (ffffffff811ea52a)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:init_zero_pfn
```
```
In mm/mprotect.c (ffffffff811f49d7)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff811f7124)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff811f7b1a)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/rmap.c (ffffffff811f8df1)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:__page_check_address
```
```
In mm/memblock.c (ffffffff818ccf06)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:get_allocated_memblock_memory_regions_info
  - mm/memblock.c:get_allocated_memblock_reserved_regions_info
```
```
In mm/hugetlb.c (ffffffff8120e93f)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff812104cd)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse.c (ffffffff81214156)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
```
```
In mm/sparse-vmemmap.c (ffffffff81ff3176)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff81217450)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff81219bff)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/memory_hotplug.c (ffffffff81ff398b)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff81225479)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81228415)
Location: arch/x86/include/asm/page_64.h:12
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
In mm/khugepaged.c (ffffffff8122e3f8)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/zbud.c (ffffffff8123bc53)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/zbud.c:free_zbud_page
```
```
In mm/cma.c (ffffffff81ff5537)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In mm/usercopy.c (ffffffff81240b9c)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In fs/direct-io.c (ffffffff81287268)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff8129cda7)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/crypto/crypto.c (ffffffff8129dade)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_zeroout_range
```
```
In fs/iomap.c (ffffffff812b0b44)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_zero
```
```
In fs/proc/kcore.c (ffffffff812c9a1c)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In fs/proc/vmcore.c (ffffffff812ca6dd)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In fs/jbd2/journal.c (ffffffff813366ea)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/crypto.c (ffffffff8134fbcf)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8138519a)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff813f46dc)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff813f4f5b)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
```
```
In crypto/skcipher.c (ffffffff813f65c8)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
```
```
In crypto/rsa-pkcs1pad.c (ffffffff813fa19c)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In block/bio.c (ffffffff8140fb65)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - block/bio.c:bio_map_kern
```
```
In block/blk-merge.c (ffffffff8141e782)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-lib.c (ffffffff81420c0e)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_zeroout
  - block/blk-lib.c:__blkdev_issue_zeroout
```
```
In block/bio-integrity.c (ffffffff814479c1)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
```
```
In lib/cpumask.c (ffffffff82003fcc)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
```
```
In lib/scatterlist.c (ffffffff8145e685)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff81464575)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In lib/swiotlb.c (ffffffff81478c14)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_init_with_tbl
  - lib/swiotlb.c:swiotlb_init_with_tbl
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
```
```
In drivers/pci/host/pcie-designware.c (ffffffff814c762d)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/pci/host/pcie-designware.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff8153b525)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81542482)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In drivers/xen/manage.c (ffffffff81544090)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff8200e944)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81547ed0)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81548326)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_map_ring
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_map_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8200ebee)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8154de15)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81551527)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_set_dma_mask
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8157bfd1)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81587e0f)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/mem.c (ffffffff8158fffd)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/agp/generic.c (ffffffff8159cb44)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8159ec2e)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815a137f)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff815af82b)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:build_completion_wait
  - drivers/iommu/amd_iommu.c:build_completion_wait
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff815b43c6)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff815b50ec)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff815bd6b2)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:domain_unmap
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel-svm.c (ffffffff815be70f)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815bed2b)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/dma-mapping.c (ffffffff815e0e2e)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dma_common_mmap
```
```
In drivers/spi/spi.c (ffffffff81676ffd)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8168888d)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In drivers/usb/core/hcd.c (ffffffff8169ad1a)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/devio.c (ffffffff816aa123)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816bd3be)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816e78bb)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/md/dm-io.c (ffffffff8173ceb4)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/md/dm-io.c:km_get_page
```
```
In drivers/md/dm-kcopyd.c (ffffffff8201e3f1)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff817603ba)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff8202156d)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/memmap.c (ffffffff818ce435)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178d7d0)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In net/core/skbuff.c (ffffffff817a059f)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:build_skb
```
```
In net/ipv4/tcp.c (ffffffff81804a8b)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/packet/af_packet.c (ffffffff818ac84d)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
```
```
In lib/dma-noop.c (ffffffff818c5582)
Location: arch/x86/include/asm/page_64.h:12
Inline: True
Inline callers:
  - lib/dma-noop.c:dma_noop_alloc
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
In arch/x86/kernel/head64.c (ffffffff8209d46b)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:early_make_pgtable
  - arch/x86/kernel/head64.c:reset_early_page_tables
```
```
In init/main.c (ffffffff8209e002)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81003ea9)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d397)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/pt.c (ffffffff8101270d)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/xen/mmu.c (ffffffff8101a9ae)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff820a3c2b)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
```
```
In arch/x86/xen/mmu_hvm.c (ffffffff8101bb70)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff820a4304)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8101cadb)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/p2m.c (ffffffff8101dfab)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff820a5ed2)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810249b7)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_get_user_pgd
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_set_domain_pte
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff820a768b)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
```
```
In arch/x86/xen/smp_pv.c (ffffffff810292cf)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In arch/x86/xen/efi.c (ffffffff820a8dd6)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81029dfd)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_do_hypercall
  - arch/x86/hyperv/hv_init.c:hv_do_hypercall
```
```
In arch/x86/realmode/init.c (ffffffff820a8e74)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:init_real_mode
```
```
In arch/x86/kernel/espfix_64.c (ffffffff820aac7b)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/pci-dma.c (0)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff81033642)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff8103b88c)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104f3d4)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff820b44fc)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/kernel/mpparse.c (ffffffff820b4ebc)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:smp_scan_config
  - arch/x86/kernel/mpparse.c:smp_scan_config
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff820b79b8)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e52c)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/kernel/check.c (ffffffff8106793c)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff820ba1a2)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff820bb83a)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff8106aea7)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
  - arch/x86/kernel/tce_64.c:free_tce_table
```
```
In arch/x86/mm/init.c (ffffffff820bc323)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:early_alloc_pgt_buf
```
```
In arch/x86/mm/init_64.c (ffffffff819028ca)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/ioremap.c (ffffffff820bcb2b)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff810721de)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:alloc_pte_page
```
```
In arch/x86/mm/pat.c (ffffffff81073391)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff81073ed8)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff810746f4)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/numa.c (ffffffff820bd8b9)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_reset_distance
```
```
In arch/x86/mm/kaslr.c (ffffffff81902ba3)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/platform/efi/efi.c (ffffffff820bf98a)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107cbe3)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/fork.c (ffffffff8108179a)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/resource.c (ffffffff8108b751)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff810dcc63)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
```
```
In kernel/power/swap.c (ffffffff810dd310)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In kernel/profile.c (ffffffff810fa33b)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/crash_core.c (ffffffff8111d237)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - kernel/crash_core.c:paddr_vmcoreinfo_note
```
```
In kernel/kexec_core.c (ffffffff8111d63a)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_add_entry
```
```
In kernel/kexec_file.c (ffffffff8111fddb)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
```
```
In kernel/trace/trace.c (ffffffff81163386)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/events/ring_buffer.c (ffffffff811af3ad)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_free_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page_alloc.c (ffffffff820cf619)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap.c (ffffffff811ca0df)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/shmem.c (ffffffff811dbcfc)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In mm/percpu.c (ffffffff811e4b69)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/list_lru.c (ffffffff811edd02)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffff811ee510)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/gup.c (ffffffff811ef6ec)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
```
```
In mm/memory.c (ffffffff811f1c77)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:init_zero_pfn
```
```
In mm/page_vma_mapped.c (ffffffff81202018)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff81202d1a)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/memblock.c (ffffffff81904380)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
```
```
In mm/hugetlb.c (ffffffff8121a340)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff8121a9fd)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse.c (ffffffff8121f54d)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
```
```
In mm/sparse-vmemmap.c (ffffffff820d58aa)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812234a3)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff8122592f)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/memory_hotplug.c (ffffffff820d6149)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff81230b55)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff8123482d)
Location: arch/x86/include/asm/page_64.h:13
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
In mm/khugepaged.c (ffffffff812391f2)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/zbud.c (ffffffff812478b3)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - mm/zbud.c:free_zbud_page
```
```
In mm/cma.c (ffffffff820d7ceb)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In mm/usercopy.c (ffffffff8124c89f)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
```
```
In fs/direct-io.c (ffffffff8129477c)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff812ab7c1)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
```
```
In fs/crypto/bio.c (ffffffff812ae2c0)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap.c (ffffffff812bdf54)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_zero
```
```
In fs/proc/kcore.c (ffffffff812d6aa9)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - fs/proc/kcore.c:elf_kcore_store_hdr
  - fs/proc/kcore.c:kclist_add_private
```
```
In fs/proc/vmcore.c (ffffffff812d7a00)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In fs/jbd2/journal.c (ffffffff8134b3df)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/crypto.c (ffffffff8136467f)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81399897)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff81400a25)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff8140127e)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
```
```
In crypto/skcipher.c (ffffffff814029a3)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814069ac)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In block/bio.c (ffffffff8141d4e5)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - block/bio.c:bio_map_kern
```
```
In block/blk-merge.c (ffffffff8142bd46)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-lib.c (ffffffff8142eae0)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zeroout
```
```
In block/bio-integrity.c (ffffffff81455d7f)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
```
```
In lib/scatterlist.c (ffffffff81463e3e)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff814695e8)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
```
```
In lib/swiotlb.c (ffffffff81481fdb)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_init_with_tbl
  - lib/swiotlb.c:swiotlb_init_with_tbl
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
```
```
In drivers/pci/dwc/pcie-designware-host.c (ffffffff814d383d)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff8154ed85)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff815562f2)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
```
```
In drivers/xen/manage.c (ffffffff81557f08)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff820f03f4)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8155b9d0)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8155d34d)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff820f06b1)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff815622a5)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81565cf7)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8159023d)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8159c29d)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/mem.c (ffffffff815a40a6)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/agp/generic.c (ffffffff815b0b74)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff815b2afe)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815b4f93)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c59bb)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff815ca5cd)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff815cafa4)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff815d32b3)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:domain_unmap
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel-svm.c (ffffffff815d431d)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d493b)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/dma-mapping.c (ffffffff815f5c9e)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dma_common_mmap
```
```
In drivers/spi/spi.c (ffffffff8168b6f8)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8169e047)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In drivers/usb/core/hcd.c (ffffffff816b009d)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/devio.c (ffffffff816bf093)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816d140d)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816fb477)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/md/dm-io.c (ffffffff81756ba4)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/md/dm-io.c:km_get_page
```
```
In drivers/md/dm-kcopyd.c (ffffffff82100eab)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff8177ec64)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff821040e6)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/memmap.c (ffffffff819058f1)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff817ab968)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In net/core/skbuff.c (ffffffff817bad73)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:build_skb
```
```
In net/ipv4/tcp.c (ffffffff81824dc8)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/packet/af_packet.c (ffffffff818cf774)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
```
```
In lib/cpumask.c (ffffffff8210f16d)
Location: arch/x86/include/asm/page_64.h:13
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
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
In arch/x86/kernel/head64.c (ffffffff826a31e4)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
```
```
In init/main.c (ffffffff826a3fd4)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81004107)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d937)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff8100dcf9)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff810126f1)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/xen/mmu.c (ffffffff8101b2ae)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_mfn_pte_fn
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff826aa32a)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
```
```
In arch/x86/xen/mmu_hvm.c (ffffffff8101c860)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff826aa9d3)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8101d78b)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/p2m.c (ffffffff8101ecc2)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff826ac59f)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025557)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_get_user_pgd
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff826ade3b)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
```
```
In arch/x86/xen/smp_pv.c (ffffffff81029537)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In arch/x86/xen/efi.c (ffffffff826af3c5)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102a5e1)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/realmode/init.c (ffffffff826af531)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:init_real_mode
```
```
In arch/x86/kernel/ldt.c (ffffffff81031d9e)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff826b13f3)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/pci-dma.c (0)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff81035971)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff8103e2ac)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_shutdown
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052e24)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff826bac2f)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff826be363)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106225c)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/kernel/check.c (ffffffff8106bbcc)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff826c0b51)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff826c221c)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff8106f7a7)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
  - arch/x86/kernel/tce_64.c:free_tce_table
```
```
In arch/x86/mm/init.c (ffffffff826c2d53)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:early_alloc_pgt_buf
```
```
In arch/x86/mm/init_64.c (ffffffff8198c843)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/ioremap.c (ffffffff826c36fd)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81077a4e)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:alloc_pte_page
```
```
In arch/x86/mm/mmap.c (ffffffff8107814a)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_phys_addr_range
```
```
In arch/x86/mm/pat.c (ffffffff81078d51)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff81079908)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff8107ab1e)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/numa.c (ffffffff826c46f0)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_reset_distance
```
```
In arch/x86/mm/kaslr.c (ffffffff8198cae4)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff826c5873)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5fe9)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi.c (ffffffff826c7ab6)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81083ac3)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/fork.c (ffffffff8108807b)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/resource.c (ffffffff810924d1)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff810e4e8e)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
```
```
In kernel/power/swap.c (ffffffff810e5560)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In kernel/profile.c (ffffffff81104c97)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/crash_core.c (ffffffff81128927)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - kernel/crash_core.c:paddr_vmcoreinfo_note
```
```
In kernel/kexec_core.c (ffffffff81128d8a)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_add_entry
```
```
In kernel/kexec_file.c (ffffffff8112b57b)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
```
```
In kernel/trace/ring_buffer.c (ffffffff811691d1)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In kernel/trace/trace.c (ffffffff811703b4)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/events/core.c (ffffffff811c036f)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/ring_buffer.c (ffffffff811c2f6d)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_free_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page_alloc.c (ffffffff826d8039)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap.c (ffffffff811def9f)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/shmem.c (ffffffff811f1b14)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In mm/percpu.c (ffffffff811fae00)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/list_lru.c (ffffffff81204162)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffff81204860)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/gup.c (ffffffff8120672e)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff812088d9)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:init_zero_pfn
```
```
In mm/page_vma_mapped.c (ffffffff8121a758)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff8121ba76)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/memblock.c (ffffffff8198e389)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
```
```
In mm/hugetlb.c (ffffffff8123547c)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff81235c7a)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse.c (ffffffff8123a783)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
```
```
In mm/sparse-vmemmap.c (ffffffff826de4cf)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff8123ea6d)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff81240fbf)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/memory_hotplug.c (ffffffff826ded94)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff8124b182)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff81252740)
Location: arch/x86/include/asm/page_64.h:14
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
In mm/khugepaged.c (ffffffff81258cac)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/zbud.c (ffffffff81267a63)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - mm/zbud.c:free_zbud_page
```
```
In mm/cma.c (ffffffff826e097f)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In mm/usercopy.c (ffffffff8126cd5f)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
```
```
In fs/direct-io.c (ffffffff812b7720)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff812cef55)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
```
```
In fs/crypto/bio.c (ffffffff812d1cbc)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap.c (ffffffff812e1824)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_zero
```
```
In fs/proc/kcore.c (ffffffff812fb2f9)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - fs/proc/kcore.c:elf_kcore_store_hdr
  - fs/proc/kcore.c:kclist_add_private
```
```
In fs/proc/vmcore.c (ffffffff812fc0e0)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In fs/jbd2/journal.c (ffffffff8136fa0c)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/crypto.c (ffffffff8138939f)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813bf067)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff81429025)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff8142988e)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
```
```
In crypto/skcipher.c (ffffffff8142b013)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8142f2ec)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/gcm.c (ffffffff81439d8a)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In block/bio.c (ffffffff81448375)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - block/bio.c:bio_map_kern
```
```
In block/blk-merge.c (ffffffff81457106)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-lib.c (ffffffff81459d67)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
```
```
In block/bio-integrity.c (ffffffff814819db)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
```
```
In lib/scatterlist.c (ffffffff8148f82e)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff814958b8)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
```
```
In lib/swiotlb.c (ffffffff814bde56)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_init_with_tbl
  - lib/swiotlb.c:swiotlb_init_with_tbl
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
```
```
In drivers/pci/dwc/pcie-designware-host.c (ffffffff81513c0d)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff815b2525)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff815b9df2)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
```
```
In drivers/xen/manage.c (ffffffff815bc083)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff826f9bfe)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff815bfcf0)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815c164d)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff826f9ebb)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff815c65a5)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815c9e97)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815f4d3d)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816015a6)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/generic.c (ffffffff8161771a)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8161972e)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8161bc33)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff8162aa03)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_dte_irq_entry
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff8163100a)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff81631d74)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff81639fbb)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:domain_unmap
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel-svm.c (ffffffff8163b09d)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163b6cb)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/dma-mapping.c (ffffffff8165dbbe)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dma_common_mmap
  - drivers/base/dma-mapping.c:dma_common_get_sgtable
```
```
In drivers/spi/spi.c (ffffffff816f5083)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff817091e7)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In drivers/usb/core/hcd.c (ffffffff8171b5e2)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/devio.c (ffffffff8172aa8a)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8173da7d)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81767fe7)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81773d13)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/md/dm-io.c (ffffffff817c8db4)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/md/dm-io.c:km_get_page
```
```
In drivers/md/dm-kcopyd.c (ffffffff8270a568)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff817f5204)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff8270d7c7)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/memmap.c (ffffffff8198f964)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81822ee0)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In net/core/skbuff.c (ffffffff81832e4d)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:build_skb
```
```
In net/ipv4/tcp.c (ffffffff818a3738)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/packet/af_packet.c (ffffffff819546e4)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
```
```
In lib/cpumask.c (ffffffff8271955e)
Location: arch/x86/include/asm/page_64.h:14
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
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
In arch/x86/kernel/head64.c (ffffffff826cc1dc)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In init/main.c (ffffffff826cd0c1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/entry/vdso/vma.c (ffffffff810048a2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/events/intel/bts.c (ffffffff8100e1a0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e4a5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff81013182)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/xen/mmu.c (ffffffff8101bc60)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:remap_area_pfn_pte_fn
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff826d348d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/mmu_hvm.c (ffffffff8101d275)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff826d3b35)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8101e0f5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/p2m.c (ffffffff8101f751)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff826d56e6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810262a3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_get_user_pgd
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff826d71bf)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
```
```
In arch/x86/xen/smp_pv.c (ffffffff81029f99)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In arch/x86/xen/efi.c (ffffffff826d8664)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102b1ea)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102bd07)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/realmode/init.c (ffffffff826d8c28)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:init_real_mode
```
```
In arch/x86/kernel/ldt.c (ffffffff8103301e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff826daa9a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/alternative.c (ffffffff810368d3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff8103f833)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81055b0b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff826e49f5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff826e8168)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106534e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/kernel/check.c (ffffffff8106eb25)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff826ead67)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff826ec429)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff8107269f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
  - arch/x86/kernel/tce_64.c:free_tce_table
```
```
In arch/x86/mm/init.c (ffffffff826ecf65)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:early_alloc_pgt_buf
```
```
In arch/x86/mm/init_64.c (ffffffff819e9152)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/ioremap.c (ffffffff826ed96b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff8107a465)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:alloc_pte_page
```
```
In arch/x86/mm/mmap.c (ffffffff8107ac09)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_phys_addr_range
```
```
In arch/x86/mm/pat.c (ffffffff8107b745)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff8107c4ce)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff8107d8c4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/numa.c (ffffffff826ee986)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_reset_distance
```
```
In arch/x86/mm/kaslr.c (ffffffff819e93ea)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff826ef95d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826efe9a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi.c (ffffffff826f1bb5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8108676e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_query_variable_info
  - arch/x86/platform/efi/efi_64.c:efi_thunk_query_variable_info
  - arch/x86/platform/efi/efi_64.c:efi_thunk_query_variable_info
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/fork.c (ffffffff8108bdc2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/resource.c (ffffffff81095eae)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff810ecaf5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
```
```
In kernel/power/swap.c (ffffffff810eda55)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In kernel/dma/mapping.c (ffffffff8110c62b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_mmap
  - kernel/dma/mapping.c:dma_common_get_sgtable
```
```
In kernel/dma/direct.c (0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff8110d7ef)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In kernel/profile.c (ffffffff8110fa45)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/crash_core.c (ffffffff811365e5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/crash_core.c:paddr_vmcoreinfo_note
```
```
In kernel/kexec_core.c (ffffffff81136e05)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_add_entry
```
```
In kernel/kexec_file.c (ffffffff81139675)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In kernel/trace/ring_buffer.c (ffffffff8117b364)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In kernel/trace/trace.c (ffffffff8117f354)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/events/core.c (ffffffff811e0783)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/ring_buffer.c (ffffffff811e3325)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_free_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page_alloc.c (ffffffff827024dd)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap.c (ffffffff81200665)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/shmem.c (ffffffff81211fec)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In mm/percpu.c (ffffffff8121c05c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/list_lru.c (ffffffff81224e05)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffff8122560a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/gup.c (ffffffff81225ec0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In mm/memory.c (ffffffff812298fb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:init_zero_pfn
```
```
In mm/page_vma_mapped.c (ffffffff8123c84c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff8123d815)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/memblock.c (ffffffff819eac06)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
```
```
In mm/hugetlb.c (ffffffff8125839f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff8125a6d9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse.c (ffffffff8125dcf3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_early_usemaps_alloc_node
  - mm/sparse.c:sparse_early_usemaps_alloc_node
  - mm/sparse.c:sparse_early_usemaps_alloc_node
```
```
In mm/sparse-vmemmap.c (ffffffff82708a0a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff82708b67)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff81264104)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/memory_hotplug.c (ffffffff827092cf)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff8126dd82)
Location: arch/x86/include/asm/page_64.h:18
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
Location: arch/x86/include/asm/page_64.h:18
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
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/zbud.c (ffffffff8128c3b5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/zbud.c:free_zbud_page
```
```
In mm/cma.c (ffffffff8270aeaa)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In mm/usercopy.c (ffffffff812919af)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In fs/dcache.c (ffffffff812b7393)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/dcache.c:__d_alloc
  - fs/dcache.c:__d_free_external_name
```
```
In fs/direct-io.c (ffffffff812e155f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff812f96e6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In fs/crypto/bio.c (ffffffff812fc80a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap.c (ffffffff8130df15)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_zero
```
```
In fs/proc/kcore.c (ffffffff81328929)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/proc/kcore.c:elf_kcore_store_hdr
```
```
In fs/proc/vmcore.c (ffffffff81329b40)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In fs/jbd2/journal.c (ffffffff8139df18)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/crypto.c (ffffffff813b820b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813efdf3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff8145bdf9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff8145c99b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
```
```
In crypto/skcipher.c (ffffffff8145dd81)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81461f73)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/gcm.c (ffffffff8146ca71)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In block/bio.c (ffffffff8147b4c0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/bio.c:bio_map_kern
```
```
In block/blk-merge.c (ffffffff8148ac8b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-lib.c (ffffffff8148d421)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
```
```
In block/bio-integrity.c (ffffffff814b6488)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
```
```
In lib/scatterlist.c (ffffffff814c4509)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff814cabe0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff815ea9f2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff815f1c04)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/xen/manage.c (ffffffff815f4571)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff82723f99)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff815f8400)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815f9747)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8272423c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff815fed97)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81602a95)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162ddbe)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8163a838)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/generic.c (ffffffff81651211)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816533e8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816558e5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff81667955)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff8166bfc0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff8166d0fa)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff81675133)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:domain_unmap
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel-svm.c (ffffffff81676623)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81676ca5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/spi/spi.c (ffffffff81732879)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/net/xen-netfront.c (ffffffff81747d1c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In drivers/usb/core/hcd.c (ffffffff8175a401)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/devio.c (ffffffff81769469)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81775851)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8177e3f6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817a961d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b435e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/i2c/busses/i2c-amd-platdrv.c (ffffffff817dd432)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_xfer
```
```
In drivers/md/dm-io.c (ffffffff81811bc5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/md/dm-io.c:km_get_page
```
```
In drivers/md/dm-kcopyd.c (ffffffff82734775)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff8183e758)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff82737a5b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/memmap.c (ffffffff819ec1d8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d1df)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In net/core/skbuff.c (ffffffff8187d36d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff818ba9e0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/ipv4/tcp.c (ffffffff818f8a8f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/packet/af_packet.c (ffffffff819ae97d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/xdp/xsk.c (ffffffff819cb534)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
```
```
In lib/cpumask.c (ffffffff82743d32)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
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
In arch/x86/kernel/head64.c (ffffffff828821dc)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In init/main.c (ffffffff828830a2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/entry/vdso/vma.c (ffffffff810047d0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/events/intel/bts.c (ffffffff8100e670)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e975)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff81013b52)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/xen/mmu.c (ffffffff8101b91f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828893b1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/mmu_hvm.c (ffffffff8101c955)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff82889bc8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8101d975)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/p2m.c (ffffffff8101f009)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8288b76a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025e53)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_get_user_pgd
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_batched_set_pte
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff8288d251)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a579)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In arch/x86/xen/efi.c (ffffffff8288e6a3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102bd1f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102ca11)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102cdca)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/realmode/init.c (ffffffff8288f00c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:init_real_mode
```
```
In arch/x86/kernel/ldt.c (ffffffff81034438)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff82890e7c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/alternative.c (ffffffff81037ae1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81040e33)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810531ab)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105c295)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff8289b4ca)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8289ecbd)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106afbe)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/kernel/check.c (ffffffff81074b31)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff828a1a02)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828a3011)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff810786ef)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
  - arch/x86/kernel/tce_64.c:free_tce_table
```
```
In arch/x86/mm/init.c (ffffffff828a3af7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In arch/x86/mm/init_64.c (ffffffff81a24a98)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/ioremap.c (ffffffff828a44fd)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81080c15)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:alloc_pte_page
```
```
In arch/x86/mm/mmap.c (ffffffff81081549)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_phys_addr_range
```
```
In arch/x86/mm/pat.c (ffffffff810820b5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff81082ec3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff810843f4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/numa.c (ffffffff828a5674)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_reset_distance
```
```
In arch/x86/mm/kaslr.c (ffffffff81a24d30)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108a380)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a6b57)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi.c (ffffffff828a8962)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8108d9fa)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/fork.c (ffffffff810936cf)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/resource.c (ffffffff8109e21e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff810f8195)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
```
```
In kernel/power/swap.c (ffffffff810f90c5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In kernel/dma/mapping.c (ffffffff8111841d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_mmap
  - kernel/dma/mapping.c:dma_common_get_sgtable
```
```
In kernel/dma/direct.c (ffffffff81118d24)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
```
```
In kernel/dma/swiotlb.c (ffffffff811193ef)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In kernel/profile.c (ffffffff8111b135)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/crash_core.c (ffffffff81141d75)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/crash_core.c:paddr_vmcoreinfo_note
```
```
In kernel/kexec_core.c (ffffffff81142465)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_add_entry
```
```
In kernel/kexec_file.c (ffffffff81144f45)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In kernel/trace/ring_buffer.c (ffffffff811856a4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In kernel/trace/trace.c (ffffffff8118cbc3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/events/core.c (ffffffff811f0bee)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/ring_buffer.c (ffffffff811f37e5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_free_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page_alloc.c (ffffffff828b9c03)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/swap.c (ffffffff81212fd5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/shmem.c (ffffffff81226199)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In mm/percpu.c (ffffffff8122f03c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/list_lru.c (ffffffff81237f15)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffff81238a2f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/gup.c (ffffffff81239630)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In mm/memory.c (ffffffff8123ce2a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:init_zero_pfn
```
```
In mm/mremap.c (ffffffff8124f3e9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81250c58)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff81251dc5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/memblock.c (ffffffff81a25e6d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
```
```
In mm/hugetlb.c (ffffffff8126ca6f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff8126e55b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse.c (ffffffff81272549)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
```
```
In mm/sparse-vmemmap.c (ffffffff81a27218)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff828bfe0c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/slub.c (ffffffff81278874)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/memory_hotplug.c (ffffffff828c0574)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff81282bf2)
Location: arch/x86/include/asm/page_64.h:18
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
Location: arch/x86/include/asm/page_64.h:18
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
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/zbud.c (ffffffff812a1325)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/zbud.c:free_zbud_page
```
```
In mm/cma.c (ffffffff828c208e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In mm/usercopy.c (ffffffff812a69ec)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In fs/direct-io.c (ffffffff812f4fd3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff8130e198)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In fs/crypto/bio.c (ffffffff81312071)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap.c (ffffffff81323635)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_zero
```
```
In fs/proc/kcore.c (ffffffff8134014d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/vmcore.c (ffffffff81340970)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In fs/jbd2/journal.c (ffffffff813b6c88)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/crypto.c (ffffffff813d178b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8140b0d3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff814796f9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff8147a00b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
```
```
In crypto/skcipher.c (ffffffff8147b621)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8147fd43)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff8148a1e1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff8149001e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In block/bio.c (ffffffff81498c20)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/bio.c:bio_map_kern
```
```
In block/blk-merge.c (ffffffff814a4857)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-lib.c (ffffffff814a6ca9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
```
```
In block/bio-integrity.c (ffffffff814c9db7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
```
```
In lib/scatterlist.c (ffffffff814d8bf9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff814df910)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff81604cec)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8160c9a4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/xen/manage.c (ffffffff8160f3d1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff828dc172)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81613760)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81614807)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828dc415)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81619e67)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8161d7b5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8164bfce)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81658aeb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/generic.c (ffffffff8166f3dc)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816715e8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81673ae5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff81685e75)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:free_pt_l2
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff8168a45a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff8168b4cb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff81692dd5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:domain_unmap
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel-pasid.c (ffffffff816947c4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff81695aeb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81695d55)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81702b6c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/spi/spi.c (ffffffff81755269)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/net/tun.c (ffffffff81763676)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff8176bdfc)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In drivers/usb/core/hcd.c (ffffffff8177e942)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/devio.c (ffffffff8178daec)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8179ae6f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817a4a68)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817cf588)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817da8af)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff828ea6cf)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_get_page
```
```
In drivers/md/dm-io.c (ffffffff8183db65)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/md/dm-io.c:km_get_page
```
```
In drivers/md/dm-kcopyd.c (ffffffff828eddd4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff8186a708)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff828f1987)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/memmap.c (ffffffff81a27428)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
```
```
In drivers/firmware/efi/efi.c (ffffffff81a234df)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In arch/x86/power/hibernate_64.c (ffffffff8188d08f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In net/core/skbuff.c (ffffffff8189df4b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff818e1926)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/ipv4/tcp.c (ffffffff819267b6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/packet/af_packet.c (ffffffff819e509d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/xdp/xsk.c (ffffffff81a04785)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
```
```
In lib/cpumask.c (ffffffff828fe053)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
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
In arch/x86/kernel/head64.c (ffffffff828991dc)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In init/main.c (ffffffff8289a0fc)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81004a6a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/events/intel/bts.c (ffffffff8100ef33)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f245)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff8101502a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/xen/mmu.c (ffffffff8101d45f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a0732)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/mmu_hvm.c (ffffffff8101e475)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff828a0f74)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8101f516)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/p2m.c (ffffffff81020b69)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a2ba1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81027b53)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_get_user_pgd
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a46e1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102c356)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/xen/efi.c (ffffffff828a5c49)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102ddfe)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102e771)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102ea08)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/realmode/init.c (ffffffff828a654a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:init_real_mode
```
```
In arch/x86/kernel/ldt.c (ffffffff810361c5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff828a83e7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/alternative.c (ffffffff8103975d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81043523)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105633c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105f635)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff828b32a7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828b6bee)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ea8e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/check.c (ffffffff810786f7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff828b9c70)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828bb343)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff8107c266)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
  - arch/x86/kernel/tce_64.c:free_tce_table
```
```
In arch/x86/mm/init.c (ffffffff828bbf96)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In arch/x86/mm/init_64.c (ffffffff81a94e6c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/ioremap.c (ffffffff828bc9cc)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81084705)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wt
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/mmap.c (ffffffff810851c0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_phys_addr_range
```
```
In arch/x86/mm/pat.c (ffffffff81085d35)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff81086b25)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff8108806c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/numa.c (ffffffff828bdc0f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_reset_distance
```
```
In arch/x86/mm/kaslr.c (ffffffff81a950de)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108e0d5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828bf1ee)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi.c (ffffffff828c0983)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810918aa)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/fork.c (ffffffff81098a82)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/resource.c (ffffffff810a278c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff81100717)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
```
```
In kernel/power/swap.c (ffffffff811017b5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In kernel/dma/mapping.c (ffffffff811227ce)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_mmap
  - kernel/dma/mapping.c:dma_common_get_sgtable
```
```
In kernel/dma/direct.c (ffffffff81123206)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
```
```
In kernel/dma/swiotlb.c (ffffffff81123e54)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In kernel/profile.c (ffffffff81125811)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/crash_core.c (ffffffff8114d125)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/crash_core.c:paddr_vmcoreinfo_note
```
```
In kernel/kexec_core.c (ffffffff8114d885)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_add_entry
```
```
In kernel/kexec_file.c (ffffffff81150345)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In kernel/trace/ring_buffer.c (ffffffff811929e4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In kernel/trace/trace.c (ffffffff8119a477)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/cpumap.c (ffffffff811f3c59)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/events/core.c (ffffffff812083b0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/ring_buffer.c (ffffffff8120b4d7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_free_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/swap.c (ffffffff81222ddb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/shmem.c (ffffffff81235b57)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In mm/percpu.c (ffffffff8123f03f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/list_lru.c (ffffffff812494c5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
  - mm/list_lru.c:list_lru_add
```
```
In mm/gup.c (ffffffff8124c030)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In mm/memory.c (ffffffff8124ea94)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:init_zero_pfn
```
```
In mm/mremap.c (ffffffff8126173c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81262f38)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff812640a5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/page_alloc.c (ffffffff828d6d1d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/memblock.c (ffffffff81a96591)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
```
```
In mm/hugetlb.c (ffffffff81287e9a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
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
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff81289b8d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse.c (ffffffff828d8b90)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
```
```
In mm/sparse-vmemmap.c (ffffffff81a97ac6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff828d9177)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
```
In mm/slub.c (ffffffff81294971)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/memory_hotplug.c (ffffffff828d98fb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812a123c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff812a66be)
Location: arch/x86/include/asm/page_64.h:18
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
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff812b27b5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In mm/zbud.c (ffffffff812bc5e5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/zbud.c:free_zbud_page
```
```
In mm/cma.c (ffffffff828db45a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In mm/usercopy.c (ffffffff812c20d1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In mm/hmm.c (ffffffff812c3e3a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/direct-io.c (ffffffff81316bb2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/io_uring.c (ffffffff8132dfdf)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_mem_free
```
```
In fs/dax.c (ffffffff8133468d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In fs/crypto/bio.c (ffffffff813395b5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/direct-io.c (ffffffff8134d6a5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/proc/kcore.c (ffffffff81368437)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/vmcore.c (ffffffff81368d43)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In fs/jbd2/journal.c (ffffffff813e1367)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/crypto.c (ffffffff813fc2ac)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81437eb2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff814a7397)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814a7ed6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
```
```
In crypto/skcipher.c (ffffffff814a98a1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814adf3e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff814b79c2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff814bd20b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c0e33)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/bio.c (ffffffff814c6c2a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/bio.c:bio_map_kern
```
```
In block/blk-merge.c (ffffffff814d23f8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-lib.c (ffffffff814d4bc4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
```
```
In block/bio-integrity.c (ffffffff814f86b2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
```
```
In lib/scatterlist.c (ffffffff81504aa9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff8150b7c0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8163760a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff816405de)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/xen/manage.c (ffffffff816431cc)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff828f6a6b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8164757a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff816484e8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828f6d04)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8164dc39)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
```
```
In drivers/xen/swiotlb-xen.c (ffffffff816509e5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81680dc0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8168dfcb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/generic.c (ffffffff816a4f39)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816a710a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816a95d1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816bd5d3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:free_pt_l2
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816c1e06)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff816c2efb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff816cb6c5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:domain_unmap
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel-pasid.c (ffffffff816cd0b9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff816ce3eb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816ce695)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8173ca19)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/dax/super.c (ffffffff8173f896)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/spi/spi.c (ffffffff8179136f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/net/tun.c (ffffffff817a13a3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff817a9bee)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In drivers/usb/core/hcd.c (ffffffff817bcebf)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/devio.c (ffffffff817cc5f1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817d9ff0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817e3ca8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8180f9fd)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8181afd1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff829050fb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_get_page
```
```
In drivers/md/dm-io.c (ffffffff81880815)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/md/dm-io.c:km_get_page
```
```
In drivers/md/dm-kcopyd.c (ffffffff82909259)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff818ae5f7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff8290cfd7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/memmap.c (ffffffff81a97ceb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
```
```
In drivers/firmware/efi/efi.c (ffffffff81a9361d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In arch/x86/power/hibernate_64.c (ffffffff818d7abf)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In net/core/skbuff.c (ffffffff818e871a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff81930099)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/ipv4/tcp.c (ffffffff81987679)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/packet/af_packet.c (ffffffff81a54214)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/xdp/xsk.c (ffffffff81a74cb6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
```
```
In lib/cpumask.c (ffffffff8291acb3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
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
In arch/x86/kernel/head64.c (ffffffff8289c1dc)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In init/main.c (ffffffff8289d0e1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81004ae3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/events/intel/bts.c (ffffffff8100efd0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f8f5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff8101592d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/xen/mmu.c (ffffffff8101ddff)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a3822)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/mmu_hvm.c (ffffffff8101edf5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff828a4042)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8101fe76)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/p2m.c (ffffffff810214c9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a5c54)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81028493)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_get_user_pgd
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a7771)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ccf6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/xen/efi.c (ffffffff828a8c51)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102e70e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102f081)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f318)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/realmode/init.c (ffffffff828a9589)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:init_real_mode
```
```
In arch/x86/kernel/ldt.c (ffffffff81036af0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff828ab447)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/alternative.c (ffffffff81039f2d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81043c73)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056bec)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105fec5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff828b66fe)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828ba0c3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107003e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/check.c (ffffffff81079747)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff828c015e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828c181f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff8107d356)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
  - arch/x86/kernel/tce_64.c:free_tce_table
```
```
In arch/x86/mm/init.c (ffffffff828c243d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In arch/x86/mm/init_64.c (ffffffff81acc74c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/ioremap.c (ffffffff828c2e73)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81085355)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/mmap.c (ffffffff81085eb0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_phys_addr_range
```
```
In arch/x86/mm/pat.c (ffffffff81086a25)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff81087815)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81088d34)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/numa.c (ffffffff828c4099)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_reset_distance
```
```
In arch/x86/mm/kaslr.c (ffffffff81acc9be)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108ed72)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c5669)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi.c (ffffffff828c6e1a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81092599)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828c9435)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
```
```
In kernel/fork.c (ffffffff8109f044)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/resource.c (ffffffff810a8d5c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff8110cb77)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
```
```
In kernel/power/swap.c (ffffffff8110dbe5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In kernel/dma/mapping.c (ffffffff8112ecb8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_mmap
```
```
In kernel/dma/direct.c (ffffffff8112f646)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
```
```
In kernel/dma/swiotlb.c (ffffffff8112fde4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In kernel/profile.c (ffffffff811317e1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/crash_core.c (ffffffff81158df5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/crash_core.c:paddr_vmcoreinfo_note
```
```
In kernel/kexec_core.c (ffffffff81159595)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_add_entry
```
```
In kernel/kexec_file.c (ffffffff8115bfd5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In kernel/trace/ring_buffer.c (ffffffff8119e664)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In kernel/trace/trace.c (ffffffff811a5d27)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/cpumap.c (ffffffff812009f9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/events/core.c (ffffffff81215720)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/ring_buffer.c (ffffffff812187b7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_free_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/swap.c (ffffffff81230573)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/shmem.c (ffffffff81243d97)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In mm/percpu.c (ffffffff8124d49f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/list_lru.c (ffffffff81257915)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
  - mm/list_lru.c:list_lru_add
```
```
In mm/gup.c (ffffffff8125a519)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In mm/memory.c (ffffffff8125d03e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:init_zero_pfn
```
```
In mm/mremap.c (ffffffff8126fefa)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812716e8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff81272915)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/page_alloc.c (ffffffff828df1ae)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/memblock.c (ffffffff81acde68)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
```
```
In mm/hugetlb.c (ffffffff81297a9a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
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
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff812996fd)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse.c (ffffffff8129d72b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_buffer_free
```
```
In mm/sparse-vmemmap.c (ffffffff81acf394)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff828e15ca)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
```
In mm/slub.c (ffffffff812a4741)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/memory_hotplug.c (ffffffff828e1d51)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812ae692)
Location: arch/x86/include/asm/page_64.h:18
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
Location: arch/x86/include/asm/page_64.h:18
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
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff812c6ede)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In mm/zbud.c (ffffffff812ce4d5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/zbud.c:free_zbud_page
```
```
In mm/cma.c (ffffffff828e3890)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In mm/usercopy.c (ffffffff812d4001)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In mm/hmm.c (ffffffff812d5b82)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/direct-io.c (ffffffff81329a30)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/io_uring.c (ffffffff81341215)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_mem_free
```
```
In fs/dax.c (ffffffff8134825d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In fs/crypto/bio.c (ffffffff8134f438)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/direct-io.c (ffffffff81365965)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/proc/kcore.c (ffffffff813806a4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/vmcore.c (ffffffff81380fa3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In fs/jbd2/journal.c (ffffffff813fb3b7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/crypto.c (ffffffff8141618c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81451c72)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff814c2007)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814c2b36)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
```
```
In crypto/skcipher.c (ffffffff814c4591)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814c8beb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff814d0be2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff814d5eae)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d9c63)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/bio.c (ffffffff814e0809)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/bio.c:bio_map_kern
```
```
In block/blk-merge.c (ffffffff814eb778)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-lib.c (ffffffff814edec4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
```
```
In block/bio-integrity.c (ffffffff8151642f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
```
```
In lib/scatterlist.c (ffffffff81523129)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff815295e0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8165935b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81662cee)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/xen/manage.c (ffffffff8166576c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff828ffac2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81669a1a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8166a988)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828ffd5b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81670119)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81672f65)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816a3470)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816b065b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/generic.c (ffffffff816c7c69)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816c9e4a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816cc311)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816de2d5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_dte_irq_entry
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:free_pt_l2
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816e4d26)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff816e5deb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff816eea65)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:domain_unmap
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel-pasid.c (ffffffff816f0919)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff816f222b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f24d5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff817607bc)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/dax/super.c (ffffffff81763a76)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/spi/spi.c (ffffffff817b4f6c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/net/tun.c (ffffffff817c6363)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff817cd65e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In drivers/usb/core/hcd.c (ffffffff817ed954)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/devio.c (ffffffff817fd280)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180b0d1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81814a9a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81840e4a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184bcd4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8290eb36)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_get_page
```
```
In drivers/md/dm-io.c (ffffffff818b26d5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/md/dm-io.c:km_get_page
```
```
In drivers/md/dm-kcopyd.c (ffffffff82912c5e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff818e0a95)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff829169aa)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/memmap.c (ffffffff81acf5b9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
```
```
In drivers/firmware/efi/efi.c (ffffffff81acada4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff829198ad)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f3717)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa
```
```
In arch/x86/power/hibernate_64.c (ffffffff81909dff)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In net/core/skbuff.c (ffffffff8191a95a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff819622f9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/ipv4/tcp.c (ffffffff819bde39)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/packet/af_packet.c (ffffffff81a8ae24)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/xdp/xsk.c (ffffffff81aab886)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
```
```
In lib/cpumask.c (ffffffff82924b22)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
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
In arch/x86/kernel/head64.c (ffffffff82cc21dc)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In init/main.c (ffffffff82cc363d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81005a72)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/events/intel/bts.c (ffffffff81010600)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff81010d05)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff8101751b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/xen/mmu.c (ffffffff810201bf)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff82cc9ad7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/mmu_hvm.c (ffffffff810213a5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff82cca32b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_do_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_update_mem_tables
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff81022596)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/p2m.c (ffffffff81023c99)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:p2m_top_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82ccbf3f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102a3a3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:check_pt_base
  - arch/x86/xen/mmu_pv.c:check_pt_base
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_p2m_free
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_get_user_pgd
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff82ccdb50)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ecd9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/xen/efi.c (ffffffff82cce588)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff81030ca7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff810316ca)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81031838)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/realmode/init.c (ffffffff82cced80)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
```
```
In arch/x86/kernel/ldt.c (ffffffff810388fd)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff82cd0760)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/alternative.c (ffffffff8103cb9b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff810475f0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105bd9b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81065995)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff82cdb7bb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff82cdf2d4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107745e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/check.c (ffffffff81080aba)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_for_bios_corruption
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff82ce44b1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/mm/init.c (ffffffff82ce5778)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In arch/x86/mm/init_64.c (ffffffff81bc3fd7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/ioremap.c (ffffffff82ce626b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/mmap.c (ffffffff81089610)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_phys_addr_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81089c25)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_ctor
  - arch/x86/mm/pgtable.c:pgd_ctor
  - arch/x86/mm/pgtable.c:___p4d_free_tlb
  - arch/x86/mm/pgtable.c:___p4d_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff8108a9d2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f065)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
```
In arch/x86/mm/pat/memtype.c (ffffffff8108f90c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/mm/numa.c (ffffffff82ce75ad)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_reset_distance
```
```
In arch/x86/mm/kaslr.c (ffffffff81bc528a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff8109511b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82ce8879)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi.c (ffffffff82cea3bf)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810982a9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109cfb4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_gpa
```
```
In kernel/fork.c (ffffffff810a38f9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/resource.c (ffffffff810b018c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff81116220)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
```
```
In kernel/power/swap.c (ffffffff81118c05)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In kernel/dma/mapping.c (ffffffff8113d744)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_mmap
  - kernel/dma/mapping.c:dma_common_get_sgtable
```
```
In kernel/dma/swiotlb.c (ffffffff8113ebd0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In kernel/profile.c (ffffffff81140b54)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/crash_core.c (ffffffff811699c5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/crash_core.c:paddr_vmcoreinfo_note
```
```
In kernel/kexec_core.c (ffffffff8116a665)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_add_entry
```
```
In kernel/kexec_file.c (ffffffff8116cf35)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In kernel/trace/ring_buffer.c (ffffffff811b5bd4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In kernel/trace/trace.c (ffffffff811bc016)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/cpumap.c (ffffffff812284b1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/events/core.c (ffffffff81231ef8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/ring_buffer.c (ffffffff81244417)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:__rb_free_aux
```
```
In mm/swap.c (ffffffff8125de61)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/shmem.c (ffffffff8126f527)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In mm/percpu.c (ffffffff8127b83f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/list_lru.c (ffffffff81286155)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/gup.c (ffffffff81288a2e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In mm/memory.c (ffffffff8128d665)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:do_set_pmd
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:init_zero_pfn
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
```
```
In mm/mremap.c (ffffffff8129fdda)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/mremap.c:move_normal_pmd
  - mm/mremap.c:move_normal_pmd
```
```
In mm/page_vma_mapped.c (ffffffff812a1bb5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff812a36d5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/page_alloc.c (ffffffff812b3bb8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/memblock.c (ffffffff81bc6850)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
```
```
In mm/hugetlb.c (ffffffff812cb130)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
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
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff812cea39)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse.c (ffffffff812d13ea)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_buffer_free
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:check_usemap_section_nr
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7d93)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff82cfec1b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
```
In mm/slub.c (ffffffff812ddab9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:cache_from_obj
```
```
In mm/memory_hotplug.c (ffffffff812e1cc3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_section
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812e3cf2)
Location: arch/x86/include/asm/page_64.h:18
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
Location: arch/x86/include/asm/page_64.h:18
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
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff812fc7fe)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In mm/zbud.c (ffffffff81304e68)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
```
```
In mm/usercopy.c (ffffffff81309d5e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In mm/hmm.c (ffffffff8130b7da)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/direct-io.c (ffffffff8136381d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/io_uring.c (ffffffff8137c312)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_uring_mmap
```
```
In fs/dax.c (ffffffff8138ecdd)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In fs/crypto/bio.c (ffffffff81395a37)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/direct-io.c (ffffffff813acde5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/proc/kcore.c (ffffffff813cad74)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/vmcore.c (ffffffff813cb611)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In fs/jbd2/journal.c (ffffffff81448b2f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/crypto.c (ffffffff8146472c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814a49d0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In crypto/skcipher.c (ffffffff8152341c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
```
```
In crypto/rsa-pkcs1pad.c (ffffffff815272bb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff8152f8c4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff81535a91)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff815391ec)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/blk-map.c (ffffffff81549be9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_kern
```
```
In block/blk-lib.c (ffffffff8154d450)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
```
```
In block/bio-integrity.c (ffffffff81576baf)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
```
```
In lib/scatterlist.c (ffffffff81586254)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff8158cc50)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In lib/bootconfig.c (ffffffff82d0a4df)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_destroy_all
```
```
In lib/cpumask.c (ffffffff82d0a932)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
```
```
In drivers/virtio/virtio_ring.c (ffffffff81709bd7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff817129ec)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
```
```
In drivers/xen/manage.c (ffffffff81714e2c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff82d16e6b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8171979e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171aaff)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff82d17057)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenstored_local_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81720669)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_alloc
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817236b5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817559c0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81763a0c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/generic.c (ffffffff8177c99b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8177eaba)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81780c71)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i810_setup
```
```
In drivers/iommu/dma-iommu.c (ffffffff81791d85)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
```
In drivers/iommu/amd/iommu.c (ffffffff8179519f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:increase_address_space
  - drivers/iommu/amd/iommu.c:free_sub_pt
  - drivers/iommu/amd/iommu.c:free_sub_pt
  - drivers/iommu/amd/iommu.c:free_pt_l5
  - drivers/iommu/amd/iommu.c:free_pt_l4
  - drivers/iommu/amd/iommu.c:free_pt_l3
  - drivers/iommu/amd/iommu.c:free_pt_l2
  - drivers/iommu/amd/iommu.c:free_pt_l2
```
```
In drivers/iommu/amd/init.c (ffffffff8179af76)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:iommu_init_ga_log
  - drivers/iommu/amd/init.c:iommu_init_ga_log
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:iommu_set_device_table
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179c6cb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/iommu.c (ffffffff817a4055)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_free_coherent
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/iommu.c:domain_unmap
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff817a83eb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_get_entry
```
```
In drivers/iommu/intel/svm.c (ffffffff817aa07b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817aaa25)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff818205c5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
```
```
In drivers/dax/super.c (ffffffff8182399e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
```
```
In drivers/scsi/scsi_lib.c (ffffffff81836f56)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
```
In drivers/spi/spi.c (ffffffff8187bb24)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/net/tun.c (ffffffff8188b5ab)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/xen-netfront.c (ffffffff81899146)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In drivers/usb/core/hcd.c (ffffffff818bcde5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/devio.c (ffffffff818cc89d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818da75c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_alloc_split_dma_aligned_buf
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818e6927)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81911b49)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191eaf6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81923a2e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_get_page
```
```
In drivers/md/dm-io.c (ffffffff81982e35)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/md/dm-io.c:km_get_page
```
```
In drivers/md/dm-kcopyd.c (ffffffff82d25807)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff819b3ac1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff82d28de6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/memmap.c (ffffffff81bc7ff5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
```
```
In drivers/firmware/efi/efi.c (ffffffff81bc32a4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff82d2bf6a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_tsc_clocksource
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9272)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In net/core/skbuff.c (ffffffff819ecf59)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff81a3642b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/ipv4/tcp.c (ffffffff81aa900e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/packet/af_packet.c (ffffffff81b855f6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81ba7196)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bba99f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_mappings
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
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
In arch/x86/kernel/head64.c (ffffffff82fae21c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In init/main.c (ffffffff82faf6f4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81004a22)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/events/intel/bts.c (ffffffff8100fb60)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff81010263)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff810179bb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/xen/mmu.c (ffffffff81020bef)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff82fb593c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/mmu_hvm.c (ffffffff81021b65)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff82fb6199)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_do_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_update_mem_tables
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff81022c76)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/p2m.c (ffffffff81024271)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
  - arch/x86/xen/p2m.c:p2m_top_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82fb7d73)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102ad83)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:check_pt_base
  - arch/x86/xen/mmu_pv.c:check_pt_base
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_p2m_free
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_get_user_pgd
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff82fb9980)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102fae9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/xen/efi.c (ffffffff82fba3e4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff81031a17)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff810323da)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81032538)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/realmode/init.c (ffffffff82fbac41)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
```
```
In arch/x86/kernel/ldt.c (ffffffff81039249)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff82fbc5a0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/alternative.c (ffffffff8103d05b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81046e20)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105a7eb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81063c45)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff82fc7c11)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff82fcb678)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077a8e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/check.c (ffffffff81bd824b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_for_bios_corruption
```
```
In arch/x86/kernel/sev-es.c (ffffffff81083802)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/sev-es.c:vc_do_mmio
  - arch/x86/kernel/sev-es.c:sev_es_ap_hlt_loop
  - arch/x86/kernel/sev-es.c:get_jump_table_addr
  - arch/x86/kernel/sev-es.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev-es.c:vc_handle_ioio
  - arch/x86/kernel/sev-es.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev-es.c:setup_vc_stacks
  - arch/x86/kernel/sev-es.c:setup_vc_stacks
  - arch/x86/kernel/sev-es.c:sev_es_efi_map_ghcbs
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff82fd1d12)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/mm/init.c (ffffffff82fd2fce)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In arch/x86/mm/init_64.c (ffffffff81c3ced4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/ioremap.c (ffffffff82fd3bf1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/mmap.c (ffffffff810897f0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_phys_addr_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a709)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_ctor
  - arch/x86/mm/pgtable.c:pgd_ctor
  - arch/x86/mm/pgtable.c:___p4d_free_tlb
  - arch/x86/mm/pgtable.c:___p4d_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff8108ac72)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ee55)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
```
In arch/x86/mm/pat/memtype.c (ffffffff8108f5fc)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/mm/numa.c (ffffffff82fd4f22)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_reset_distance
```
```
In arch/x86/mm/kaslr.c (ffffffff81c3e15d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81bda23f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82fd628b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi.c (ffffffff82fd7da7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81097429)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/fork.c (ffffffff810a1516)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
```
```
In kernel/resource.c (ffffffff810ab8ac)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff811126a0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
```
```
In kernel/power/swap.c (ffffffff811146d5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In kernel/printk/printk.c (ffffffff82fdc64a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/dma/mapping.c (ffffffff81137b5f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_noncoherent
```
```
In kernel/dma/ops_helpers.c (ffffffff81139b3e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_mmap
  - kernel/dma/ops_helpers.c:dma_common_get_sgtable
```
```
In kernel/dma/swiotlb.c (ffffffff8113a240)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In kernel/profile.c (ffffffff8113ce84)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/crash_core.c (ffffffff81166115)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/crash_core.c:paddr_vmcoreinfo_note
```
```
In kernel/kexec_core.c (ffffffff81166da5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_add_entry
```
```
In kernel/kexec_file.c (ffffffff811695bb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In kernel/trace/ring_buffer.c (ffffffff811b34b4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In kernel/trace/trace.c (ffffffff811b9c26)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/cpumap.c (ffffffff8122f265)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/events/core.c (ffffffff8123bb68)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/ring_buffer.c (ffffffff8124eac7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:__rb_free_aux
```
```
In mm/swap.c (ffffffff81268261)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/shmem.c (ffffffff8127a897)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In mm/percpu.c (ffffffff8128636f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/list_lru.c (ffffffff81290405)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/gup.c (ffffffff8129270e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In mm/memory.c (ffffffff8129fb17)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:do_set_pmd
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:init_zero_pfn
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
```
```
In mm/mremap.c (ffffffff812ab244)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812ad6b1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff812aefb5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/page_alloc.c (ffffffff812bf66b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/memblock.c (ffffffff81c3f572)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
```
```
In mm/hugetlb.c (ffffffff812d6d40)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
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
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff812da379)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse.c (ffffffff812dcf0a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_buffer_free
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:check_usemap_section_nr
```
```
In mm/sparse-vmemmap.c (ffffffff81c40abe)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff82feb623)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
```
In mm/slub.c (ffffffff812e68cb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memory_hotplug.c (ffffffff81be9aa5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_section
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812efa55)
Location: arch/x86/include/asm/page_64.h:18
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
Location: arch/x86/include/asm/page_64.h:18
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
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff81308ade)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_kmem_state
```
```
In mm/zbud.c (ffffffff81310bc8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
```
```
In mm/usercopy.c (ffffffff81315b7e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In mm/hmm.c (ffffffff813176c6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/direct-io.c (ffffffff81370465)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_zero_block
```
```
In fs/io_uring.c (ffffffff8138a4e2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_uring_mmap
```
```
In fs/dax.c (ffffffff813a03cc)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In fs/crypto/bio.c (ffffffff813a6fd3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
```
```
In fs/iomap/direct-io.c (ffffffff813be4c5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/proc/kcore.c (ffffffff813dca34)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/vmcore.c (ffffffff813dd2bd)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In fs/jbd2/journal.c (ffffffff81465723)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/crypto.c (ffffffff8147feec)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c21d0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In crypto/skcipher.c (ffffffff8154036c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8154423b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff8154c484)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff81552a01)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81555fe5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/blk-map.c (ffffffff81565b49)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_kern
```
```
In block/blk-lib.c (ffffffff81569850)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
```
```
In block/bio-integrity.c (ffffffff8159383c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
```
```
In lib/scatterlist.c (ffffffff815a3334)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff815a96a0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In lib/bootconfig.c (ffffffff82ff7ac6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_destroy_all
```
```
In lib/cpumask.c (ffffffff82ff7f26)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8167c2b8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff81726b47)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8172f77c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
```
```
In drivers/xen/manage.c (ffffffff81731a1c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff83004a5b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff817369ec)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81737c6f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff83004c37)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenstored_local_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8173d5c9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_alloc
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81740365)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
```
In drivers/xen/unpopulated-alloc.c (ffffffff81743837)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/unpopulated-alloc.c:fill_list
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81770c30)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8177ea12)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/generic.c (ffffffff81795aeb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81796fea)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81798c21)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i810_setup
```
```
In drivers/iommu/amd/iommu.c (ffffffff817a355f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:increase_address_space
  - drivers/iommu/amd/iommu.c:free_sub_pt
  - drivers/iommu/amd/iommu.c:free_sub_pt
  - drivers/iommu/amd/iommu.c:free_pt_l5
  - drivers/iommu/amd/iommu.c:free_pt_l4
  - drivers/iommu/amd/iommu.c:free_pt_l3
  - drivers/iommu/amd/iommu.c:free_pt_l2
  - drivers/iommu/amd/iommu.c:free_pt_l2
```
```
In drivers/iommu/amd/init.c (ffffffff817a9206)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_ga_log
  - drivers/iommu/amd/init.c:iommu_init_ga_log
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
```
```
In drivers/iommu/intel/dmar.c (ffffffff817aa39b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/iommu.c (ffffffff81c0ca1b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/iommu.c:domain_unmap
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff817b429b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_get_entry
```
```
In drivers/iommu/intel/svm.c (ffffffff817b651b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b6f85)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff817bdfb5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8182f4b5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
```
```
In drivers/dax/super.c (ffffffff81832641)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
```
```
In drivers/scsi/scsi_lib.c (ffffffff818479c6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/spi/spi.c (ffffffff8188ad00)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/net/tun.c (ffffffff8189974f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/xen-netfront.c (ffffffff818a7646)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit_one
```
```
In drivers/usb/core/hcd.c (ffffffff818c9ad7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/devio.c (ffffffff818d7a7f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818e4db8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818efa5f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/xhci.c (ffffffff8190cb2f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81918d07)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8192617d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8192b1a0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_get_page
```
```
In drivers/md/dm-io.c (ffffffff81986f55)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/md/dm-io.c:km_get_page
```
```
In drivers/md/dm-kcopyd.c (ffffffff83013da8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff819b5f41)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff830174fe)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/memmap.c (ffffffff81c40d2f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
```
```
In drivers/firmware/efi/efi.c (ffffffff81c3c1cf)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff8301a98a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c8ec2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In net/core/skbuff.c (ffffffff819ecc19)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff81a3828d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81a3d29b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
```
```
In net/ipv4/tcp.c (ffffffff81ab34fe)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/packet/af_packet.c (ffffffff81b94fe6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81bb6909)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bcf0cf)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_mappings
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
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
In arch/x86/kernel/head64.c (ffffffff831b821c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In init/main.c (ffffffff831b971c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81004a12)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/events/intel/bts.c (ffffffff81010bae)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff810111f8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff81018d3a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/xen/mmu.c (ffffffff81022f8f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff831c0147)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/mmu_hvm.c (ffffffff81023ef5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff831c0b40)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_update_mem_tables
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff81024ec6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/p2m.c (ffffffff81026492)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff831c24ad)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102b973)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_get_user_pgd
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff831c4040)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/xen/smp_pv.c (ffffffff810305d6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/xen/efi.c (ffffffff831c4a91)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff831c507c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff81032537)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff81032f3f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff810331d8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103397c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff810345b0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
```
In arch/x86/realmode/init.c (ffffffff831c54e1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
```
```
In arch/x86/kernel/ldt.c (ffffffff8103ad79)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81bc602b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff8103e86b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff810487ce)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105b188)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810642e5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff831d2571)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff831d5faf)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107851e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/check.c (ffffffff81bca0b3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
```
```
In arch/x86/kernel/sev.c (ffffffff81083d62)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_do_mmio
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff831dc9c7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/mm/init.c (ffffffff831ddc12)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In arch/x86/mm/init_64.c (ffffffff81c2f285)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/ioremap.c (ffffffff81bcb72c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff8108a4e0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_phys_addr_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8108b359)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_ctor
  - arch/x86/mm/pgtable.c:pgd_ctor
  - arch/x86/mm/pgtable.c:___p4d_free_tlb
  - arch/x86/mm/pgtable.c:___p4d_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff8108b862)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f9e5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
```
In arch/x86/mm/pat/memtype.c (ffffffff810909b5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/mm/numa.c (ffffffff831df9ef)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_reset_distance
```
```
In arch/x86/mm/kaslr.c (ffffffff81c30475)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81bcc366)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff831e0ce4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi.c (ffffffff831e24d4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81097c99)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/fork.c (ffffffff810a2291)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
```
```
In kernel/resource.c (ffffffff810acc2c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff811130f0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:create_zone_bm_rtree
  - kernel/power/snapshot.c:create_zone_bm_rtree
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
```
```
In kernel/power/swap.c (ffffffff81114e95)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In kernel/printk/printk.c (ffffffff831e73ac)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/dma/ops_helpers.c (ffffffff8113ab27)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_vaddr_to_page
```
```
In kernel/dma/swiotlb.c (ffffffff8113b7f1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In kernel/profile.c (ffffffff8113e0c4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/crash_core.c (ffffffff81166eb5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/crash_core.c:paddr_vmcoreinfo_note
```
```
In kernel/kexec_core.c (ffffffff81167b45)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_add_entry
```
```
In kernel/kexec_file.c (ffffffff8116a2ee)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In kernel/trace/ring_buffer.c (ffffffff811b56b7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In kernel/trace/trace.c (ffffffff811ba2cb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/cpumap.c (ffffffff8123417d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/events/core.c (ffffffff812401f9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/ring_buffer.c (ffffffff812533da)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:__rb_free_aux
```
```
In mm/filemap.c (ffffffff8125fa3f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/swap.c (ffffffff8126cad1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/shmem.c (ffffffff8127f9d2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In mm/percpu.c (ffffffff8128b627)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/slab_common.c (ffffffff8128d503)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/list_lru.c (ffffffff81295895)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/gup.c (ffffffff812981d0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In mm/memory.c (ffffffff812a5380)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:finish_fault
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:init_zero_pfn
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
```
```
In mm/mremap.c (ffffffff812b0644)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812b2cbf)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff812b44e5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/page_alloc.c (ffffffff812c4ceb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/memblock.c (ffffffff81c31633)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
```
```
In mm/memory_hotplug.c (ffffffff831f43c0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/hugetlb.c (ffffffff812de960)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
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
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff812e1bd7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse.c (ffffffff812e46fe)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_buffer_free
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:check_usemap_section_nr
```
```
In mm/sparse-vmemmap.c (ffffffff81c32a20)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff831f5ee0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
```
In mm/slub.c (ffffffff812ee08b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/migrate.c (ffffffff812f53d5)
Location: arch/x86/include/asm/page_64.h:18
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
Location: arch/x86/include/asm/page_64.h:18
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
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff8130f221)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_kmem_state
```
```
In mm/zbud.c (ffffffff81316c98)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/zbud.c:zbud_reclaim_page
  - mm/zbud.c:zbud_free
```
```
In mm/usercopy.c (ffffffff8131bd6e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In mm/hmm.c (ffffffff8131d3c3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/direct-io.c (ffffffff81376d2d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_zero_block
```
```
In fs/io_uring.c (ffffffff813915a1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_uring_mmap
```
```
In fs/dax.c (ffffffff813a6aab)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In fs/crypto/bio.c (ffffffff813ae03a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
```
```
In fs/iomap/direct-io.c (ffffffff813c5505)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/proc/kcore.c (ffffffff813e39b1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/vmcore.c (ffffffff813e407b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In fs/jbd2/journal.c (ffffffff8146aec3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/crypto.c (ffffffff8148573c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c87ed)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In crypto/skcipher.c (ffffffff8154886d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8154c8ab)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff815552e4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff8155b2c1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8155e74a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/blk-map.c (ffffffff8156e1ea)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In block/blk-lib.c (ffffffff815717ad)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
```
```
In block/bio-integrity.c (ffffffff8159a61e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
```
```
In lib/scatterlist.c (ffffffff815aa6f7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff815b4299)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In lib/bootconfig.c (ffffffff832025d6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_destroy_all
```
```
In lib/cpumask.c (ffffffff83202b9d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165f168)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff8170a7f7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff817137de)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
```
```
In drivers/xen/manage.c (ffffffff8171550b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff8320f513)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8171a4d8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171b68f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8320f799)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81721149)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8172552b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_fixup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init_early
```
```
In drivers/xen/unpopulated-alloc.c (ffffffff81727227)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/unpopulated-alloc.c:fill_list
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817546e0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81762362)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/generic.c (ffffffff817787a8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81779cba)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8177b7b0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i810_setup
```
```
In drivers/iommu/amd/iommu.c (ffffffff8178630f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:set_dte_entry
```
```
In drivers/iommu/amd/init.c (ffffffff8178aefa)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff8178c6e5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:free_sub_pt
  - drivers/iommu/amd/io_pgtable.c:free_sub_pt
  - drivers/iommu/amd/io_pgtable.c:free_pt_l5
  - drivers/iommu/amd/io_pgtable.c:free_pt_l4
  - drivers/iommu/amd/io_pgtable.c:free_pt_l3
  - drivers/iommu/amd/io_pgtable.c:free_pt_l2
  - drivers/iommu/amd/io_pgtable.c:free_pt_l2
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178d13b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/iommu.c (ffffffff81bfe19d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/iommu.c:domain_unmap
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff8179735f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_get_entry
```
```
In drivers/iommu/intel/svm.c (ffffffff817997ad)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179a265)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff817a11a5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff818125ed)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
```
```
In drivers/dax/super.c (ffffffff81815431)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182aa45)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/spi/spi.c (ffffffff8186d692)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/net/tun.c (ffffffff8187bbc4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/xen-netfront.c (ffffffff8188aef8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit
```
```
In drivers/usb/core/hcd.c (ffffffff818acb58)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/devio.c (ffffffff818ba985)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818c7c87)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818d3187)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/xhci.c (ffffffff818f008f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff818fc287)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8190984d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8190e6c6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_get_page
```
```
In drivers/md/dm-io.c (ffffffff8196b635)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/md/dm-io.c:km_get_page
```
```
In drivers/md/dm-kcopyd.c (ffffffff8321ee8a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff8199a6ff)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff832223dd)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/memmap.c (ffffffff81c32c92)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
```
```
In drivers/firmware/efi/efi.c (ffffffff81c2e66f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff832259b9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819adf92)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In net/core/skbuff.c (ffffffff819d30ec)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:napi_build_skb
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff81a1f88d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81a240bb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
```
```
In net/ipv4/tcp.c (ffffffff81a9e681)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/packet/af_packet.c (ffffffff81b84056)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81ba58a9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
```
```
In arch/x86/pci/fixup.c (ffffffff81bbf974)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bc2a8d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
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
In arch/x86/kernel/head64.c (ffffffff8329821c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In init/main.c (ffffffff83299a9e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81005042)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/events/intel/bts.c (ffffffff81011891)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff81011f78)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff8101a60d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/xen/mmu.c (ffffffff810270ff)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff832a0915)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/mmu_hvm.c (ffffffff81028255)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/mmu_hvm.c:xen_hvm_exit_mmap
```
```
In arch/x86/xen/setup.c (ffffffff832a13d2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8102933b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/p2m.c (ffffffff8102a9a2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff832a2ef3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810300d3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_get_user_pgd
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff832a4ba0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/xen/smp_pv.c (ffffffff81035458)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/xen/efi.c (ffffffff832a56d7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff832a5a64)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_get_partition_id
```
```
In arch/x86/hyperv/mmu.c (ffffffff810376b7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff810380ed)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81038378)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81038e0a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81039850)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
```
In arch/x86/realmode/init.c (ffffffff832a61fd)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
```
```
In arch/x86/kernel/ldt.c (ffffffff810407a4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81c98ffc)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff810445db)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff8104f117)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8106472c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106e2d5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff832b4eaa)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff832b8c47)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81085d7e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/check.c (ffffffff81c9f3d6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
```
```
In arch/x86/kernel/sev.c (ffffffff81092f22)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_do_mmio
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff832bfa7d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/mm/init.c (ffffffff832c0e7a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In arch/x86/mm/init_64.c (ffffffff81d4d987)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/ioremap.c (ffffffff81ca0e9a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff81099a40)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_phys_addr_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a8f9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_ctor
  - arch/x86/mm/pgtable.c:pgd_ctor
  - arch/x86/mm/pgtable.c:___p4d_free_tlb
  - arch/x86/mm/pgtable.c:___p4d_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff8109ae42)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109f4c5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
```
In arch/x86/mm/pat/memtype.c (ffffffff810a0505)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff81d4ec33)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81ca23f8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff832c43c2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi.c (ffffffff832c5e3d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810a7c69)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/fork.c (ffffffff810b3096)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
```
```
In kernel/resource.c (ffffffff810be79c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff81133290)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
```
```
In kernel/power/swap.c (ffffffff81134f35)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In kernel/dma/ops_helpers.c (ffffffff8115da67)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_vaddr_to_page
```
```
In kernel/dma/swiotlb.c (ffffffff8115e92a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In kernel/profile.c (ffffffff811613a7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/crash_core.c (ffffffff8118c675)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/crash_core.c:paddr_vmcoreinfo_note
```
```
In kernel/kexec_core.c (ffffffff8118d465)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_add_entry
```
```
In kernel/kexec_file.c (ffffffff8118feae)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In kernel/trace/ring_buffer.c (ffffffff811df7d7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In kernel/trace/trace.c (ffffffff811e4af2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/cpumap.c (ffffffff8126deb1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/events/core.c (ffffffff8127ab85)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/ring_buffer.c (ffffffff8128ecfa)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/filemap.c (ffffffff8129c3af)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/swap.c (ffffffff812a97f1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/shmem.c (ffffffff812bdd03)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In mm/percpu.c (ffffffff812cb3c9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/slab_common.c (ffffffff812cc9a7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/list_lru.c (ffffffff812d5f15)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/gup.c (ffffffff812d8c0e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In mm/memory.c (ffffffff812e68d5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:finish_fault
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:init_zero_pfn
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
```
```
In mm/mremap.c (ffffffff812f1e35)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff812f4882)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff812f60c5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/page_alloc.c (ffffffff8130919b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/memblock.c (ffffffff81d50412)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_ptr
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
```
```
In mm/hugetlb.c (ffffffff81325d45)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
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
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff81328cb1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse.c (ffffffff8132ba0e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_buffer_free
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:check_usemap_section_nr
```
```
In mm/sparse-vmemmap.c (ffffffff81d513f0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff832dc5b6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
```
In mm/slub.c (ffffffff81336469)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/kfence/core.c (ffffffff832dcdc5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_pool
  - mm/kfence/core.c:kfence_init_pool
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/migrate.c (ffffffff8133f9d5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/huge_memory.c (ffffffff81348109)
Location: arch/x86/include/asm/page_64.h:18
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
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff8135a09a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_kmem_state
```
```
In mm/zbud.c (ffffffff81362fe1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/zbud.c:zbud_zpool_free
```
```
In mm/usercopy.c (ffffffff8136904e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In mm/hmm.c (ffffffff8136a75d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/bootmem_info.c (ffffffff832de73d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/direct-io.c (ffffffff813c32de)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_zero_block
```
```
In fs/io_uring.c (ffffffff813df3a8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_uring_mmap
```
```
In fs/dax.c (ffffffff813f653b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In fs/crypto/bio.c (ffffffff813fda77)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
```
```
In fs/iomap/direct-io.c (ffffffff814152a5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/proc/kcore.c (ffffffff8143566c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/vmcore.c (ffffffff81435c2b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In fs/jbd2/journal.c (ffffffff814c16d3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/crypto.c (ffffffff814dce5c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff815212a0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In crypto/skcipher.c (ffffffff815a904d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
```
```
In crypto/rsa-pkcs1pad.c (ffffffff815ad08b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff815b6314)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff815bbc61)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff815bfaa4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/blk-map.c (ffffffff815d26aa)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In block/blk-lib.c (ffffffff815d5ebd)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
```
```
In block/bio-integrity.c (ffffffff81602807)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
```
```
In lib/scatterlist.c (ffffffff81613987)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff8161a4f0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In lib/cpumask.c (ffffffff832ea399)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff816d1d18)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff817864fe)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81791044)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
  - drivers/xen/grant-table.c:gnttab_end_foreign_access
```
```
In drivers/xen/manage.c (ffffffff8179251b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff832f84ba)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81798c07)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8179a13b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff832f8740)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8179ff69)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817a43d5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_fixup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init_early
```
```
In drivers/xen/unpopulated-alloc.c (ffffffff817a62a7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/unpopulated-alloc.c:fill_list
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817d7da3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff817e641b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/generic.c (ffffffff817fe66c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff817ffc21)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81801850)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i810_setup
```
```
In drivers/iommu/amd/iommu.c (ffffffff8180d171)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:set_dte_entry
```
```
In drivers/iommu/amd/init.c (ffffffff818123fa)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81813d95)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:free_sub_pt
  - drivers/iommu/amd/io_pgtable.c:free_sub_pt
  - drivers/iommu/amd/io_pgtable.c:free_pt_l5
  - drivers/iommu/amd/io_pgtable.c:free_pt_l4
  - drivers/iommu/amd/io_pgtable.c:free_pt_l3
  - drivers/iommu/amd/io_pgtable.c:free_pt_l2
  - drivers/iommu/amd/io_pgtable.c:free_pt_l2
```
```
In drivers/iommu/intel/dmar.c (ffffffff8181449b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/iommu.c (ffffffff81cfff03)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/iommu.c:domain_unmap
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff8181f375)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_get_entry
```
```
In drivers/iommu/intel/svm.c (ffffffff81821cf6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff818228a5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff81829de5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8189cc7d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
```
```
In drivers/dax/super.c (ffffffff8189fc41)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/dax/super.c:generic_fsdax_supported
  - drivers/dax/super.c:generic_fsdax_supported
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b64ce)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/spi/spi.c (ffffffff818fd677)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/net/tun.c (ffffffff8190d0f4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/xen-netfront.c (ffffffff8191da61)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit
```
```
In drivers/usb/core/hcd.c (ffffffff81941ba9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/devio.c (ffffffff81951105)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8195fb48)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8196dc27)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/xhci.c (ffffffff8198cd1f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8199b177)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819aa0be)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff819af484)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_get_page
```
```
In drivers/md/dm-io.c (ffffffff81a13af5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/md/dm-io.c:km_get_page
```
```
In drivers/md/dm-kcopyd.c (ffffffff83308427)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff81a4703f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In drivers/firmware/memmap.c (ffffffff81d516a3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
```
```
In drivers/firmware/efi/efi.c (ffffffff81d4cd2f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff8330fb93)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5c452)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/hv/hv_common.c (ffffffff81a60fe6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In net/core/skbuff.c (ffffffff81a82df6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_free_head
  - net/core/skbuff.c:napi_build_skb
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff81ad384d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffff81ad868b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
```
```
In net/ipv4/tcp.c (ffffffff81b5a441)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/packet/af_packet.c (ffffffff81c50146)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81c73454)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
  - net/xdp/xsk.c:xsk_mmap
```
```
In arch/x86/pci/fixup.c (ffffffff81c8f8e4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
```
```
In arch/x86/power/hibernate_64.c (ffffffff81c9314d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
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
In arch/x86/kernel/head64.c (ffffffff83446200)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In init/main.c (ffffffff83447cd0)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/coco/tdx/tdx.c (ffffffff81003026)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_get_report
  - arch/x86/coco/tdx/tdx.c:tdx_get_report
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81004042)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/events/intel/bts.c (ffffffff810130b2)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff81013838)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff8101cb0c)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/xen/mmu.c (ffffffff8102b2d4)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff8344f8f5)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/mmu_hvm.c (ffffffff8102c77d)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu_hvm.c:xen_hvm_exit_mmap
```
```
In arch/x86/xen/setup.c (ffffffff834503ff)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8102dc61)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/p2m.c (ffffffff8102f3f2)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff83452127)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81035748)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_get_user_pgd
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff83453d6c)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103b3c8)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/xen/efi.c (ffffffff83454701)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff83454aff)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_get_partition_id
```
```
In arch/x86/hyperv/mmu.c (ffffffff8103d8c7)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff8103e381)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8103e65f)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff8103f525)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_set_mem_host_visibility
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103fbae)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81040723)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
```
In arch/x86/realmode/init.c (ffffffff8345536c)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
```
```
In arch/x86/kernel/ldt.c (ffffffff81048155)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8104aeeb)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/alternative.c (ffffffff8104cc27)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff8105a387)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8107104c)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107bb25)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8346a9b7)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81096116)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/check.c (ffffffff81e4eb84)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
```
```
In arch/x86/kernel/sev.c (ffffffff810a5483)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_do_mmio
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:vmgexit_psc
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff83471f7e)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/mm/init.c (ffffffff83473469)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In arch/x86/mm/init_64.c (ffffffff81f1d6bb)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/ioremap.c (ffffffff81e50447)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff810ac980)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_phys_addr_range
```
```
In arch/x86/mm/pgtable.c (ffffffff810adbc5)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_ctor
  - arch/x86/mm/pgtable.c:___p4d_free_tlb
  - arch/x86/mm/pgtable.c:___p4d_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff810ae262)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b3105)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
```
In arch/x86/mm/pat/memtype.c (ffffffff810b4475)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:memtype_kernel_map_sync
  - arch/x86/mm/pat/memtype.c:memtype_kernel_map_sync
  - arch/x86/mm/pat/memtype.c:memtype_kernel_map_sync
```
```
In arch/x86/mm/kaslr.c (ffffffff81f1ea86)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81e51ad9)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83476d8e)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi.c (ffffffff83478c0e)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810bd11b)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/resource.c (ffffffff810d5cd5)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff81155125)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
```
```
In kernel/power/swap.c (ffffffff811571e5)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In kernel/dma/ops_helpers.c (ffffffff811879f6)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_vaddr_to_page
```
```
In kernel/dma/swiotlb.c (ffffffff81188bd2)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_init_remap
```
```
In kernel/profile.c (ffffffff811941ba)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/crash_core.c (ffffffff811bbaf5)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - kernel/crash_core.c:paddr_vmcoreinfo_note
```
```
In kernel/kexec_core.c (ffffffff811bc931)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_add_entry
```
```
In kernel/kexec_file.c (ffffffff811bf677)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In kernel/trace/ring_buffer.c (ffffffff812135b7)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In kernel/trace/trace.c (ffffffff8121be68)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/cpumap.c (ffffffff812bccfd)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/events/core.c (ffffffff812cdbaf)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/ring_buffer.c (ffffffff812e3c02)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/swap.c (ffffffff81303165)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/shmem.c (ffffffff8131b563)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In mm/percpu.c (ffffffff8348a9bb)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_fc_alloc
  - mm/percpu.c:pcpu_fc_alloc
  - mm/percpu.c:pcpu_fc_alloc
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_populate_pte
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/slab_common.c (ffffffff8132bccb)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/list_lru.c (ffffffff813353e5)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/gup.c (ffffffff81338bcf)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
```
```
In mm/memory.c (ffffffff81344d7d)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:pmd_install
  - mm/memory.c:init_zero_pfn
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
```
```
In mm/mremap.c (ffffffff81355b83)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81358982)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff8135a0b5)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/vmalloc.c (ffffffff81365f5b)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
```
```
In mm/page_alloc.c (ffffffff81371696)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/memblock.c (ffffffff81f20858)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
```
```
In mm/hugetlb.c (ffffffff81394ab0)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
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
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffffffff81397f09)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse.c (ffffffff8139b6ac)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:check_usemap_section_nr
```
```
In mm/sparse-vmemmap.c (ffffffff81f2167d)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff83491dfc)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
```
In mm/slub.c (ffffffff813a7ccb)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/kfence/core.c (ffffffff813af118)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_pool
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:param_set_sample_interval
  - mm/kfence/core.c:kfence_init
  - mm/kfence/core.c:kfence_init
```
```
In mm/migrate.c (ffffffff813b4cd5)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/migrate_device.c (ffffffff813b6e3d)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813be3f8)
Location: arch/x86/include/asm/page_64.h:19
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
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff813d344d)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_kmem_state
```
```
In mm/zbud.c (ffffffff813dfb9d)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - mm/zbud.c:zbud_zpool_free
```
```
In mm/usercopy.c (ffffffff813e6c47)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
```
```
In mm/hmm.c (ffffffff813e835c)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/bootmem_info.c (ffffffff83494032)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/direct-io.c (ffffffff8144a6f5)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/dax.c (ffffffff81468c3d)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
```
```
In fs/crypto/bio.c (ffffffff81471201)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
```
```
In fs/iomap/direct-io.c (ffffffff8148c9a1)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/proc/kcore.c (ffffffff814af846)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:kclist_add_private
```
```
In fs/proc/vmcore.c (ffffffff814afffd)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In fs/jbd2/journal.c (ffffffff8154c075)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/crypto.c (ffffffff8156ae4b)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff815b4b64)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
```
```
In crypto/skcipher.c (ffffffff81650631)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
```
```
In crypto/rsa-pkcs1pad.c (ffffffff816554c1)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff8165f5c1)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff816654d1)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81669fff)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/blk-map.c (ffffffff8167e3eb)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In block/blk-lib.c (ffffffff81682018)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
```
```
In block/bio-integrity.c (ffffffff816b537e)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
```
```
In io_uring/io_uring.c (ffffffff81e90ac3)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_mmap
  - io_uring/io_uring.c:virt_to_head_page
```
```
In lib/scatterlist.c (ffffffff816df079)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff816e7b40)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff817fae58)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/virtio/virtio_ring.c (ffffffff818bd23e)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
```
```
In drivers/xen/manage.c (ffffffff818cad60)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff834b0cf8)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff818d1e1e)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff818d3506)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff834b0fd1)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff818d9a17)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818dd6b5)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_fixup
```
```
In drivers/xen/unpopulated-alloc.c (ffffffff818e0357)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/xen/unpopulated-alloc.c:fill_list
```
```
In drivers/xen/grant-dma-ops.c (0)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81915fc8)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff819259b0)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/generic.c (ffffffff8193d2cd)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8193f061)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81940f20)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i810_setup
```
```
In drivers/iommu/amd/iommu.c (ffffffff8194d8b9)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:set_dte_entry
```
```
In drivers/iommu/amd/init.c (ffffffff8195331a)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81954c11)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:v1_free_pgtable
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
  - drivers/iommu/amd/io_pgtable.c:free_pt_lvl
  - drivers/iommu/amd/io_pgtable.c:free_pt_lvl
```
```
In drivers/iommu/intel/dmar.c (ffffffff819552eb)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ec8658)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/iommu.c:domain_unmap
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff8195f22f)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
```
```
In drivers/iommu/intel/svm.c (ffffffff81961ea6)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81962545)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196a267)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff819e654b)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a019cb)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/spi/spi.c (ffffffff81a4ecc4)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/net/tun.c (ffffffff81a63a06)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/xen-netfront.c (ffffffff81a72d43)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit
```
```
In drivers/usb/core/hcd.c (ffffffff81a9b1d9)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/devio.c (ffffffff81aaa845)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81ab9fd7)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81ac8226)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/xhci.c (ffffffff81ae8f20)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81af8952)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81b0861e)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81b0dc04)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_get_page
```
```
In drivers/i2c/busses/i2c-designware-amdpsp.c (ffffffff81b3a21d)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_check_i2c_req
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81b52a92)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
```
```
In drivers/md/dm-io.c (ffffffff81b7c3b5)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/md/dm-io.c:km_get_page
```
```
In drivers/md/dm-kcopyd.c (ffffffff834c19ce)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff81bb4ea5)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In drivers/firmware/memmap.c (ffffffff81f21ba7)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
```
```
In drivers/firmware/efi/efi.c (ffffffff81f1c96f)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff834c99ca)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
  - drivers/clocksource/hyperv_timer.c:resume_hv_clock_tsc
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcc462)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
```
```
In drivers/hv/hv_common.c (ffffffff81bd161b)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:hv_query_ext_cap
```
```
In net/core/skbuff.c (ffffffff81bf7b9e)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_free_head
  - net/core/skbuff.c:napi_build_skb
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff81c51159)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81c54c46)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/page_pool.c (ffffffff81c59574)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
```
```
In net/ipv4/tcp.c (ffffffff81ce8f55)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/packet/af_packet.c (ffffffff81df0d85)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81e15fc4)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
  - net/xdp/xsk.c:xsk_mmap
```
```
In arch/x86/pci/fixup.c (ffffffff81e3e903)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
```
```
In arch/x86/power/hibernate_64.c (ffffffff81e42b03)
Location: arch/x86/include/asm/page_64.h:19
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
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
In arch/x86/kernel/head64.c (ffffffff83e5f20f)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In init/main.c (ffffffff83e61504)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/coco/tdx/tdx.c (ffffffff81003edb)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
  - arch/x86/coco/tdx/tdx.c:tdx_mcall_get_report0
  - arch/x86/coco/tdx/tdx.c:tdx_mcall_get_report0
```
```
In arch/x86/entry/vdso/vma.c (ffffffff8100474f)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/events/intel/bts.c (ffffffff810170f2)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff81017908)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff81020ebd)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/xen/mmu.c (ffffffff81031ff4)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff83e6b4a4)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/mmu_hvm.c (ffffffff8103383d)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/mmu_hvm.c:xen_hvm_exit_mmap
```
```
In arch/x86/xen/setup.c (ffffffff83e6c6fc)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff81035021)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/p2m.c (ffffffff81036765)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff83e6f072)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103d3b8)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_get_user_pgd
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff83e71507)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043b88)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/xen/efi.c (ffffffff83e72141)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff83e726a2)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_get_partition_id
```
```
In arch/x86/hyperv/mmu.c (ffffffff810466c7)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff81047245)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81047555)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff81048695)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_set_mem_host_visibility
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048ae7)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff810499e9)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
```
In arch/x86/realmode/init.c (ffffffff83e731f9)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
```
```
In arch/x86/kernel/ldt.c (ffffffff81052e9f)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81056960)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/alternative.c (ffffffff81059039)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81068137)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8108110c)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108cf42)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff83e8fa35)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810abda6)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/check.c (ffffffff810b9329)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
```
```
In arch/x86/kernel/sev.c (ffffffff810bdc13)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_do_mmio
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:vmgexit_psc
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff83e99297)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/mm/init.c (ffffffff83e9ac09)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In arch/x86/mm/init_64.c (ffffffff820c7379)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_set_pmd
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/ioremap.c (ffffffff810c5800)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff810c6a30)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_phys_addr_range
```
```
In arch/x86/mm/pgtable.c (ffffffff810c7ddc)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_ctor
  - arch/x86/mm/pgtable.c:___p4d_free_tlb
  - arch/x86/mm/pgtable.c:___p4d_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff810c856a)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cdb55)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
```
In arch/x86/mm/pat/memtype.c (ffffffff810cf0d5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:memtype_kernel_map_sync
  - arch/x86/mm/pat/memtype.c:memtype_kernel_map_sync
  - arch/x86/mm/pat/memtype.c:memtype_kernel_map_sync
```
```
In arch/x86/mm/kaslr.c (ffffffff820c78a4)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810d4d56)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83e9ffb2)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi.c (ffffffff83ea2e13)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810d872b)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/resource.c (ffffffff810f4f85)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff811850e5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
```
```
In kernel/power/swap.c (ffffffff81187f25)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In kernel/dma/ops_helpers.c (ffffffff811c3636)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_vaddr_to_page
```
```
In kernel/dma/swiotlb.c (ffffffff811c4d91)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_init_remap
```
```
In kernel/profile.c (ffffffff811d182a)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/crash_core.c (ffffffff811fd995)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/crash_core.c:paddr_vmcoreinfo_note
```
```
In kernel/kexec_core.c (ffffffff811fe8c1)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_add_entry
```
```
In kernel/kexec_file.c (ffffffff81201997)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In kernel/trace/ring_buffer.c (ffffffff8125cd74)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In kernel/trace/trace.c (ffffffff81265b39)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/cpumap.c (ffffffff8132015d)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/events/core.c (ffffffff81339125)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/ring_buffer.c (ffffffff8134c2d2)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/swap.c (ffffffff8136e955)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/vmscan.c (ffffffff8137f487)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In mm/shmem.c (ffffffff8138f323)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In mm/percpu.c (ffffffff83ebb91e)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_fc_alloc
  - mm/percpu.c:pcpu_fc_alloc
  - mm/percpu.c:pcpu_fc_alloc
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_populate_pte
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/slab_common.c (ffffffff813a23ae)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/slab_common.c:__ksize
  - mm/slab_common.c:kfree
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/list_lru.c (ffffffff813ac185)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/gup.c (ffffffff813b03dc)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In mm/memory.c (ffffffff813bcfad)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:pmd_install
  - mm/memory.c:init_zero_pfn
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
```
```
In mm/mremap.c (ffffffff813d0193)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff813d308d)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff813d4b25)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/page_alloc.c (ffffffff813eedc6)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/memblock.c (ffffffff820c9478)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
```
```
In mm/hugetlb.c (ffffffff8140ddd6)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
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
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/hugetlb_vmemmap.c (ffffffff81413430)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In mm/mempolicy.c (ffffffff81417bf7)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse.c (ffffffff8141b6ec)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:check_usemap_section_nr
```
```
In mm/sparse-vmemmap.c (ffffffff820cb81c)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff83ec5855)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
```
In mm/slub.c (ffffffff8142c3bb)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:cache_from_obj
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/kfence/core.c (ffffffff8142f66f)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_pool
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:param_set_sample_interval
  - mm/kfence/core.c:kfence_init
  - mm/kfence/core.c:kfence_init
```
```
In mm/migrate.c (ffffffff81433e85)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/migrate_device.c (ffffffff8143898a)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81440c58)
Location: arch/x86/include/asm/page_64.h:21
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
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff81458e32)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_slab_obj
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_kmem_state
```
```
In mm/zbud.c (ffffffff814664fd)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/zbud.c:zbud_zpool_free
```
```
In mm/usercopy.c (ffffffff8146e821)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
```
```
In mm/hmm.c (ffffffff81470267)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/bootmem_info.c (ffffffff83ec855f)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/direct-io.c (ffffffff814d8df7)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/dax.c (ffffffff814f97db)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_load_hole
```
```
In fs/crypto/bio.c (ffffffff81502cf1)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
```
```
In fs/iomap/direct-io.c (ffffffff8151feb1)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/proc/task_mmu.c (ffffffff8152fa0f)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In fs/proc/kcore.c (ffffffff81545f99)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:kclist_add_private
```
```
In fs/proc/vmcore.c (ffffffff815468a7)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In fs/jbd2/journal.c (ffffffff815ebe45)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/crypto.c (ffffffff8160eccb)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8165fb44)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In crypto/skcipher.c (ffffffff81709dd1)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8170f6f1)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff817193f1)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff817202e1)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff817245ca)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/blk-map.c (ffffffff8173b0cb)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In block/blk-lib.c (ffffffff8173f66b)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
```
```
In block/bio-integrity.c (ffffffff81774efc)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
```
```
In io_uring/io_uring.c (ffffffff81789bcf)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_mmap
  - io_uring/io_uring.c:io_uring_mmap
```
```
In lib/scatterlist.c (ffffffff817cf279)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff817d7a10)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In drivers/pci/p2pdma.c (ffffffff8191c793)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_alloc_sgl
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/acpi/scan.c (ffffffff8195f4d9)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_drop_device
  - drivers/acpi/scan.c:acpi_device_hotplug
```
```
In drivers/virtio/virtio_ring.c (ffffffff81a0c08e)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In drivers/xen/manage.c (ffffffff81a1bf22)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff83eeaafb)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a23f8e)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a256a6)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff83eeaef3)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81a2c504)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a30b95)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_fixup
```
```
In drivers/xen/unpopulated-alloc.c (ffffffff81a348c8)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/xen/unpopulated-alloc.c:fill_list
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81a350a9)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc_pages
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81a716e8)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81a823e4)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/generic.c (ffffffff81a9e13d)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81aa0421)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81aa2fe0)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i810_setup
```
```
In drivers/iommu/amd/iommu.c (ffffffff81ab1dd9)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:set_dte_entry
```
```
In drivers/iommu/amd/init.c (ffffffff81ab9432)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:iommu_set_device_table
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81abaa81)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:v1_free_pgtable
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages
  - drivers/iommu/amd/io_pgtable.c:free_pt_lvl
  - drivers/iommu/amd/io_pgtable.c:free_pt_lvl
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81abb11d)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abb8eb)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac3aea)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/iommu.c:domain_unmap
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel/pasid.c (ffffffff81ac6da9)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
```
```
In drivers/iommu/intel/svm.c (ffffffff81acabf6)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acb295)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad4287)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81b625cd)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b8002b)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/spi/spi.c (ffffffff81bd0523)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf_attrs
```
```
In drivers/net/tun.c (ffffffff81bf2be6)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/xen-netfront.c (ffffffff81c054c3)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit
```
```
In drivers/usb/core/hcd.c (ffffffff81c20029)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/devio.c (ffffffff81c31c4d)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81c433c7)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81c52586)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/xhci.c (ffffffff81c751d0)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81c86914)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c97b80)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81c9dcc4)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
```
In drivers/i2c/busses/i2c-designware-amdpsp.c (ffffffff81ccfc4d)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_check_i2c_req
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81ceacd3)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
```
```
In drivers/md/dm-io.c (ffffffff81d1a1a5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/md/dm-io.c:km_get_page
```
```
In drivers/md/dm-kcopyd.c (ffffffff83f00eeb)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff81d595a5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In drivers/firmware/memmap.c (ffffffff820cc271)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
```
```
In drivers/firmware/efi/efi.c (ffffffff820c49c8)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff83f0b0b5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d765a2)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In drivers/hv/hv_common.c (ffffffff81d7d09b)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:hv_query_ext_cap
```
```
In net/core/skbuff.c (ffffffff81da68fe)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_free_head
  - net/core/skbuff.c:napi_build_skb
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff81e06938)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81e0a3d1)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/page_pool.c (ffffffff81e0f554)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
```
```
In net/ipv4/tcp.c (ffffffff81eac4d5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/packet/af_packet.c (ffffffff81fc6c42)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In net/xdp/xsk.c (ffffffff81fed011)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
  - net/xdp/xsk.c:xsk_mmap
```
```
In arch/x86/pci/fixup.c (ffffffff82018473)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
```
```
In arch/x86/power/hibernate_64.c (ffffffff8201d573)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
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
In init/main.c (ffffffff83681970)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/coco/tdx/tdx.c (ffffffff81003545)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
  - arch/x86/coco/tdx/tdx.c:tdx_mcall_get_report0
  - arch/x86/coco/tdx/tdx.c:tdx_mcall_get_report0
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81003f0f)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/events/intel/bts.c (ffffffff81016a92)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff810172a8)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff81020c0d)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/xen/mmu.c (ffffffff81031ff4)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff8368bf44)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/mmu_hvm.c (ffffffff810337cd)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/mmu_hvm.c:xen_hvm_exit_mmap
```
```
In arch/x86/xen/setup.c (ffffffff8368d21f)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff81034fa1)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/p2m.c (ffffffff810366d5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8368ffb0)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103d288)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_get_user_pgd
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff83692380)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043ca8)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/xen/efi.c (ffffffff83693051)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff836935c2)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_get_partition_id
```
```
In arch/x86/hyperv/mmu.c (ffffffff8104690c)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff810475c5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff810478d5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_unmap_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff810489fb)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_vtom_set_host_visibility
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048d59)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81049c19)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_call_create_vp
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
  - arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc
```
```
In arch/x86/realmode/init.c (ffffffff836941b9)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
```
```
In arch/x86/kernel/head64.c (ffffffff8369444f)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/kernel/ldt.c (ffffffff81053e82)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81057930)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/alternative.c (ffffffff8105a5e7)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff810699b6)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8108358c)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108fd45)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff836b32ad)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af966)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/check.c (ffffffff810bc4f9)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
```
```
In arch/x86/kernel/sev.c (ffffffff810c1283)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_do_mmio
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:__set_pages_state
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:vmgexit_psc
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff836bccb7)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/mm/init.c (ffffffff836be601)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In arch/x86/mm/init_64.c (ffffffff8214b409)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_set_pmd
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/ioremap.c (ffffffff810c8ef0)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff810ca1c0)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_phys_addr_range
```
```
In arch/x86/mm/pgtable.c (ffffffff810cb51c)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_ctor
  - arch/x86/mm/pgtable.c:pgd_ctor
  - arch/x86/mm/pgtable.c:___p4d_free_tlb
  - arch/x86/mm/pgtable.c:___p4d_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff810cbb24)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d1115)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
```
In arch/x86/mm/pat/memtype.c (ffffffff810d2685)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:memtype_kernel_map_sync
  - arch/x86/mm/pat/memtype.c:memtype_kernel_map_sync
  - arch/x86/mm/pat/memtype.c:memtype_kernel_map_sync
```
```
In arch/x86/mm/kaslr.c (ffffffff8214b8f3)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810d8256)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff836c40f2)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi.c (ffffffff836c7063)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810e3cbb)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/resource.c (ffffffff811013b5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff81195e45)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
```
```
In kernel/power/swap.c (ffffffff811990b5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In kernel/dma/ops_helpers.c (ffffffff811d6186)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_vaddr_to_page
```
```
In kernel/dma/swiotlb.c (ffffffff811d7a9e)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_init_remap
```
```
In kernel/profile.c (ffffffff811e5aba)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/crash_core.c (ffffffff81212b15)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/crash_core.c:paddr_vmcoreinfo_note
```
```
In kernel/kexec_core.c (ffffffff81213cc1)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_add_entry
```
```
In kernel/kexec_file.c (ffffffff81216d67)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In kernel/trace/ring_buffer.c (ffffffff81273d64)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In kernel/trace/trace.c (ffffffff8127cea9)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/cpumap.c (ffffffff8134ffcf)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/events/core.c (ffffffff8136a728)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/ring_buffer.c (ffffffff8137d322)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/vmscan.c (ffffffff813b09b7)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In mm/shmem.c (ffffffff813c092f)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
```
```
In mm/percpu.c (ffffffff836e3f4e)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_fc_alloc
  - mm/percpu.c:pcpu_fc_alloc
  - mm/percpu.c:pcpu_fc_alloc
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_populate_pte
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/slab_common.c (ffffffff813d5898)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/slab_common.c:__ksize
  - mm/slab_common.c:kfree
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/list_lru.c (ffffffff813e0525)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/gup.c (ffffffff813e49ac)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In mm/memory.c (ffffffff813f1cf3)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:pmd_install
  - mm/memory.c:init_zero_pfn
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
```
```
In mm/mremap.c (ffffffff81404ef6)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81407c50)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff814094f5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/vmalloc.c (ffffffff814104f2)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/vmalloc.c:zero_iter
```
```
In mm/page_alloc.c (ffffffff81422b96)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/memblock.c (ffffffff8214d6d8)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
```
```
In mm/hugetlb.c (ffffffff814411b5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
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
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/hugetlb_vmemmap.c (ffffffff81446990)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In mm/mempolicy.c (ffffffff8144b1bc)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/sparse.c (ffffffff8144ec8c)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:check_usemap_section_nr
```
```
In mm/sparse-vmemmap.c (ffffffff8214faac)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff836ea935)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
```
```
In mm/slub.c (ffffffff8146196b)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:cache_from_obj
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/kfence/core.c (ffffffff814648a6)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_pool
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:param_set_sample_interval
  - mm/kfence/core.c:kfence_init
```
```
In mm/migrate.c (ffffffff814697d5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/migrate_device.c (ffffffff8146f0e9)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814764fc)
Location: arch/x86/include/asm/page_64.h:21
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
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff8148eac2)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_slab_obj
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_kmem_state
```
```
In mm/zbud.c (ffffffff8149be34)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/zbud.c:zbud_zpool_free
```
```
In mm/usercopy.c (ffffffff814a2fb6)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
```
```
In mm/hmm.c (ffffffff814a4a37)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/bootmem_info.c (ffffffff836ed5cf)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/direct-io.c (ffffffff81511cd5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/dax.c (ffffffff81530c5e)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_load_hole
```
```
In fs/crypto/bio.c (ffffffff8153a2cf)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
```
```
In fs/iomap/direct-io.c (ffffffff81557f5f)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/proc/task_mmu.c (ffffffff8156823a)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In fs/proc/kcore.c (ffffffff8157db3a)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:kclist_add_private
```
```
In fs/proc/vmcore.c (ffffffff8157e4a2)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In fs/jbd2/journal.c (ffffffff81623925)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/crypto.c (ffffffff81646b5f)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff816984b4)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In crypto/skcipher.c (ffffffff817439e1)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8174a761)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff81754d81)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff8175bbe1)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In block/blk-map.c (ffffffff817779e3)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In block/blk-lib.c (ffffffff8177bbb6)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
```
```
In block/bio-integrity.c (ffffffff817b4c19)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
```
```
In io_uring/io_uring.c (ffffffff817c9b24)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_mmap
```
```
In io_uring/kbuf.c (ffffffff817e00d6)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In lib/scatterlist.c (ffffffff8180d729)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In lib/iov_iter.c (ffffffff818147b6)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_extract_pages
```
```
In lib/kfifo.c (ffffffff81816c20)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In drivers/pci/p2pdma.c (ffffffff8195fd53)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_alloc_sgl
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/acpi/scan.c (ffffffff819a58d9)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_drop_device
  - drivers/acpi/scan.c:acpi_device_hotplug
```
```
In drivers/virtio/virtio_ring.c (ffffffff81a54fae)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In drivers/xen/manage.c (ffffffff81a650c2)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff837104eb)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81a6d4c5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a6ec56)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff83710903)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81a75ca7)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a7a3a5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_fixup
```
```
In drivers/xen/unpopulated-alloc.c (ffffffff81a7e2d8)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/xen/unpopulated-alloc.c:fill_list
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81a7eab9)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc_pages
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81abbf98)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81acd9e4)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/generic.c (ffffffff81ae9adb)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81aebd41)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81aee8b0)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i810_setup
```
```
In drivers/iommu/amd/iommu.c (ffffffff81afde8a)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:set_dte_entry
```
```
In drivers/iommu/amd/init.c (ffffffff81b0589f)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:iommu_set_device_table
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b07151)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:v1_free_pgtable
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages
  - drivers/iommu/amd/io_pgtable.c:free_pt_lvl
  - drivers/iommu/amd/io_pgtable.c:free_pt_lvl
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b07b24)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b081cb)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0f5f4)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/iommu.c:domain_unmap
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b13939)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
```
```
In drivers/iommu/intel/svm.c (ffffffff81b17746)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b17f05)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b22a57)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
```
In drivers/block/virtio_blk.c (ffffffff81b7ecb1)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81bb5bcd)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd408d)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/spi/spi.c (ffffffff81c281a3)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf_attrs
```
```
In drivers/net/tun.c (ffffffff81c4a193)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/virtio_net.c (ffffffff81c53f0a)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_rq_free_unused_buf
  - drivers/net/virtio_net.c:virtnet_rq_free_unused_buf
  - drivers/net/virtio_net.c:virtnet_commit_rss_command
  - drivers/net/virtio_net.c:virtnet_commit_rss_command
  - drivers/net/virtio_net.c:virtnet_commit_rss_command
  - drivers/net/virtio_net.c:virtnet_commit_rss_command
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:xmit_skb
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:add_recvbuf_big
  - drivers/net/virtio_net.c:add_recvbuf_big
  - drivers/net/virtio_net.c:add_recvbuf_big
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:mergeable_buf_free
  - drivers/net/virtio_net.c:receive_small
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:__virtnet_xdp_xmit_one
```
```
In drivers/net/xen-netfront.c (ffffffff81c6abd3)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit
```
```
In drivers/usb/core/hcd.c (ffffffff81c86fa9)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/devio.c (ffffffff81c98ecd)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81caab27)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81cb9b46)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/xhci.c (ffffffff81cdc2f0)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81ced744)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cfeead)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81d05034)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81d538e3)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
```
```
In drivers/md/dm-io.c (ffffffff81d83305)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/md/dm-io.c:km_get_page
```
```
In drivers/md/dm-kcopyd.c (ffffffff83726d9b)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff81dc3f52)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In drivers/firmware/memmap.c (ffffffff82150521)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
```
```
In drivers/firmware/efi/efi.c (ffffffff82148a38)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff83731350)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de44e2)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In drivers/hv/hv_common.c (ffffffff81deb48b)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:hv_query_ext_cap
  - drivers/hv/hv_common.c:hv_kmsg_dump
```
```
In net/core/skbuff.c (ffffffff81e159a6)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_free_head
  - net/core/skbuff.c:napi_build_skb
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff81e795cf)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81e7cbad)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/page_pool.c (ffffffff81e82d27)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
```
```
In net/ipv4/tcp.c (ffffffff81f0abde)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/packet/af_packet.c (ffffffff82026cd5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In arch/x86/pci/fixup.c (ffffffff82098923)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
```
```
In arch/x86/power/hibernate_64.c (ffffffff8209dc03)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
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
In init/main.c (ffffffff838b0995)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/coco/tdx/tdx.c (ffffffff81002cc5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
  - arch/x86/coco/tdx/tdx.c:tdx_hcall_get_quote
  - arch/x86/coco/tdx/tdx.c:tdx_mcall_get_report0
  - arch/x86/coco/tdx/tdx.c:tdx_mcall_get_report0
```
```
In arch/x86/entry/vdso/vma.c (ffffffff8100681f)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/events/intel/bts.c (ffffffff8101c5d2)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff8101cde8)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff81026d2e)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/xen/mmu.c (ffffffff810382e4)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:arbitrary_virt_to_machine
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff838bbb04)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/mmu_hvm.c (ffffffff81039acd)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/mmu_hvm.c:xen_hvm_exit_mmap
```
```
In arch/x86/xen/setup.c (ffffffff838bcddf)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8103b1a1)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/p2m.c (ffffffff8103c8d5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff838bfb00)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81043748)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_get_user_pgd
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff838c1e90)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/xen/smp_pv.c (ffffffff8104a1a8)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/xen/efi.c (ffffffff838c2bc1)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8104b3ce)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In arch/x86/hyperv/mmu.c (ffffffff8104d11c)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff8104da23)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8104dfc6)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_do_hypercall
  - arch/x86/hyperv/irqdomain.c:hv_do_hypercall
```
```
In arch/x86/hyperv/ivm.c (ffffffff8104f4f9)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_snp_boot_ap
  - arch/x86/hyperv/ivm.c:hv_do_hypercall
  - arch/x86/hyperv/ivm.c:hv_do_hypercall
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8104fd13)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81050886)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_proc.c:hv_do_hypercall
  - arch/x86/hyperv/hv_proc.c:hv_do_hypercall
```
```
In arch/x86/realmode/init.c (ffffffff838c40a9)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:setup_real_mode
```
```
In arch/x86/kernel/head64.c (ffffffff838c433f)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/kernel/ldt.c (ffffffff8105b0a2)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105ebd0)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/alternative.c (ffffffff81061838)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81070b50)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810970d5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff838e3b8d)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b64f6)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/check.c (ffffffff810c3679)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
```
```
In arch/x86/kernel/sev.c (ffffffff810c86e3)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_do_mmio
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:__set_pages_state
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:vmgexit_psc
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff838ed777)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/mm/init.c (ffffffff838ef0c1)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In arch/x86/mm/init_64.c (ffffffff8222deb9)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_set_pmd
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/ioremap.c (ffffffff838f04b8)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/mmap.c (ffffffff810d2620)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_phys_addr_range
```
```
In arch/x86/mm/pgtable.c (ffffffff810d3a6c)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_ctor
  - arch/x86/mm/pgtable.c:pgd_ctor
  - arch/x86/mm/pgtable.c:___p4d_free_tlb
  - arch/x86/mm/pgtable.c:___p4d_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff810d41b4)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d97f5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:alloc_pmd_page
  - arch/x86/mm/pat/set_memory.c:alloc_pte_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
```
In arch/x86/mm/pat/memtype.c (ffffffff810dae15)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:memtype_kernel_map_sync
  - arch/x86/mm/pat/memtype.c:memtype_kernel_map_sync
  - arch/x86/mm/pat/memtype.c:memtype_kernel_map_sync
```
```
In arch/x86/mm/kaslr.c (ffffffff8222e3a3)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810e0ad6)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff838f4d72)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi.c (ffffffff838f7c63)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810ec4d9)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/resource.c (ffffffff8110aae5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff811a4865)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
```
```
In kernel/power/swap.c (ffffffff811a8115)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In kernel/dma/ops_helpers.c (ffffffff811eb1b6)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_vaddr_to_page
```
```
In kernel/dma/swiotlb.c (ffffffff811ecdba)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_init_remap
  - kernel/dma/swiotlb.c:swiotlb_init_remap
```
```
In kernel/profile.c (ffffffff811fb80a)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/crash_core.c (ffffffff8122a1b5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/crash_core.c:paddr_vmcoreinfo_note
```
```
In kernel/kexec_core.c (ffffffff8122bc11)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_add_entry
```
```
In kernel/kexec_file.c (ffffffff8122ec4a)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In kernel/trace/ring_buffer.c (ffffffff8128e373)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In kernel/trace/trace.c (ffffffff81297dbb)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/cpumap.c (ffffffff81377408)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/events/core.c (ffffffff813930b8)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/ring_buffer.c (ffffffff813a6582)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/vmscan.c (ffffffff813d9ec7)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In mm/shmem.c (ffffffff813eb5b9)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
```
```
In mm/percpu.c (ffffffff839167de)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_fc_alloc
  - mm/percpu.c:pcpu_fc_alloc
  - mm/percpu.c:pcpu_fc_alloc
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/slab_common.c (ffffffff813ff54e)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/slab_common.c:__ksize
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/list_lru.c (ffffffff8140aec5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del_obj
  - mm/list_lru.c:list_lru_add_obj
```
```
In mm/gup.c (ffffffff8140f20a)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In mm/memory.c (ffffffff8141ca1e)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:pmd_install
  - mm/memory.c:init_zero_pfn
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
  - mm/memory.c:p4d_populate
  - mm/memory.c:p4d_populate
  - mm/memory.c:pud_populate
  - mm/memory.c:pud_populate
```
```
In mm/mremap.c (ffffffff81431470)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/mremap.c:pud_populate
  - mm/mremap.c:pud_populate
```
```
In mm/page_vma_mapped.c (ffffffff81434325)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff81435ce5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/vmalloc.c (ffffffff8143ce52)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/vmalloc.c:zero_iter
```
```
In mm/page_alloc.c (ffffffff8144fa76)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/memblock.c (ffffffff82230288)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
```
```
In mm/slub.c (ffffffff8145dc98)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__memcg_slab_post_alloc_hook
```
```
In mm/zswap.c (ffffffff814702f5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/zswap.c:shrink_memcg_cb
  - mm/zswap.c:shrink_memcg_cb
  - mm/zswap.c:zswap_lru_del
  - mm/zswap.c:zswap_lru_add
```
```
In mm/hugetlb.c (ffffffff8147b2e6)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
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
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:pud_populate
  - mm/hugetlb.c:pud_populate
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/hugetlb_vmemmap.c (ffffffff81480ca4)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_split_pmd
```
```
In mm/mempolicy.c (ffffffff81484bc6)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/sparse.c (ffffffff81488840)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:check_usemap_section_nr
```
```
In mm/sparse-vmemmap.c (ffffffff82232621)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff8391dcd5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
```
```
In mm/kfence/core.c (ffffffff8149420a)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_late
  - mm/kfence/core.c:kfence_init_late
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:kfence_init
  - mm/kfence/core.c:kfence_init
```
```
In mm/migrate.c (ffffffff81498705)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/migrate_device.c (ffffffff8149dbea)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a5d8c)
Location: arch/x86/include/asm/page_64.h:21
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
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff814be472)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_slab_obj
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_kmem_state
```
```
In mm/zbud.c (ffffffff814cb534)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/zbud.c:zbud_zpool_free
```
```
In mm/usercopy.c (ffffffff814d3e4a)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
```
```
In mm/hmm.c (ffffffff814d5a5f)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/bootmem_info.c (ffffffff839205cf)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/direct-io.c (ffffffff81546198)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/dax.c (ffffffff81565b3e)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - fs/dax.c:dax_pmd_load_hole
```
```
In fs/crypto/bio.c (ffffffff8156f66c)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
  - fs/crypto/bio.c:fscrypt_zeroout_range_inline_crypt
```
```
In fs/iomap/direct-io.c (ffffffff8158e58f)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/proc/task_mmu.c (ffffffff8159d5a2)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_scan_hugetlb_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In fs/proc/kcore.c (ffffffff815b6580)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:kclist_add_private
```
```
In fs/proc/vmcore.c (ffffffff815b6ee2)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In fs/jbd2/journal.c (ffffffff8165c990)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/crypto.c (ffffffff8168001f)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff816d4b34)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In crypto/skcipher.c (ffffffff81785d11)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8178c321)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff81796d41)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff8179dae1)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In block/blk-map.c (ffffffff817b9c03)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In block/blk-lib.c (ffffffff817bdfa6)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
```
```
In block/bio-integrity.c (ffffffff817f8ca5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_copy_user
```
```
In io_uring/io_uring.c (ffffffff8180f6a4)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_mmap
```
```
In lib/scatterlist.c (ffffffff818533d9)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In lib/iov_iter.c (ffffffff8185982c)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_extract_pages
```
```
In lib/kfifo.c (ffffffff8185bf00)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In drivers/pci/p2pdma.c (ffffffff819a9442)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_alloc_sgl
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
  - drivers/pci/p2pdma.c:p2pmem_alloc_mmap
```
```
In drivers/acpi/scan.c (ffffffff819ee259)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_drop_device
  - drivers/acpi/scan.c:acpi_device_hotplug
```
```
In drivers/virtio/virtio_ring.c (ffffffff81aa6075)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In drivers/xen/manage.c (ffffffff81ab7922)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff83943e6b)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81abf535)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81ac0c16)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff83944283)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81ac7e97)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81accef5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_fixup
```
```
In drivers/xen/unpopulated-alloc.c (ffffffff81ad0848)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/xen/unpopulated-alloc.c:fill_list
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81ad1029)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc_pages
  - drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81b0ecb5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81b20ab4)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/generic.c (ffffffff81b3cf6b)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81b3f281)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81b41df0)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:i810_setup
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b515fa)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__get_gcr3_pte
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:set_dte_entry
```
```
In drivers/iommu/amd/init.c (ffffffff81b5969c)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:iommu_set_device_table
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b5b121)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:v1_free_pgtable
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages
  - drivers/iommu/amd/io_pgtable.c:free_pt_lvl
  - drivers/iommu/amd/io_pgtable.c:free_pt_lvl
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b5bb54)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5c1eb)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b63ee4)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
  - drivers/iommu/intel/iommu.c:domain_unmap
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b68dfb)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
```
```
In drivers/iommu/intel/svm.c (ffffffff81b6cd36)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6d845)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b79697)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_sgtable
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
```
In drivers/block/virtio_blk.c (ffffffff81bd33ac)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81c0a1ad)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_clear_memmap_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c28cfd)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
```
In drivers/spi/spi.c (ffffffff81cda8f3)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf_attrs
```
```
In drivers/net/tun.c (ffffffff81cffb1f)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/virtio_net.c (ffffffff81d045d5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_commit_rss_command
  - drivers/net/virtio_net.c:virtnet_commit_rss_command
  - drivers/net/virtio_net.c:virtnet_commit_rss_command
  - drivers/net/virtio_net.c:virtnet_commit_rss_command
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:xmit_skb
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:add_recvbuf_big
  - drivers/net/virtio_net.c:add_recvbuf_big
  - drivers/net/virtio_net.c:add_recvbuf_big
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:mergeable_buf_free
  - drivers/net/virtio_net.c:receive_small
  - drivers/net/virtio_net.c:receive_small_xdp
  - drivers/net/virtio_net.c:xdp_linearize_page
  - drivers/net/virtio_net.c:__virtnet_xdp_xmit_one
  - drivers/net/virtio_net.c:virtnet_rq_unmap
```
```
In drivers/net/xen-netfront.c (ffffffff81d1f5ad)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit
```
```
In drivers/usb/core/hcd.c (ffffffff81d3ba09)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/devio.c (ffffffff81d4da3d)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81d5f7d7)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81d6e8b6)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
```
```
In drivers/usb/host/xhci.c (ffffffff81d91310)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81da3507)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db3fad)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81dbabf4)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81e0a3bd)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_do_enable
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
```
```
In drivers/md/dm-io.c (ffffffff81e3a9c5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/md/dm-io.c:km_get_page
```
```
In drivers/md/dm-kcopyd.c (ffffffff8395ac8b)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff81e7c832)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In drivers/firmware/memmap.c (ffffffff82233361)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
```
```
In drivers/firmware/efi/efi.c (ffffffff8222b458)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff839658f0)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9a5d2)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
```
```
In drivers/hv/hv_common.c (ffffffff81ea1568)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:hv_kmsg_dump
```
```
In net/core/skbuff.c (ffffffff81ed2d3a)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_free_head
  - net/core/skbuff.c:napi_build_skb
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff81f39669)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/core/gro.c (ffffffff81f3cefd)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - net/core/gro.c:skb_gro_receive
```
```
In net/core/page_pool.c (ffffffff81f43b12)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_put_page_bulk
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204c780)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_hash_skb_data
```
```
In net/packet/af_packet.c (ffffffff820f66e5)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_fill_skb
```
```
In arch/x86/pci/fixup.c (ffffffff8216fe03)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:rs690_fix_64bit_dma
```
```
In arch/x86/power/hibernate_64.c (ffffffff82175403)
Location: arch/x86/include/asm/page_64.h:21
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8288a1dc)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In init/main.c (ffffffff8288b0e1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81004ae3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/events/intel/bts.c (ffffffff8100efd0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f8f5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff8101592d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/xen/mmu.c (ffffffff8101ddff)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/xen/suspend.c (ffffffff8101ea42)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff82891843)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/mmu_hvm.c (ffffffff8101ef55)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff82892068)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8101ffd6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/p2m.c (ffffffff81021629)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82893c5d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810285f3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_get_user_pgd
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff82895781)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ce56)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/xen/efi.c (ffffffff82896c61)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102e86e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102f1e1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f478)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/realmode/init.c (ffffffff82897599)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:init_real_mode
```
```
In arch/x86/kernel/ldt.c (ffffffff81036c50)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff82899459)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/alternative.c (ffffffff8103a08d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81043df3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105676c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105fa45)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff828a4705)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828a80db)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106efde)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/check.c (ffffffff81078747)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff828ab134)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828ac7f5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff8107c356)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
  - arch/x86/kernel/tce_64.c:free_tce_table
```
```
In arch/x86/mm/init.c (ffffffff828ad413)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In arch/x86/mm/init_64.c (ffffffff81a6b5bc)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/ioremap.c (ffffffff828ade49)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81084355)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/mmap.c (ffffffff81084eb0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_phys_addr_range
```
```
In arch/x86/mm/pat.c (ffffffff81085a25)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff81086815)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81087d34)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/numa.c (ffffffff828af06f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_reset_distance
```
```
In arch/x86/mm/kaslr.c (ffffffff81a6b82e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108dd32)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b0601)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi.c (ffffffff828b1db2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81091559)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/fork.c (ffffffff81098964)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/resource.c (ffffffff810a267c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff81104d97)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
```
```
In kernel/power/swap.c (ffffffff81106768)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/power/swap.c:swap_read_pages
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:hib_submit_io
```
```
In kernel/dma/mapping.c (ffffffff81127298)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_mmap
```
```
In kernel/dma/direct.c (ffffffff81127c75)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
```
```
In kernel/dma/swiotlb.c (ffffffff81128594)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In kernel/profile.c (ffffffff81129f91)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/crash_core.c (ffffffff81151415)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/crash_core.c:paddr_vmcoreinfo_note
```
```
In kernel/kexec_core.c (ffffffff81151bb5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_add_entry
```
```
In kernel/kexec_file.c (ffffffff811545f5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In kernel/trace/ring_buffer.c (ffffffff81196c84)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In kernel/trace/trace.c (ffffffff8119e347)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/cpumap.c (ffffffff811f9019)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/events/core.c (ffffffff8120dd70)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/ring_buffer.c (ffffffff81210e07)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_free_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/swap.c (ffffffff81228bc3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/shmem.c (ffffffff8123c3e7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In mm/percpu.c (ffffffff81245aef)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/list_lru.c (ffffffff8124ff65)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
  - mm/list_lru.c:list_lru_add
```
```
In mm/gup.c (ffffffff81252b69)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In mm/memory.c (ffffffff8125568e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:init_zero_pfn
```
```
In mm/mremap.c (ffffffff8126854a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81269d38)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff8126af65)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/page_alloc.c (ffffffff828c8062)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/memblock.c (ffffffff81a6ccd8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
```
```
In mm/hugetlb.c (ffffffff8129007a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
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
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff81291cdd)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse.c (ffffffff81295d0b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_buffer_free
```
```
In mm/sparse-vmemmap.c (ffffffff81a6e204)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff828ca47e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
```
In mm/slub.c (ffffffff8129cd21)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/memory_hotplug.c (ffffffff828cac05)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812a6c72)
Location: arch/x86/include/asm/page_64.h:18
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
Location: arch/x86/include/asm/page_64.h:18
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
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff812bf4be)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In mm/zbud.c (ffffffff812c6ab5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/zbud.c:free_zbud_page
```
```
In mm/cma.c (ffffffff828cc744)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In mm/usercopy.c (ffffffff812cc5e1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In mm/hmm.c (ffffffff812ce162)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/direct-io.c (ffffffff81322010)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/io_uring.c (ffffffff813397f5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_mem_free
```
```
In fs/dax.c (ffffffff8134083d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In fs/crypto/bio.c (ffffffff81347a18)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/direct-io.c (ffffffff8135df45)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/proc/kcore.c (ffffffff81378c84)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/vmcore.c (ffffffff81379583)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In fs/jbd2/journal.c (ffffffff813f3997)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/crypto.c (ffffffff8140e76c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8144a252)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff814ba5e7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814bb116)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
```
```
In crypto/skcipher.c (ffffffff814bcb71)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814c11cb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff814c91c2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff814ce48e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d2243)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/bio.c (ffffffff814d8de9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/bio.c:bio_map_kern
```
```
In block/blk-merge.c (ffffffff814e3d58)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-lib.c (ffffffff814e64a4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
```
```
In block/bio-integrity.c (ffffffff8150ea0f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
```
```
In lib/scatterlist.c (ffffffff8151b709)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff81521bc0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8161f1fb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81628b5e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/xen/manage.c (ffffffff8162b30c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff828e72df)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8162f88a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff816307f8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828e7578)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff816361d9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81638c55)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81668ed0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816760cb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/generic.c (ffffffff8168d6b9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8168f89a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81691d61)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816a3d25)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_dte_irq_entry
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:free_pt_l2
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816aa806)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff816ab8cb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff816b41d5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:domain_unmap
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel-pasid.c (ffffffff816b6109)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff816b7a1b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b7cc5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81714eac)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/dax/super.c (ffffffff81718166)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/nvme/host/core.c (ffffffff81742a85)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_submit_user_cmd
  - drivers/nvme/host/core.c:nvme_setup_discard
  - drivers/nvme/host/core.c:nvme_setup_discard
```
```
In drivers/spi/spi.c (ffffffff81779a4c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/net/tun.c (ffffffff8178ae43)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff8179227e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In drivers/usb/core/hcd.c (ffffffff817a5d34)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/devio.c (ffffffff817b5660)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817c34b1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817cce7a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817f91fa)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/md/dm-io.c (ffffffff81858555)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/md/dm-io.c:km_get_page
```
```
In drivers/md/dm-kcopyd.c (ffffffff828f8a72)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff81884455)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff828fbefe)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/memmap.c (ffffffff81a6e429)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
```
```
In drivers/firmware/efi/efi.c (ffffffff81a69c14)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff828fea19)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81894a47)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa
```
```
In arch/x86/power/hibernate_64.c (ffffffff818a91bf)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In net/core/skbuff.c (ffffffff818ba95a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff819022c9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/ipv4/tcp.c (ffffffff8195dca9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/packet/af_packet.c (ffffffff81a2a4b4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/xdp/xsk.c (ffffffff81a4ac16)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
```
```
In lib/cpumask.c (ffffffff82909826)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
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
In arch/x86/kernel/head64.c (ffffffff82888190)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In init/main.c (ffffffff82889072)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/entry/vdso/vma.c (ffffffff810031c3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/events/intel/bts.c (ffffffff8100dd30)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e655)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff81014bfd)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/hyperv/mmu.c (ffffffff8101e216)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8101eb5e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8101ee02)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/realmode/init.c (ffffffff8288f8b2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:init_real_mode
```
```
In arch/x86/kernel/ldt.c (ffffffff8102657b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff82891754)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/alternative.c (ffffffff81029969)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81033423)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104697c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8104fd75)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff8289c847)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828a01b2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105f3bb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/kernel/check.c (ffffffff81067f37)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff828a33fb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828a4abc)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff8106ba83)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
  - arch/x86/kernel/tce_64.c:free_tce_table
```
```
In arch/x86/mm/init.c (ffffffff828a56da)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In arch/x86/mm/init_64.c (ffffffff81a27b30)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/ioremap.c (ffffffff828a60ae)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81072f65)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:populate_pgd
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:alloc_pte_page
```
```
In arch/x86/mm/mmap.c (ffffffff81073b80)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_phys_addr_range
```
```
In arch/x86/mm/pat.c (ffffffff810747a5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff81075501)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff8107699d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/numa.c (ffffffff828a7261)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_reset_distance
```
```
In arch/x86/mm/kaslr.c (ffffffff81a27d72)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8107c852)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a8786)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi.c (ffffffff828a9f38)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81080019)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/fork.c (ffffffff810873ce)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/resource.c (ffffffff8109105c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff810f6037)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
```
```
In kernel/power/swap.c (ffffffff810f70a5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In kernel/dma/mapping.c (ffffffff81119cf8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_mmap
```
```
In kernel/dma/direct.c (ffffffff8111a686)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
```
```
In kernel/dma/swiotlb.c (ffffffff8111ae24)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In kernel/profile.c (ffffffff8111c821)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/crash_core.c (ffffffff811446f5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/crash_core.c:paddr_vmcoreinfo_note
```
```
In kernel/kexec_core.c (ffffffff81144e95)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_add_entry
```
```
In kernel/kexec_file.c (ffffffff81147915)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In kernel/trace/ring_buffer.c (ffffffff81189f74)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In kernel/trace/trace.c (ffffffff811913a7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/cpumap.c (ffffffff811ebd69)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/events/core.c (ffffffff81200b40)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/ring_buffer.c (ffffffff81203b97)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_free_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/swap.c (ffffffff8121bd03)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/shmem.c (ffffffff8122f3e7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In mm/percpu.c (ffffffff81238a9f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/list_lru.c (ffffffff81242f05)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
  - mm/list_lru.c:list_lru_add
```
```
In mm/gup.c (ffffffff81245933)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff81247d8e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:init_zero_pfn
```
```
In mm/mremap.c (ffffffff8125a77a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8125bfaa)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff8125cf95)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/page_alloc.c (ffffffff828c0787)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/memblock.c (ffffffff81a2921f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
```
```
In mm/hugetlb.c (ffffffff81281d3b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
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
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff81283926)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse.c (ffffffff8128791b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_buffer_free
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a641)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff828c2ba3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
```
In mm/slub.c (ffffffff8128e8b1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/memory_hotplug.c (ffffffff828c332a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff81298718)
Location: arch/x86/include/asm/page_64.h:18
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
Location: arch/x86/include/asm/page_64.h:18
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
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff812b05ae)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In mm/zbud.c (ffffffff812b7af5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/zbud.c:free_zbud_page
```
```
In mm/cma.c (ffffffff828c4e60)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In mm/usercopy.c (ffffffff812bd451)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In mm/hmm.c (ffffffff812bf015)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/direct-io.c (ffffffff81312bb0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/io_uring.c (ffffffff8132a525)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_mem_free
```
```
In fs/dax.c (ffffffff81332f74)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In fs/crypto/bio.c (ffffffff813386f8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/direct-io.c (ffffffff8134ebe5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/proc/kcore.c (ffffffff81369754)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/vmcore.c (ffffffff8136a053)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In fs/jbd2/journal.c (ffffffff813e4417)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/crypto.c (ffffffff813ff1ec)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8143aca2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff814ab007)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814abb36)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
```
```
In crypto/skcipher.c (ffffffff814ad591)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814b1beb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff814b9be2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff814beeae)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c2c63)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/bio.c (ffffffff814c9799)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/bio.c:bio_map_kern
```
```
In block/blk-merge.c (ffffffff814d4638)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-lib.c (ffffffff814d6a14)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
```
```
In block/bio-integrity.c (ffffffff814fee3f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
```
```
In lib/scatterlist.c (ffffffff8150b9f9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff81511eb0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8161381b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816551ab)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/generic.c (ffffffff8166b0a9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8166d28a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8166f751)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff81681715)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_dte_irq_entry
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:free_pt_l2
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff81687ff6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff8168922b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff81691e95)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:domain_unmap
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel-pasid.c (ffffffff81693d49)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff8169565b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81695905)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff816e892c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/nvdimm/btt.c (ffffffff816ec10b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/nvdimm/btt.c:arena_clear_freelist_error
```
```
In drivers/dax/super.c (ffffffff816f0696)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/nvme/host/core.c (ffffffff81724715)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_submit_user_cmd
  - drivers/nvme/host/core.c:nvme_setup_discard
  - drivers/nvme/host/core.c:nvme_setup_discard
```
```
In drivers/spi/spi.c (ffffffff817597fc)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/net/tun.c (ffffffff8176a793)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/usb/core/hcd.c (ffffffff81798264)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/devio.c (ffffffff817a7090)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817be39a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c9224)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In drivers/md/dm-io.c (ffffffff8181fb65)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/md/dm-io.c:km_get_page
```
```
In drivers/md/dm-kcopyd.c (ffffffff828f0384)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff828f379a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/memmap.c (ffffffff81a2a831)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
```
```
In drivers/firmware/efi/efi.c (ffffffff81a260e4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff828f654c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
```
In drivers/hv/vmbus_drv.c (ffffffff8184e6e5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/hv/hv.c (ffffffff8184f93f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/hv/hv.c:hv_synic_enable_regs
  - drivers/hv/hv.c:hv_synic_enable_regs
  - drivers/hv/hv.c:hv_post_message
```
```
In drivers/hv/connection.c (ffffffff818501fc)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/hv/connection.c:vmbus_negotiate_version
  - drivers/hv/connection.c:vmbus_negotiate_version
  - drivers/hv/connection.c:vmbus_negotiate_version
```
```
In drivers/hv/channel.c (ffffffff81850a2b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/hv/channel.c:virt_to_hvpfn
```
```
In arch/x86/power/hibernate_64.c (ffffffff81863e1c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In net/core/skbuff.c (ffffffff818748aa)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff818bc0f9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/ipv4/tcp.c (ffffffff81917799)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/packet/af_packet.c (ffffffff819e76a4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/xdp/xsk.c (ffffffff81a07806)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
```
```
In lib/cpumask.c (ffffffff82901b74)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
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
In arch/x86/kernel/head64.c (ffffffff8289d1dc)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In init/main.c (ffffffff8289e0e1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81004aa3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/events/intel/bts.c (ffffffff8100ef90)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f8b5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff810158ed)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/xen/mmu.c (ffffffff8101ddbf)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a4822)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/mmu_hvm.c (ffffffff8101edb5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff828a5042)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff8101fe36)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/p2m.c (ffffffff81021489)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a6c54)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81028453)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_get_user_pgd
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a8771)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ccb6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/xen/efi.c (ffffffff828a9c51)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102e6ce)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102f041)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f2d8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/realmode/init.c (ffffffff828aa589)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:init_real_mode
```
```
In arch/x86/kernel/ldt.c (ffffffff81036ab0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff828ac439)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/alternative.c (ffffffff81039eed)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81043c33)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056b9c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105fe75)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff828b7615)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828bafda)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f48e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/check.c (ffffffff810786f7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff828be033)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828bf6f4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff8107c306)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
  - arch/x86/kernel/tce_64.c:free_tce_table
```
```
In arch/x86/mm/init.c (ffffffff828c0312)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In arch/x86/mm/init_64.c (ffffffff81ad79cc)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/ioremap.c (ffffffff828c0d48)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81084305)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/mmap.c (ffffffff81084e60)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_phys_addr_range
```
```
In arch/x86/mm/pat.c (ffffffff810859d5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff810867c5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81087ce4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/numa.c (ffffffff828c1f6e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_reset_distance
```
```
In arch/x86/mm/kaslr.c (ffffffff81ad7c3e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108dce2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c3500)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi.c (ffffffff828c4cb1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81091509)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In kernel/fork.c (ffffffff81098914)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/resource.c (ffffffff810a262c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff81103047)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
```
```
In kernel/power/swap.c (ffffffff811040b5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In kernel/dma/mapping.c (ffffffff81125188)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_mmap
```
```
In kernel/dma/direct.c (ffffffff81125b16)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
```
```
In kernel/dma/swiotlb.c (ffffffff811262b4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In kernel/profile.c (ffffffff81127cb1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/crash_core.c (ffffffff8114f2c5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/crash_core.c:paddr_vmcoreinfo_note
```
```
In kernel/kexec_core.c (ffffffff8114fa65)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_add_entry
```
```
In kernel/kexec_file.c (ffffffff811523d5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In kernel/trace/ring_buffer.c (ffffffff81194a54)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In kernel/trace/trace.c (ffffffff8119c117)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/cpumap.c (ffffffff811f6de9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/events/core.c (ffffffff8120bb10)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/ring_buffer.c (ffffffff8120eba7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_free_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/swap.c (ffffffff81226963)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/shmem.c (ffffffff8123a187)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In mm/percpu.c (ffffffff8124388f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/list_lru.c (ffffffff8124dd05)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
  - mm/list_lru.c:list_lru_add
```
```
In mm/gup.c (ffffffff81250909)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In mm/memory.c (ffffffff8125342e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:init_zero_pfn
```
```
In mm/mremap.c (ffffffff812662ea)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81267ad8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff81268d05)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/page_alloc.c (ffffffff828dade2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/memblock.c (ffffffff81ad90e8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
```
```
In mm/hugetlb.c (ffffffff8128de8a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
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
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff8128faed)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse.c (ffffffff81293b1b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_buffer_free
```
```
In mm/sparse-vmemmap.c (ffffffff81ada614)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff828dd1fe)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
```
In mm/slub.c (ffffffff8129ab31)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/memory_hotplug.c (ffffffff828dd985)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812a4a82)
Location: arch/x86/include/asm/page_64.h:18
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
Location: arch/x86/include/asm/page_64.h:18
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
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff812bd2ce)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In mm/zbud.c (ffffffff812c48c5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/zbud.c:free_zbud_page
```
```
In mm/cma.c (ffffffff828df4c4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In mm/usercopy.c (ffffffff812ca3f1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In mm/hmm.c (ffffffff812cbf72)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/direct-io.c (ffffffff8131fae0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/io_uring.c (ffffffff813372c5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_mem_free
```
```
In fs/dax.c (ffffffff8133e30d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In fs/crypto/bio.c (ffffffff813454e8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/direct-io.c (ffffffff8135ba15)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/proc/kcore.c (ffffffff81376754)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/vmcore.c (ffffffff81377053)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In fs/jbd2/journal.c (ffffffff813f0d17)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/crypto.c (ffffffff8140baec)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814462f2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff814b6677)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814b71a6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
```
```
In crypto/skcipher.c (ffffffff814b8c01)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814bd25b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff814c5252)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff814ca51e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814ce2d3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/bio.c (ffffffff814d4e79)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/bio.c:bio_map_kern
```
```
In block/blk-merge.c (ffffffff814dfde8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-lib.c (ffffffff814e2534)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
```
```
In block/bio-integrity.c (ffffffff8150aa9f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
```
```
In lib/scatterlist.c (ffffffff81517799)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff8151dc50)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8164d19b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81656b2e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/xen/manage.c (ffffffff816595ac)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff828fade5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff8165d85a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8165e7c8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff828fb07e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff81663f59)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81666da5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816972b0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816a449b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/generic.c (ffffffff816bb929)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816bdb0a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816bffd1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d1f95)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_dte_irq_entry
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:free_pt_l2
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816d89e6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff816d9aab)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff816e2725)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:domain_unmap
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel-pasid.c (ffffffff816e45d9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff816e5eeb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e6195)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81753c7c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/dax/super.c (ffffffff81756f36)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/spi/spi.c (ffffffff817a9dec)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/net/tun.c (ffffffff817bb1e3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff817c24de)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In drivers/usb/core/hcd.c (ffffffff817e27d4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/devio.c (ffffffff817f2100)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817fff51)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8180991a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81835cca)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81840b54)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In drivers/i2c/busses/i2c-amd-mp2-plat.c (ffffffff81868fcd)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_xfer
```
```
In drivers/md/dm-io.c (ffffffff818a7b85)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/md/dm-io.c:km_get_page
```
```
In drivers/md/dm-kcopyd.c (ffffffff8290d2aa)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff818d58f5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff82910fdf)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/memmap.c (ffffffff81ada839)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
```
```
In drivers/firmware/efi/efi.c (ffffffff81ad6024)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff82913c48)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
```
In arch/x86/power/hibernate_64.c (ffffffff818fa81f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In net/core/skbuff.c (ffffffff8190b95a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff819532f9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/ipv4/tcp.c (ffffffff819c8479)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/packet/af_packet.c (ffffffff81a96064)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/xdp/xsk.c (ffffffff81ab6ac6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
```
```
In lib/cpumask.c (ffffffff8291f170)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
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
In arch/x86/kernel/head64.c (ffffffff8289d1dc)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In init/main.c (ffffffff8289e0e8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81004be3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vdso_fault
```
```
In arch/x86/events/intel/bts.c (ffffffff8100f160)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff8100faa5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/pt.c (ffffffff81015b2d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
```
```
In arch/x86/xen/mmu.c (ffffffff8101e00f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a47f6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/mmu_hvm.c (ffffffff8101f005)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/xen/setup.c (ffffffff828a5016)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_remap_memory
  - arch/x86/xen/setup.c:xen_remap_memory
```
```
In arch/x86/xen/pmu.c (ffffffff81020086)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_init
```
```
In arch/x86/xen/p2m.c (ffffffff810216d9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_setup_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:xen_build_mfn_list_list
  - arch/x86/xen/p2m.c:p2m_mid_mfn_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a6c28)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810290e3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:paddr_vmcoreinfo_note
  - arch/x86/xen/mmu_pv.c:remap_area_pfn_pte_fn
  - arch/x86/xen/mmu_pv.c:xen_destroy_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_create_contiguous_region
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_set_fixmap
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:set_page_prot_flags
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_free_pgtbl
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:drop_mm_ref_this_cpu
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_get_user_pgd
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
  - arch/x86/xen/mmu_pv.c:xen_reserve_special_pages
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a8781)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102daa6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/xen/efi.c (ffffffff828a9c61)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102f4be)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102fe61)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81030118)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/realmode/init.c (ffffffff828aa599)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/realmode/init.c:init_real_mode
```
```
In arch/x86/kernel/ldt.c (ffffffff810379b0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff828ac457)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/alternative.c (ffffffff8103aeed)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff81045033)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105803c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810613d5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff828b7716)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828bb0f0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107170e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/check.c (ffffffff8107a7f7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff828c1180)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828c2841)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff8107e406)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:tce_build
  - arch/x86/kernel/tce_64.c:free_tce_table
```
```
In arch/x86/mm/init.c (ffffffff828c345d)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
```
```
In arch/x86/mm/init_64.c (ffffffff81ae3e8c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pte
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pmd
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_pud_init
```
```
In arch/x86/mm/ioremap.c (ffffffff828c3e93)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_init
  - arch/x86/mm/ioremap.c:early_ioremap_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81086445)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_wc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:set_memory_uc
  - arch/x86/mm/pageattr.c:alloc_pmd_page
  - arch/x86/mm/pageattr.c:alloc_pte_page
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/mmap.c (ffffffff81086fb0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:valid_phys_addr_range
```
```
In arch/x86/mm/pat.c (ffffffff81087b25)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff810888f5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81089ed4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/numa.c (ffffffff828c50b9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_reset_distance
```
```
In arch/x86/mm/kaslr.c (ffffffff81ae40fe)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff810900c2)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c66a6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi.c (ffffffff828c7e57)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81093939)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828ca472)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
```
```
In kernel/fork.c (ffffffff810a053b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/resource.c (ffffffff810aa66c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In kernel/power/snapshot.c (ffffffff8110e437)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:memory_bm_free
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:free_zone_bm_rtree
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:get_image_page
```
```
In kernel/power/swap.c (ffffffff8110f4a5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_submit_io
```
```
In kernel/dma/mapping.c (ffffffff811317c8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_mmap
```
```
In kernel/dma/direct.c (ffffffff81132156)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
```
```
In kernel/dma/swiotlb.c (ffffffff811328f4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
```
```
In kernel/profile.c (ffffffff81134331)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/crash_core.c (ffffffff8115c0e5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/crash_core.c:paddr_vmcoreinfo_note
```
```
In kernel/kexec_core.c (ffffffff8115c8c5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_add_entry
```
```
In kernel/kexec_file.c (ffffffff8115f2c5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In kernel/trace/ring_buffer.c (ffffffff811a2664)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
```
```
In kernel/trace/trace.c (ffffffff811a9db7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/cpumap.c (ffffffff812050c5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/events/core.c (ffffffff8121a920)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/ring_buffer.c (ffffffff8121dab7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_to_page
  - kernel/events/ring_buffer.c:perf_mmap_free_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/swap.c (ffffffff81235c93)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/shmem.c (ffffffff81249872)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In mm/percpu.c (ffffffff8125304f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_free_alloc_info
```
```
In mm/list_lru.c (ffffffff8125d6b5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
  - mm/list_lru.c:list_lru_add
```
```
In mm/gup.c (ffffffff8126028f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In mm/memory.c (ffffffff81262e35)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:init_zero_pfn
```
```
In mm/mremap.c (ffffffff81275c7b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8127746e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pgtable-generic.c (ffffffff81278695)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgtable_trans_huge_withdraw
  - mm/pgtable-generic.c:pgtable_trans_huge_deposit
```
```
In mm/page_alloc.c (ffffffff828e0203)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/memblock.c (ffffffff81ae559e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_double_array
  - mm/memblock.c:memblock_discard
  - mm/memblock.c:memblock_discard
```
```
In mm/hugetlb.c (ffffffff8129dc38)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
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
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff8129e33b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse.c (ffffffff812a397b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_buffer_free
```
```
In mm/sparse-vmemmap.c (ffffffff81ae6aca)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff828e2615)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
```
In mm/slub.c (ffffffff812aaa11)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
```
In mm/memory_hotplug.c (ffffffff828e2d9c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memory_hotplug.c:register_page_bootmem_info_node
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In mm/migrate.c (ffffffff812b55dd)
Location: arch/x86/include/asm/page_64.h:18
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
Location: arch/x86/include/asm/page_64.h:18
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
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff812cdb2e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_slab_state
```
```
In mm/zbud.c (ffffffff812d5355)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/zbud.c:free_zbud_page
```
```
In mm/cma.c (ffffffff828e48db)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In mm/usercopy.c (ffffffff812db0f1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In mm/hmm.c (ffffffff812dcce6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/direct-io.c (ffffffff81331800)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/io_uring.c (ffffffff8134a385)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_mmap
  - fs/io_uring.c:io_mem_free
```
```
In fs/dax.c (ffffffff81352669)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In fs/crypto/bio.c (ffffffff813587c8)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_zeroout_range
```
```
In fs/iomap/direct-io.c (ffffffff8136f165)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_zero
```
```
In fs/proc/kcore.c (ffffffff8138a204)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/vmcore.c (ffffffff8138ab03)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
```
In fs/jbd2/journal.c (ffffffff81406803)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/ecryptfs/crypto.c (ffffffff8142178c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:virt_to_scatterlist
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8145d622)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff814cf117)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814cfc5b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
```
```
In crypto/skcipher.c (ffffffff814d16c1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814d5d2b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/gcm.c (ffffffff814ddd22)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_init_common
  - crypto/gcm.c:crypto_gcm_init_common
```
```
In crypto/drbg.c (ffffffff814e2fee)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814e6da3)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/bio.c (ffffffff814eda29)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/bio.c:bio_map_kern
```
```
In block/blk-merge.c (ffffffff814f8c48)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
```
In block/blk-lib.c (ffffffff814fb3c4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_zero_pages
```
```
In block/bio-integrity.c (ffffffff8152413f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
```
```
In lib/scatterlist.c (ffffffff81530f39)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In lib/kfifo.c (ffffffff815374c0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8166782b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8167110e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/xen/manage.c (ffffffff81673bac)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/manage.c:xen_suspend
```
```
In drivers/xen/events/events_base.c (ffffffff82900b16)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/events/events_fifo.c (ffffffff81677e6a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/events/events_fifo.c:init_control_block
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81679308)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff82900daf)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
```
In drivers/xen/xenbus/xenbus_dev_backend.c (ffffffff8167e519)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_mmap
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81681355)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_dma_supported
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816b1860)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff816be92b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/char/agp/generic.c (ffffffff816d5ef9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816d80da)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_remove
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816da5a1)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816ec595)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_dte_irq_entry
  - drivers/iommu/amd_iommu.c:__get_gcr3_pte
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_sub_pt
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:free_pt_l2
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816f2f96)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff816f405b)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
  - drivers/iommu/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel-iommu.c (ffffffff816fcd85)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_free_coherent
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
  - drivers/iommu/intel-iommu.c:domain_unmap
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel-pasid.c (ffffffff816fec99)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_get_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff817005eb)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81700895)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8176f0ec)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
```
```
In drivers/dax/super.c (ffffffff817723b6)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
```
```
In drivers/spi/spi.c (ffffffff817c3c7c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_map_buf
```
```
In drivers/net/tun.c (ffffffff817d4219)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff817dc79e)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In drivers/usb/core/hcd.c (ffffffff817fd524)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/devio.c (ffffffff8180c340)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8181a061)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81823a2a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81850000)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185b024)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8290fb98)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_get_page
```
```
In drivers/md/dm-io.c (ffffffff818c3dc5)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/md/dm-io.c:km_get_page
```
```
In drivers/md/dm-kcopyd.c (ffffffff82913cc0)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_init
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff818f2415)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_io_rw_extended
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff82917a0c)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/memmap.c (ffffffff81ae6cef)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:release_firmware_map_entry
```
```
In drivers/firmware/efi/efi.c (ffffffff81ae24e4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff8291a90f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_init_clocksource
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819051a7)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_va_to_pa
```
```
In arch/x86/power/hibernate_64.c (ffffffff8191b97f)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In net/core/skbuff.c (ffffffff8192ca7a)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:build_skb
```
```
In net/core/xdp.c (ffffffff81974e01)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_release_frame
  - net/core/xdp.c:__xdp_return
  - net/core/xdp.c:__xdp_return
```
```
In net/ipv4/tcp.c (ffffffff819d1fc9)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/packet/af_packet.c (ffffffff81aa2cd4)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/xdp/xsk.c (ffffffff81ac2c06)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_mmap
```
```
In lib/cpumask.c (ffffffff82925b94)
Location: arch/x86/include/asm/page_64.h:18
Inline: True
Inline callers:
  - lib/cpumask.c:free_bootmem_cpumask_var
```
</details>
</li>
</ul>

## Differences
