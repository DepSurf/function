# Function: <code>mmap_read_unlock</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81087a6a)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area
```
```
In kernel/exit.c (ffffffff810adf2d)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff810c2c21)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/sched/fair.c (ffffffff810e9acf)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex.c (ffffffff8115c6a6)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:fixup_pi_state_owner
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
```
```
In kernel/acct.c (ffffffff811697e9)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff811c6669)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
```
```
In kernel/events/core.c (ffffffff812327e2)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff81247027)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In mm/filemap.c (ffffffff812534ae)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
```
```
In mm/oom_kill.c (ffffffff812571f5)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reap_task_mm
```
```
In mm/shmem.c (ffffffff81271151)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/gup.c (ffffffff81289f0e)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:__mm_populate
```
```
In mm/memory.c (ffffffff8129560e)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mincore.c (ffffffff8129621f)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mmap.c (ffffffff8129bbec)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mremap.c (ffffffff812a1294)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff812a15d5)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff812acdc6)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - mm/process_vm_access.c:process_vm_rw_single_vec
```
```
In mm/madvise.c (ffffffff812b5a49)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - mm/madvise.c:madvise_remove
  - mm/madvise.c:madvise_willneed
```
```
In mm/swapfile.c (ffffffff812be466)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff812cdec8)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:lookup_node
```
```
In mm/ksm.c (ffffffff812d591c)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff812e23be)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/khugepaged.c (ffffffff812f3be6)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff812f9f51)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/userfaultfd.c (ffffffff813090c7)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/frame_vector.c (ffffffff81309b21)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
```
In mm/ptdump.c (ffffffff8130cdbc)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff8131dd1e)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
```
```
In fs/userfaultfd.c (ffffffff81374af8)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/io_uring.c (ffffffff8137f4f1)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/proc/task_mmu.c (ffffffff813b684a)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff813bf52f)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In drivers/iommu/intel/svm.c (ffffffff817a97cd)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189e17a)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a2980)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
```
In net/ipv4/tcp.c (ffffffff81aa9a4b)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff81ba831f)
Location: include/linux/mmap_lock.h:59
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_pin_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void mmap_read_unlock(struct mm_struct *mm);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004c19)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810678b5)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81067ddd)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/mm/fault.c (ffffffff81088183)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area
```
```
In kernel/exit.c (ffffffff810a73d0)
Location: include/linux/mmap_lock.h:141
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff810be008)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/sched/fair.c (ffffffff810e7915)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex.c (ffffffff81156cf4)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/futex.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff81165f3a)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff811c3b48)
Location: include/linux/mmap_lock.h:141
Inline: True
```
```
In kernel/events/core.c (ffffffff8123c3e7)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff81251674)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In mm/filemap.c (ffffffff8125e0bb)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
```
```
In mm/oom_kill.c (ffffffff81261de3)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reap_task_mm
```
```
In mm/shmem.c (ffffffff8127a63c)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/gup.c (ffffffff81293c02)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:get_dump_page
  - mm/gup.c:get_dump_page
  - mm/gup.c:__mm_populate
```
```
In mm/memory.c (ffffffff812a04e7)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mincore.c (ffffffff812a0f97)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mmap.c (ffffffff812a6e84)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mremap.c (ffffffff812acacc)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff812ace11)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff812b89e1)
Location: include/linux/mmap_lock.h:141
Inline: True
```
```
In mm/madvise.c (ffffffff812c0f25)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/madvise.c:madvise_remove
```
```
In mm/swapfile.c (ffffffff812c9c2c)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff812d984f)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:lookup_node
Direct callers:
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/ksm.c (ffffffff812e13bc)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff812ed65f)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat_array
  - mm/migrate.c:add_page_for_migration
