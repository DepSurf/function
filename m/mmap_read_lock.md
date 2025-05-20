# Function: <code>mmap_read_lock</code>

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
In arch/x86/mm/fault.c (ffffffff81087bfe)
Location: include/linux/mmap_lock.h:44
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/exit.c (ffffffff810adfac)
Location: include/linux/mmap_lock.h:44
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff810c2a78)
Location: include/linux/mmap_lock.h:44
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/futex.c (ffffffff8115c67e)
Location: include/linux/mmap_lock.h:44
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:fixup_pi_state_owner
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
```
```
In kernel/acct.c (ffffffff811697a8)
Location: include/linux/mmap_lock.h:44
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff811c662d)
Location: include/linux/mmap_lock.h:44
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:trace_user_stack_print
```
```
In kernel/events/core.c (ffffffff81232790)
Location: include/linux/mmap_lock.h:44
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff81246fec)
Location: include/linux/mmap_lock.h:44
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In mm/gup.c (ffffffff8128b4f2)
Location: include/linux/mmap_lock.h:44
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:__mm_populate
  - mm/gup.c:fixup_user_fault
```
```
In mm/mincore.c (ffffffff812961f1)
Location: include/linux/mmap_lock.h:44
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/msync.c (ffffffff812a1624)
Location: include/linux/mmap_lock.h:44
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff812acc93)
Location: include/linux/mmap_lock.h:44
Inline: True
Inline callers:
  - mm/process_vm_access.c:process_vm_rw_single_vec
```
```
In mm/madvise.c (ffffffff812b5a24)
Location: include/linux/mmap_lock.h:44
Inline: True
Inline callers:
  - mm/madvise.c:madvise_remove
  - mm/madvise.c:madvise_willneed
```
```
In mm/swapfile.c (ffffffff812be41f)
Location: include/linux/mmap_lock.h:44
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff812ce09c)
Location: include/linux/mmap_lock.h:44
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/ksm.c (ffffffff812d5814)
Location: include/linux/mmap_lock.h:44
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff812e2353)
Location: include/linux/mmap_lock.h:44
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/khugepaged.c (ffffffff812f25d4)
Location: include/linux/mmap_lock.h:44
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff812fb7e6)
Location: include/linux/mmap_lock.h:44
Inline: True
```
```
In mm/userfaultfd.c (ffffffff81309039)
Location: include/linux/mmap_lock.h:44
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/frame_vector.c (ffffffff81309940)
Location: include/linux/mmap_lock.h:44
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
```
In mm/ptdump.c (ffffffff8130cd83)
Location: include/linux/mmap_lock.h:44
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff8131dc70)
Location: include/linux/mmap_lock.h:44
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
```
```
In fs/io_uring.c (ffffffff8137f495)
Location: include/linux/mmap_lock.h:44
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In drivers/iommu/intel/svm.c (ffffffff817a9761)
Location: include/linux/mmap_lock.h:44
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189e0d4)
Location: include/linux/mmap_lock.h:44
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a29a9)
Location: include/linux/mmap_lock.h:44
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
```
In net/ipv4/tcp.c (ffffffff81aa99b3)
Location: include/linux/mmap_lock.h:44
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff81ba82eb)
Location: include/linux/mmap_lock.h:44
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
void mmap_read_lock(struct mm_struct *mm);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004bb9)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810677ae)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81067d92)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/mm/fault.c (ffffffff8108832c)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/exit.c (ffffffff810a7400)
Location: include/linux/mmap_lock.h:114
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff810bde67)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/futex.c (ffffffff81156cc3)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/futex.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff81165edf)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff811c3ae6)
Location: include/linux/mmap_lock.h:114
Inline: True
```
```
In kernel/events/core.c (ffffffff8123c388)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff8125162c)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In mm/gup.c (ffffffff81295219)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:__mm_populate
  - mm/gup.c:fixup_user_fault
```
```
In mm/mincore.c (ffffffff812a0f58)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/msync.c (ffffffff812ace78)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff812b8899)
Location: include/linux/mmap_lock.h:114
Inline: True
```
```
In mm/madvise.c (ffffffff812c0ee4)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/madvise.c:madvise_remove
```
```
In mm/swapfile.c (ffffffff812c9bb5)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff812d9690)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/ksm.c (ffffffff812e1294)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff812ed5c5)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat_array
  - mm/migrate.c:add_page_for_migration
