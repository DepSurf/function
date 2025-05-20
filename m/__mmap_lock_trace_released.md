# Function: <code>__mmap_lock_trace_released</code>

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
In arch/x86/entry/vdso/vma.c (ffffffff81004cf7)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810678c2)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81067dea)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/mm/fault.c (ffffffff81088188)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area
```
```
In kernel/fork.c (ffffffff810a0efa)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810a73e2)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/exit.c:mmap_read_unlock
```
```
In kernel/sys.c (ffffffff810c0136)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/sched/fair.c (ffffffff810e791e)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex.c (ffffffff81156cf9)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/futex.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff81165f46)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff811c3b50)
Location: include/linux/mmap_lock.h:39
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff81233684)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/bpf/stackmap.c:do_up_read
```
```
In kernel/events/core.c (ffffffff8123c3f3)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff8125167c)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:xol_add_vma
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/filemap.c (ffffffff8125e0cb)
Location: include/linux/mmap_lock.h:39
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
In mm/oom_kill.c (ffffffff81261deb)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reap_task_mm
```
```
In mm/shmem.c (ffffffff8127a648)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff8127dc64)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/gup.c (ffffffff81293c07)
Location: include/linux/mmap_lock.h:39
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
In mm/memory.c (ffffffff812a04ef)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mincore.c (ffffffff812a0fa7)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mlock.c (ffffffff812a2e7f)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff812a8224)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff812a972c)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff812ac8d4)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff812ace16)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff812b89ea)
Location: include/linux/mmap_lock.h:39
Inline: True
```
```
In mm/madvise.c (ffffffff812c0f2d)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/madvise.c:madvise_remove
```
```
In mm/swapfile.c (ffffffff812c9c31)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff812dba8b)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:lookup_node
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff812ddf05)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff812e273a)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
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
In mm/migrate.c (ffffffff812ed668)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat_array
  - mm/migrate.c:add_page_for_migration