```
```
In mm/khugepaged.c (ffffffff812ff373)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff8130540b)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_count_precharge
```
```
In mm/userfaultfd.c (ffffffff81314f31)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/frame_vector.c (ffffffff813157d5)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
```
In mm/ptdump.c (ffffffff81318cff)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff813291db)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
```
```
In fs/userfaultfd.c (ffffffff813829a8)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/io_uring.c (ffffffff8138d9ad)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/binfmt_elf.c (ffffffff813b09be)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff813b34be)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/proc/task_mmu.c (ffffffff813c87be)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff813d1352)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In drivers/iommu/intel/svm.c (ffffffff817b5bb6)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ad496)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b269f)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
```
In net/ipv4/tcp.c (ffffffff81ab70be)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff81bb8072)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_pin_pages
```
**Symbols:**

```
ffffffff810a73d0-ffffffff810a73f7: mmap_read_unlock (STB_LOCAL)
ffffffff812d76e0-ffffffff812d770d: mmap_read_unlock (STB_LOCAL)
ffffffff81313b30-ffffffff81313b5d: mmap_read_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void mmap_read_unlock(struct mm_struct *mm);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004c06)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81067a07)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8106834a)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff810699f4)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
```
In arch/x86/mm/fault.c (ffffffff81088c4b)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area
```
```
In kernel/exit.c (ffffffff810a8460)
Location: include/linux/mmap_lock.h:141
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff810bf9ad)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/sched/fair.c (ffffffff810e97e2)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex.c (ffffffff81158101)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/futex.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff81166c67)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff811c4c55)
Location: include/linux/mmap_lock.h:141
Inline: True
```
```
In kernel/bpf/task_iter.c (ffffffff8121bcc7)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_stop
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In kernel/events/core.c (ffffffff81240a34)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff81257872)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handler_chain
```
```
In mm/filemap.c (ffffffff81260d79)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
```
```
In mm/oom_kill.c (ffffffff81266921)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/shmem.c (ffffffff8127f77c)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/gup.c (ffffffff8129959c)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:get_dump_page
  - mm/gup.c:get_dump_page
  - mm/gup.c:__mm_populate
```
```
In mm/memory.c (ffffffff812a5e24)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mincore.c (ffffffff812a669d)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mmap.c (ffffffff812ab99e)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mremap.c (ffffffff812b1c5a)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff812b20fa)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff812bdeab)
Location: include/linux/mmap_lock.h:141
Inline: True
```
```
In mm/madvise.c (ffffffff812c8143)
Location: include/linux/mmap_lock.h:141
Inline: True
```
```
In mm/swapfile.c (ffffffff812d0b03)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff812e10ce)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
Direct callers:
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/ksm.c (ffffffff812e8ad1)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff812f3976)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff8130072c)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff81305ff0)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff8130ace8)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/userfaultfd.c (ffffffff8131b66e)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
Direct callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/ptdump.c (ffffffff8131eeec)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff8132efe8)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
```
```
In fs/userfaultfd.c (ffffffff81389a28)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/io_uring.c (ffffffff81391a05)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/binfmt_elf.c (ffffffff813b7b00)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff813ba4ab)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/proc/task_mmu.c (ffffffff813cf7f2)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff813d824f)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In drivers/iommu/intel/svm.c (ffffffff81798f15)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81890628)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818959bc)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
```
In net/ipv4/tcp.c (ffffffff81aa22ba)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff81ba723f)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_pin_pages
```
**Symbols:**

```
ffffffff810a8460-ffffffff810a8487: mmap_read_unlock (STB_LOCAL)
ffffffff812ded50-ffffffff812ded7d: mmap_read_unlock (STB_LOCAL)
ffffffff81319cd0-ffffffff81319cfd: mmap_read_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void mmap_read_unlock(struct mm_struct *mm);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81005230)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81071e01)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810727ca)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff810740ff)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
```
In arch/x86/mm/fault.c (ffffffff81098081)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area
```
```
In kernel/fork.c (ffffffff810b32ed)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:replace_mm_exe_file
```
```
In kernel/exit.c (ffffffff810b9f10)
Location: include/linux/mmap_lock.h:141
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff810d242d)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/sched/fair.c (ffffffff81101072)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex.c (ffffffff8117d028)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/futex.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff8118c427)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff811f0195)
Location: include/linux/mmap_lock.h:141
Inline: True
```
```
In kernel/bpf/task_iter.c (ffffffff81252bc7)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_stop
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In kernel/bpf/stackmap.c (ffffffff81271a10)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/bpf/stackmap.c:do_up_read
```
```
In kernel/events/core.c (ffffffff8127b49f)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff81293345)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handler_chain
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In mm/filemap.c (ffffffff8129d7dc)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
```
```
In mm/oom_kill.c (ffffffff812a3244)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_reaper
```
```
In mm/shmem.c (ffffffff812bda33)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/gup.c (ffffffff812d9edf)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:get_dump_page
  - mm/gup.c:get_dump_page
  - mm/gup.c:__mm_populate
```
```
In mm/memory.c (ffffffff812e72ae)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mincore.c (ffffffff812e7b6d)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mmap.c (ffffffff812ed095)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mremap.c (ffffffff812f3829)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff812f3ce9)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff8130065b)
Location: include/linux/mmap_lock.h:141
Inline: True
```
```
In mm/madvise.c (ffffffff8130d122)
Location: include/linux/mmap_lock.h:141
Inline: True
```
```
In mm/swapfile.c (ffffffff813161de)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff8132839e)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:lookup_node
Direct callers:
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/sparse-vmemmap.c (ffffffff8132c8e3)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_remap_alloc
  - mm/sparse-vmemmap.c:vmemmap_remap_free
```
```
In mm/ksm.c (ffffffff81330a01)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff8133df6d)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff8134a3c9)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff8134fe56)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff81353402)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/memory-failure.c (ffffffff81cc2fdd)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In mm/userfaultfd.c (ffffffff8136893d)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
Direct callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/ptdump.c (ffffffff8136c2c6)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff8137c7d8)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
  - fs/exec.c:get_arg_page
```
```
In fs/userfaultfd.c (ffffffff813d6d08)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/io_uring.c (ffffffff813df910)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/binfmt_elf.c (ffffffff814077f4)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8140a1aa)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/proc/task_mmu.c (ffffffff81420bce)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff81429984)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In security/tomoyo/domain.c (ffffffff81565114)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In drivers/iommu/io-pgfault.c (ffffffff8182ff10)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - drivers/iommu/io-pgfault.c:iopf_handle_single
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8192420c)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff8192992c)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
```
```
In net/ipv4/tcp.c (ffffffff81b5e14a)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff81c74fbd)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
**Symbols:**

```
ffffffff810b9f10-ffffffff810b9f2f: mmap_read_unlock (STB_LOCAL)
ffffffff81326720-ffffffff8132674f: mmap_read_unlock (STB_LOCAL)
ffffffff81366a90-ffffffff81366abf: mmap_read_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void mmap_read_unlock(struct mm_struct *mm);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004293)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8108015c)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81080aad)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81082637)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
```
In arch/x86/mm/fault.c (ffffffff810aacbd)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area
```
```
In kernel/fork.c (ffffffff810c950d)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:replace_mm_exe_file
```
```
In kernel/exit.c (ffffffff810d2c9a)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff810ea6df)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/sched/fair.c (ffffffff8111c79e)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex/core.c (ffffffff811b2bf6)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/futex/core.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff811bb96e)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff812287a6)
Location: include/linux/mmap_lock.h:141
Inline: True
```
```
In kernel/bpf/task_iter.c (ffffffff8129a78e)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:do_mmap_read_unlock
  - kernel/bpf/task_iter.c:bpf_find_vma
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In kernel/bpf/stackmap.c (ffffffff812c0b8b)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff812cf2a7)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff812e8e22)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handler_chain
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In mm/filemap.c (ffffffff812f4893)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:__folio_lock_or_retry
```
```
In mm/oom_kill.c (ffffffff812fb10e)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_reaper
```
```
In mm/shmem.c (ffffffff813197a6)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/gup.c (ffffffff8133b291)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:get_dump_page
  - mm/gup.c:get_dump_page
  - mm/gup.c:fault_in_safe_writeable
  - mm/gup.c:__mm_populate
```
```
In mm/memory.c (ffffffff8134854f)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mincore.c (ffffffff81348de5)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mmap.c (ffffffff81350418)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mremap.c (ffffffff8135775e)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff81357b16)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff813679fb)
Location: include/linux/mmap_lock.h:141
Inline: True
```
```
In mm/madvise.c (ffffffff81378b59)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/swapfile.c (ffffffff8138136a)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff81397615)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
Direct callers:
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/sparse-vmemmap.c (ffffffff8139c953)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_remap_alloc
  - mm/sparse-vmemmap.c:vmemmap_remap_free
```
```
In mm/ksm.c (ffffffff813a1622)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff813b14e8)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff813c0f59)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff813c8072)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff813cdf32)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_can_attach
```
```
In mm/memory-failure.c (ffffffff81e754e7)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In mm/userfaultfd.c (ffffffff813e625c)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
Direct callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/ptdump.c (ffffffff813ea5a9)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff813fa879)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:get_arg_page
```
```
In fs/userfaultfd.c (ffffffff81460669)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/binfmt_elf.c (ffffffff8147c513)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8147eeb9)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/proc/task_mmu.c (ffffffff81498a16)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff814a2dcf)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In security/tomoyo/domain.c (ffffffff8160090c)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In io_uring/io_uring.c (ffffffff816ca126)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_pin_pages
```
```
In drivers/iommu/io-pgfault.c (ffffffff8197116a)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - drivers/iommu/io-pgfault.c:iopf_handle_single
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a796d1)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a7f9cd)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
```
```
In net/ipv4/tcp.c (ffffffff81cecb1e)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff81e18fb4)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_pin_pages
```
**Symbols:**