```
```
In mm/khugepaged.c (ffffffff812fca8d)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff81301485)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_count_precharge
```
```
In mm/userfaultfd.c (ffffffff81314e77)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/frame_vector.c (ffffffff8131574b)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
```
In mm/ptdump.c (ffffffff81318cbf)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff81329110)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
```
```
In fs/io_uring.c (ffffffff8138d94b)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In drivers/iommu/intel/svm.c (ffffffff817b5b37)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ad406)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b26cd)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
```
In net/ipv4/tcp.c (ffffffff81ab6ef5)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff81bb8032)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_pin_pages
```
**Symbols:**

```
ffffffff810a7400-ffffffff810a743e: mmap_read_lock (STB_LOCAL)
ffffffff81313b60-ffffffff81313ba4: mmap_read_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void mmap_read_lock(struct mm_struct *mm);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004ba9)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8106789a)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068302)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/mm/fault.c (ffffffff81088e47)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/exit.c (ffffffff810a8490)
Location: include/linux/mmap_lock.h:114
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff810bf6fc)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/futex.c (ffffffff811580d3)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/futex.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff81166c0f)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff811c4bf6)
Location: include/linux/mmap_lock.h:114
Inline: True
```
```
In kernel/events/core.c (ffffffff812409d8)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff812577ad)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handler_chain
```
```
In mm/gup.c (ffffffff8129abe3)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:__mm_populate
  - mm/gup.c:fixup_user_fault
```
```
In mm/mincore.c (ffffffff812a6710)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/msync.c (ffffffff812b215f)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff812bdd63)
Location: include/linux/mmap_lock.h:114
Inline: True
```
```
In mm/madvise.c (ffffffff812c8048)
Location: include/linux/mmap_lock.h:114
Inline: True
```
```
In mm/swapfile.c (ffffffff812d0aab)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff812e0f10)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/ksm.c (ffffffff812e899b)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff812f3902)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff813005ee)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff8130383b)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff8130e3ea)
Location: include/linux/mmap_lock.h:114
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8131b5b7)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
Direct callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/ptdump.c (ffffffff8131eeaf)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff8132ef20)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
```
```
In fs/io_uring.c (ffffffff813919b0)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In drivers/iommu/intel/svm.c (ffffffff81798e59)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81890588)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818959ea)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
```
In net/ipv4/tcp.c (ffffffff81aa20f5)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff81ba7202)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_pin_pages
```
**Symbols:**

```
ffffffff810a8490-ffffffff810a84cb: mmap_read_lock (STB_LOCAL)
ffffffff81319d00-ffffffff81319d41: mmap_read_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void mmap_read_lock(struct mm_struct *mm);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff810051d9)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81071c7a)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81072782)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/mm/fault.c (ffffffff810982b6)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810b3295)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:replace_mm_exe_file
```
```
In kernel/exit.c (ffffffff810b9f30)
Location: include/linux/mmap_lock.h:114
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff810d217c)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/futex.c (ffffffff8117d003)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/futex.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff8118c3cf)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff811f0136)
Location: include/linux/mmap_lock.h:114
Inline: True
```
```
In kernel/events/core.c (ffffffff8127b449)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff812933a5)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handler_chain
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In mm/gup.c (ffffffff812db593)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:__mm_populate
  - mm/gup.c:fixup_user_fault
```
```
In mm/mincore.c (ffffffff812e7bd8)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/msync.c (ffffffff812f3d5a)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff81300513)
Location: include/linux/mmap_lock.h:114
Inline: True
```
```
In mm/madvise.c (ffffffff8130ce20)
Location: include/linux/mmap_lock.h:114
Inline: True
```
```
In mm/swapfile.c (ffffffff81316186)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff813281e0)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/sparse-vmemmap.c (ffffffff8132c8c3)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_remap_alloc
```
```
In mm/ksm.c (ffffffff813308cb)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff8133deee)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff8134a28e)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff8134d59f)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff81359217)
Location: include/linux/mmap_lock.h:114
Inline: True
```
```
In mm/memory-failure.c (ffffffff81cc2f42)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In mm/userfaultfd.c (ffffffff81368887)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
Direct callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/ptdump.c (ffffffff8136c28f)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff8137c710)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - fs/exec.c:exec_mmap
  - fs/exec.c:get_arg_page
```
```
In fs/io_uring.c (ffffffff813df8af)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In security/tomoyo/domain.c (ffffffff815650db)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In drivers/iommu/io-pgfault.c (ffffffff8182fe97)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - drivers/iommu/io-pgfault.c:iopf_handle_single
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8192417d)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81929957)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
```
```
In net/ipv4/tcp.c (ffffffff81b5dece)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff81c74f7f)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
**Symbols:**

```
ffffffff810b9f30-ffffffff810b9f65: mmap_read_lock (STB_LOCAL)
ffffffff81366ac0-ffffffff81366afb: mmap_read_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void mmap_read_lock(struct mm_struct *mm);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004239)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107ffee)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81080a64)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/mm/fault.c (ffffffff810aaf12)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810c94b5)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:replace_mm_exe_file
```
```
In kernel/exit.c (ffffffff810d2c29)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff810ea4f7)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/futex/core.c (ffffffff811b2bd1)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/futex/core.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff811bb916)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff81228744)
Location: include/linux/mmap_lock.h:114
Inline: True
```
```
In kernel/events/core.c (ffffffff812cf252)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff812e8e98)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handler_chain
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In mm/gup.c (ffffffff8133b24e)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:fault_in_safe_writeable
  - mm/gup.c:__mm_populate
  - mm/gup.c:fixup_user_fault
