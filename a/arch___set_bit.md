# Function: <code>arch___set_bit</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810077ab)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/amd/core.c (ffffffff81009102)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015b65)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff810197b3)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101c1c1)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102de9d)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102ec20)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/kernel/signal.c (ffffffff81030ba1)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81048234)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d582)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060d36)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106ae80)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/kernel/kvm.c (ffffffff8107687d)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077a0d)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff81087760)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828bedea)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
```
```
In kernel/workqueue.c (ffffffff810bccc9)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__flush_work
```
```
In kernel/sched/core.c (ffffffff81a98102)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/rt.c (ffffffff810e40e8)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff810f0ea7)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff810f5967)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/sched/isolation.c (ffffffff828c55a8)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff8111650e)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
```
```
In kernel/time/timer.c (ffffffff81128240)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffffffff811435ef)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/events/uprobes.c (ffffffff8120d48a)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8121602c)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff81231b61)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
```
```
In mm/memory.c (ffffffff81253ece)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff812650f4)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff81a91446)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/swap_state.c (ffffffff8127759d)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff81284997)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (0)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
```
```
In mm/ksm.c (ffffffff812928fb)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff81294214)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812a11e2)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812a6d8c)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812aa9dd)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/cma.c (0)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812c038c)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/pipe.c (ffffffff812d577f)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
```
In fs/file.c (ffffffff812edf13)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
```
```
In fs/dax.c (ffffffff8133597c)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff813765d9)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813890c6)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff813a3210)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff813cb63a)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff813e9da9)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff81409138)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/dev.c:fuse_request_send
  - fs/fuse/dev.c:fuse_request_send
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dev.c:__fuse_request_alloc
```
```
In fs/fuse/file.c (ffffffff81412660)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_flush
```
```
In fs/fuse/inode.c (ffffffff81412e78)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_sb_destroy
  - fs/fuse/inode.c:fuse_fill_super
```
```
In security/integrity/ima/ima_template.c (ffffffff814a02f6)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/scsi_ioctl.c (ffffffff828ebf95)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
```
In block/blk-cgroup.c (ffffffff814f10ac)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8154def9)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff815cf847)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff8162889b)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff828f5ec4)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff816529b8)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff8166ed71)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81695636)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816beb3b)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_alloc
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff828fc6ff)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816cfa0f)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff81762236)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffff817948fe)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff817960bd)
Location: arch/x86/include/asm/bitops.h:67
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
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffffffff82902e8b)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8179b8e7)
Location: arch/x86/include/asm/bitops.h:67
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
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8179c3f1)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
```
```
In drivers/net/tun.c (ffffffff8179cde6)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
```
```
In drivers/input/input.c (ffffffff81827293)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff81828dcb)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff81829562)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8182d69e)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8183069c)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/extcon/extcon.c (ffffffff818c8d72)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
```
```
In net/socket.c (ffffffff818d984e)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff818e2b56)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffffffff81903355)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/netlink/af_netlink.c (ffffffff81966b3d)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81982f70)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8198523e)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff8198c505)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81994e0b)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff8199e484)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a1841)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819b1cfd)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff819b7121)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
```
```
In net/unix/af_unix.c (ffffffff819fa2a9)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff819fda44)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a07721)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a45b41)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81a590e9)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/rfkill/input.c (ffffffff81a6658c)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81a7465c)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In lib/idr.c (ffffffff81a7840c)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff81a7ca5e)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81a883c8)
Location: arch/x86/include/asm/bitops.h:67
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In arch/x86/events/core.c (ffffffff8100796b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_pmu_start
```
```
In arch/x86/events/amd/core.c (ffffffff810094b2)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016525)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a133)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101cb41)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102e7ad)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f530)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/kernel/signal.c (ffffffff81031029)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81048ae4)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104df22)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810615e6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b820)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/kernel/kvm.c (ffffffff8107790d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/paravirt.c (ffffffff81078a7d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff81088450)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c5263)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81097853)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/workqueue.c (ffffffff810c2949)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__flush_work
```
```
In kernel/sched/core.c (ffffffff81acf9d8)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/rt.c (ffffffff810ee617)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/debug.c (ffffffff810fcb57)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff811014bf)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/sched/isolation.c (ffffffff828cdc11)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff811228de)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/time/timer.c (ffffffff811341e0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffffffff8114f12f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/events/uprobes.c (ffffffff8121a914)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8122393b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff8123fc21)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/memory.c (ffffffff81262425)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff81273984)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff81ac877b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/swap_state.c (ffffffff8128707d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff81294537)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/ksm.c (ffffffff812a267e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff812a3f13)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812b25f2)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812b8237)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812bbf81)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/cma.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812d22dc)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/pipe.c (ffffffff812e72ef)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
```
In fs/file.c (ffffffff812ff9d3)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
```
```
In fs/dax.c (ffffffff8134957c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff8138e849)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813a1a4c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff813bc070)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff813e49fa)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff81403e49)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff814221bf)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In security/integrity/ima/ima_template.c (ffffffff814ba959)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/scsi_ioctl.c (ffffffff828f4b64)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
```
In block/blk-cgroup.c (ffffffff8150a5c7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8156f0f9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff815f0ac7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff8164a38b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff828fef1b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81674f58)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff81691381)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816b81c6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816e1eeb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_alloc
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff82905699)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f384f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff81786226)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffff817b849e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff817b9a7d)
Location: arch/x86/include/asm/bitops.h:66
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
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffffffff8290c088)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
```
```
In drivers/net/phy/sfp-bus.c (ffffffff817bf397)
Location: arch/x86/include/asm/bitops.h:66
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
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817bfea5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/net/tun.c (ffffffff817c0886)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/input/input.c (ffffffff818587c3)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff8185a33b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff8185aef2)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8185efce)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81861fcc)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/extcon/extcon.c (ffffffff818fb1c2)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
```
```
In net/socket.c (ffffffff8190b82e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81914d36)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffffffff81936105)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/netlink/af_netlink.c (ffffffff8199d5bd)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b97d9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bb32e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff819c2e55)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff819cb95b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff819d4f71)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d84f1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819e8a83)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff819ede21)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a30f29)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff81a34634)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a3e291)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a7c731)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81a8f1f9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffffffff81a9d0ac)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81aaafec)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In lib/idr.c (ffffffff81aaf6cc)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff81ab3d8e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81abf668)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In arch/x86/events/core.c (ffffffff810089db)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_pmu_start
```
```
In arch/x86/events/amd/core.c (ffffffff8100a491)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_alloc_nb
```
```
In arch/x86/events/intel/uncore.c (ffffffff81018a75)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101ba73)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101e1e1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff81030d95)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81031a70)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/signal.c (ffffffff8103396d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:setup_rt_frame
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8104cc14)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810528a8)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810671f6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81071641)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In arch/x86/kernel/kvm.c (ffffffff8107ebfd)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/mm/tlb.c (ffffffff8108ba10)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109c982)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/workqueue.c (ffffffff810c8e02)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/sched/core.c (ffffffff810dde38)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/rt.c (ffffffff810f828d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff811072e7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff8110bcf6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/sched/isolation.c (ffffffff82ceefd5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff8112ef2e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/time/timer.c (ffffffff81145d3d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
```
```
In kernel/smp.c (ffffffff8115f853)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/events/uprobes.c (ffffffff8124730b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/watch_queue.c (ffffffff8124d26e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/filemap.c (ffffffff81251e79)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff8126e48d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/memory.c (ffffffff81291eeb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff812a4c58)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff82cfb4e0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:reserve_bootmem_region
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/swap_state.c (ffffffff812b968c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff812c7927)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/ksm.c (ffffffff812d6d9a)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff812d9a33)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812e7b92)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812e9500)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812f14a7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff81307fff)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c741)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In mm/page_reporting.c (ffffffff8130cf06)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In fs/pipe.c (ffffffff8131ec5f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
```
```
In fs/file.c (ffffffff81338ae5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
```
```
In fs/dax.c (ffffffff8138e8d8)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/ext4/balloc.c (ffffffff813d9c20)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff813edca6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff81407ca4)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff8142ce44)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff81451c99)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff8146e84b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
```
```
In security/integrity/ima/ima_template.c (ffffffff8151aef9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/scsi_ioctl.c (ffffffff81568096)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8156b199)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In lib/idr.c (ffffffff815e9570)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff815ee285)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff815fbb34)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
```
```
In drivers/gpio/gpiolib.c (ffffffff816135bb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff8169cd6e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff816f946b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff82d15fe1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff817259f8)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff81743ada)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8176c2a6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff81796624)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
```
```
In drivers/iommu/amd/init.c (ffffffff82d1c413)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:copy_device_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817aafe1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81837f8c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
```
In drivers/scsi/sr.c (ffffffff8184ad5a)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffff8187f02e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff81880f80)
Location: arch/x86/include/asm/bitops.h:66
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
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffffffff81884e86)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
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
In drivers/net/phy/linkmode.c (ffffffff8188602d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8188846f)
Location: arch/x86/include/asm/bitops.h:66
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
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_quirk_2500basex
```
```
In drivers/net/phy/bcm84881.c (ffffffff818892b1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81889945)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/net/tun.c (ffffffff8188a966)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189f7f7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/input/input.c (ffffffff81929ae1)
Location: arch/x86/include/asm/bitops.h:66
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
In drivers/input/input-mt.c (ffffffff8192cf62)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff8192d724)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81931a7e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/extcon/extcon.c (ffffffff819d2862)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/socket.c (ffffffff819dda1e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff819e6cd6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffffffff81a0ae53)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/skmsg.c (ffffffff81a3c70c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/netlink/af_netlink.c (ffffffff81a79ac2)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ethtool/bitset.c (ffffffff81a8794b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa432b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa622e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81aae569)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81ab890b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81ac198b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac4b82)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ad6d3a)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff81adbc01)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b093c6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/unix/af_unix.c (ffffffff81b25668)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff81b29434)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b32ff2)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b771c4)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81b8b5ef)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffffffff81b98d28)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81ba6f6c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81ba9fbb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_sk_clone
```
```
In net/mptcp/subflow.c (ffffffff81baef28)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:mptcp_sock_destruct
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
In arch/x86/events/core.c (ffffffff81007a8b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_pmu_start
```
```
In arch/x86/events/amd/core.c (ffffffff81009311)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_alloc_nb
```
```
In arch/x86/events/intel/core.c (ffffffff8100ef7d)
Location: arch/x86/include/asm/bitops.h:66
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
In arch/x86/events/intel/uncore.c (ffffffff810191f5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101bf73)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101e721)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff81031b05)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103276c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/signal.c (ffffffff810343dd)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:setup_rt_frame
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8104c074)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051b4c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81065426)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff8106934d)
Location: arch/x86/include/asm/bitops.h:66
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81072c71)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In arch/x86/kernel/kvm.c (ffffffff8107e2ca)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/sev-es.c (ffffffff8108400d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/sev-es.c:vc_handle_exitcode
  - arch/x86/kernel/sev-es.c:vc_handle_exitcode
  - arch/x86/kernel/sev-es.c:vc_handle_exitcode
  - arch/x86/kernel/sev-es.c:vc_handle_exitcode
  - arch/x86/kernel/sev-es.c:vc_handle_vmmcall
  - arch/x86/kernel/sev-es.c:vc_handle_vmmcall
  - arch/x86/kernel/sev-es.c:vc_handle_dr7_write
  - arch/x86/kernel/sev-es.c:vc_do_mmio
  - arch/x86/kernel/sev-es.c:sev_es_ap_hlt_loop
  - arch/x86/kernel/sev-es.c:sev_es_ap_hlt_loop
  - arch/x86/kernel/sev-es.c:sev_es_ap_hlt_loop
  - arch/x86/kernel/sev-es.c:get_jump_table_addr
  - arch/x86/kernel/sev-es.c:get_jump_table_addr
  - arch/x86/kernel/sev-es.c:get_jump_table_addr
  - arch/x86/kernel/sev-es.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev-es.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev-es.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev-es.c:vc_handle_cpuid
  - arch/x86/kernel/sev-es.c:vc_handle_cpuid
  - arch/x86/kernel/sev-es.c:vc_handle_cpuid
  - arch/x86/kernel/sev-es.c:vc_handle_cpuid
  - arch/x86/kernel/sev-es.c:vc_handle_ioio
  - arch/x86/kernel/sev-es.c:vc_handle_ioio
  - arch/x86/kernel/sev-es.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev-es.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev-es.c:sev_es_ghcb_hv_call
```
```
In arch/x86/mm/tlb.c (ffffffff8108ba60)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/workqueue.c (ffffffff810c3f62)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/sched/core.c (ffffffff810da3a8)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/rt.c (ffffffff810f649d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff81105af7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff81108f3c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/sched/membarrier.c:ipi_rseq
```
```
In kernel/sched/isolation.c (ffffffff82fdb6ec)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff8112af0e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/time/timer.c (ffffffff81140a24)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffffffff8115b7f3)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/events/uprobes.c (ffffffff81251987)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/watch_queue.c (ffffffff812576ce)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/filemap.c (ffffffff8125d4cb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff8126a7c1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/shmem.c (ffffffff81278e8f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/memory.c (ffffffff8129c7ab)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffffffff812b0304)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff81c3e42b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:reserve_bootmem_region
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/swap_state.c (ffffffff812c5120)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff812d3497)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/ksm.c (ffffffff812e292a)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff812e4da3)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812f2f82)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812f49a0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812fda07)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff81313d9f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/mapping_dirty_helpers.c (ffffffff81318681)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In mm/page_reporting.c (ffffffff81318e5f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In fs/pipe.c (ffffffff8132a189)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
```
```
In fs/inode.c (ffffffff81340334)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/file.c (ffffffff81344565)
Location: arch/x86/include/asm/bitops.h:66
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
In fs/io_uring.c (ffffffff8138f567)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
```
```
In fs/dax.c (ffffffff813a0037)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/iomap/buffered-io.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff813eb8d0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff814001f6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
```
```
In fs/ext4/mballoc.c (ffffffff8141a6f4)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff81445c44)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff8146e157)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff81488fcb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
```
```
In security/integrity/ima/ima_template.c (ffffffff81537e99)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/scsi_ioctl.c (ffffffff81bf3732)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81585c79)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In lib/idr.c (ffffffff8160e620)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff816129b5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff816206c4)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
```
```
In drivers/gpio/gpiolib.c (ffffffff816384ab)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163a2b2)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff816b9bce)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff8171615b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff83003c93)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff817427e8)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff8175f935)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81786dc6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff817a4e04)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
```
```
In drivers/iommu/amd/init.c (ffffffff8300a232)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:copy_device_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b7441)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff818488a5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
```
In drivers/scsi/sr.c (ffffffff8185b15c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffff8188d8ce)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff8188f6b0)
Location: arch/x86/include/asm/bitops.h:66
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
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffffffff81893909)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
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
In drivers/net/phy/linkmode.c (ffffffff8189448d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8189670f)
Location: arch/x86/include/asm/bitops.h:66
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
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_quirk_ubnt_uf_instant
  - drivers/net/phy/sfp-bus.c:sfp_quirk_2500basex