```
ffffffff81395870-ffffffff813958af: mmap_read_unlock (STB_LOCAL)
ffffffff813e3e30-ffffffff813e3e6f: mmap_read_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void mmap_read_unlock(struct mm_struct *mm);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004b5e)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109030e)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810929ea)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093a82)
Location: include/linux/mmap_lock.h:141
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff810950b4)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
```
In arch/x86/mm/fault.c (ffffffff810c49b6)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area
```
```
In kernel/fork.c (ffffffff810e6a69)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:replace_mm_exe_file
```
```
In kernel/exit.c (ffffffff810f17a2)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff8110b1df)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/sched/fair.c (ffffffff81144376)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex/core.c (ffffffff811f3aa6)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/futex/core.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff811fd7e4)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff81273e4f)
Location: include/linux/mmap_lock.h:141
Inline: True
```
```
In kernel/bpf/task_iter.c (ffffffff812f6a0e)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:do_mmap_read_unlock
  - kernel/bpf/task_iter.c:bpf_find_vma
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In kernel/bpf/stackmap.c (ffffffff8132441b)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff813372a0)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff813500dc)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In mm/filemap.c (ffffffff8135e9d3)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:__folio_lock_or_retry
```
```
In mm/oom_kill.c (ffffffff8136445a)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff813797ae)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/vmscan.c:walk_mm
```
```
In mm/shmem.c (ffffffff8138d758)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/gup.c (ffffffff813b1ca1)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
  - mm/gup.c:get_dump_page
  - mm/gup.c:fault_in_safe_writeable
  - mm/gup.c:__mm_populate