```
```
In mm/mincore.c (ffffffff81348e50)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/msync.c (ffffffff81357b8c)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff8136788e)
Location: include/linux/mmap_lock.h:114
Inline: True
```
```
In mm/madvise.c (ffffffff81378b14)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_populate
```
```
In mm/swapfile.c (ffffffff81381319)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (ffffffff81397402)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/sparse-vmemmap.c (ffffffff8139c933)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_remap_alloc
  - mm/sparse-vmemmap.c:vmemmap_remap_free
```
```
In mm/ksm.c (ffffffff813a14eb)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff813b1442)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff813c0e36)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff813c6702)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/memcontrol.c (ffffffff813d2aed)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_can_attach
```
```
In mm/memory-failure.c (ffffffff81e75447)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In mm/userfaultfd.c (ffffffff813e619a)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
Direct callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/ptdump.c (ffffffff813ea56f)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_walk_pgd
```
```
In fs/exec.c (ffffffff813fa9fe)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - fs/exec.c:get_arg_page
```
```
In security/tomoyo/domain.c (ffffffff816008d3)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In io_uring/io_uring.c (ffffffff816ca0cd)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_pin_pages
```
```
In drivers/iommu/io-pgfault.c (ffffffff819710ef)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - drivers/iommu/io-pgfault.c:iopf_handle_single
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a795b3)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a7f9f8)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
```
```
In net/ipv4/tcp.c (ffffffff81cec8c1)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff81e18f77)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_pin_pages
```
**Symbols:**

```
ffffffff813e3e70-ffffffff813e3ebd: mmap_read_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void mmap_read_lock(struct mm_struct *mm);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004b14)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810902cf)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810928fb)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093a5f)
Location: include/linux/mmap_lock.h:114
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff810c4c15)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In kernel/fork.c (ffffffff810e6a16)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:replace_mm_exe_file
```
```
In kernel/exit.c (ffffffff810f1731)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff8110aff7)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/futex/core.c (ffffffff811f3a81)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/futex/core.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff811fd7ad)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff81273df0)
Location: include/linux/mmap_lock.h:114
Inline: True
```
```
In kernel/events/core.c (ffffffff8133725b)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff8135003b)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In mm/gup.c (ffffffff813b1c18)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:fault_in_safe_writeable
  - mm/gup.c:__mm_populate
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
```
```
In mm/mincore.c (ffffffff813c1478)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mmap.c (ffffffff813c9ec7)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
```
```
In mm/msync.c (ffffffff813d232d)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff813e384e)
Location: include/linux/mmap_lock.h:114
Inline: True
```
```
In mm/madvise.c (ffffffff813f6444)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_populate
```
```
In mm/swapfile.c (ffffffff813ffb73)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb_vmemmap.c (ffffffff81413cdb)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
```
```
In mm/mempolicy.c (ffffffff81416fe2)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/ksm.c (ffffffff81420639)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff81432112)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff81442d06)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff8144cc9f)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff814582c6)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_can_attach
```
```
In mm/memory-failure.c (ffffffff8145eba5)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In mm/userfaultfd.c (ffffffff8146dc5a)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
Direct callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/exec.c (ffffffff81485178)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - fs/exec.c:get_arg_page
```
```
In security/tomoyo/domain.c (ffffffff816b1823)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In io_uring/rsrc.c (ffffffff817a2224)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_pin_pages
```
```
In drivers/iommu/iommu-sva.c (ffffffff81adbe8f)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In net/ipv4/tcp.c (ffffffff81eb07d1)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff81ff034b)
Location: include/linux/mmap_lock.h:114
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
**Symbols:**