```
```
In drivers/net/phy/bcm84881.c (ffffffff81897521)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81897bb5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/net/tun.c (ffffffff81898b66)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ae857)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/input/input.c (ffffffff81931051)
Location: arch/x86/include/asm/bitops.h:66
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
In drivers/input/input-mt.c (ffffffff81934386)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff81934af4)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81938cfe)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/extcon/extcon.c (ffffffff819d2442)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/socket.c (ffffffff819dd40e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff819e6506)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffffffff81a0c09f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffffffff81a2ae1e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/core/skmsg.c (ffffffff81a3eddc)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/netlink/af_netlink.c (ffffffff81a8297b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ethtool/bitset.c (ffffffff81a912cb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aae96b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab087e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81ab832d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81ac3c7b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad0512)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ae331a)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff81ae85f1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b17be1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/unix/af_unix.c (ffffffff81b34078)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff81b37d64)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b41912)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b85fa0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81b9a5b9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffffffff81ba89f8)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81bb62ac)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81bb9df9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/subflow.c (ffffffff81bc1ac1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:mptcp_sock_destruct
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
In arch/x86/events/core.c (ffffffff81006ae8)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
```
```
In arch/x86/events/amd/core.c (ffffffff81009d19)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff8100f75b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff81016a79)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101a515)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101d323)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101fc31)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff810218e1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff8103261f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81033561)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81033bbc)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/signal.c (ffffffff81035eef)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8104dbb4)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c292ee)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81065afa)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff81069dea)
Location: arch/x86/include/asm/bitops.h:66
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810733af)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f3e6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/sev.c (ffffffff81084860)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
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
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
```
```
In arch/x86/mm/tlb.c (ffffffff8108c1e0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/workqueue.c (ffffffff810c57de)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/sched/core.c (ffffffff810dc9d4)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/rt.c (ffffffff810f84bd)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/topology.c (ffffffff811032ff)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/sched/debug.c (ffffffff81107a47)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff8110aecc)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/sched/membarrier.c:ipi_rseq
```
```
In kernel/sched/isolation.c (ffffffff831e6446)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff8112b1ac)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/time/timer.c (ffffffff81141af9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffffffff8115c8d5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/events/uprobes.c (ffffffff812557b9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/watch_queue.c (ffffffff8125bb57)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/filemap.c (ffffffff8126014d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff8126f902)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
```
```
In mm/shmem.c (ffffffff8127de3f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/memory.c (ffffffff812a1fc5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffffffff812b5904)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff831f2876)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_range
  - mm/page_alloc.c:reserve_bootmem_region
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/swap_state.c (ffffffff812cbdd5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff812da2de)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/ksm.c (ffffffff812ea0ba)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff812ec98a)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812f9302)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812faf30)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8130477b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff81319f4f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131e873)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In mm/page_reporting.c (ffffffff8131f04c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In fs/pipe.c (ffffffff81330139)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
```
```
In fs/inode.c (ffffffff8134685c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/file.c (ffffffff8134a905)
Location: arch/x86/include/asm/bitops.h:66
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
In fs/io_uring.c (ffffffff8139e92b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
```
```
In fs/dax.c (ffffffff813a75d4)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/iomap/buffered-io.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff813f1e10)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff81406691)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
```
```
In fs/ext4/mballoc.c (ffffffff81420ba3)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff8144b50e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff81473599)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff8148e8d5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
```
```
In security/integrity/ima/ima_template.c (ffffffff81540500)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/scsi_ioctl.c (ffffffff81be569f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8158d009)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In lib/idr.c (ffffffff815f1dfc)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff815f5f3b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81603d05)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
```
```
In drivers/gpio/gpiolib.c (ffffffff8161bfee)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161df24)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff8169baae)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff816f746f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff8320e75e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff817261d8)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff81743795)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8176a726)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff817892dd)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc
```
```
In drivers/iommu/amd/init.c (ffffffff83214d68)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:copy_device_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179b029)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182bc4a)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
```
In drivers/scsi/sr.c (ffffffff8183e14f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffff8187020e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff81871f78)
Location: arch/x86/include/asm/bitops.h:66
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
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffffffff818764f1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
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
In drivers/net/phy/linkmode.c (ffffffff81876d8d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/sfp-bus.c (ffffffff818792db)
Location: arch/x86/include/asm/bitops.h:66
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
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_quirk_ubnt_uf_instant
  - drivers/net/phy/sfp-bus.c:sfp_quirk_2500basex
```
```
In drivers/net/phy/bcm84881.c (ffffffff81879d3c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8187a43f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/net/tun.c (ffffffff8187b2a6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81892e82)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iova_dirty_bitmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/input/input.c (ffffffff819142d1)
Location: arch/x86/include/asm/bitops.h:66
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
In drivers/input/input-mt.c (ffffffff819176f0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff81917e34)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8191c56e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/extcon/extcon.c (ffffffff819b7a44)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/socket.c (ffffffff819c3662)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff819cbf36)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffffffff819f2254)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffffffff81a11ffb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/core/skmsg.c (ffffffff81a4d15c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/netlink/af_netlink.c (ffffffff81a6ba5b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ethtool/bitset.c (ffffffff81a7aace)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/fec.c (ffffffff81a81789)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/fec.c:fec_prepare_data
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a99aeb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9ba5e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81aa3627)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81aaed8b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abb652)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81aca127)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff81ad3881)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b057b1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/unix/af_unix.c (ffffffff81b21bb8)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff81b25a04)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b2f602)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81b54c45)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
```
```
In net/ipv6/ip6mr.c (ffffffff81b74c50)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81b89528)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffffffff81b97998)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81ba661c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81ba91d9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/subflow.c (ffffffff81bb240a)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:mptcp_sock_destruct
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb860c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In net/mptcp/sockopt.c (ffffffff81bbc069)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In arch/x86/events/core.c (ffffffff8100720a)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
```
```
In arch/x86/events/amd/core.c (ffffffff8100adfc)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff8100fc0d)
Location: arch/x86/include/asm/bitops.h:66
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
In arch/x86/events/intel/p4.c (ffffffff810185cd)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101ce83)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81020423)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81023081)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff810254a1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff810377ab)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81038704)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81038f9b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/signal.c (ffffffff8103b170)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81055384)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81d47acb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106fc1a)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff8107447a)
Location: arch/x86/include/asm/bitops.h:66
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8107f843)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In arch/x86/kernel/kvm.c (ffffffff8108e146)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/sev.c (ffffffff81093a20)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:vc_handle_exitcode
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
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:get_jump_table_addr
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:__sev_es_nmi_complete
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
```
```
In arch/x86/mm/tlb.c (ffffffff8109b9ed)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/workqueue.c (ffffffff810d83ca)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/sched/core.c (ffffffff810f14fc)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/rt.c (ffffffff81113a84)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/topology.c (ffffffff81120698)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:asym_cpu_capacity_scan
```
```
In kernel/sched/debug.c (ffffffff81125b37)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff811296fb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/sched/membarrier.c:ipi_rseq
```
```
In kernel/sched/isolation.c (ffffffff832ca542)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff8114bb8c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/time/timer.c (ffffffff811650e9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffffffff81181a4b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff811a3540)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff8126e672)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
```
```
In kernel/events/uprobes.c (ffffffff81291469)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/watch_queue.c (ffffffff81297a02)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/filemap.c (ffffffff8129cadb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/swap.c (ffffffff812aca92)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
```
```
In mm/shmem.c (ffffffff812bfeb9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/memory.c (ffffffff812e308e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffffffff812f7594)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff832d8768)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_range
  - mm/page_alloc.c:reserve_bootmem_region
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/swap_state.c (ffffffff81310f8b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff813211a1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/ksm.c (ffffffff81331fdc)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff81334b57)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/kfence/core.c (ffffffff832dce34)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_pool
```
```
In mm/migrate.c (ffffffff813404e3)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81344d99)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8134e4b0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/secretmem.c (ffffffff8136674c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff81367049)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136bc53)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In mm/page_reporting.c (ffffffff8136c41c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In fs/pipe.c (ffffffff8137d8f6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
```
```
In fs/inode.c (ffffffff81394296)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/file.c (ffffffff813986b5)
Location: arch/x86/include/asm/bitops.h:66
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
In fs/io_uring.c (ffffffff813eec86)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
```
```
In fs/dax.c (ffffffff813f4d2c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/iomap/buffered-io.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff81443e44)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff81458f06)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
```
```
In fs/ext4/mballoc.c (ffffffff81473fa7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff8149f472)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff814ca196)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff814e6345)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
```
```
In security/integrity/ima/ima_template.c (ffffffff8159fd3f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/blk-cgroup.c (ffffffff815f2977)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In lib/idr.c (ffffffff8165f0a9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff81663445)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff8166fee1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/xarray.c:xas_squash_marks
```
```
In drivers/gpio/gpiolib.c (ffffffff8168b50c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168d639)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff81711963)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff81771c0f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff832f74f1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff817a51b8)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff817c43c9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff817ef9c1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff8180f153)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc
```
```
In drivers/iommu/amd/init.c (ffffffff832fe4f6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:copy_device_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81823b59)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b77fe)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
```
In drivers/scsi/sr.c (ffffffff818cac17)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffff819007ee)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (ffffffff81902578)
Location: arch/x86/include/asm/bitops.h:66
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
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffffffff81907101)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
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
In drivers/net/phy/linkmode.c (ffffffff8190799d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8190a13b)
Location: arch/x86/include/asm/bitops.h:66
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
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_quirk_ubnt_uf_instant
  - drivers/net/phy/sfp-bus.c:sfp_quirk_2500basex