```
```
In mm/khugepaged.c (ffffffff812ff378)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff81305418)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_count_precharge
```
```
In mm/userfaultfd.c (ffffffff81314f39)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/frame_vector.c (ffffffff813157de)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
```
In mm/ptdump.c (ffffffff81318d07)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff813291e8)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:__bprm_mm_init
  - fs/exec.c:__bprm_mm_init
```
```
In fs/userfaultfd.c (ffffffff81380629)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff81385243)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff81396a10)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_unaccount_mem
```
```
In fs/binfmt_elf.c (ffffffff813b09c3)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff813b34c3)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/coredump.c (ffffffff813b97ee)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/task_mmu.c (ffffffff813c87c3)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff813d1357)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In ipc/shm.c (ffffffff814aeabb)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In drivers/iommu/intel/svm.c (ffffffff817b5bc6)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ad49f)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b26a8)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
```
In net/ipv4/tcp.c (ffffffff81ab70ca)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff81bb807e)
Location: include/linux/mmap_lock.h:39
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
In arch/x86/entry/vdso/vma.c (ffffffff81004ce4)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81067a11)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068354)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff810699fe)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
```
In arch/x86/mm/fault.c (ffffffff81088c50)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area
```
```
In kernel/fork.c (ffffffff810a1c71)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810a8472)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/exit.c:mmap_read_unlock
```
```
In kernel/sys.c (ffffffff810c1b35)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/sched/fair.c (ffffffff810e97eb)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex.c (ffffffff81158106)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/futex.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff81166c70)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff811c4c5d)
Location: include/linux/mmap_lock.h:39
Inline: True
```
```
In kernel/bpf/task_iter.c (ffffffff8121bcd1)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_stop
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In kernel/bpf/stackmap.c (ffffffff8123743c)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/bpf/stackmap.c:do_up_read
```
```
In kernel/events/core.c (ffffffff81240a3d)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff8125787a)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handler_chain
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/filemap.c (ffffffff81260d86)
Location: include/linux/mmap_lock.h:39
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
In mm/oom_kill.c (ffffffff81266929)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/shmem.c (ffffffff8127f785)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff81282e31)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/gup.c (ffffffff812995a1)
Location: include/linux/mmap_lock.h:39
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
In mm/memory.c (ffffffff812a5e2c)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mincore.c (ffffffff812a66aa)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mlock.c (ffffffff812a86d9)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff812abc2f)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff812aebb6)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff812b1bcb)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff812b20ff)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff812bdeb4)
Location: include/linux/mmap_lock.h:39
Inline: True
```
```
In mm/madvise.c (ffffffff812c8154)
Location: include/linux/mmap_lock.h:39
Inline: True
```
```
In mm/swapfile.c (ffffffff812d0b0b)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff812e3316)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff812e54b2)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff812e9ec7)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
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
In mm/migrate.c (ffffffff812f3982)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff81300735)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff81305ff5)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff8130acf2)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/userfaultfd.c (ffffffff8131b676)
Location: include/linux/mmap_lock.h:39
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
```
```
In mm/ptdump.c (ffffffff8131eef4)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff8132eff2)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:__bprm_mm_init
  - fs/exec.c:__bprm_mm_init
```
```
In fs/userfaultfd.c (ffffffff81387138)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff8138bff0)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff81391a12)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/binfmt_elf.c (ffffffff813b7b05)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff813ba4b0)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/coredump.c (ffffffff813c0949)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/task_mmu.c (ffffffff813cf7f7)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff813d8254)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In ipc/shm.c (ffffffff814b48d8)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In drivers/iommu/intel/svm.c (ffffffff81798f1e)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81890631)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818959c5)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
```
In net/ipv4/tcp.c (ffffffff81aa22c3)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff81ba7248)
Location: include/linux/mmap_lock.h:39
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
In arch/x86/entry/vdso/vma.c (ffffffff810052f3)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81071e01)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810727ca)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff810740ff)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
```
In arch/x86/mm/fault.c (ffffffff81098081)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area
```
```
In kernel/fork.c (ffffffff810b32ed)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810b9f10)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/exit.c:mmap_read_unlock
```
```
In kernel/sys.c (ffffffff810d48e0)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/sched/fair.c (ffffffff81101072)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex.c (ffffffff8117d028)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/futex.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff8118c427)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff811f0195)
Location: include/linux/mmap_lock.h:39
Inline: True
```
```
In kernel/bpf/task_iter.c (ffffffff81252bc7)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_stop
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In kernel/bpf/stackmap.c (ffffffff81271a10)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/bpf/stackmap.c:do_up_read
```
```
In kernel/events/core.c (ffffffff8127b49f)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff81293345)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handler_chain
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/filemap.c (ffffffff8129d7dc)
Location: include/linux/mmap_lock.h:39
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
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_reaper
```
```
In mm/shmem.c (ffffffff812bda33)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff812c0f17)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/gup.c (ffffffff812d9edf)
Location: include/linux/mmap_lock.h:39
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
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mincore.c (ffffffff812e7b6d)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mlock.c (ffffffff812e9d09)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff812ed328)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff812f0396)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff812f378b)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff812f3ce9)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff8130065b)
Location: include/linux/mmap_lock.h:39
Inline: True
```
```
In mm/madvise.c (ffffffff8130d122)
Location: include/linux/mmap_lock.h:39
Inline: True
```
```
In mm/swapfile.c (ffffffff813161de)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff8132a4ff)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:lookup_node
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/sparse-vmemmap.c (ffffffff8132c8e3)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_remap_alloc
  - mm/sparse-vmemmap.c:vmemmap_remap_free
```
```
In mm/mmu_notifier.c (ffffffff8132d094)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff81331de9)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
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
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff8134a3c9)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff8134fe56)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff81353402)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
```
```
In mm/memory-failure.c (ffffffff81cc2fdd)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In mm/userfaultfd.c (ffffffff8136893d)
Location: include/linux/mmap_lock.h:39
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
```
```
In mm/ptdump.c (ffffffff8136c2c6)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff8137c7d8)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:__bprm_mm_init
  - fs/exec.c:__bprm_mm_init
  - fs/exec.c:get_arg_page
```
```
In fs/userfaultfd.c (ffffffff813d4415)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff813d959b)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff813df910)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/binfmt_elf.c (ffffffff814077f4)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8140a1aa)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/coredump.c (ffffffff814107b0)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/task_mmu.c (ffffffff81420bce)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff81429984)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In ipc/shm.c (ffffffff8150cf80)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In security/tomoyo/domain.c (ffffffff81565114)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In drivers/iommu/io-pgfault.c (ffffffff8182ff10)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - drivers/iommu/io-pgfault.c:iopf_handle_single
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8192420c)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff8192992c)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
```
```
In net/ipv4/tcp.c (ffffffff81b5e14a)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff81c74fbd)
Location: include/linux/mmap_lock.h:39
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
In arch/x86/entry/vdso/vma.c (ffffffff81004359)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8108015c)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81080aad)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81082637)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
```
In arch/x86/mm/fault.c (ffffffff810aacbd)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area
```
```
In kernel/fork.c (ffffffff810c950d)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810d2c9a)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff810ed25d)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:prctl_set_vma
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/sched/fair.c (ffffffff8111c79e)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex/core.c (ffffffff811b2bf6)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/futex/core.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff811bb96e)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff812287a6)
Location: include/linux/mmap_lock.h:39
Inline: True
```
```
In kernel/bpf/task_iter.c (ffffffff8129a78e)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:do_mmap_read_unlock
  - kernel/bpf/task_iter.c:bpf_find_vma
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In kernel/bpf/stackmap.c (ffffffff812c0b8b)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff812cf2a7)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff812e8e22)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handler_chain
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/filemap.c (ffffffff812f4893)
Location: include/linux/mmap_lock.h:39
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
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_reaper
```
```
In mm/shmem.c (ffffffff813197a6)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff8131dd71)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/gup.c (ffffffff8133b291)
Location: include/linux/mmap_lock.h:39
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
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mincore.c (ffffffff81348de5)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mlock.c (ffffffff81349c69)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff81350601)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff81353766)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff81357556)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff81357b16)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff813679fb)
Location: include/linux/mmap_lock.h:39
Inline: True
```
```
In mm/madvise.c (ffffffff81378b01)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
  - mm/madvise.c:do_madvise
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/swapfile.c (ffffffff8138136a)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff81399bde)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/sparse-vmemmap.c (ffffffff8139c953)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_remap_alloc
  - mm/sparse-vmemmap.c:vmemmap_remap_free