Direct callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/memory.c (ffffffff813c0a66)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mincore.c (ffffffff813c14b0)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mmap.c (ffffffff813c9f34)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mremap.c (ffffffff813d1cd9)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff813d22bc)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff813e39bb)
Location: include/linux/mmap_lock.h:141
Inline: True
```
```
In mm/madvise.c (ffffffff813f6489)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/swapfile.c (ffffffff813ffbc0)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb_vmemmap.c (ffffffff81413d14)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
```
```
In mm/mempolicy.c (ffffffff814171ef)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
Direct callers:
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/ksm.c (ffffffff81420861)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff814321ef)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff81442e1e)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff8144cb39)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff81453015)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_can_attach
```
```
In mm/memory-failure.c (ffffffff8145ec08)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In mm/userfaultfd.c (ffffffff8146dd0f)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
Direct callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff814838d6)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:get_arg_page
```
```
In fs/userfaultfd.c (ffffffff814f0539)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/binfmt_elf.c (ffffffff8150f1c3)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff81511e3c)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/proc/task_mmu.c (ffffffff8152ccd1)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff815380fb)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In security/tomoyo/domain.c (ffffffff816b185c)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In io_uring/rsrc.c (ffffffff817a2280)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_pin_pages
```
```
In drivers/iommu/iommu-sva.c (ffffffff81adbf09)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In net/ipv4/tcp.c (ffffffff81eb0a1f)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff81ff0389)
Location: include/linux/mmap_lock.h:141
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
**Symbols:**