```
```
In drivers/net/phy/bcm84881.c (ffffffff8190adc3)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8190b53f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/net/tun.c (ffffffff8190caa6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81925d7f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_populate_bitmap
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/input/input.c (ffffffff819b63c8)
Location: arch/x86/include/asm/bitops.h:66
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
In drivers/input/input-mt.c (ffffffff819b9960)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff819ba0a4)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819bee45)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/extcon/extcon.c (ffffffff81a66892)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/socket.c (ffffffff81a72ef2)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81a7b596)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffffffff81aa4124)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffffffff81acd36c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/core/skmsg.c (ffffffff81b0587e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/netlink/af_netlink.c (ffffffff81b2508b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ethtool/bitset.c (ffffffff81b34eec)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/fec.c (ffffffff81b3b4d0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/fec.c:fec_prepare_data
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b54f58)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b5707e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81b5f7c7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81b6ba6b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b78867)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81b889a7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff81b92525)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc830e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/unix/af_unix.c (ffffffff81be70e8)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff81beb143)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81bf5982)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81c1b505)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
```
```
In net/ipv6/ip6mr.c (ffffffff81c3f55c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81c55638)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffffffff81c642bf)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81c7416c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81c78e39)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
```
In net/mptcp/subflow.c (ffffffff81c8066e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:mptcp_sock_destruct
```
```
In net/mptcp/pm_netlink.c (ffffffff81c883bc)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
```
In net/mptcp/sockopt.c (ffffffff81c8bc09)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
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
In arch/x86/events/core.c (ffffffff81006727)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
```
```
In arch/x86/events/amd/core.c (ffffffff8100a504)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff810111bb)
Location: arch/x86/include/asm/bitops.h:66
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
In arch/x86/events/intel/p4.c (ffffffff8101a77d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101f6a5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff810233a3)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81026a41)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81029381)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff8103d9b8)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8103e98e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff8103ee0b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103fd84)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/signal.c (ffffffff810420f9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff810612c0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81f162fa)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107d4a2)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff81082cda)
Location: arch/x86/include/asm/bitops.h:66
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8108ecc3)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In arch/x86/kernel/kvm.c (ffffffff8109e946)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:kvm_sev_es_hcall_prepare
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/sev.c (ffffffff810a3d20)
Location: arch/x86/include/asm/bitops.h:66
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
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/kernel/sev.c:vc_handle_ioio
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
  - arch/x86/kernel/sev.c:sev_es_ghcb_hv_call
