# Function: <code>___set_bit</code>

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
In arch/x86/events/core.c (ffffffff8100642e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
```
```
In arch/x86/events/amd/core.c (ffffffff8100c0de)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff810159db)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
```
```
In arch/x86/events/intel/p4.c (ffffffff8101e8cd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
```
```
In arch/x86/events/intel/uncore.c (ffffffff81023ed5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81028913)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102c781)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff8102fd01)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff810467d4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff810476eb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In arch/x86/hyperv/ivm.c (ffffffff81047ecc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048cbd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__cpumask_to_vpset
```
```
In arch/x86/kernel/signal.c (ffffffff8104b195)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8106fc50)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108e9a5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff810957da)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a34f3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In arch/x86/kernel/kvm.c (ffffffff810b60c6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/sev.c (ffffffff810bc1a6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:snp_issue_guest_request
  - arch/x86/kernel/sev.c:snp_issue_guest_request
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_do_mmio
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:vmgexit_psc
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:vc_handle_cpuid
  - arch/x86/kernel/sev.c:vc_handle_cpuid
  - arch/x86/kernel/sev.c:vc_handle_cpuid
  - arch/x86/kernel/sev.c:vc_handle_cpuid
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
```
```
In arch/x86/mm/tlb.c (ffffffff810c82ff)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In kernel/workqueue.c (ffffffff81113436)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In kernel/sched/core.c (ffffffff8113460c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/build_policy.c (ffffffff8115b0a0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:init_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff83ea8fce)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/sched/build_utility.c:ipi_rseq
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:cpu_attach_domain
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff811a7b4b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In kernel/time/timer.c (ffffffff811d7269)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffffffff811f9345)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff812186f7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff81320a1d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
```
```
In kernel/events/uprobes.c (ffffffff81350544)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/watch_queue.c (ffffffff813580ca)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/filemap.c (ffffffff8135e11e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:filemap_add_folio
```
```
In mm/swap.c (ffffffff8136debd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
```
```
In mm/vmscan.c (ffffffff8138744c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
```
```
In mm/shmem.c (ffffffff813903fe)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In mm/memory.c (ffffffff813bba6c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_present_pte
```
```
In mm/rmap.c (ffffffff813d7b8c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff83ebe834)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:memmap_init_compound
  - mm/page_alloc.c:__init_zone_device_page
  - mm/page_alloc.c:memmap_init_range
  - mm/page_alloc.c:reserve_bootmem_region
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/swap_state.c (ffffffff813f974d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8140cc38)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_add_to_page_cache
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:__prep_compound_gigantic_folio
```
```
In mm/sparse.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In mm/ksm.c (ffffffff81422fdb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff8142788f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In mm/kfence/core.c (ffffffff8142f474)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_pool
```
```
In mm/migrate.c (ffffffff81431abd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/migrate_device.c (ffffffff81439ae6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In mm/huge_memory.c (ffffffff8143c1f7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8144941c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/secretmem.c (ffffffff8146b439)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff8146c28c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/mapping_dirty_helpers.c (ffffffff81471e96)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In mm/page_reporting.c (ffffffff814728aa)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In fs/pipe.c (ffffffff814882b5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
```
```
In fs/file.c (ffffffff814a700a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
```
```
In fs/dax.c (ffffffff814f7f6d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/iomap/buffered-io.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff81557d00)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff8156fe6c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
```
```
In fs/ext4/mballoc.c (ffffffff81590392)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_set_bits
```
```
In fs/ext4/super.c (ffffffff815c3424)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff815f75ad)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff8161a9dc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In block/blk-cgroup.c (ffffffff817620f8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In io_uring/io_uring.c (ffffffff81788da1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_register_restrictions
  - io_uring/io_uring.c:io_register_restrictions
```
```
In io_uring/filetable.c (ffffffff8179403e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - io_uring/filetable.c:io_install_fixed_file
```
```
In io_uring/rsrc.c (ffffffff817a1e9b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:__io_sqe_files_update
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff818c12e5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c6323)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl_unlocked
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff81977454)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff819f14c2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff83ee9345)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/grant-table.c (ffffffff81a17d21)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:put_free_entry_locked
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81a326b6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff81a5afd6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81a8db16)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_set
```
```
In drivers/iommu/amd/iommu.c (ffffffff81ab1edb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:domain_id_alloc
```
```
In drivers/iommu/amd/init.c (ffffffff83ef36f8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:__copy_device_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acbc41)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b818eb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
```
```
In drivers/scsi/sr.c (ffffffff81b98b68)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffff81bdbf35)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy-c45.c (ffffffff81bdeb26)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
```
```
In drivers/net/phy/phy_device.c (ffffffff81be51b8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
```
```
In drivers/net/phy/linkmode.c (ffffffff81be52ad)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81be841b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
```
```
In drivers/net/phy/bcm84881.c (ffffffff81be9510)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81be9bee)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In drivers/net/tun.c (ffffffff81bec6cd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In drivers/input/input.c (ffffffff81ca748e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff81cab056)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:copy_abs
```
```
In drivers/input/ff-core.c (ffffffff81cabd32)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81cb0f55)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/extcon/extcon.c (ffffffff81d842d5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
```
```
In net/socket.c (ffffffff81d92e33)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81d9c423)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffffffff81dc469f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:__dev_alloc_name
```
```
In net/core/gro.c (ffffffff81e0987d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/net-sysfs.c (ffffffff81e0b671)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_queue_show
```
```
In net/core/skmsg.c (ffffffff81e46047)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/netlink/af_netlink.c (ffffffff81e669d6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ethtool/bitset.c (ffffffff81e7f32e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/fec.c (ffffffff81e8672d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethtool_fec_to_link_modes
  - net/ethtool/fec.c:ethtool_fec_to_link_modes
  - net/ethtool/fec.c:ethtool_fec_to_link_modes
  - net/ethtool/fec.c:ethtool_fec_to_link_modes
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea4009)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea7c3d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81eb14df)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81ebf71b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_ipv4.c (ffffffff83f0eba1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
```
```
In net/ipv4/raw.c (ffffffff81edc986)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81ee0a47)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff83f0f3f1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_init
```
```
In net/ipv4/ping.c (ffffffff81f0ca14)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f27859)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/unix/af_unix.c (ffffffff81f4b815)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff81f50ae7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81f5cb19)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_get_saddr_eval
```
```
In net/ipv6/udp.c (ffffffff81f87c54)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81fafbfc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81fc7d48)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffffffff81fdc3a3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81fee9cc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81ffab49)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:mptcp_data_ready
```
```
In net/mptcp/subflow.c (ffffffff81fffcdd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:mptcp_set_connected
```
```
In net/mptcp/pm.c (ffffffff820057a3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_mp_prio_received
```
```
In net/mptcp/pm_netlink.c (ffffffff82007c06)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
```
```
In net/mptcp/sockopt.c (ffffffff8200c98c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In net/mptcp/pm_userspace.c (ffffffff8200df24)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
```
```
In net/mctp/af_mctp.c (ffffffff82010c94)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_pf_create
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
```
In lib/idr.c (ffffffff820216b1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff8203a7be)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/vsprintf.c (ffffffff820417e8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In lib/xarray.c (ffffffff8204771d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - lib/xarray.c:xas_squash_marks
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
In arch/x86/events/core.c (ffffffff81005bce)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
```
```
In arch/x86/events/amd/core.c (ffffffff8100b88a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff8101526b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
```
```
In arch/x86/events/intel/p4.c (ffffffff8101e5bd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
```
```
In arch/x86/events/intel/uncore.c (ffffffff81023bf5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81028943)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102c7d1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff8102fdf1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff81046a16)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81047c16)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff8104827c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048f1d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__cpumask_to_vpset
```
```
In arch/x86/kernel/process_64.c (ffffffff8104a3b9)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/signal.c (ffffffff8104ba35)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81071853)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81091865)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff8109874a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a6486)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In arch/x86/kernel/kvm.c (ffffffff810b91c6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/sev.c (ffffffff810bf3df)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:snp_issue_guest_request
  - arch/x86/kernel/sev.c:snp_issue_guest_request
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_do_mmio
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:vmgexit_psc
  - arch/x86/kernel/sev.c:vc_handle_cpuid
  - arch/x86/kernel/sev.c:vc_handle_cpuid
  - arch/x86/kernel/sev.c:vc_handle_cpuid
  - arch/x86/kernel/sev.c:vc_handle_cpuid
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
```
```
In arch/x86/mm/tlb.c (ffffffff810cba3f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In kernel/workqueue.c (ffffffff8111fa36)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In kernel/sched/core.c (ffffffff81143809)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/build_policy.c (ffffffff8116b2a2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:init_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff836cda8e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/sched/build_utility.c:ipi_rseq
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:cpu_attach_domain
```
```
In kernel/irq/matrix.c (ffffffff811b982b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In kernel/time/timer.c (ffffffff811ebbc9)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffffffff8120e004)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff8122df67)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff813508cd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
```
```
In kernel/events/uprobes.c (ffffffff81381775)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/watch_queue.c (ffffffff8138995d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/filemap.c (ffffffff81390f24)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:filemap_add_folio
```
```
In mm/swap.c (ffffffff813a00dd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
```
```
In mm/vmscan.c (ffffffff813b0938)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In mm/shmem.c (ffffffff813c2d4b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
```
```
In mm/mm_init.c (ffffffff8214bfc9)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:reserve_bootmem_region
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In mm/memory.c (ffffffff813f0fc0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_present_pte
```
```
In mm/rmap.c (ffffffff8140c677)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/rmap.c:folio_add_new_anon_rmap
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In mm/page_alloc.c (ffffffff8141c043)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/swap_state.c (ffffffff8142c4ef)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8144005b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_add_to_page_cache
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:__prep_compound_gigantic_folio
```
```
In mm/sparse.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In mm/ksm.c (ffffffff81458032)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff8145cdfc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In mm/kfence/core.c (ffffffff81464661)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_pool
```
```
In mm/migrate.c (ffffffff814676df)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/migrate_device.c (ffffffff8146e80c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In mm/huge_memory.c (ffffffff814715cb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8147f5ff)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/secretmem.c (ffffffff814a021b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff814a1127)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a67d9)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In mm/page_reporting.c (ffffffff814a701a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In fs/pipe.c (ffffffff814bd1bd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
```
```
In fs/file.c (ffffffff814dbfe7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
```
```
In fs/dax.c (ffffffff8152f16d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/iomap/buffered-io.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff8158fa50)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff815a7cee)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
```
```
In fs/ext4/mballoc.c (ffffffff815c754d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_set_bits
```
```
In fs/ext4/super.c (ffffffff815fab74)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff8162f6c1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff816523dc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_args_to_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In block/blk-cgroup.c (ffffffff817a1ee0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_activate_policy
```
```
In io_uring/io_uring.c (ffffffff817c9770)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_register_restrictions
  - io_uring/io_uring.c:io_register_restrictions
```
```
In io_uring/filetable.c (ffffffff817d4d4f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - io_uring/filetable.c:io_install_fixed_file
```
```
In io_uring/rsrc.c (ffffffff817e300f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:__io_sqe_files_update
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff81904277)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff819093d3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl_unlocked
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff819bde3a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff81a39b72)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff8370ebf8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/grant-table.c (ffffffff81a60db1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:put_free_entry_locked
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81a7bf3c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff81aa55bc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81ad92c6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_set
```
```
In drivers/iommu/amd/iommu.c (ffffffff81afdf8b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:domain_id_alloc
```
```
In drivers/iommu/amd/init.c (ffffffff83719298)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:__copy_device_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b187bf)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd55f1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
```
```
In drivers/scsi/sr.c (ffffffff81bef108)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffff81c33432)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy-c45.c (ffffffff81c361a0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_adv
```
```
In drivers/net/phy/phy_device.c (ffffffff81c3c876)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
```
```
In drivers/net/phy/linkmode.c (ffffffff81c3cd3d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81c407bb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
```
```
In drivers/net/phy/bcm84881.c (ffffffff81c41928)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81c4201e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In drivers/net/tun.c (ffffffff81c44ab0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In drivers/input/input.c (ffffffff81d0e65e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff81d1263e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:copy_abs
```
```
In drivers/input/ff-core.c (ffffffff81d13312)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81d185b0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
```
```
In drivers/hid/bpf/hid_bpf_jmp_table.c (ffffffff81dd6f8e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog
```
```
In drivers/extcon/extcon.c (ffffffff81df2687)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
```
```
In net/socket.c (ffffffff81e0122e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81e0ac73)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffffffff81e346ff)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:__dev_alloc_name
```
```
In net/core/gro.c (ffffffff81e7c048)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/net-sysfs.c (ffffffff81e7ea21)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_queue_show
```
```
In net/core/skmsg.c (ffffffff81ea1723)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/netlink/af_netlink.c (ffffffff81ec2796)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ethtool/bitset.c (ffffffff81edb91e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/fec.c (ffffffff81ee310d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethtool_fec_to_link_modes
  - net/ethtool/fec.c:ethtool_fec_to_link_modes
  - net/ethtool/fec.c:ethtool_fec_to_link_modes
  - net/ethtool/fec.c:ethtool_fec_to_link_modes
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f02859)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f0647d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81f0fb6f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81f1dbf4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_ipv4.c (ffffffff837351b1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
```
```
In net/ipv4/raw.c (ffffffff81f3bc6d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81f3fcc7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff83735a01)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_init
```
```
In net/ipv4/ping.c (ffffffff81f6c5a1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81fab5bc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff81fb0457)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81fbc851)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_get_saddr_eval
```
```
In net/ipv6/udp.c (ffffffff81fe8104)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff82010254)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff82028cec)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffffffff82058083)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In net/xdp/xsk.c (ffffffff8206aafc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff82072b8c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_unaccepted_force_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:mptcp_data_ready
```
```
In net/mptcp/subflow.c (ffffffff8207bcfe)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:mptcp_set_connected
```
```
In net/mptcp/pm.c (ffffffff82081993)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_mp_prio_received
```
```
In net/mptcp/pm_netlink.c (ffffffff82083f86)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
```
```
In net/mptcp/sockopt.c (ffffffff820892e1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In net/mptcp/pm_userspace.c (ffffffff8208a804)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
```
```
In net/mctp/af_mctp.c (ffffffff8208d504)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_pf_create
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
```
In lib/idr.c (ffffffff820a16f7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff820b8c2e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/vsprintf.c (ffffffff820bfde4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In lib/xarray.c (ffffffff820c5dba)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - lib/xarray.c:xas_squash_marks
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
In arch/x86/events/core.c (ffffffff8100b2ce)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
```
```
In arch/x86/events/amd/core.c (ffffffff8101106c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff8101abf7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
  - arch/x86/events/intel/core.c:intel_pmu_enable_fixed
```
```
In arch/x86/events/intel/p4.c (ffffffff81024a0d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
```
```
In arch/x86/events/intel/uncore.c (ffffffff81029d25)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8102eaa3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81032931)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81036091)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff8104d226)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8104e37f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff8104ec5c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8105018d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__cpumask_to_vpset
```
```
In arch/x86/kernel/process_64.c (ffffffff81051619)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/signal.c (ffffffff81052cb5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81079073)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81086a70)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:mce_track_storm
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81098c35)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff8109fcea)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/vmware.c:vmware_sev_es_hcall_prepare
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810a02c6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/mshyperv.c:hv_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/mshyperv.c:hv_sev_es_hcall_prepare
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810ad4e6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In arch/x86/kernel/kvm.c (ffffffff810c0606)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/sev.c (ffffffff810c672f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:snp_issue_guest_request
  - arch/x86/kernel/sev.c:snp_issue_guest_request
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_do_mmio
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:sev_es_play_dead
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:vmgexit_psc
  - arch/x86/kernel/sev.c:vc_handle_cpuid
  - arch/x86/kernel/sev.c:vc_handle_cpuid
  - arch/x86/kernel/sev.c:vc_handle_cpuid
  - arch/x86/kernel/sev.c:vc_handle_cpuid
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/kernel/sev.c:__sev_cpuid_hv_ghcb
  - arch/x86/kernel/sev.c:__sev_cpuid_hv_ghcb
  - arch/x86/kernel/sev.c:__sev_cpuid_hv_ghcb
  - arch/x86/kernel/sev.c:__sev_cpuid_hv_ghcb
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
```
```
In arch/x86/mm/tlb.c (ffffffff810d40cf)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In kernel/workqueue.c (ffffffff81129f86)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In kernel/sched/core.c (ffffffff8114ed29)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/build_policy.c (ffffffff81178c37)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:init_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff838feecc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:ipi_rseq
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:cpu_attach_domain
```
```
In kernel/irq/matrix.c (ffffffff811c96eb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In kernel/time/timer.c (ffffffff81201714)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffffffff81225794)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff81247d8e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff81377cfd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
```
```
In kernel/events/uprobes.c (ffffffff813aab07)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/watch_queue.c (ffffffff813b33ad)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/filemap.c (ffffffff813bac6f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:filemap_add_folio
```
```
In mm/swap.c (ffffffff813c9d5d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
```
```
In mm/vmscan.c (ffffffff813d9e48)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In mm/shmem.c (ffffffff813ed9c3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:__shmem_get_inode
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_alloc_and_add_folio
  - mm/shmem.c:shmem_alloc_and_add_folio
```
```
In mm/mm_init.c (ffffffff8222eb5f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:reserve_bootmem_region
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In mm/memory.c (ffffffff8141bd1a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_present_pte
```
```
In mm/rmap.c (ffffffff81438efd)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/rmap.c:folio_add_new_anon_rmap
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In mm/page_alloc.c (ffffffff81448bb3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/slub.c (ffffffff81457518)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In mm/swap_state.c (ffffffff81465c27)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff81479f69)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_add_to_page_cache
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:gather_bootmem_prealloc
  - mm/hugetlb.c:__prep_compound_gigantic_folio
```
```
In mm/sparse.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In mm/ksm.c (ffffffff814929c7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/kfence/core.c (ffffffff81493e1f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In mm/migrate.c (ffffffff81496b9c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/migrate_device.c (ffffffff8149d270)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
```
```
In mm/huge_memory.c (ffffffff814a1f85)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814ad62b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/secretmem.c (ffffffff814cf8a2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff814d08b7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d7860)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In mm/page_reporting.c (ffffffff814d801a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In fs/pipe.c (ffffffff814ef65a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
```
```
In fs/file.c (ffffffff8150e207)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
```
```
In fs/dax.c (ffffffff8156404d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/iomap/buffered-io.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff815c85d2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff815e0afe)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
```
```
In fs/ext4/mballoc.c (ffffffff815fdd3d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_set_bits
```
```
In fs/ext4/super.c (ffffffff81633754)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff81668b9d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff8168b9ec)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_args_to_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In block/blk-cgroup.c (ffffffff817e5a2d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_activate_policy
```
```
In io_uring/filetable.c (ffffffff81818b6c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - io_uring/filetable.c:io_install_fixed_file
```
```
In io_uring/rsrc.c (ffffffff818270e9)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:__io_sqe_files_update
```
```
In io_uring/register.c (ffffffff8182b100)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - io_uring/register.c:io_register_restrictions
  - io_uring/register.c:io_register_restrictions
```
```
In lib/bitmap-str.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8194bc9a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff819505af)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl
```
```
In drivers/pci/pci.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff81a0870a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff81a853f2)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff839423c8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/grant-table.c (ffffffff81ab35e1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:put_free_entry_locked
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81ace3ec)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff81af800c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81b2c5b6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_set
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b57452)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
```
```
In drivers/iommu/amd/init.c (ffffffff8394cd98)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:__copy_device_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6e0ff)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
```
```
In drivers/iommu/iommufd/iova_bitmap.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c198cb)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:timeline_fence_set_deadline
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c2a249)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
```
```
In drivers/scsi/sr.c (ffffffff81c448a7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/gpu/drm/drm_edid.c (ffffffff81c93995)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_edid.c:drm_parse_cea_ext
  - drivers/gpu/drm/drm_edid.c:drm_parse_cea_ext
```
```
In drivers/gpu/drm/drm_mm.c (ffffffff81ca0d13)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mm.c:drm_mm_scan_add_block
  - drivers/gpu/drm/drm_mm.c:drm_mm_replace_node
  - drivers/gpu/drm/drm_mm.c:drm_mm_insert_node_in_range
  - drivers/gpu/drm/drm_mm.c:drm_mm_reserve_node
```
```
In drivers/net/phy/phy.c (ffffffff81ce8122)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy-c45.c (ffffffff81ceb120)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_baset1_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_baset1_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_baset1_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_baset1_read_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_adv
```
```
In drivers/net/phy/phy_device.c (ffffffff81cf1c76)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:phy_copy_pause_bits
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_c37_read_status
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
  - drivers/net/phy/phy_device.c:features_init
```
```
In drivers/net/phy/linkmode.c (ffffffff81cf213d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81cf5e1b)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
```
```
In drivers/net/phy/bcm84881.c (ffffffff81cf6fb8)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_config_init
  - drivers/net/phy/bcm84881.c:bcm84881_config_init
  - drivers/net/phy/bcm84881.c:bcm84881_config_init
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81cf76de)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In drivers/net/tun.c (ffffffff81cfa610)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In drivers/input/input.c (ffffffff81dc42ae)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_set_capability
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff81dc823e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:input_mt_init_slots
  - drivers/input/input-mt.c:copy_abs
```
```
In drivers/input/ff-core.c (ffffffff81dc8f42)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81dce260)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In drivers/hid/bpf/hid_bpf_jmp_table.c (ffffffff81e8f1c1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog
```
```
In drivers/extcon/extcon.c (ffffffff81ea8cd7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
```
```
In net/socket.c (ffffffff81ebd92e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81ec7663)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffffffff81eeab55)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:__dev_alloc_name
```
```
In net/core/gro.c (ffffffff81f3c398)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/net-sysfs.c (ffffffff81f3f92e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_queue_show
```
```
In net/core/skmsg.c (ffffffff81f63f23)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/netlink/af_netlink.c (ffffffff81f85ae6)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ethtool/common.c (ffffffff81f9c451)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ethtool/common.c:ethtool_forced_speed_maps_init
```
```
In net/ethtool/bitset.c (ffffffff81f9f6e5)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/fec.c (ffffffff81fa6eed)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethtool_fec_to_link_modes
  - net/ethtool/fec.c:ethtool_fec_to_link_modes
  - net/ethtool/fec.c:ethtool_fec_to_link_modes
  - net/ethtool/fec.c:ethtool_fec_to_link_modes
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc6cae)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fca76d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81fd3d5f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81fe22c4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_ipv4.c (ffffffff83969771)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
```
```
In net/ipv4/raw.c (ffffffff82001d8d)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff82005987)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff8396a071)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_init
```
```
In net/ipv4/ping.c (ffffffff82032cf1)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff820789ac)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff8207dab7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff82089c71)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_get_saddr_eval
```
```
In net/ipv6/udp.c (ffffffff820b6344)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff820df1e4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff820f872c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffffffff8212ab93)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
```
```
In net/xdp/xsk.c (ffffffff8213e20c)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff8214b8a0)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_unaccepted_force_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:mptcp_data_ready
```
```
In net/mptcp/subflow.c (ffffffff82151062)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_finish_connect
```
```
In net/mptcp/pm_netlink.c (ffffffff821595d3)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:fill_remote_addresses_vec
  - net/mptcp/pm_netlink.c:fill_remote_addresses_vec
```
```
In net/mptcp/sockopt.c (ffffffff8215f061)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In net/mptcp/pm_userspace.c (ffffffff821603b7)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
```
```
In net/mctp/af_mctp.c (ffffffff821639c4)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_pf_create
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
```
In lib/idr.c (ffffffff8217971f)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff8219353e)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/vsprintf.c (ffffffff82199ddc)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In lib/xarray.c (ffffffff821a073a)
Location: include/asm-generic/bitops/instrumented-non-atomic.h:26
Inline: True
Inline callers:
  - lib/xarray.c:xas_squash_marks
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
