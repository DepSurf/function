# Function: <code>__mmap_lock_trace_acquire_returned</code>

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
In arch/x86/entry/vdso/vma.c (ffffffff81004cad)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810677bf)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81067da4)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/mm/fault.c (ffffffff810880e4)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810a0b36)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810a741b)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/exit.c:mmap_read_lock
```
```
In kernel/sys.c (ffffffff810c00ef)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/sched/fair.c (ffffffff810e7813)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex.c (ffffffff81156cd8)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/futex.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff81165ef0)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff811c3afa)
Location: include/linux/mmap_lock.h:32
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff81233532)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff8123c399)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff81251641)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:xol_add_vma
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/oom_kill.c (ffffffff81261dbd)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reap_task_mm
```
```
In mm/util.c (ffffffff8127dc26)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/gup.c (ffffffff81293b0a)
Location: include/linux/mmap_lock.h:32
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
In mm/memory.c (ffffffff812a0473)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:vm_insert_page
```
```
In mm/mincore.c (ffffffff812a0f69)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mlock.c (ffffffff812a2e50)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff812a8885)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff812a96a4)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff812ac844)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff812ace86)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff812b88a7)
Location: include/linux/mmap_lock.h:32
Inline: True
```
```
In mm/madvise.c (ffffffff812c0ef1)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/madvise.c:madvise_remove
```
```
In mm/swapfile.c (ffffffff812c9bea)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff812db8e2)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff812ddeea)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff812e272d)
Location: include/linux/mmap_lock.h:32
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
In mm/migrate.c (ffffffff812ed5fc)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat_array
  - mm/migrate.c:add_page_for_migration