```
```
In arch/x86/mm/tlb.c (ffffffff810ae06f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/workqueue.c (ffffffff810f3111)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/sched/core.c (ffffffff8110d8ec)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/build_policy.c (ffffffff81131129)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:init_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff8347d6e5)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff8117152b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/time/timer.c (ffffffff81198d29)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffffffff811b80a7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff811d4688)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff812bd580)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
```
```
In kernel/events/uprobes.c (ffffffff812e6a57)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/watch_queue.c (ffffffff812edcca)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/filemap.c (ffffffff812f3e21)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:filemap_add_folio
```
```
In mm/swap.c (ffffffff81302f24)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
```
```
In mm/shmem.c (ffffffff8131c797)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/memory.c (ffffffff813439e5)
Location: arch/x86/include/asm/bitops.h:66
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
In mm/rmap.c (ffffffff8135d019)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff8348ccbe)
Location: arch/x86/include/asm/bitops.h:66
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
In mm/swap_state.c (ffffffff8137bdf2)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8138df84)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:__prep_compound_gigantic_page
```
```
In mm/sparse.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/ksm.c (ffffffff813a333e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff813a633b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In mm/kfence/core.c (ffffffff813aef18)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_pool
```
```
In mm/migrate.c (ffffffff813b1f8b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/migrate_device.c (ffffffff813b7e0f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/huge_memory.c (ffffffff813ba0a7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813c4bc4)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/secretmem.c (ffffffff813e3a5c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff813e45b6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9e19)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In mm/page_reporting.c (ffffffff813ea71a)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In fs/pipe.c (ffffffff813fe615)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
```
```
In fs/file.c (ffffffff8141ae0a)
Location: arch/x86/include/asm/bitops.h:66
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
In fs/dax.c (ffffffff814678ad)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/iomap/buffered-io.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff814bfd20)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff814d70e7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff814f601a)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_buddy_mark_free
  - fs/ext4/mballoc.c:mb_set_bits
```
```
In fs/ext4/super.c (ffffffff81525d12)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
  - fs/ext4/super.c:count_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff81555eb5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff81574ecd)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
```
```
In security/integrity/ima/ima_template.c (ffffffff8164593a)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/blk-cgroup.c (ffffffff816a343c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In io_uring/io_uring.c (ffffffff81e8f32f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_register_restrictions
  - io_uring/io_uring.c:io_register_restrictions
  - io_uring/io_uring.c:__io_sqe_files_update
  - io_uring/io_uring.c:io_fixed_fd_install
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In lib/idr.c (ffffffff81778915)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff8177d4ee)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/vsprintf.c (ffffffff8178481f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In lib/xarray.c (ffffffff8178cae4)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
```
```
In drivers/gpio/gpiolib.c (ffffffff817a8812)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817ad013)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff81840a1a)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff818a72dd)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff834afb40)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/grant-table.c (ffffffff818c7191)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:put_free_entry_locked
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff818def16)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff819010d6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8192f756)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_set
```
```
In drivers/iommu/amd/iommu.c (ffffffff8194df64)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc
```
```
In drivers/iommu/amd/init.c (ffffffff834b712d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:copy_device_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81962fd4)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a02f74)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
```
```
In drivers/scsi/sr.c (ffffffff81a17c4e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffff81a525ee)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
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
In drivers/net/phy/phy-c45.c (ffffffff81a54396)
Location: arch/x86/include/asm/bitops.h:66
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
In drivers/net/phy/phy_device.c (ffffffff81a5a380)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
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
In drivers/net/phy/linkmode.c (ffffffff81a5aa1d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81a5d877)
Location: arch/x86/include/asm/bitops.h:66
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
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_quirk_ubnt_uf_instant
  - drivers/net/phy/sfp-bus.c:sfp_quirk_2500basex
```
```
In drivers/net/phy/bcm84881.c (ffffffff81a5e770)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81a5ed6e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/net/tun.c (ffffffff81a61384)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7c834)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_populate_bitmap
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/input/input.c (ffffffff81b15bf7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_copy_abs
  - drivers/input/input.c:input_copy_abs
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff81b19645)
Location: arch/x86/include/asm/bitops.h:66
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
In drivers/input/ff-core.c (ffffffff81b1a0a2)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81b1f0a5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/extcon/extcon.c (ffffffff81bd7da5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
```
```
In net/socket.c (ffffffff81be5773)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81befe83)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamping
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_set_timestamp
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffffffff81c13fef)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:__dev_alloc_name
```
```
In net/core/filter.c (ffffffff81c4ac7f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/core/gro.c (ffffffff81c54300)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/net-sysfs.c (ffffffff81c55bf1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_queue_show
```
```
In net/core/skmsg.c (ffffffff81c8aee7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/netlink/af_netlink.c (ffffffff81cae0ed)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ethtool/bitset.c (ffffffff81cc06da)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/fec.c (ffffffff81cc74c3)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/fec.c:fec_prepare_data
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce2b20)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce4fed)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81cee27f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81cfabdb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_ipv4.c (ffffffff834cc2e1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
```
```
In net/ipv4/raw.c (ffffffff81d15976)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81d19e67)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff834cc958)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_init
```
```
In net/ipv4/ping.c (ffffffff81d439d4)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5dba9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/unix/af_unix.c (ffffffff81d7e719)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff81d83447)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81d8eb39)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_get_saddr_eval
```
```
In net/ipv6/udp.c (ffffffff81db7c34)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_destroy_sock
```
```
In net/ipv6/ip6mr.c (ffffffff81ddda4c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81df53c8)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffffffff81e06fa3)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81e17a1c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81e1d9e9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:mptcp_data_ready
```
```
In net/mptcp/subflow.c (ffffffff81e27dad)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:mptcp_sock_destruct
  - net/mptcp/subflow.c:mptcp_set_connected