```
ffffffff8146b8c0-ffffffff8146b90d: mmap_read_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void mmap_read_lock(struct mm_struct *mm);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff810042f1)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810931e9)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109582b)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810969e5)
Location: include/linux/mmap_lock.h:145
Inline: True
```
```
In kernel/fork.c (ffffffff810f23b7)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:replace_mm_exe_file
```
```
In kernel/exit.c (ffffffff810fd681)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff811171c1)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/futex/core.c (ffffffff81208221)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - kernel/futex/core.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff8121292d)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff8128b704)
Location: include/linux/mmap_lock.h:145
Inline: True
```
```
In kernel/trace/trace_events_user.c (ffffffff812c5e5e)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl_unreg
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
  - kernel/trace/trace_events_user.c:update_enable_bit_for
  - kernel/trace/trace_events_user.c:user_event_enabler_fault_fixup
  - kernel/trace/trace_events_user.c:user_event_mm_fault_in
```
```
In kernel/events/core.c (ffffffff81368142)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff8138120b)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In mm/gup.c (ffffffff813e2e50)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - mm/gup.c:fault_in_safe_writeable
  - mm/gup.c:__mm_populate
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
```
```
In mm/mincore.c (ffffffff813f61ac)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
```
In mm/mmap.c (ffffffff813fe3cb)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
```
```
In mm/msync.c (ffffffff81406ef2)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff814185a1)
Location: include/linux/mmap_lock.h:145
Inline: True
```
```
In mm/madvise.c (ffffffff814291d2)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_populate
```
```
In mm/swapfile.c (ffffffff81432a07)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb_vmemmap.c (ffffffff8144724f)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_alloc
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
```
```
In mm/mempolicy.c (ffffffff8144a572)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/ksm.c (ffffffff814552ff)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff814681ed)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff814785c6)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff814825c4)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff8148e006)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_can_attach
```
```
In mm/memory-failure.c (ffffffff814949f5)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In mm/userfaultfd.c (ffffffff814a2690)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
Direct callers:
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In fs/exec.c (ffffffff814ba109)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - fs/exec.c:get_arg_page
```
```
In security/tomoyo/domain.c (ffffffff816ea223)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In io_uring/rsrc.c (ffffffff817e331e)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_pin_pages
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b2a0b5)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In net/ipv4/tcp.c (ffffffff81f0f2b4)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff8206c4f6)
Location: include/linux/mmap_lock.h:145
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
**Symbols:**

```
ffffffff814a06f0-ffffffff814a0740: mmap_read_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void mmap_read_lock(struct mm_struct *mm);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81006c00)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_join_timens
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a659)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109cd6b)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109df55)
Location: include/linux/mmap_lock.h:143
Inline: True
```
```
In kernel/fork.c (ffffffff810fbf86)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
```
```
In kernel/exit.c (ffffffff811064f1)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/sys.c (ffffffff81120bb1)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
```
In kernel/futex/core.c (ffffffff8121f0b1)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - kernel/futex/core.c:fault_in_user_writeable
```
```
In kernel/acct.c (ffffffff81229fc6)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - kernel/acct.c:acct_collect
```
```
In kernel/trace/trace_output.c (ffffffff812a6ab6)
Location: include/linux/mmap_lock.h:143
Inline: True
```
```
In kernel/trace/trace_events_user.c (ffffffff812e26b2)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl_unreg
  - kernel/trace/trace_events_user.c:update_enable_bit_for
  - kernel/trace/trace_events_user.c:user_event_enabler_create
  - kernel/trace/trace_events_user.c:user_event_enabler_fault_fixup
  - kernel/trace/trace_events_user.c:user_event_mm_fault_in
```
```
In kernel/events/core.c (ffffffff81391061)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
```
```
In kernel/events/uprobes.c (ffffffff813aa5bb)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In mm/gup.c (ffffffff8140d690)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - mm/gup.c:fault_in_safe_writeable
  - mm/gup.c:__mm_populate
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:fixup_user_fault
```
```
In mm/mincore.c (ffffffff81421e5c)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
```
In mm/mmap.c (ffffffff8142a7b1)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
```
```
In mm/msync.c (ffffffff814335a2)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
  - mm/msync.c:__do_sys_msync
```
```
In mm/process_vm_access.c (ffffffff814450f1)
Location: include/linux/mmap_lock.h:143
Inline: True
```
```
In mm/madvise.c (ffffffff81462a02)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_populate
```
```
In mm/swapfile.c (ffffffff8146be26)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb_vmemmap.c (ffffffff81480585)
Location: include/linux/mmap_lock.h:143
Inline: True
```
```
In mm/mempolicy.c (ffffffff81482b11)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/ksm.c (ffffffff8148f200)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff81496e4d)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff814a7cf6)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff814b1839)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff814bd986)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_can_attach
```
```
In mm/memory-failure.c (ffffffff814c4305)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In mm/userfaultfd.c (ffffffff814d274f)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
Direct callers:
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In fs/exec.c (ffffffff814ec689)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - fs/exec.c:get_arg_page
```
```
In fs/userfaultfd.c (ffffffff8155955f)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_move
```
```
In security/tomoyo/domain.c (ffffffff81726f33)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In io_uring/rsrc.c (ffffffff818273d4)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_pin_pages
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b81285)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In net/ipv4/tcp.c (ffffffff81fd3491)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
```
In net/xdp/xdp_umem.c (ffffffff821402f4)
Location: include/linux/mmap_lock.h:143
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
**Symbols:**

```
ffffffff814cfd90-ffffffff814cfde0: mmap_read_lock (STB_LOCAL)
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