```
```
In mm/mmu_notifier.c (ffffffff8139d342)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff813a2f73)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
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
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff813c0f59)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff813c8072)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff813cdf32)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_can_attach
```
```
In mm/memory-failure.c (ffffffff81e754e7)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In mm/userfaultfd.c (ffffffff813e625c)
Location: include/linux/mmap_lock.h:39
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
```
```
In mm/ptdump.c (ffffffff813ea5a9)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff813fb087)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:get_arg_page
```
```
In fs/userfaultfd.c (ffffffff8145f208)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff8146363e)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/binfmt_elf.c (ffffffff8147c513)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8147eeb9)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/coredump.c (ffffffff81484a9e)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/task_mmu.c (ffffffff81498a16)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff814a2dcf)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In ipc/shm.c (ffffffff8159eeba)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In security/tomoyo/domain.c (ffffffff8160090c)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In io_uring/io_uring.c (ffffffff816ca126)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_pin_pages
```
```
In drivers/iommu/io-pgfault.c (ffffffff8197116a)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - drivers/iommu/io-pgfault.c:iopf_handle_single
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a796d1)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a7f9cd)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
```
```
In net/ipv4/tcp.c (ffffffff81cecb1e)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff81e18fb4)
Location: include/linux/mmap_lock.h:39
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
In arch/x86/entry/vdso/vma.c (ffffffff81004c9c)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109030e)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810929ea)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093a82)
Location: include/linux/mmap_lock.h:39
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff810950b4)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
```
In arch/x86/mm/fault.c (ffffffff810c49b6)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area
```
```
In kernel/fork.c (ffffffff810e6a69)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810f17a2)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff8110e67d)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:prctl_set_vma
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/sched/fair.c (ffffffff81144376)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex/core.c (ffffffff811f3aa6)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/futex/core.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff811fd7e4)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff81273e4f)
Location: include/linux/mmap_lock.h:39
Inline: True
```
```
In kernel/bpf/task_iter.c (ffffffff812f6a0e)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:do_mmap_read_unlock
  - kernel/bpf/task_iter.c:bpf_find_vma
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In kernel/bpf/stackmap.c (ffffffff8132441b)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff813372a0)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff813500dc)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:xol_add_vma
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/filemap.c (ffffffff8135e9d3)
Location: include/linux/mmap_lock.h:39
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
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff813797ae)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/vmscan.c:walk_mm
```
```
In mm/shmem.c (ffffffff8138d758)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff8139186e)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/gup.c (ffffffff813b1ca1)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
  - mm/gup.c:get_dump_page
  - mm/gup.c:fault_in_safe_writeable
  - mm/gup.c:__mm_populate
```
```
In mm/memory.c (ffffffff813c0a66)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mincore.c (ffffffff813c14b0)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mlock.c (ffffffff813c2759)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff813c9f34)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff813cdb7d)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff813d1c85)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff813d22bc)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff813e39bb)
Location: include/linux/mmap_lock.h:39
Inline: True
```
```
In mm/madvise.c (ffffffff813f6431)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
  - mm/madvise.c:do_madvise
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/swapfile.c (ffffffff813ffbc0)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb_vmemmap.c (ffffffff81413d14)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
```
```
In mm/mempolicy.c (ffffffff81419b2f)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff8141c7c2)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff81422bf0)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
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
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff81442e1e)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff8144cb39)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff81453015)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_can_attach
```
```
In mm/memory-failure.c (ffffffff8145ec08)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In mm/userfaultfd.c (ffffffff8146dd0f)
Location: include/linux/mmap_lock.h:39
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
```
```
In mm/ptdump.c (ffffffff814726d9)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff81484984)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:get_arg_page
```
```
In fs/userfaultfd.c (ffffffff814eef7e)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff814f272e)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/binfmt_elf.c (ffffffff8150f1c3)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff81511e3c)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/coredump.c (ffffffff81517f6e)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/task_mmu.c (ffffffff8152ccd1)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff815380fb)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In ipc/shm.c (ffffffff816485d6)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In security/tomoyo/domain.c (ffffffff816b185c)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In io_uring/rsrc.c (ffffffff817a2280)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_pin_pages
```
```
In drivers/iommu/iommu-sva.c (ffffffff81adbf09)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In net/ipv4/tcp.c (ffffffff81eb0a1f)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff81ff0389)
Location: include/linux/mmap_lock.h:39
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
In arch/x86/entry/vdso/vma.c (ffffffff81004484)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/process_64.c (ffffffff8104a7c1)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109322f)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81095920)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096a0b)
Location: include/linux/mmap_lock.h:39
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109803f)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
```
In arch/x86/mm/fault.c (ffffffff810c8203)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area
```
```
In kernel/fork.c (ffffffff810f2420)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff810fd6f4)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff8111ac56)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:prctl_set_vma
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/sched/fair.c (ffffffff81154b20)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex/core.c (ffffffff81208249)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/futex/core.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff8121296b)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff8128b76c)
Location: include/linux/mmap_lock.h:39
Inline: True
```
```
In kernel/trace/trace_events_user.c (ffffffff812c5e8f)
Location: include/linux/mmap_lock.h:39
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
In kernel/bpf/task_iter.c (ffffffff813248de)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:do_mmap_read_unlock
  - kernel/bpf/task_iter.c:bpf_find_vma
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In kernel/bpf/stackmap.c (ffffffff8135467b)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff8136818a)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff813812ba)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:xol_add_vma
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/filemap.c (ffffffff8139176b)
Location: include/linux/mmap_lock.h:39
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
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff813ae1a4)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/vmscan.c:walk_mm
```
```
In mm/shmem.c (ffffffff813c0113)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff813c4244)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/gup.c (ffffffff813e5fa1)
Location: include/linux/mmap_lock.h:39
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
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mincore.c (ffffffff813f61e7)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
```
In mm/mlock.c (ffffffff813f76a1)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff813fe445)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:do_vmi_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:expand_stack
  - mm/mmap.c:expand_stack
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff814023c7)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff8140678d)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff81406e81)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff81418709)
Location: include/linux/mmap_lock.h:39
Inline: True
```
```
In mm/madvise.c (ffffffff8142921f)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
  - mm/madvise.c:do_madvise
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/swapfile.c (ffffffff81432a58)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb_vmemmap.c (ffffffff8144726e)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_alloc
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
```
```
In mm/mempolicy.c (ffffffff8144cfd5)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff8144fd75)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff81457c09)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
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
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff814786ed)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff814823ea)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff81488c68)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_can_attach
```
```
In mm/memory-failure.c (ffffffff81494a5b)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In mm/userfaultfd.c (ffffffff814a2759)
Location: include/linux/mmap_lock.h:39
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
```
```
In mm/ptdump.c (ffffffff814a6e2d)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff814b9567)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:get_arg_page
  - fs/exec.c:get_arg_page
```
```
In fs/userfaultfd.c (ffffffff81525f27)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff81529367)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/binfmt_elf.c (ffffffff81546a80)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff815497ff)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/coredump.c (ffffffff8154f86a)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/task_mmu.c (ffffffff81565111)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff81570368)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In ipc/shm.c (ffffffff81680b2a)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In security/tomoyo/domain.c (ffffffff816ea25d)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In io_uring/rsrc.c (ffffffff817e336b)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_pin_pages
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b2a133)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In net/ipv4/tcp.c (ffffffff81f0f316)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff8206c534)
Location: include/linux/mmap_lock.h:39
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
In arch/x86/entry/vdso/vma.c (ffffffff81006d93)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso_once
  - arch/x86/entry/vdso/vma.c:map_vdso
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/process_64.c (ffffffff81051914)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a69f)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109ce60)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109df7b)
Location: include/linux/mmap_lock.h:39
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109f5df)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
```
In arch/x86/kernel/shstk.c (ffffffff810ca47f)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/shstk.c:shstk_pop_sigframe
  - arch/x86/kernel/shstk.c:shstk_pop_sigframe
  - arch/x86/kernel/shstk.c:alloc_shstk