```
```
In mm/khugepaged.c (ffffffff812ff55a)
Location: include/linux/mmap_lock.h:32
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
In mm/memcontrol.c (ffffffff813053df)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_count_precharge
```
```
In mm/userfaultfd.c (ffffffff81314e8b)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/frame_vector.c (ffffffff81315764)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
```
In mm/ptdump.c (ffffffff81318cd3)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff81329125)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:__bprm_mm_init
```
```
In fs/userfaultfd.c (ffffffff81380465)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff813851ff)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff813969e5)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_unaccount_mem
```
```
In fs/binfmt_elf.c (ffffffff813b099e)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff813b349e)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/coredump.c (ffffffff813b96f5)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/task_mmu.c (ffffffff813c8791)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff813d1282)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In ipc/shm.c (ffffffff814ae9bb)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In drivers/iommu/intel/svm.c (ffffffff817b5b4c)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ad41e)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b25b2)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
```
In net/ipv4/tcp.c (ffffffff81ab6f0d)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff81bb8043)
Location: include/linux/mmap_lock.h:32
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
In arch/x86/entry/vdso/vma.c (ffffffff81004c9a)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810678ac)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068311)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/mm/fault.c (ffffffff81088bac)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810a18c3)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810a84a8)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/exit.c:mmap_read_lock
```
```
In kernel/sys.c (ffffffff810c1af1)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/sched/fair.c (ffffffff810e96e0)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex.c (ffffffff811580e5)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/futex.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff81166c1d)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff811c4c07)
Location: include/linux/mmap_lock.h:32
Inline: True
```
```
In kernel/bpf/task_iter.c (ffffffff8121c002)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In kernel/bpf/stackmap.c (ffffffff812372ef)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff812409e6)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff812577be)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handler_chain
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/oom_kill.c (ffffffff812668f3)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/util.c (ffffffff81282df3)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/gup.c (ffffffff812994a7)
Location: include/linux/mmap_lock.h:32
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
In mm/memory.c (ffffffff812a5db0)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:vm_insert_page
```
```
In mm/mincore.c (ffffffff812a671e)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mlock.c (ffffffff812a86ad)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff812add32)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff812aeb31)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff812b1b43)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff812b216d)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff812bdd71)
Location: include/linux/mmap_lock.h:32
Inline: True
```
```
In mm/madvise.c (ffffffff812c82ed)
Location: include/linux/mmap_lock.h:32
Inline: True
```
```
In mm/swapfile.c (ffffffff812d0abd)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff812e3168)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff812e5497)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff812e9eba)
Location: include/linux/mmap_lock.h:32
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
In mm/migrate.c (ffffffff812f3913)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff81300604)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff813061d1)
Location: include/linux/mmap_lock.h:32
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
In mm/memcontrol.c (ffffffff8130acbc)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/userfaultfd.c (ffffffff8131b5c8)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/ptdump.c (ffffffff8131eec0)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff8132ef32)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:__bprm_mm_init
```
```
In fs/userfaultfd.c (ffffffff81386efb)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff8138bfac)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff813919be)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/binfmt_elf.c (ffffffff813b7ae0)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff813ba48b)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/coredump.c (ffffffff813c0855)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/task_mmu.c (ffffffff813cf7c5)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff813d817f)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In ipc/shm.c (ffffffff814b47d8)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In drivers/iommu/intel/svm.c (ffffffff81798e6c)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818905b3)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818958cf)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
```
In net/ipv4/tcp.c (ffffffff81aa210a)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff81ba7210)
Location: include/linux/mmap_lock.h:32
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
In arch/x86/entry/vdso/vma.c (ffffffff810052b7)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81071c8c)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81072791)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/mm/fault.c (ffffffff81097fe5)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810b32a7)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810b9f45)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/exit.c:mmap_read_lock
```
```
In kernel/sys.c (ffffffff810d48a6)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/sched/fair.c (ffffffff81100f70)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex.c (ffffffff8117d012)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/futex.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff8118c3dd)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff811f0147)
Location: include/linux/mmap_lock.h:32
Inline: True
```
```
In kernel/bpf/task_iter.c (ffffffff81252efe)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In kernel/bpf/stackmap.c (ffffffff812718cf)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff8127b454)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff812933b6)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handler_chain
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/oom_kill.c (ffffffff812a3222)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_reaper
```
```
In mm/util.c (ffffffff812c0ee3)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/gup.c (ffffffff812d9df1)
Location: include/linux/mmap_lock.h:32
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
In mm/memory.c (ffffffff812e723d)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
```
```
In mm/mincore.c (ffffffff812e7be6)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mlock.c (ffffffff812e9cea)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff812ef4a2)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff812f0315)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff812f3713)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff812f3d65)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff81300521)
Location: include/linux/mmap_lock.h:32
Inline: True
```
```
In mm/madvise.c (ffffffff8130d001)
Location: include/linux/mmap_lock.h:32
Inline: True
```
```
In mm/swapfile.c (ffffffff81316198)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff8132a4ce)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/sparse-vmemmap.c (ffffffff8132c8d1)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_remap_alloc
  - mm/sparse-vmemmap.c:vmemmap_remap_free
  - mm/sparse-vmemmap.c:vmemmap_remap_free
```
```
In mm/mmu_notifier.c (ffffffff8132d084)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff81331de7)
Location: include/linux/mmap_lock.h:32
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
In mm/migrate.c (ffffffff8133df07)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff8134a2a4)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff81350035)
Location: include/linux/mmap_lock.h:32
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
In mm/memcontrol.c (ffffffff813533d9)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/memory-failure.c (ffffffff81cc2f59)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In mm/userfaultfd.c (ffffffff81368898)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/ptdump.c (ffffffff8136c29d)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff8137c722)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:__bprm_mm_init
  - fs/exec.c:get_arg_page
```
```
In fs/userfaultfd.c (ffffffff813d418b)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff813d955f)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff813df8c1)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/binfmt_elf.c (ffffffff814077d7)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8140a18d)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/coredump.c (ffffffff814106c5)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/task_mmu.c (ffffffff81420ba5)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff814298bf)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In ipc/shm.c (ffffffff8150ce88)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In security/tomoyo/domain.c (ffffffff815650e9)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In drivers/iommu/io-pgfault.c (ffffffff8182fea8)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - drivers/iommu/io-pgfault.c:iopf_handle_single
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff819241a3)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff8192983f)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
```
```
In net/ipv4/tcp.c (ffffffff81b5dee3)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff81c74f8e)
Location: include/linux/mmap_lock.h:32
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
In arch/x86/entry/vdso/vma.c (ffffffff8100431a)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107fffc)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81080a72)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/mm/fault.c (ffffffff810aac22)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810c94c7)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810d2c3a)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff810ed223)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:prctl_set_vma
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/sched/fair.c (ffffffff8111c69c)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex/core.c (ffffffff811b2be0)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/futex/core.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff811bb924)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff81228759)
Location: include/linux/mmap_lock.h:32
Inline: True
```
```
In kernel/bpf/task_iter.c (ffffffff8129a543)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_find_vma
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In kernel/bpf/stackmap.c (ffffffff812c0a09)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff812cf25d)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff812e8ea9)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handler_chain
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/oom_kill.c (ffffffff812fb0e3)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_reaper
```
```
In mm/util.c (ffffffff8131dd3d)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/gup.c (ffffffff8133b260)
Location: include/linux/mmap_lock.h:32
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
In mm/memory.c (ffffffff813484cd)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
```
```
In mm/mincore.c (ffffffff81348e5e)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mlock.c (ffffffff81349c4a)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff8135056f)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff813536e5)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff813573be)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff81357b9f)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff8136789c)
Location: include/linux/mmap_lock.h:32
Inline: True
```
```
In mm/madvise.c (ffffffff81378ac6)
Location: include/linux/mmap_lock.h:32
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
In mm/swapfile.c (ffffffff8138132f)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff81399b13)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/sparse-vmemmap.c (ffffffff8139c941)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_remap_alloc
  - mm/sparse-vmemmap.c:vmemmap_remap_free
```
```
In mm/mmu_notifier.c (ffffffff8139d332)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff813a2f6e)
Location: include/linux/mmap_lock.h:32
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
In mm/migrate.c (ffffffff813b1461)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff813c0e4b)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff813c822a)
Location: include/linux/mmap_lock.h:32
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
In mm/memcontrol.c (ffffffff813cdf09)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_can_attach
```
```
In mm/memory-failure.c (ffffffff81e7545e)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In mm/userfaultfd.c (ffffffff813e61b0)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/ptdump.c (ffffffff813ea580)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff813fb004)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:get_arg_page
```
```
In fs/userfaultfd.c (ffffffff8145eed3)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff81463605)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/binfmt_elf.c (ffffffff8147c4f7)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8147ee9d)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/coredump.c (ffffffff81484948)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/task_mmu.c (ffffffff814989ec)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff814a2d13)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In ipc/shm.c (ffffffff8159eda8)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In security/tomoyo/domain.c (ffffffff816008e1)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In io_uring/io_uring.c (ffffffff816ca0db)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_pin_pages
```
```
In drivers/iommu/io-pgfault.c (ffffffff81971100)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - drivers/iommu/io-pgfault.c:iopf_handle_single
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a795c8)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a7f8d9)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
```
```
In net/ipv4/tcp.c (ffffffff81cec8d0)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff81e18f85)
Location: include/linux/mmap_lock.h:32
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
In arch/x86/entry/vdso/vma.c (ffffffff81004c57)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810902dd)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81092909)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093a6d)
Location: include/linux/mmap_lock.h:32
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff810c4912)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810e6a28)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810f1742)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff8110e643)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:prctl_set_vma
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/sched/fair.c (ffffffff811441fd)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex/core.c (ffffffff811f3a90)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/futex/core.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff811fd7c2)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff81273e05)
Location: include/linux/mmap_lock.h:32
Inline: True
```
```
In kernel/bpf/task_iter.c (ffffffff812f66c3)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_find_vma
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In kernel/bpf/stackmap.c (ffffffff813242a8)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff8133726a)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff8135004d)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:xol_add_vma
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/oom_kill.c (ffffffff81364433)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff8137972d)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/vmscan.c:walk_mm
```
```
In mm/util.c (ffffffff8139183d)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/gup.c (ffffffff813b1c27)
Location: include/linux/mmap_lock.h:32
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
In mm/memory.c (ffffffff813c097d)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
```
```
In mm/mincore.c (ffffffff813c1486)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mlock.c (ffffffff813c273a)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff813c9ed8)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:do_mas_align_munmap
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff813cdb42)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff813d19a9)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff813d2338)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff813e385c)
Location: include/linux/mmap_lock.h:32
Inline: True
```
```
In mm/madvise.c (ffffffff813f63f6)
Location: include/linux/mmap_lock.h:32
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
In mm/swapfile.c (ffffffff813ffb89)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb_vmemmap.c (ffffffff81413cec)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
```
```
In mm/mempolicy.c (ffffffff81419a61)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff8141c7b2)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff81422bee)
Location: include/linux/mmap_lock.h:32
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
In mm/migrate.c (ffffffff81432131)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff81442d1c)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff8144ccae)
Location: include/linux/mmap_lock.h:32
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
In mm/memcontrol.c (ffffffff81452fe9)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_can_attach
```
```
In mm/memory-failure.c (ffffffff8145ebb3)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In mm/userfaultfd.c (ffffffff8146dc70)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/ptdump.c (ffffffff814726b0)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff81484901)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:get_arg_page
```
```
In fs/userfaultfd.c (ffffffff814eec29)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff814f26f5)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/binfmt_elf.c (ffffffff8150f1a7)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff81511e20)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/coredump.c (ffffffff81517e45)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/task_mmu.c (ffffffff8152cca7)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff81537f0c)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In ipc/shm.c (ffffffff816484d6)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In security/tomoyo/domain.c (ffffffff816b1831)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In io_uring/rsrc.c (ffffffff817a2232)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_pin_pages
```
```
In drivers/iommu/iommu-sva.c (ffffffff81adbea0)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In net/ipv4/tcp.c (ffffffff81eb07e0)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff81ff035a)
Location: include/linux/mmap_lock.h:32
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
In arch/x86/entry/vdso/vma.c (ffffffff8100443f)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/process_64.c (ffffffff8104a730)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810931fa)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109583c)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810969f6)
Location: include/linux/mmap_lock.h:32
Inline: True
```
```
In kernel/fork.c (ffffffff810f23d0)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810fd695)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff8111ac2a)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:prctl_set_vma
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/sched/fair.c (ffffffff81154847)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex/core.c (ffffffff81208233)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/futex/core.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff81212949)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff8128b71c)
Location: include/linux/mmap_lock.h:32
Inline: True
```
```
In kernel/trace/trace_events_user.c (ffffffff812c5e6f)
Location: include/linux/mmap_lock.h:32
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
In kernel/bpf/task_iter.c (ffffffff81324596)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_find_vma
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In kernel/bpf/stackmap.c (ffffffff813544f6)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff81368154)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff8138121f)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:xol_add_vma
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/oom_kill.c (ffffffff81396905)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff813ae123)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/vmscan.c:walk_mm
```
```
In mm/util.c (ffffffff813c4210)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/gup.c (ffffffff813e5e72)
Location: include/linux/mmap_lock.h:32
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
In mm/memory.c (ffffffff813f5700)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
```
```
In mm/mincore.c (ffffffff813f61bd)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
```
In mm/mlock.c (ffffffff813f767d)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff813fe3e6)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:expand_stack
  - mm/mmap.c:expand_stack
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff81402388)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff814065a8)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff81406efd)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff814185af)
Location: include/linux/mmap_lock.h:32
Inline: True
```
```
In mm/madvise.c (ffffffff814291e3)
Location: include/linux/mmap_lock.h:32
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
In mm/swapfile.c (ffffffff81432a21)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb_vmemmap.c (ffffffff8144725d)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_alloc
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
```
```
In mm/mempolicy.c (ffffffff8144cee0)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff8144fd65)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff81457c04)
Location: include/linux/mmap_lock.h:32
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
In mm/migrate.c (ffffffff8146820e)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff814785de)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff814824b2)
Location: include/linux/mmap_lock.h:32
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
In mm/memcontrol.c (ffffffff81488c3c)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_can_attach
```
```
In mm/memory-failure.c (ffffffff81494a06)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In mm/userfaultfd.c (ffffffff814a26b5)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/ptdump.c (ffffffff814a6e04)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff814b94e4)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:get_arg_page
  - fs/exec.c:get_arg_page
  - fs/exec.c:get_arg_page