```
ffffffff813ae2a0-ffffffff813ae2df: mmap_read_unlock (STB_LOCAL)
ffffffff81414a30-ffffffff81414a6f: mmap_read_unlock (STB_LOCAL)
ffffffff8146b870-ffffffff8146b8af: mmap_read_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void mmap_read_unlock(struct mm_struct *mm);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff8100433c)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109322f)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81095920)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096a0b)
Location: include/linux/mmap_lock.h:172
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109803f)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
```
In arch/x86/mm/fault.c (ffffffff810c8203)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area
```
```
In kernel/fork.c (ffffffff810f2420)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:replace_mm_exe_file
```
```
In kernel/exit.c (ffffffff810fd6f4)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff811174bf)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/sched/fair.c (ffffffff81154b20)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex/core.c (ffffffff81208249)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - kernel/futex/core.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff8121296b)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff8128b76c)
Location: include/linux/mmap_lock.h:172
Inline: True
```
```
In kernel/trace/trace_events_user.c (ffffffff812c5e8f)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl_unreg
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
  - kernel/trace/trace_events_user.c:update_enable_bit_for
  - kernel/trace/trace_events_user.c:user_event_enabler_fault_fixup
  - kernel/trace/trace_events_user.c:user_event_mm_fault_in
```
```
In kernel/bpf/task_iter.c (ffffffff813248de)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:do_mmap_read_unlock
  - kernel/bpf/task_iter.c:bpf_find_vma
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In kernel/bpf/stackmap.c (ffffffff8135467b)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff8136818a)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff813812ba)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In mm/filemap.c (ffffffff8139176b)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:__folio_lock_or_retry
```
```
In mm/oom_kill.c (ffffffff8139692c)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff813ae1a4)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - mm/vmscan.c:walk_mm
```
```
In mm/shmem.c (ffffffff813c0113)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/gup.c (ffffffff813e5fa1)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
  - mm/gup.c:fault_in_safe_writeable
  - mm/gup.c:__mm_populate