```
```
In net/mptcp/pm.c (ffffffff81e2d383)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_mp_prio_received
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2f4fa)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
```
```
In net/mptcp/sockopt.c (ffffffff81e3328c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In net/mptcp/pm_userspace.c (ffffffff81e35284)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
```
```
In net/mctp/af_mctp.c (ffffffff81e37a39)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_pf_create
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
In arch/x86/events/core.c (ffffffff8100642e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
```
```
In arch/x86/events/amd/core.c (ffffffff8100c0de)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff810159db)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
```
```
In arch/x86/events/intel/uncore.c (ffffffff81023ed5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81028913)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102c781)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff8102fd01)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff810467d4)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff810476eb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In arch/x86/hyperv/ivm.c (ffffffff81047ecc)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048cbd)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__cpumask_to_vpset
```
```
In arch/x86/kernel/signal.c (ffffffff8104b195)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8106fc50)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff820bd8c2)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108e9a5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff810957da)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In arch/x86/kernel/kvm.c (ffffffff810b60c6)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/workqueue.c (ffffffff81113436)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/sched/core.c (ffffffff8113460c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/build_policy.c (ffffffff8115b0a0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:init_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff83ea8fce)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff811a7b4b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/time/timer.c (ffffffff811d7269)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffffffff811f9345)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff812186f7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff81320a1d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
```
```
In kernel/events/uprobes.c (ffffffff81350544)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/watch_queue.c (ffffffff813580ca)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/filemap.c (ffffffff8135e11e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:filemap_add_folio
```
```
In mm/swap.c (ffffffff8136debd)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
```
```
In mm/vmscan.c (ffffffff8138744c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
```
```
In mm/shmem.c (ffffffff813903fe)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/memory.c (ffffffff813bba6c)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff83ebe834)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8140cc38)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/ksm.c (ffffffff81422fdb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff8142788f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In mm/kfence/core.c (ffffffff8142f474)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_pool
```
```
In mm/migrate.c (ffffffff81431abd)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/migrate_device.c (ffffffff81439ae6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/huge_memory.c (ffffffff8143c1f7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8144941c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/secretmem.c (ffffffff8146b439)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff8146c28c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/mapping_dirty_helpers.c (ffffffff81471e96)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In mm/page_reporting.c (ffffffff814728aa)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In fs/pipe.c (ffffffff814882b5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
```
```
In fs/file.c (ffffffff814a700a)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/iomap/buffered-io.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff81557d00)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff8156fe6c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
```
```
In fs/ext4/mballoc.c (ffffffff81590392)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff8161a9dc)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In block/blk-cgroup.c (ffffffff817620f8)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In io_uring/io_uring.c (ffffffff81788da1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_register_restrictions
  - io_uring/io_uring.c:io_register_restrictions
```
```
In io_uring/filetable.c (ffffffff8179403e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - io_uring/filetable.c:io_install_fixed_file
```
```
In io_uring/rsrc.c (ffffffff817a1e9b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:__io_sqe_files_update
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff818c12e5)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl_unlocked
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff81977454)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff819f14c2)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff83ee9345)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/grant-table.c (ffffffff81a17d21)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:put_free_entry_locked
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81a326b6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff81a5afd6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81a8db16)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_set
```
```
In drivers/iommu/amd/iommu.c (ffffffff81ab1edb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:domain_id_alloc
```
```
In drivers/iommu/amd/init.c (ffffffff83ef36f8)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:__copy_device_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acbc41)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b818eb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
```
```
In drivers/scsi/sr.c (ffffffff81b98b68)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffff81bdbf35)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81be841b)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81be9bee)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/net/tun.c (ffffffff81bec6cd)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/input/input.c (ffffffff81ca748e)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81cb0f55)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
```
```
In net/socket.c (ffffffff81d92e33)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81d9c423)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:__dev_alloc_name
```
```
In net/core/gro.c (ffffffff81e0987d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/net-sysfs.c (ffffffff81e0b671)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_queue_show
```
```
In net/core/skmsg.c (ffffffff81e46047)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/netlink/af_netlink.c (ffffffff81e669d6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ethtool/bitset.c (ffffffff81e7f32e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/fec.c (ffffffff81e8672d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethtool_fec_to_link_modes
  - net/ethtool/fec.c:ethtool_fec_to_link_modes
  - net/ethtool/fec.c:ethtool_fec_to_link_modes
  - net/ethtool/fec.c:ethtool_fec_to_link_modes
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea4009)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea7c3d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81eb14df)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81ebf71b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_ipv4.c (ffffffff83f0eba1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
```
```
In net/ipv4/raw.c (ffffffff81edc986)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81ee0a47)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff83f0f3f1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_init
```
```
In net/ipv4/ping.c (ffffffff81f0ca14)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f27859)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
```
```
In net/unix/af_unix.c (ffffffff81f4b815)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff81f50ae7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81f5cb19)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_get_saddr_eval
```
```
In net/ipv6/udp.c (ffffffff81f87c54)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81fafbfc)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81fc7d48)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffffffff81fdc3a3)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81fee9cc)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81ffab49)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:mptcp_set_connected
```
```
In net/mptcp/pm.c (ffffffff820057a3)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_mp_prio_received
```
```
In net/mptcp/pm_netlink.c (ffffffff82007c06)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
```
```
In net/mptcp/sockopt.c (ffffffff8200c98c)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
```
```
In net/mctp/af_mctp.c (ffffffff82010c94)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_pf_create
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
```
In lib/idr.c (ffffffff820216b1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff8203a7be)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/vsprintf.c (ffffffff820417e8)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In lib/xarray.c (ffffffff8204771d)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
```
```
In arch/x86/events/amd/core.c (ffffffff8100b88a)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff8101526b)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
```
```
In arch/x86/events/intel/uncore.c (ffffffff81023bf5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81028943)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102c7d1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff8102fdf1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff81046a16)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81047c16)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff8104827c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048f1d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__cpumask_to_vpset
```
```
In arch/x86/kernel/process_64.c (ffffffff8104a3b9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/signal.c (ffffffff8104ba35)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81071853)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8213f36c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81091865)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff8109874a)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In arch/x86/kernel/kvm.c (ffffffff810b91c6)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/workqueue.c (ffffffff8111fa36)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/sched/core.c (ffffffff81143809)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/build_policy.c (ffffffff8116b2a2)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:init_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff836cda8e)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/time/timer.c (ffffffff811ebbc9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffffffff8120e004)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff8122df67)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff813508cd)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
```
```
In kernel/events/uprobes.c (ffffffff81381775)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/watch_queue.c (ffffffff8138995d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/filemap.c (ffffffff81390f24)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:filemap_add_folio
```
```
In mm/swap.c (ffffffff813a00dd)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
```
```
In mm/vmscan.c (ffffffff813b0938)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/shmem.c (ffffffff813c2d4b)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:reserve_bootmem_region
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/memory.c (ffffffff813f0fc0)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/rmap.c:folio_add_new_anon_rmap
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/page_alloc.c (ffffffff8141c043)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/swap_state.c (ffffffff8142c4ef)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8144005b)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/ksm.c (ffffffff81458032)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff8145cdfc)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In mm/kfence/core.c (ffffffff81464661)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_pool
```
```
In mm/migrate.c (ffffffff814676df)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/migrate_device.c (ffffffff8146e80c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/huge_memory.c (ffffffff814715cb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8147f5ff)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/secretmem.c (ffffffff814a021b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff814a1127)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a67d9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In mm/page_reporting.c (ffffffff814a701a)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In fs/pipe.c (ffffffff814bd1bd)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
```
```
In fs/file.c (ffffffff814dbfe7)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/iomap/buffered-io.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff8158fa50)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff815a7cee)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
```
```
In fs/ext4/mballoc.c (ffffffff815c754d)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff816523dc)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In block/blk-cgroup.c (ffffffff817a1ee0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_activate_policy
```
```
In io_uring/io_uring.c (ffffffff817c9770)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_register_restrictions
  - io_uring/io_uring.c:io_register_restrictions
```
```
In io_uring/filetable.c (ffffffff817d4d4f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - io_uring/filetable.c:io_install_fixed_file
```
```
In io_uring/rsrc.c (ffffffff817e300f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:__io_sqe_files_update
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff81904277)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl_unlocked
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff819bde3a)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff81a39b72)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff8370ebf8)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/grant-table.c (ffffffff81a60db1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:put_free_entry_locked
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81a7bf3c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff81aa55bc)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81ad92c6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_set
```
```
In drivers/iommu/amd/iommu.c (ffffffff81afdf8b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:domain_id_alloc
```
```
In drivers/iommu/amd/init.c (ffffffff83719298)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:__copy_device_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b187bf)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd55f1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
```
```
In drivers/scsi/sr.c (ffffffff81bef108)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffff81c33432)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81c407bb)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81c4201e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/net/tun.c (ffffffff81c44ab0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/input/input.c (ffffffff81d0e65e)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81d185b0)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog
```
```
In drivers/extcon/extcon.c (ffffffff81df2687)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
```
```
In net/socket.c (ffffffff81e0122e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81e0ac73)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:__dev_alloc_name
```
```
In net/core/gro.c (ffffffff81e7c048)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/net-sysfs.c (ffffffff81e7ea21)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_queue_show
```
```
In net/core/skmsg.c (ffffffff81ea1723)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/netlink/af_netlink.c (ffffffff81ec2796)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ethtool/bitset.c (ffffffff81edb91e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/fec.c (ffffffff81ee310d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethtool_fec_to_link_modes
  - net/ethtool/fec.c:ethtool_fec_to_link_modes
  - net/ethtool/fec.c:ethtool_fec_to_link_modes
  - net/ethtool/fec.c:ethtool_fec_to_link_modes
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f02859)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f0647d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81f0fb6f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81f1dbf4)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_ipv4.c (ffffffff837351b1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
```
```
In net/ipv4/raw.c (ffffffff81f3bc6d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81f3fcc7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff83735a01)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_init
```
```
In net/ipv4/ping.c (ffffffff81f6c5a1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81fab5bc)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff81fb0457)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81fbc851)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_get_saddr_eval
```
```
In net/ipv6/udp.c (ffffffff81fe8104)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff82010254)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff82028cec)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffffffff82058083)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/xdp/xsk.c (ffffffff8206aafc)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff82072b8c)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:mptcp_set_connected
```
```
In net/mptcp/pm.c (ffffffff82081993)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_mp_prio_received
```
```
In net/mptcp/pm_netlink.c (ffffffff82083f86)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
```
```
In net/mptcp/sockopt.c (ffffffff820892e1)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
```
```
In net/mctp/af_mctp.c (ffffffff8208d504)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_pf_create
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
```
In lib/idr.c (ffffffff820a16f7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff820b8c2e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/vsprintf.c (ffffffff820bfde4)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In lib/xarray.c (ffffffff820c5dba)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
```
```
In arch/x86/events/amd/core.c (ffffffff8101106c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff8101abf7)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
```
```
In arch/x86/events/intel/uncore.c (ffffffff81029d25)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8102eaa3)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81032931)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81036091)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff8104d226)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8104e37f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
```
```
In arch/x86/hyperv/ivm.c (ffffffff8104ec5c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_read
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
  - arch/x86/hyperv/ivm.c:hv_ghcb_msr_write
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8105018d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__cpumask_to_vpset
```
```
In arch/x86/kernel/process_64.c (ffffffff81051619)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
```
```
In arch/x86/kernel/signal.c (ffffffff81052cb5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81079073)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8222138c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81086a70)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:mce_track_storm
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81098c35)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff8109fcea)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:hv_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/mshyperv.c:hv_sev_es_hcall_prepare
  - arch/x86/kernel/cpu/mshyperv.c:hv_sev_es_hcall_prepare
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810ad4e6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In arch/x86/kernel/kvm.c (ffffffff810c0606)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/workqueue.c (ffffffff81129f86)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/sched/core.c (ffffffff8114ed29)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/build_policy.c (ffffffff81178c37)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:init_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff838feecc)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/time/timer.c (ffffffff81201714)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffffffff81225794)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff81247d8e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff81377cfd)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
```
```
In kernel/events/uprobes.c (ffffffff813aab07)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/watch_queue.c (ffffffff813b33ad)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In mm/filemap.c (ffffffff813bac6f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_get_folio
  - mm/filemap.c:filemap_add_folio
```
```
In mm/swap.c (ffffffff813c9d5d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
```
```
In mm/vmscan.c (ffffffff813d9e48)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/shmem.c (ffffffff813ed9c3)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:reserve_bootmem_region
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/memory.c (ffffffff8141bd1a)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/rmap.c:folio_add_new_anon_rmap
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/page_alloc.c (ffffffff81448bb3)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/slub.c (ffffffff81457518)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In mm/swap_state.c (ffffffff81465c27)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff81479f69)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/ksm.c (ffffffff814929c7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/kfence/core.c (ffffffff81493e1f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/migrate.c (ffffffff81496b9c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/migrate_device.c (ffffffff8149d270)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
```
```
In mm/huge_memory.c (ffffffff814a1f85)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814ad62b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/secretmem.c (ffffffff814cf8a2)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff814d08b7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d7860)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In mm/page_reporting.c (ffffffff814d801a)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In fs/pipe.c (ffffffff814ef65a)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
```
```
In fs/file.c (ffffffff8150e207)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/iomap/buffered-io.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff815c85d2)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/balloc.c:ext4_init_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff815e0afe)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
```
```
In fs/ext4/mballoc.c (ffffffff815fdd3d)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff8168b9ec)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In block/blk-cgroup.c (ffffffff817e5a2d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_activate_policy
```
```
In io_uring/filetable.c (ffffffff81818b6c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - io_uring/filetable.c:io_install_fixed_file
```
```
In io_uring/rsrc.c (ffffffff818270e9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:__io_sqe_files_update
```
```
In io_uring/register.c (ffffffff8182b100)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - io_uring/register.c:io_register_restrictions
  - io_uring/register.c:io_register_restrictions
```
```
In lib/bitmap-str.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8194bc9a)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl
```
```
In drivers/pci/pci.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff81a0870a)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff81a853f2)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff839423c8)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/grant-table.c (ffffffff81ab35e1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:put_free_entry_locked
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81ace3ec)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff81af800c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81b2c5b6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_set
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b57452)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
```
```
In drivers/iommu/amd/init.c (ffffffff8394cd98)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:__copy_device_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6e0ff)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
```
```
In drivers/iommu/iommufd/iova_bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c198cb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:timeline_fence_set_deadline
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c2a249)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
```
```
In drivers/scsi/sr.c (ffffffff81c448a7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/gpu/drm/drm_edid.c (ffffffff81c93995)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_edid.c:drm_parse_cea_ext
  - drivers/gpu/drm/drm_edid.c:drm_parse_cea_ext
```
```
In drivers/gpu/drm/drm_mm.c (ffffffff81ca0d13)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mm.c:drm_mm_scan_add_block
  - drivers/gpu/drm/drm_mm.c:drm_mm_replace_node
  - drivers/gpu/drm/drm_mm.c:drm_mm_insert_node_in_range
  - drivers/gpu/drm/drm_mm.c:drm_mm_reserve_node
```
```
In drivers/net/phy/phy.c (ffffffff81ce8122)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_set_pause
  - drivers/net/phy/linkmode.c:linkmode_set_pause
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81cf5e1b)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/net/tun.c (ffffffff81cfa610)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_xdp
  - drivers/net/tun.c:tun_xdp
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/input/input.c (ffffffff81dc42ae)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81dce260)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/hid/bpf/hid_bpf_jmp_table.c (ffffffff81e8f1c1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog
```
```
In drivers/extcon/extcon.c (ffffffff81ea8cd7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
```
```
In net/socket.c (ffffffff81ebd92e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81ec7663)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/dev.c:__dev_alloc_name
  - net/core/dev.c:__dev_alloc_name
```
```
In net/core/gro.c (ffffffff81f3c398)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/net-sysfs.c (ffffffff81f3f92e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_queue_show
```
```
In net/core/skmsg.c (ffffffff81f63f23)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/netlink/af_netlink.c (ffffffff81f85ae6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ethtool/common.c (ffffffff81f9c451)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ethtool/common.c:ethtool_forced_speed_maps_init
```
```
In net/ethtool/bitset.c (ffffffff81f9f6e5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/fec.c (ffffffff81fa6eed)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethtool_fec_to_link_modes
  - net/ethtool/fec.c:ethtool_fec_to_link_modes
  - net/ethtool/fec.c:ethtool_fec_to_link_modes
  - net/ethtool/fec.c:ethtool_fec_to_link_modes
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc6cae)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fca76d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81fd3d5f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81fe22c4)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
```
```
In net/ipv4/tcp_ipv4.c (ffffffff83969771)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
```
```
In net/ipv4/raw.c (ffffffff82001d8d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff82005987)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff8396a071)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_init
```
```
In net/ipv4/ping.c (ffffffff82032cf1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff820789ac)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff8207dab7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff82089c71)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_get_saddr_eval
```
```
In net/ipv6/udp.c (ffffffff820b6344)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff820df1e4)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff820f872c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffffffff8212ab93)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/xdp/xsk.c (ffffffff8213e20c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff8214b8a0)
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
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
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:fill_remote_addresses_vec
  - net/mptcp/pm_netlink.c:fill_remote_addresses_vec