```
```
In fs/userfaultfd.c (ffffffff81525b5d)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff8152932c)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/binfmt_elf.c (ffffffff81546a64)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff815497e3)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/coredump.c (ffffffff8154f743)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/task_mmu.c (ffffffff815650ec)
Location: include/linux/mmap_lock.h:32
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
In fs/proc/base.c (ffffffff81570111)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In ipc/shm.c (ffffffff81680a1d)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In security/tomoyo/domain.c (ffffffff816ea234)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In io_uring/rsrc.c (ffffffff817e332f)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_pin_pages
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b2a0c9)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In net/ipv4/tcp.c (ffffffff81f0f2cf)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff8206c508)
Location: include/linux/mmap_lock.h:32
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
In arch/x86/entry/vdso/vma.c (ffffffff81006d4e)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/process_64.c (ffffffff81051883)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a66a)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109cd7c)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109df66)
Location: include/linux/mmap_lock.h:32
Inline: True
```
```
In arch/x86/kernel/shstk.c (ffffffff810ca404)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/shstk.c:shstk_pop_sigframe
  - arch/x86/kernel/shstk.c:alloc_shstk
```
```
In kernel/fork.c (ffffffff810fbf9e)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff81106505)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff8112477e)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:prctl_set_vma
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/sched/fair.c (ffffffff811696af)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex/core.c (ffffffff8121f0c3)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/futex/core.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff81229fe2)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff812a6ace)
Location: include/linux/mmap_lock.h:32
Inline: True
```
```
In kernel/trace/trace_events_user.c (ffffffff812e26c3)
Location: include/linux/mmap_lock.h:32
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
In kernel/bpf/task_iter.c (ffffffff813497ed)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_iter_task_vma_new
  - kernel/bpf/task_iter.c:bpf_find_vma
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In kernel/bpf/stackmap.c (ffffffff8137ce66)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff81391073)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff813aa5cf)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:xol_add_vma
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/oom_kill.c (ffffffff813c0215)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff813d7753)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/vmscan.c:walk_mm
```
```
In mm/util.c (ffffffff813eedc0)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/gup.c (ffffffff814109ae)
Location: include/linux/mmap_lock.h:32
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
In mm/memory.c (ffffffff8141f3e0)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
```
```
In mm/mincore.c (ffffffff81421e6d)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
```
In mm/mlock.c (ffffffff8142325d)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff8142a7c5)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:expand_stack
  - mm/mmap.c:expand_stack
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff8142e9b8)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff81432cb8)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff814335ad)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff814450ff)
Location: include/linux/mmap_lock.h:32
Inline: True
```
```
In mm/madvise.c (ffffffff81462a13)
Location: include/linux/mmap_lock.h:32
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
In mm/swapfile.c (ffffffff8146be40)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb_vmemmap.c (ffffffff814805aa)
Location: include/linux/mmap_lock.h:32
Inline: True
```
```
In mm/mempolicy.c (ffffffff814867cf)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff81489a95)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff814926d4)
Location: include/linux/mmap_lock.h:32
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
In mm/migrate.c (ffffffff81496e6e)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff814a7d0e)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff814b184e)
Location: include/linux/mmap_lock.h:32
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
In mm/memcontrol.c (ffffffff814b82bc)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_can_attach
```
```
In mm/memory-failure.c (ffffffff814c4316)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In mm/userfaultfd.c (ffffffff814d2774)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/ptdump.c (ffffffff814d7e04)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff814ebfeb)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:get_arg_page
  - fs/exec.c:get_arg_page
  - fs/exec.c:get_arg_page
```
```
In fs/userfaultfd.c (ffffffff81559573)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_move
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
```
```
In fs/aio.c (ffffffff8155e1fc)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/binfmt_elf.c (ffffffff8157beb4)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8157ea63)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/coredump.c (ffffffff81585582)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/task_mmu.c (ffffffff8159bdaa)
Location: include/linux/mmap_lock.h:32
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
In fs/proc/base.c (ffffffff815a8aa1)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In ipc/shm.c (ffffffff816bce3c)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In security/tomoyo/domain.c (ffffffff81726f44)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In io_uring/rsrc.c (ffffffff818273e5)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_pin_pages
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b81299)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In net/ipv4/tcp.c (ffffffff81fd34ac)
Location: include/linux/mmap_lock.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff82140306)
Location: include/linux/mmap_lock.h:32
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