```
```
In arch/x86/mm/fault.c (ffffffff810d06b5)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area
```
```
In kernel/fork.c (ffffffff810fbff0)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffffffff81106564)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff811247ac)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:prctl_set_vma
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/sched/fair.c (ffffffff811699d9)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/futex/core.c (ffffffff8121f0d9)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/futex/core.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff8122a004)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff812a6b26)
Location: include/linux/mmap_lock.h:39
Inline: True
```
```
In kernel/trace/trace_events_user.c (ffffffff812e26e3)
Location: include/linux/mmap_lock.h:39
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
In kernel/bpf/task_iter.c (ffffffff8134874e)
Location: include/linux/mmap_lock.h:39
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
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffff813910a9)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff813aa66a)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:xol_add_vma
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/filemap.c (0)
Location: include/linux/mmap_lock.h:39
Inline: True
```
```
In mm/oom_kill.c (ffffffff813c023c)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff813d77d4)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/vmscan.c:walk_mm
```
```
In mm/shmem.c (ffffffff813e7806)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/shmem.c:shmem_falloc_wait
```
```
In mm/util.c (ffffffff813eedf6)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/gup.c (ffffffff81410b81)
Location: include/linux/mmap_lock.h:39
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
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mincore.c (ffffffff81421e97)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
```
In mm/mlock.c (ffffffff81423281)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_munlockall
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff8142a83a)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:do_vmi_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:expand_stack
  - mm/mmap.c:expand_stack
  - mm/mmap.c:__do_sys_brk
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mprotect.c (ffffffff8142e9f7)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff81432e9c)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff81433531)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff81445259)
Location: include/linux/mmap_lock.h:39
Inline: True
```
```
In mm/madvise.c (ffffffff81462a4f)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
  - mm/madvise.c:do_madvise
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/swapfile.c (ffffffff8146be77)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb_vmemmap.c (ffffffff814805ce)
Location: include/linux/mmap_lock.h:39
Inline: True
```
```
In mm/mempolicy.c (ffffffff814868c8)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/mmu_notifier.c (ffffffff81489aa5)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_register
```
```
In mm/ksm.c (ffffffff814926d9)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
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
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff814a7e12)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff814b1786)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffffffff814b82e8)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge
  - mm/memcontrol.c:mem_cgroup_can_attach
```
```
In mm/memory-failure.c (ffffffff814c436b)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In mm/userfaultfd.c (ffffffff814d2818)
Location: include/linux/mmap_lock.h:39
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
```
```
In mm/ptdump.c (ffffffff814d7e2d)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff814ec06b)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:alloc_bprm
  - fs/exec.c:exec_mmap
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:get_arg_page
  - fs/exec.c:get_arg_page
```
```
In fs/userfaultfd.c (ffffffff815595a2)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_move
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (ffffffff8155e239)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In fs/binfmt_elf.c (ffffffff8157bed0)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8157ea7f)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/coredump.c (ffffffff815856a9)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/task_mmu.c (ffffffff8159bc2b)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:do_pagemap_scan
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/base.c (ffffffff815a8cff)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In ipc/shm.c (ffffffff816bcf49)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
```
```
In security/tomoyo/domain.c (ffffffff81726f6d)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In io_uring/rsrc.c (ffffffff8182740d)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_pin_pages
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b81303)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In net/ipv4/tcp.c (ffffffff81fd34ef)
Location: include/linux/mmap_lock.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff82140332)
Location: include/linux/mmap_lock.h:39
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