```
```
In net/mptcp/sockopt.c (ffffffff8215f061)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In net/mptcp/pm_userspace.c (ffffffff821603b7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
```
```
In net/mctp/af_mctp.c (ffffffff821639c4)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_pf_create
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
```
In lib/idr.c (ffffffff8217971f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff8219353e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/vsprintf.c (ffffffff82199ddc)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
```
```
In lib/xarray.c (ffffffff821a073a)
Location: arch/x86/include/asm/bitops.h:66
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100796b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_pmu_start
```
```
In arch/x86/events/amd/core.c (ffffffff810094b2)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016525)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a133)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101cb41)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102e90d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f690)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/kernel/signal.c (ffffffff81031189)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81048c54)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e082)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81061166)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b310)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/kernel/kvm.c (ffffffff8107690d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077a7d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff81087450)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b01fb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/workqueue.c (ffffffff810bccb9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__flush_work
```
```
In kernel/sched/core.c (ffffffff81a6e848)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/rt.c (ffffffff810e84d8)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff810f5e87)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff810fa7cf)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/sched/isolation.c (ffffffff828b69a1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff8111aebe)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/time/timer.c (ffffffff8112c990)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffffffff8114774f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/events/uprobes.c (ffffffff81212f64)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8121bf8b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff81238271)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/memory.c (ffffffff8125aa75)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff8126bfd4)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff81a675eb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/swap_state.c (ffffffff8127f6cd)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8128cb17)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/ksm.c (ffffffff8129ac5e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff8129c4f3)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812aabd2)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812b0817)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b4561)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/cma.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812ca8bc)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/pipe.c (ffffffff812df8cf)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
```
In fs/file.c (ffffffff812f7fb3)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
```
```
In fs/dax.c (ffffffff81341b5c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff81386e29)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8139a02c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff813b4650)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff813dcfda)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff813fc429)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff8141a79f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In security/integrity/ima/ima_template.c (ffffffff814b2f39)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/scsi_ioctl.c (ffffffff828dda18)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
```
In block/blk-cgroup.c (ffffffff81502ba7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff815648b9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff815df757)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff816103eb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff828e6793)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff8163ac48)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff81656e01)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8167dc26)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816a793b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_alloc
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff828ece80)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b903f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff8173a916)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffff8177cf6e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff8177e54d)
Location: arch/x86/include/asm/bitops.h:66
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
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffffffff828f3a45)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81783e67)
Location: arch/x86/include/asm/bitops.h:66
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
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81784975)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/net/tun.c (ffffffff81785356)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/input/input.c (ffffffff8180d7d3)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff8180f34b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff8180ff02)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81813fde)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/extcon/extcon.c (ffffffff8189c4f2)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
```
```
In net/socket.c (ffffffff818ab82e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff818b4d36)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffffffff818d60d5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/netlink/af_netlink.c (ffffffff8193d42d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81959649)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195b19e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff81962cc5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff8196b7cb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81974de1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81978361)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819888f3)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff8198dbc1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/unix/af_unix.c (ffffffff819d05b9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff819d3cc4)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff819dd921)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a1bdc1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81a2e889)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffffffff81a3c43c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81a4a37c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In lib/idr.c (ffffffff81a4e51c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff81a52bde)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81a5e4b8)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In arch/x86/events/core.c (ffffffff8100613b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_pmu_start
```
```
In arch/x86/events/amd/core.c (ffffffff81007c42)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015955)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81019893)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101c231)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff8101e55d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8101ed19)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/signal.c (ffffffff81020ba9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81037fe4)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103d552)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810515c6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105b649)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/kernel/kvm.c (ffffffff810668dd)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106775d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff81076016)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a83e8)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/workqueue.c (ffffffff810ab509)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__flush_work
```
```
In kernel/sched/core.c (ffffffff81a2ac41)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/rt.c (ffffffff810d79d7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/debug.c (ffffffff810e6047)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff810ea9af)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/sched/isolation.c (ffffffff828aeb97)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff8110bf2e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/time/timer.c (ffffffff8111f200)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffffffff8113a9ff)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/events/uprobes.c (ffffffff81205cd4)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8120f17b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff8122b2ad)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/memory.c (ffffffff8124ce40)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff8125e044)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff81a240ab)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/swap_state.c (ffffffff812714ed)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8127e937)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/ksm.c (ffffffff8128c81e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff8128e0a0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff8129c52f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812a1a95)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812a55e0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/cma.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812bb843)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/pipe.c (ffffffff812d050f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
```
In fs/file.c (ffffffff812e8bd3)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
```
```
In fs/dax.c (ffffffff813324e1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff813778b9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8138aabc)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff813a50e0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff813cda5a)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff813ecea9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff8140b21f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In security/integrity/ima/ima_template.c (ffffffff814a3959)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/scsi_ioctl.c (ffffffff828d6134)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
```
In block/blk-cgroup.c (ffffffff814f2da7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff81555709)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pci/pci.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff815cad77)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff8160493b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff828def88)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/tty/sysrq.c (ffffffff81637191)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8165cd16)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff8168532b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_alloc
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff828e430d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696c7f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff8171c5b6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffff8175cd1e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff8175e2ed)
Location: arch/x86/include/asm/bitops.h:66
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
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffffffff828eaef0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
```
```
In drivers/net/phy/sfp-bus.c (ffffffff817637b7)
Location: arch/x86/include/asm/bitops.h:66
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
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817642c5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/net/tun.c (ffffffff81764ca6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In drivers/input/input.c (ffffffff817d4f43)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff817d6a9b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff817d7652)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817db70e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In net/socket.c (ffffffff8186577e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff8186ec86)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffffffff8188ff15)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/netlink/af_netlink.c (ffffffff818f6f2d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81913139)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81914c8e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff8191c7b5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff819252bb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff8192e8a1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81931e21)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819423b3)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff81947681)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8198d379)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff81990a84)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8199a6e1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d8b81)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff819eba79)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffffffff819f905c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81a06f6c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In lib/idr.c (ffffffff81a0b60c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff81a0fcde)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81a1b588)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In arch/x86/events/core.c (ffffffff8100792b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_pmu_start
```
```
In arch/x86/events/amd/core.c (ffffffff81009472)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/uncore.c (ffffffff810164e5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a0f3)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101cb01)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102e76d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f4f0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/kernel/signal.c (ffffffff81030fe9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81048a94)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ded2)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81061596)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b7c0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/kernel/kvm.c (ffffffff810768bd)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077a2d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff81087400)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c30fa)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/workqueue.c (ffffffff810bc219)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__flush_work
```
```
In kernel/sched/core.c (ffffffff81adac58)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/rt.c (ffffffff810e4b47)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/debug.c (ffffffff810f3087)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff810f798f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/sched/isolation.c (ffffffff828c9845)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff81118dae)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/time/timer.c (ffffffff8112a6b0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffffffff811455ff)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/events/uprobes.c (ffffffff81210d04)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff81219d2b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff81236011)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/memory.c (ffffffff81258815)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff81269d74)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff81ad39fb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/swap_state.c (ffffffff8127d46d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8128a927)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/ksm.c (ffffffff81298a6e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff8129a303)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812a89e2)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812ae627)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b2371)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/cma.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812c86cc)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/pipe.c (ffffffff812dd6df)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
```
In fs/file.c (ffffffff812f5dc3)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
```
```
In fs/dax.c (ffffffff8133f62c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff813848f9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8139788c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff813b1eb0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff813da47a)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff813f97a9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff8141693f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In security/integrity/ima/ima_template.c (ffffffff814aefc9)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/scsi_ioctl.c (ffffffff828f078c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
```
In block/blk-cgroup.c (ffffffff814fec37)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff81563429)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff815e4da7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff8163e1cb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff828fa23e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81668d98)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff816851c1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816ac006)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d5bab)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_alloc
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff829009bc)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e750f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff8177b0a6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffff817ad31e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff817ae8fd)
Location: arch/x86/include/asm/bitops.h:66
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
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffffffff82907483)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
```
```
In drivers/net/phy/sfp-bus.c (ffffffff817b4217)
Location: arch/x86/include/asm/bitops.h:66
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
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817b4d25)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/net/tun.c (ffffffff817b5706)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/input/input.c (ffffffff8184c953)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff8184e4cb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff8184f082)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8185315e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8185615c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/extcon/extcon.c (ffffffff818ebbe2)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
```
```
In net/socket.c (ffffffff818fc82e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81905d36)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffffffff81927105)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/netlink/af_netlink.c (ffffffff8198e5bd)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199eebe)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819ae0a1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_create_conntrack
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c3e19)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c596e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff819cd495)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff819d5f9b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff819df5b1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e2b31)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f30c3)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff819f8461)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a3b039)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff81a3e744)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a483a1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a86841)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81a9a439)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffffffff81aa82ec)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81ab622c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In lib/idr.c (ffffffff81aba90c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff81abefce)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81aca8a8)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In arch/x86/events/core.c (ffffffff81007a8b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_pmu_start
```
```
In arch/x86/events/amd/core.c (ffffffff810095d2)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016725)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a333)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101cd41)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_m2m_uncore_pci_init_box
  - arch/x86/events/intel/uncore_snbep.c:skx_upi_uncore_pci_init_box
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102f55d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81030330)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/kernel/signal.c (ffffffff81031e80)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/ioport.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81049ea4)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104f312)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81062b46)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_remove
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106cec0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/kernel/kvm.c (ffffffff81078a1d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/paravirt.c (ffffffff81079acd)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff81089530)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c62a0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81098d23)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/workqueue.c (ffffffff810c331b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__flush_work
```
```
In kernel/sched/core.c (ffffffff81ae710a)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/rt.c (ffffffff810f1238)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/debug.c (ffffffff810fe087)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff81102a9c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/sched/isolation.c (ffffffff828cebf7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff8112443e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In kernel/time/timer.c (ffffffff81137c90)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/smp.c (ffffffff811521f6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/events/uprobes.c (ffffffff8121fc1c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff81228e2b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff812462f1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/memory.c (ffffffff8126822f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff812796e4)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff81adfef5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/swap_state.c (ffffffff8128d043)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff8129a71d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:prep_compound_gigantic_page
```
```
In mm/sparse.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/ksm.c (ffffffff812a884d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff812aa1e3)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812b8d02)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812be984)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812c2778)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/cma.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812d9370)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/pipe.c (ffffffff812ee65f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
```
In fs/file.c (ffffffff81306ee7)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:do_dup2
  - fs/file.c:set_close_on_exec
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
  - fs/file.c:__alloc_fd
```
```
In fs/dax.c (ffffffff81352ff3)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff81398474)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813ac158)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/mballoc.c (ffffffff813c69f0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_mark_used
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_set_bits
```
```
In fs/ext4/super.c (ffffffff813ef75a)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ext4/super.c:ext4_calculate_overhead
```
```
In fs/hugetlbfs/inode.c (ffffffff8140f404)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/fuse/dev.c (ffffffff8142d69f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In security/integrity/ima/ima_template.c (ffffffff814c7a49)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/scsi_ioctl.c (ffffffff828f5bb8)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
  - block/scsi_ioctl.c:blk_scsi_ioctl_init
```
```
In block/blk-cgroup.c (ffffffff81517a07)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In lib/iommu-helper.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffff8157d349)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/pwm/core.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff815fec57)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/pnp/quirks.c (ffffffff8165851b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff828fff6f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81683358)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
```
In drivers/tty/sysrq.c (ffffffff8169f7c1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816c6466)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816ece6d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:domain_id_alloc
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff829066fb)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81701c0f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff81794c0f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/net/phy/phy.c (ffffffff817c72ae)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff817c888d)
Location: arch/x86/include/asm/bitops.h:66
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
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffffffff8290d0ea)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_set_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:phy_advertise_supported
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
  - drivers/net/phy/phy_device.c:genphy_read_abilities
```
```
In drivers/net/phy/sfp-bus.c (ffffffff817ce1e7)
Location: arch/x86/include/asm/bitops.h:66
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
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
  - drivers/net/phy/sfp-bus.c:sfp_parse_port
```
```
In drivers/net/phy/fixed_phy.c (ffffffff817cecf5)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/net/tun.c (ffffffff817cf8e6)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_attach
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/input/input.c (ffffffff81867c43)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_default_setkeycode
  - drivers/input/input.c:input_set_abs_params
  - drivers/input/input.c:input_set_abs_params
```
```
In drivers/input/input-mt.c (ffffffff8186969b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In drivers/input/ff-core.c (ffffffff8186a232)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8186e3ae)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8187128c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/extcon/extcon.c (ffffffff8190cc62)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
  - drivers/extcon/extcon.c:extcon_set_property_capability
```
```
In net/socket.c (ffffffff8191d82e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/socket.c:sock_fasync
```
```
In net/core/sock.c (ffffffff81926d66)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_enable_timestamp
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_set_memalloc
```
```
In net/core/dev.c (ffffffff81948774)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/netlink/af_netlink.c (ffffffff819b0e6d)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_socket_mc
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cd86f)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cf44e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
```
```
In net/ipv4/tcp.c (ffffffff819d7025)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff819dfb9b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff819e9261)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ecc51)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819fb98e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_lport_inuse
```
```
In net/ipv4/icmp.c (ffffffff81a02781)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a48817)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/unix/garbage.c (ffffffff81a4a204)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/af_inet6.c (0)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a542d1)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a93401)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81aa717b)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/rfkill/input.c (ffffffff81ab484c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81ac234c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In lib/idr.c (ffffffff81ac6d5c)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/radix-tree.c (ffffffff81acb49e)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_extend
```
```
In lib/xarray.c (ffffffff81ad6e78)
Location: arch/x86/include/asm/bitops.h:66
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
```
</details>
</li>
</ul>

## Differences
