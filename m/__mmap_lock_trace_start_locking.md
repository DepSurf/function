# Function: <code>__mmap_lock_trace_start_locking</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004c98)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810677ae)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81067d92)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/mm/fault.c (ffffffff810880cc)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810a0b1c)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810a7400)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/exit.c:mmap_read_lock
```
```
In kernel/sys.c (ffffffff810c00db)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/sched/fair.c (ffffffff810e77f7)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex.c (ffffffff81156cc3)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/futex.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff81165edf)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff811c3ae6)
Location: include/linux/mmap_lock.h:25
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff81233521)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff8123c388)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff8125162c)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:xol_add_vma
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/oom_kill.c (ffffffff81261da0)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reap_task_mm
```
```
In mm/util.c (ffffffff8127dc0e)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/gup.c (ffffffff81293af6)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:get_dump_page
  - mm/gup.c:get_dump_page
  - mm/gup.c:__mm_populate
  - mm/gup.c:fixup_user_fault
```
```
In mm/memory.c (ffffffff812a045c)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:vm_insert_page
```
```
In mm/mincore.c (ffffffff812a0f58)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mlock.c (ffffffff812a2e3c)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff812a8865)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff812a9692)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff812ac829)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff812ace78)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff812b8899)
Location: include/linux/mmap_lock.h:25
Inline: True
```
```
In mm/madvise.c (ffffffff812c0ee4)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/madvise.c:madvise_remove
```
```
In mm/swapfile.c (ffffffff812c9bb5)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff812db8c7)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff812dded5)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff812e2718)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff812ed5c5)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat_array
  - mm/migrate.c:add_page_for_migration
```
```
In mm/khugepaged.c (ffffffff812ff543)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff813053cb)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_count_precharge
```
```
In mm/userfaultfd.c (ffffffff81314e77)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/frame_vector.c (ffffffff8131574b)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
```
In mm/ptdump.c (ffffffff81318cbf)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff81329110)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:__bprm_mm_init
```
```
In fs/userfaultfd.c (ffffffff8138044c)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff813851e4)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff813969d0)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_unaccount_mem
```
```
In fs/binfmt_elf.c (ffffffff813b0987)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff813b3487)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/coredump.c (ffffffff813b96d9)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/task_mmu.c (ffffffff813c8783)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff813d1264)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In ipc/shm.c (ffffffff814ae9a5)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In drivers/iommu/intel/svm.c (ffffffff817b5b37)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ad406)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b259a)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
```
In net/ipv4/tcp.c (ffffffff81ab6ef5)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff81bb8032)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_pin_pages
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
In arch/x86/entry/vdso/vma.c (ffffffff81004c88)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8106789a)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068302)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/mm/fault.c (ffffffff81088b97)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810a18ac)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810a8490)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/exit.c:mmap_read_lock
```
```
In kernel/sys.c (ffffffff810c1ae0)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/sched/fair.c (ffffffff810e96c7)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex.c (ffffffff811580d3)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/futex.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff81166c0f)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff811c4bf6)
Location: include/linux/mmap_lock.h:25
Inline: True
```
```
In kernel/bpf/task_iter.c (ffffffff8121bff1)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In kernel/bpf/stackmap.c (ffffffff812372e1)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff812409d8)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff812577ad)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handler_chain
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/oom_kill.c (ffffffff812668e4)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/util.c (ffffffff81282dde)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/gup.c (ffffffff81299496)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:get_dump_page
  - mm/gup.c:get_dump_page
  - mm/gup.c:__mm_populate
  - mm/gup.c:fixup_user_fault