```
```
In mm/memory.c (ffffffff813f57ec)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mincore.c (ffffffff813f61e7)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
```
In mm/mmap.c (ffffffff813fe445)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:expand_stack
```
```
In mm/msync.c (ffffffff81406e81)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff81418709)
Location: include/linux/mmap_lock.h:172
Inline: True
```
```
In mm/madvise.c (ffffffff8142921f)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/swapfile.c (ffffffff81432a58)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb_vmemmap.c (ffffffff8144726e)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_alloc
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
```
```
In mm/mempolicy.c (ffffffff8144a781)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
Direct callers:
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/ksm.c (ffffffff81455532)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff814682ee)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff814786ed)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff814823ea)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff81488c68)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_can_attach
```
```
In mm/memory-failure.c (ffffffff81494a5b)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In mm/userfaultfd.c (ffffffff814a2759)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
Direct callers:
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In fs/exec.c (ffffffff814b918e)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:get_arg_page
```
```
In fs/userfaultfd.c (ffffffff81527389)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff81565111)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff81570368)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In security/tomoyo/domain.c (ffffffff816ea25d)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In io_uring/rsrc.c (ffffffff817e336b)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_pin_pages
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b2a133)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In net/ipv4/tcp.c (ffffffff81f0f316)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff8206c534)
Location: include/linux/mmap_lock.h:172
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
**Symbols:**

```
ffffffff81448700-ffffffff8144872d: mmap_read_unlock (STB_LOCAL)
ffffffff814a06b0-ffffffff814a06dd: mmap_read_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void mmap_read_unlock(struct mm_struct *mm);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81006c4b)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a69f)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109ce60)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109df7b)
Location: include/linux/mmap_lock.h:170
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109f5df)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
```
In arch/x86/kernel/shstk.c (ffffffff810ca47f)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/shstk.c:shstk_pop_sigframe
  - arch/x86/kernel/shstk.c:shstk_pop_sigframe
```
```
In arch/x86/mm/fault.c (ffffffff810d06b5)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area
```
```
In kernel/fork.c (ffffffff810fbff0)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
```
```
In kernel/exit.c (ffffffff81106564)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff81120eaf)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/sched/fair.c (ffffffff811699d9)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex/core.c (ffffffff8121f0d9)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - kernel/futex/core.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff8122a004)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff812a6b26)
Location: include/linux/mmap_lock.h:170
Inline: True
```
```
In kernel/trace/trace_events_user.c (ffffffff812e26e3)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl_unreg
  - kernel/trace/trace_events_user.c:update_enable_bit_for
  - kernel/trace/trace_events_user.c:user_event_enabler_create
  - kernel/trace/trace_events_user.c:user_event_enabler_fault_fixup
  - kernel/trace/trace_events_user.c:user_event_mm_fault_in
```
```
In kernel/bpf/task_iter.c (ffffffff8134874e)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:do_mmap_read_unlock
  - kernel/bpf/task_iter.c:bpf_iter_task_vma_destroy
  - kernel/bpf/task_iter.c:bpf_find_vma
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In kernel/bpf/stackmap.c (ffffffff8137cfeb)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff813910a9)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff813aa66a)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In mm/filemap.c (0)
Location: include/linux/mmap_lock.h:170
Inline: False
```
```
In mm/oom_kill.c (ffffffff813c023c)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff813d77d4)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - mm/vmscan.c:walk_mm
```
```
In mm/shmem.c (ffffffff813e7806)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - mm/shmem.c:shmem_falloc_wait
```
```
In mm/gup.c (ffffffff81410b81)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
  - mm/gup.c:fault_in_safe_writeable
  - mm/gup.c:__mm_populate
```
```
In mm/memory.c (ffffffff8141f4cc)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mincore.c (ffffffff81421e97)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
```
In mm/mmap.c (ffffffff8142a83a)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:expand_stack
```
```
In mm/msync.c (ffffffff81433531)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff81445259)
Location: include/linux/mmap_lock.h:170
Inline: True
```
```
In mm/madvise.c (ffffffff81462a4f)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/swapfile.c (ffffffff8146be77)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb_vmemmap.c (ffffffff814805ce)
Location: include/linux/mmap_lock.h:170
Inline: True
```
```
In mm/mempolicy.c (ffffffff81482b53)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
Direct callers:
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/ksm.c (ffffffff8148f452)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff81496f4e)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff814a7e12)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff814b1786)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff814b82e8)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_can_attach
```
```
In mm/memory-failure.c (ffffffff814c436b)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In mm/userfaultfd.c (ffffffff814d2818)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
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
Direct callers:
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In fs/exec.c (ffffffff814eb97e)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:get_arg_page
```
```
In fs/userfaultfd.c (ffffffff815595a2)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_move
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff8159bc2b)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:do_pagemap_scan
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff815a8cff)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In security/tomoyo/domain.c (ffffffff81726f6d)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In io_uring/rsrc.c (ffffffff8182740d)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_pin_pages
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b81303)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In net/ipv4/tcp.c (ffffffff81fd34ef)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff82140332)
Location: include/linux/mmap_lock.h:170
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
**Symbols:**

```
ffffffff81481f60-ffffffff81481f8d: mmap_read_unlock (STB_LOCAL)
ffffffff814cfd50-ffffffff814cfd7d: mmap_read_unlock (STB_LOCAL)
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