```
```
In mm/memory.c (ffffffff812a5d9c)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:vm_insert_page
```
```
In mm/mincore.c (ffffffff812a6710)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mlock.c (ffffffff812a869c)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff812add15)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff812aeb22)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff812b1b2b)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff812b215f)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff812bdd63)
Location: include/linux/mmap_lock.h:25
Inline: True
```
```
In mm/madvise.c (ffffffff812c803e)
Location: include/linux/mmap_lock.h:25
Inline: True
```
```
In mm/swapfile.c (ffffffff812d0aab)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff812e3150)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff812e5485)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff812e9ea8)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff812f3902)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff813005ee)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff813061bd)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff8130acab)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/userfaultfd.c (ffffffff8131b5b7)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/ptdump.c (ffffffff8131eeaf)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff8132ef20)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:__bprm_mm_init
```
```
In fs/userfaultfd.c (ffffffff81386ee5)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff8138bf94)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff813919b0)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/binfmt_elf.c (ffffffff813b7acc)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff813ba477)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/coredump.c (ffffffff813c0839)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/task_mmu.c (ffffffff813cf7b7)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff813d8164)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In ipc/shm.c (ffffffff814b47c5)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In drivers/iommu/intel/svm.c (ffffffff81798e59)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81890588)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818958ba)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
```
In net/ipv4/tcp.c (ffffffff81aa20f5)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff81ba7202)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_pin_pages
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
In arch/x86/entry/vdso/vma.c (ffffffff810052a8)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81071c7a)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81072782)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/mm/fault.c (ffffffff81097fd0)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810b3295)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810b9f30)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/exit.c:mmap_read_lock
```
```
In kernel/sys.c (ffffffff810d4895)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/sched/fair.c (ffffffff81100f57)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex.c (ffffffff8117d003)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/futex.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff8118c3cf)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff811f0136)
Location: include/linux/mmap_lock.h:25
Inline: True
```
```
In kernel/bpf/task_iter.c (ffffffff81252eed)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In kernel/bpf/stackmap.c (ffffffff812718c1)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff8127b449)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff812933a5)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handler_chain
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/oom_kill.c (ffffffff812a3211)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_reaper
```
```
In mm/util.c (ffffffff812c0ece)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/gup.c (ffffffff812d9de0)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:get_dump_page
  - mm/gup.c:get_dump_page
  - mm/gup.c:__mm_populate
  - mm/gup.c:fixup_user_fault
```
```
In mm/memory.c (ffffffff812e722c)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
```
```
In mm/mincore.c (ffffffff812e7bd8)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mlock.c (ffffffff812e9cdc)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff812ef485)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff812f0306)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff812f36fb)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff812f3d5a)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff81300513)
Location: include/linux/mmap_lock.h:25
Inline: True
```
```
In mm/madvise.c (ffffffff8130ce16)
Location: include/linux/mmap_lock.h:25
Inline: True
```
```
In mm/swapfile.c (ffffffff81316186)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff8132a4b6)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/sparse-vmemmap.c (ffffffff8132c8c3)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_remap_alloc
  - mm/sparse-vmemmap.c:vmemmap_remap_free
```
```
In mm/mmu_notifier.c (ffffffff8132d075)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff81331dd8)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff8133deee)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff8134a28e)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff81350021)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff813533cb)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/memory-failure.c (ffffffff81cc2f42)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In mm/userfaultfd.c (ffffffff81368887)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/ptdump.c (ffffffff8136c28f)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff8137c710)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:__bprm_mm_init
  - fs/exec.c:get_arg_page
```
```
In fs/userfaultfd.c (ffffffff813d4175)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff813d9547)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff813df8af)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/binfmt_elf.c (ffffffff814077c3)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8140a179)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/coredump.c (ffffffff814106a9)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/task_mmu.c (ffffffff81420b97)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff814298a4)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In ipc/shm.c (ffffffff8150ce75)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In security/tomoyo/domain.c (ffffffff815650db)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In drivers/iommu/io-pgfault.c (ffffffff8182fe97)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - drivers/iommu/io-pgfault.c:iopf_handle_single
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8192417d)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff8192982a)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
```
```
In net/ipv4/tcp.c (ffffffff81b5dece)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff81c74f7f)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In arch/x86/entry/vdso/vma.c (ffffffff81004308)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107ffee)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81080a64)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/mm/fault.c (ffffffff810aac0d)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810c94b5)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810d2c29)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff810ed213)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:prctl_set_vma
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/sched/fair.c (ffffffff8111c683)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex/core.c (ffffffff811b2bd1)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/futex/core.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff811bb916)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff81228744)
Location: include/linux/mmap_lock.h:25
Inline: True
```
```
In kernel/bpf/task_iter.c (ffffffff8129a52e)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_find_vma
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In kernel/bpf/stackmap.c (ffffffff812c09fb)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff812cf252)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff812e8e98)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handler_chain
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/oom_kill.c (ffffffff812fb0ce)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_reaper
```
```
In mm/util.c (ffffffff8131dd28)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/gup.c (ffffffff8133b24e)
Location: include/linux/mmap_lock.h:25
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
  - mm/gup.c:fixup_user_fault
```
```
In mm/memory.c (ffffffff813484bc)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
```
```
In mm/mincore.c (ffffffff81348e50)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mlock.c (ffffffff81349c3c)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff8135055d)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff813536d6)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff813573ad)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff81357b8c)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff8136788e)
Location: include/linux/mmap_lock.h:25
Inline: True
```
```
In mm/madvise.c (ffffffff81378aad)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
  - mm/madvise.c:do_madvise
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_populate
```
```
In mm/swapfile.c (ffffffff81381319)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff81399afa)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/sparse-vmemmap.c (ffffffff8139c933)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_remap_alloc
  - mm/sparse-vmemmap.c:vmemmap_remap_free
```
```
In mm/mmu_notifier.c (ffffffff8139d324)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff813a2f5f)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff813b1442)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff813c0e36)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff813c8216)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff813cdefb)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_can_attach
```
```
In mm/memory-failure.c (ffffffff81e75447)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In mm/userfaultfd.c (ffffffff813e619a)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/ptdump.c (ffffffff813ea56f)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff813faff3)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:get_arg_page
```
```
In fs/userfaultfd.c (ffffffff8145eebe)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff814635ed)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/binfmt_elf.c (ffffffff8147c4e4)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8147ee8a)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/coredump.c (ffffffff8148492c)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/task_mmu.c (ffffffff814989de)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff814a2cf7)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In ipc/shm.c (ffffffff8159ed95)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In security/tomoyo/domain.c (ffffffff816008d3)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In io_uring/io_uring.c (ffffffff816ca0cd)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_pin_pages
```
```
In drivers/iommu/io-pgfault.c (ffffffff819710ef)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - drivers/iommu/io-pgfault.c:iopf_handle_single
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a795b3)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a7f8c4)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
```
```
In net/ipv4/tcp.c (ffffffff81cec8c1)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff81e18f77)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_pin_pages
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
In arch/x86/entry/vdso/vma.c (ffffffff81004c41)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810902cf)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810928fb)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093a5f)
Location: include/linux/mmap_lock.h:25
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff810c48fd)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810e6a16)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810f1731)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff8110e633)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:prctl_set_vma
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/sched/fair.c (ffffffff811441e5)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex/core.c (ffffffff811f3a81)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/futex/core.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff811fd7ad)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff81273df0)
Location: include/linux/mmap_lock.h:25
Inline: True
```
```
In kernel/bpf/task_iter.c (ffffffff812f66ae)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_find_vma
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In kernel/bpf/stackmap.c (ffffffff8132429a)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff8133725b)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff8135003b)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:xol_add_vma
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/oom_kill.c (ffffffff8136441e)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff81379720)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/vmscan.c:walk_mm
```
```
In mm/util.c (ffffffff81391828)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/gup.c (ffffffff813b1c18)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
  - mm/gup.c:get_dump_page
  - mm/gup.c:fault_in_safe_writeable
  - mm/gup.c:__mm_populate
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
```
```
In mm/memory.c (ffffffff813c096c)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
```
```
In mm/mincore.c (ffffffff813c1478)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mlock.c (ffffffff813c272c)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff813c9ec7)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff813cdb36)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff813d1998)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff813d232d)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff813e384e)
Location: include/linux/mmap_lock.h:25
Inline: True
```
```
In mm/madvise.c (ffffffff813f63dd)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
  - mm/madvise.c:do_madvise
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_populate
```
```
In mm/swapfile.c (ffffffff813ffb73)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb_vmemmap.c (ffffffff81413cdb)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
```
```
In mm/mempolicy.c (ffffffff81419a49)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff8141c7a4)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff81422bdf)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff81432112)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff81442d06)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff8144cc9f)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff81452fdb)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_can_attach
```
```
In mm/memory-failure.c (ffffffff8145eba5)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In mm/userfaultfd.c (ffffffff8146dc5a)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/ptdump.c (ffffffff8147269f)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff814848f0)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:get_arg_page
```
```
In fs/userfaultfd.c (ffffffff814eec11)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff814f26dd)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/binfmt_elf.c (ffffffff8150f194)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff81511e0d)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/coredump.c (ffffffff81517e24)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/task_mmu.c (ffffffff8152cc99)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff81537eea)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In ipc/shm.c (ffffffff816484c2)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In security/tomoyo/domain.c (ffffffff816b1823)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In io_uring/rsrc.c (ffffffff817a2224)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_pin_pages
```
```
In drivers/iommu/iommu-sva.c (ffffffff81adbe8f)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In net/ipv4/tcp.c (ffffffff81eb07d1)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff81ff034b)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In arch/x86/entry/vdso/vma.c (ffffffff81004421)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/process_64.c (ffffffff8104a719)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810931e9)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109582b)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810969e5)
Location: include/linux/mmap_lock.h:25
Inline: True
```
```
In kernel/fork.c (ffffffff810f23b7)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810fd681)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff8111ac17)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:prctl_set_vma
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/sched/fair.c (ffffffff8115482b)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex/core.c (ffffffff81208221)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/futex/core.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff8121292d)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff8128b704)
Location: include/linux/mmap_lock.h:25
Inline: True
```
```
In kernel/trace/trace_events_user.c (ffffffff812c5e5e)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl_unreg
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
  - kernel/trace/trace_events_user.c:update_enable_bit_for
  - kernel/trace/trace_events_user.c:user_event_mm_remove
  - kernel/trace/trace_events_user.c:user_event_enabler_fault_fixup
  - kernel/trace/trace_events_user.c:user_event_mm_fault_in
```
```
In kernel/bpf/task_iter.c (ffffffff8132457e)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_find_vma
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In kernel/bpf/stackmap.c (ffffffff813544da)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff81368142)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff8138120b)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:xol_add_vma
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/oom_kill.c (ffffffff813968ed)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff813ae116)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/vmscan.c:walk_mm
```
```
In mm/util.c (ffffffff813c41f8)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/gup.c (ffffffff813e5e58)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
  - mm/gup.c:fault_in_safe_writeable
  - mm/gup.c:__mm_populate
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
```
```
In mm/memory.c (ffffffff813f56ec)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
```
```
In mm/mincore.c (ffffffff813f61ac)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
```
In mm/mlock.c (ffffffff813f766c)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff813fe3cb)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:expand_stack
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff81402376)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff81406594)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff81406ef2)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff814185a1)
Location: include/linux/mmap_lock.h:25
Inline: True
```
```
In mm/madvise.c (ffffffff814291d2)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
  - mm/madvise.c:do_madvise
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_populate
```
```
In mm/swapfile.c (ffffffff81432a07)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb_vmemmap.c (ffffffff8144724f)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_alloc
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
```
```
In mm/mempolicy.c (ffffffff8144cec5)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff8144fd54)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff81457bef)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff814681ed)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff814785c6)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff8148249d)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff81488c2b)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_can_attach
```
```
In mm/memory-failure.c (ffffffff814949f5)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In mm/userfaultfd.c (ffffffff814a2690)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/ptdump.c (ffffffff814a6def)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff814b94d0)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:get_arg_page
  - fs/exec.c:get_arg_page
```
```
In fs/userfaultfd.c (ffffffff81525b42)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff81529316)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/binfmt_elf.c (ffffffff81546a4e)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff815497cd)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/coredump.c (ffffffff8154f71e)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/task_mmu.c (ffffffff815650d1)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff815700ed)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In ipc/shm.c (ffffffff81680a06)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In security/tomoyo/domain.c (ffffffff816ea223)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In io_uring/rsrc.c (ffffffff817e331e)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_pin_pages
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b2a0b5)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In net/ipv4/tcp.c (ffffffff81f0f2b4)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff8206c4f6)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In arch/x86/entry/vdso/vma.c (ffffffff81006d30)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/process_64.c (ffffffff8105186c)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a659)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109cd6b)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109df55)
Location: include/linux/mmap_lock.h:25
Inline: True
```
```
In arch/x86/kernel/shstk.c (ffffffff810ca3f5)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/shstk.c:shstk_pop_sigframe
  - arch/x86/kernel/shstk.c:alloc_shstk
```
```
In kernel/fork.c (ffffffff810fbf86)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff811064f1)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff8112476b)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:prctl_set_vma
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/sched/fair.c (ffffffff8116967d)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex/core.c (ffffffff8121f0b1)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/futex/core.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff81229fc6)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff812a6ab6)
Location: include/linux/mmap_lock.h:25
Inline: True
```
```
In kernel/trace/trace_events_user.c (ffffffff812e26b2)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl_unreg
  - kernel/trace/trace_events_user.c:update_enable_bit_for
  - kernel/trace/trace_events_user.c:user_event_enabler_create
  - kernel/trace/trace_events_user.c:user_event_mm_remove
  - kernel/trace/trace_events_user.c:user_event_enabler_fault_fixup
  - kernel/trace/trace_events_user.c:user_event_mm_fault_in
```
```
In kernel/bpf/task_iter.c (ffffffff813497d9)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_iter_task_vma_new
  - kernel/bpf/task_iter.c:bpf_find_vma
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In kernel/bpf/stackmap.c (ffffffff8137ce4a)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff81391061)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff813aa5bb)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:xol_add_vma
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/oom_kill.c (ffffffff813c01fd)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff813d7746)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/vmscan.c:walk_mm
```
```
In mm/util.c (ffffffff813eeda8)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/gup.c (ffffffff81410994)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
  - mm/gup.c:fault_in_safe_writeable
  - mm/gup.c:__mm_populate
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
```
```
In mm/memory.c (ffffffff8141f3cc)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
```
```
In mm/mincore.c (ffffffff81421e5c)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
```
In mm/mlock.c (ffffffff8142324c)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff8142a7b1)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:expand_stack
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff8142e9a6)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff81432ca4)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff814335a2)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff814450f1)
Location: include/linux/mmap_lock.h:25
Inline: True
```
```
In mm/madvise.c (ffffffff81462a02)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
  - mm/madvise.c:do_madvise
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_populate
```
```
In mm/swapfile.c (ffffffff8146be26)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb_vmemmap.c (ffffffff81480585)
Location: include/linux/mmap_lock.h:25
Inline: True
```
```
In mm/mempolicy.c (ffffffff814867b4)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff81489a84)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff814926bf)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff81496e4d)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff814a7cf6)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff814b1839)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff814b82ab)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_can_attach
```
```
In mm/memory-failure.c (ffffffff814c4305)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In mm/userfaultfd.c (ffffffff814d274f)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/ptdump.c (ffffffff814d7def)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff814ebfd7)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:get_arg_page
  - fs/exec.c:get_arg_page
```
```
In fs/userfaultfd.c (ffffffff8155955f)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_move
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff8155e1e6)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/binfmt_elf.c (ffffffff8157be9e)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8157ea4d)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/coredump.c (ffffffff8158555d)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/task_mmu.c (ffffffff8159bd9a)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:do_pagemap_scan
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff815a8a7d)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In ipc/shm.c (ffffffff816bce25)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In security/tomoyo/domain.c (ffffffff81726f33)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In io_uring/rsrc.c (ffffffff818273d4)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_pin_pages
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b81285)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In net/ipv4/tcp.c (ffffffff81fd3491)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff821402f4)
Location: include/linux/mmap_lock.h:25
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
