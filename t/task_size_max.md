# Function: <code>task_size_max</code>

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
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff810048db)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005250)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/core.c (ffffffff8100909e)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102a341)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_get_user_pgd
```
```
In arch/x86/kernel/process_64.c (ffffffff81035349)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
```
In arch/x86/kernel/signal.c (ffffffff81036493)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/kernel/traps.c (ffffffff81c275df)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_bug
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8103a16f)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_opcodes
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff8103c582)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff8103d005)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103fea4)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:arch_check_bp_in_kernelspace
  - arch/x86/kernel/hw_breakpoint.c:arch_check_bp_in_kernelspace
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81044334)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff81047093)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:putreg
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81048e06)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff810694a5)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
```
```
In arch/x86/mm/init.c (ffffffff831dd7ad)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/mm/init.c:poking_init
```
```
In arch/x86/mm/fault.c (ffffffff81c2a8c0)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
```
In arch/x86/mm/mmap.c (ffffffff8108a4bc)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:mmap_address_hint_valid
```
```
In arch/x86/mm/maccess.c (ffffffff8108c7f5)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/mm/maccess.c:copy_from_kernel_nofault_allowed
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81091888)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81096ae0)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
```
```
In kernel/fork.c (ffffffff810a4112)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/fork.c:__do_sys_clone3
```
```
In kernel/exit.c (ffffffff810aa1ac)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810b35e3)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_regset
```
```
In kernel/signal.c (ffffffff810bbce3)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
```
```
In kernel/sys.c (ffffffff810bf6dc)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:validate_prctl_map_addr
```
```
In kernel/sched/core.c (ffffffff810dbf35)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_attr_copy_to_user
```
```
In kernel/printk/printk.c (ffffffff8111a8b4)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff8113d03e)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:set_syscall_user_dispatch
```
```
In kernel/futex.c (ffffffff81157dd6)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:get_futex_key
```
```
In kernel/compat.c (ffffffff8116ad60)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/bpf_trace.c (ffffffff811e8622)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat
```
```
In kernel/trace/trace_kprobe.c (ffffffff811eba04)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/bpf/helpers.c (ffffffff81219d81)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
```
```
In kernel/events/core.c (ffffffff8125045b)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff81256cb0)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In kernel/rseq.c (ffffffff8125a7e3)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:rseq_get_rseq_cs
  - kernel/rseq.c:rseq_get_rseq_cs
  - kernel/rseq.c:rseq_get_rseq_cs
  - kernel/rseq.c:rseq_get_rseq_cs
```
```
In mm/maccess.c (ffffffff81267200)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/shmem.c (ffffffff8127baba)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_unmapped_area
```
```
In mm/gup.c (ffffffff8129ab6e)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8129f8ae)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff812a65c4)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mlock.c (ffffffff812a8613)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_mlockall
```
```
In mm/mmap.c (ffffffff812ab40f)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:get_unmapped_area
  - mm/mmap.c:get_unmapped_area
```
```
In mm/mmu_gather.c (ffffffff812ae790)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_gather_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mremap.c (ffffffff812b17b1)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - mm/mremap.c:mremap_to
  - mm/mremap.c:mremap_to
```
```
In mm/mempolicy.c (ffffffff812e3c6c)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In fs/read_write.c (ffffffff81325f8e)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_read
```
```
In fs/exec.c (ffffffff8132d0d1)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - fs/exec.c:setup_new_exec
  - fs/exec.c:__bprm_mm_init
```
```
In fs/readdir.c (ffffffff8133e3dc)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff813408b1)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In fs/eventpoll.c (ffffffff81382393)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/io_uring.c (ffffffff8139cd48)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:__io_compat_recvmsg_copy_hdr
  - fs/io_uring.c:io_import_iovec
```
```
In fs/binfmt_elf.c (ffffffff813b95a4)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
```
```
In fs/compat_binfmt_elf.c (ffffffff813bc196)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In lib/iov_iter.c (ffffffff815ab4be)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:__import_iovec
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In lib/usercopy.c (ffffffff815b7286)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In lib/strncpy_from_user.c (ffffffff815eac74)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff815ead99)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
  - lib/strnlen_user.c:strnlen_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff816058dd)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In arch/x86/lib/usercopy.c (ffffffff81608246)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81608305)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:clear_user
```
```
In drivers/pci/proc.c (ffffffff81647a67)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/acpi/acpi_dbg.c (ffffffff816ec04c)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
```
```
In drivers/char/mem.c (ffffffff8176d08e)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81892cc4)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unmap_dma
```
```
In drivers/usb/core/devio.c (ffffffff818ba74f)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In net/socket.c (ffffffff819c5aa4)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/core/scm.c (ffffffff819dc570)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - net/core/scm.c:put_cmsg
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
In arch/x86/entry/vdso/vma.c (ffffffff81004f0b)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
  - arch/x86/entry/vdso/vma.c:map_vdso_randomized
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005862)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/core.c (ffffffff81009f96)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102e946)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_get_user_pgd
```
```
In arch/x86/kernel/process_64.c (ffffffff8103a629)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
```
In arch/x86/kernel/signal.c (ffffffff8103b733)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/kernel/traps.c (ffffffff81d4562f)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_bug
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8103fb1f)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_opcodes
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff81042082)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff81042b05)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff81045e64)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:arch_check_bp_in_kernelspace
  - arch/x86/kernel/hw_breakpoint.c:arch_check_bp_in_kernelspace
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104ae4c)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104d4eb)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:putreg
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8104f7f6)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81073b55)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
```
```
In arch/x86/mm/init.c (ffffffff832c09be)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/mm/init.c:poking_init
```
```
In arch/x86/mm/fault.c (ffffffff81d48eaa)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
```
In arch/x86/mm/mmap.c (ffffffff81099a1c)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:mmap_address_hint_valid
```
```
In arch/x86/mm/maccess.c (ffffffff8109c035)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/mm/maccess.c:copy_from_kernel_nofault_allowed
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810a1408)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810a6a80)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810ade82)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
```
In kernel/fork.c (ffffffff810b5932)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/fork.c:__do_sys_clone3
```
```
In kernel/exit.c (ffffffff810bbcec)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810c5783)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_regset
```
```
In kernel/signal.c (ffffffff810ce743)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/signal.c:__x64_compat_sys_sigaction
  - kernel/signal.c:__x64_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
```
```
In kernel/sys.c (ffffffff810d215c)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:validate_prctl_map_addr
```
```
In kernel/sched/core.c (ffffffff810ef0a5)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_attr_copy_to_user
```
```
In kernel/printk/printk.c (ffffffff81139f5b)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff8116016e)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:set_syscall_user_dispatch
```
```
In kernel/futex.c (ffffffff8117cc56)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:get_futex_key
```
```
In kernel/compat.c (ffffffff81190e08)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/trace_eprobe.c (ffffffff81209b8e)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
```
```
In kernel/trace/bpf_trace.c (ffffffff812192a2)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121c936)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/bpf/helpers.c (ffffffff81250981)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
```
```
In kernel/events/core.c (ffffffff8128b1ad)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff81292a47)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In kernel/rseq.c (ffffffff812965d3)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In mm/maccess.c (ffffffff812a3c40)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/shmem.c (ffffffff812b9c2a)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_unmapped_area
```
```
In mm/gup.c (ffffffff812db51e)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff812e0b8a)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff812e7a94)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mlock.c (ffffffff812e9c5a)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_mlockall
```
```
In mm/mmap.c (ffffffff812ecaef)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:get_unmapped_area
  - mm/mmap.c:get_unmapped_area
```
```
In mm/mmu_gather.c (ffffffff812eff30)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_gather_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mremap.c (ffffffff812f3381)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - mm/mremap.c:mremap_to
  - mm/mremap.c:mremap_to
```
```
In mm/hugetlb.c (ffffffff81322465)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/mempolicy.c (ffffffff8132af5a)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In mm/memory-failure.c (ffffffff81cc2f95)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In fs/read_write.c (ffffffff8137123e)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_read
```
```
In fs/exec.c (ffffffff8137a7d1)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - fs/exec.c:setup_new_exec
  - fs/exec.c:__bprm_mm_init
```
```
In fs/readdir.c (ffffffff8138bd6c)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8138e281)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - fs/select.c:__x64_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x64_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In fs/eventpoll.c (ffffffff813cf603)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/io_uring.c (ffffffff813e6a64)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:__io_compat_recvmsg_copy_hdr
  - fs/io_uring.c:io_import_iovec
```
```
In fs/binfmt_elf.c (ffffffff814092b4)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
```
```
In fs/compat_binfmt_elf.c (ffffffff8140be96)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In lib/iov_iter.c (ffffffff81614ade)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:__import_iovec
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In lib/usercopy.c (ffffffff8161d8b6)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In lib/strncpy_from_user.c (ffffffff81657174)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81657299)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
  - lib/strnlen_user.c:strnlen_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff816741cd)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In arch/x86/lib/usercopy.c (ffffffff81676e86)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81676f45)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:clear_user
```
```
In drivers/pci/proc.c (ffffffff816b93c7)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/acpi/acpi_dbg.c (ffffffff8176616c)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
```
```
In drivers/char/mem.c (ffffffff817f285e)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff819256e6)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unmap_dma
```
```
In drivers/usb/core/devio.c (ffffffff81950ecf)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In net/core/scm.c (ffffffff81a8c7b0)
Location: arch/x86/include/asm/page_64.h:78
Inline: True
Inline callers:
  - net/core/scm.c:put_cmsg
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
In arch/x86/entry/vdso/vma.c (ffffffff81004455)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004a37)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/core.c (ffffffff8100962e)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81033ac6)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_get_user_pgd
```
```
In arch/x86/kernel/process_64.c (ffffffff810416d1)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
```
In arch/x86/kernel/signal.c (ffffffff8104242b)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/kernel/traps.c (ffffffff81f1382f)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_bug
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff81049d72)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff8104a9d3)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8104ea34)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:arch_check_bp_in_kernelspace
  - arch/x86/kernel/hw_breakpoint.c:arch_check_bp_in_kernelspace
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8105528b)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff81058f16)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:putreg
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8105aa9b)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff810821f5)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
```
```
In arch/x86/mm/init.c (ffffffff83472f5c)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - arch/x86/mm/init.c:poking_init
```
```
In arch/x86/mm/fault.c (ffffffff81f1822f)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
```
In arch/x86/mm/mmap.c (ffffffff810ac958)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:mmap_address_hint_valid
```
```
In arch/x86/mm/maccess.c (ffffffff810af625)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - arch/x86/mm/maccess.c:copy_from_kernel_nofault_allowed
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810b5528)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810bbd50)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810c4275)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
```
In kernel/fork.c (ffffffff810cbd54)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - kernel/fork.c:__do_sys_clone3
```
```
In kernel/exit.c (ffffffff810d27d8)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810dcd2b)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_regset
```
```
In kernel/signal.c (ffffffff810e6482)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
```
```
In kernel/sys.c (ffffffff810ea4d7)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:validate_prctl_map_addr
```
```
In kernel/sched/core.c (ffffffff8110bf07)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_attr_copy_to_user
```
```
In kernel/printk/printk.c (ffffffff8115e21d)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:do_syslog
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff8118a642)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:set_syscall_user_dispatch
```
```
In kernel/futex/core.c (ffffffff811b2ceb)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cmpxchg_value_locked
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/futex/waitwake.c (ffffffff811b6744)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
```
```
In kernel/compat.c (ffffffff811c05ef)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/trace_eprobe.c (ffffffff81245869)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
```
```
In kernel/trace/bpf_trace.c (ffffffff81256716)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125b48e)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/bpf/helpers.c (ffffffff812980a1)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
```
```
In kernel/events/core.c (ffffffff812dfb8f)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff812e83f8)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
```
```
In kernel/rseq.c (ffffffff812ec56b)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
  - kernel/rseq.c:rseq_update_cpu_id
```
```
In mm/maccess.c (ffffffff812fbca0)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/shmem.c (ffffffff813148f9)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_unmapped_area
```
```
In mm/gup.c (ffffffff8133b1ce)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:fault_in_readable
  - mm/gup.c:fault_in_writeable
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff81341eb3)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff81348cfd)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mlock.c (ffffffff8134a019)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_mlockall
```
```
In mm/mmap.c (ffffffff8134fdff)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:get_unmapped_area
  - mm/mmap.c:get_unmapped_area
  - mm/mmap.c:generic_get_unmapped_area_topdown
  - mm/mmap.c:generic_get_unmapped_area
```
```
In mm/mmu_gather.c (ffffffff813533f9)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_gather_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mprotect.c (ffffffff81354df4)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81357093)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
```
```
In mm/madvise.c (ffffffff81375d24)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
```
```
In mm/hugetlb.c (ffffffff8138f919)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/mempolicy.c (ffffffff8139a9d0)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In mm/memory-failure.c (ffffffff81e7549a)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In fs/read_write.c (ffffffff813f222b)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_read
```
```
In fs/exec.c (ffffffff813fb011)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:setup_new_exec
```
```
In fs/readdir.c (ffffffff8140d2e6)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8140f56e)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In fs/eventpoll.c (ffffffff814583e2)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/binfmt_elf.c (ffffffff8147df65)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
```
```
In fs/compat_binfmt_elf.c (ffffffff81480e3b)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/hugetlbfs/inode.c (ffffffff815563d2)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
```
```
In io_uring/io_uring.c (ffffffff816c82ad)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_compat_recvmsg_copy_hdr
  - io_uring/io_uring.c:io_provide_buffers_prep
  - io_uring/io_uring.c:__io_import_iovec
```
```
In lib/iov_iter.c (ffffffff816e0cce)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:__import_iovec
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In lib/usercopy.c (ffffffff816eb412)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In lib/strncpy_from_user.c (ffffffff8176e9b4)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8176eaf9)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
  - lib/strnlen_user.c:strnlen_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff8178e8ee)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In arch/x86/lib/usercopy.c (ffffffff81791d95)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81791f25)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:clear_user
```
```
In drivers/pci/proc.c (ffffffff817ddad3)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/acpi/acpi_dbg.c (ffffffff8189ae7c)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
```
```
In drivers/char/mem.c (ffffffff8193303b)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7e03f)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unmap_dma
```
```
In drivers/usb/core/devio.c (ffffffff81aa9f04)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In net/core/scm.c (ffffffff81c0203f)
Location: arch/x86/include/asm/page_64.h:79
Inline: True
Inline callers:
  - net/core/scm.c:put_cmsg
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
In arch/x86/entry/vdso/vma.c (ffffffff81004db2)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:arch_setup_additional_pages
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810054a7)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/core.c (ffffffff8100aace)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103b516)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_get_user_pgd
```
```
In arch/x86/kernel/process_64.c (ffffffff8104ae31)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
```
In arch/x86/kernel/signal_64.c (ffffffff8104baeb)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn
  - arch/x86/kernel/signal_64.c:x64_setup_rt_frame
```
```
In arch/x86/kernel/traps.c (ffffffff820ba9ef)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_bug
```
```
In arch/x86/kernel/ldt.c (ffffffff81052901)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:read_default_ldt
  - arch/x86/kernel/ldt.c:read_ldt
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff81054f52)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/signal_32.c (ffffffff81055d36)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
  - arch/x86/kernel/signal_32.c:__do_compat_sys_rt_sigreturn
  - arch/x86/kernel/signal_32.c:__do_compat_sys_sigreturn
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff810565e9)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8105b931)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
  - arch/x86/kernel/hw_breakpoint.c:arch_check_bp_in_kernelspace
  - arch/x86/kernel/hw_breakpoint.c:arch_check_bp_in_kernelspace
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81062eeb)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff810667f6)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:putreg
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8106886b)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81094c35)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
```
```
In arch/x86/mm/init.c (ffffffff83e9a73f)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - arch/x86/mm/init.c:poking_init
```
```
In arch/x86/mm/fault.c (ffffffff820bfa1f)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
```
In arch/x86/mm/mmap.c (ffffffff810c69f8)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:mmap_address_hint_valid
```
```
In arch/x86/mm/maccess.c (ffffffff810c9ab5)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - arch/x86/mm/maccess.c:copy_from_kernel_nofault_allowed
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810d0508)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810e0520)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
```
In kernel/fork.c (ffffffff810e9394)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - kernel/fork.c:__do_sys_clone3
```
```
In kernel/exit.c (ffffffff810f1298)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810fcf58)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_regset
```
```
In kernel/signal.c (ffffffff811070b2)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sys.c (ffffffff8110afd7)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:validate_prctl_map_addr
```
```
In kernel/sched/core.c (ffffffff8112f9a7)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_attr_copy_to_user
```
```
In kernel/printk/printk.c (ffffffff8119110d)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:do_syslog
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff811c6bf2)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:set_syscall_user_dispatch
```
```
In kernel/futex/core.c (ffffffff811f3bbb)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cmpxchg_value_locked
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/futex/waitwake.c (ffffffff811f7894)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
```
```
In kernel/compat.c (ffffffff812029df)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/trace_eprobe.c (ffffffff81294f04)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
```
```
In kernel/trace/trace_events_synth.c (ffffffff812983a2)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/trace_events_synth.c:trace_string
```
```
In kernel/trace/bpf_trace.c (ffffffff812a7f76)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ad39e)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/bpf/helpers.c (ffffffff812f3240)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
```
```
In kernel/events/core.c (ffffffff81347f9e)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff8134f065)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_add_vma
```
```
In kernel/rseq.c (ffffffff8135689b)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In mm/maccess.c (ffffffff81365e80)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/shmem.c (ffffffff8138b910)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_unmapped_area
```
```
In mm/gup.c (ffffffff813b2e2e)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:fault_in_readable
  - mm/gup.c:fault_in_writeable
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff813b9dd1)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff813c139d)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mlock.c (ffffffff813c2b87)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_mlockall
```
```
In mm/mmap.c (ffffffff813c9a39)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - mm/mmap.c:do_mas_munmap
  - mm/mmap.c:do_mas_munmap
  - mm/mmap.c:get_unmapped_area
  - mm/mmap.c:get_unmapped_area
  - mm/mmap.c:generic_get_unmapped_area_topdown
  - mm/mmap.c:generic_get_unmapped_area
```
```
In mm/mmu_gather.c (ffffffff813cd6db)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_gather_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mprotect.c (ffffffff813cf2ec)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff813d163f)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
```
```
In mm/madvise.c (ffffffff813f2f6b)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
```
```
In mm/hugetlb.c (ffffffff814100a4)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/mempolicy.c (ffffffff8141aa13)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:copy_nodes_to_user
```
```
In mm/memory-failure.c (ffffffff8145ebd0)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In fs/read_write.c (ffffffff8147ac5c)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_read
```
```
In fs/exec.c (ffffffff8148490e)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:setup_new_exec
```
```
In fs/readdir.c (ffffffff81497d9d)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8149a16e)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814e0393)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e399f)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
```
```
In fs/eventpoll.c (ffffffff814e7d22)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/binfmt_elf.c (ffffffff81510f1e)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:padzero
```
```
In fs/compat_binfmt_elf.c (ffffffff81513fc3)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:padzero
```
```
In fs/proc/kcore.c (ffffffff81545c8e)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In fs/hugetlbfs/inode.c (ffffffff815f7eb2)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
```
```
In security/keys/keyctl.c (ffffffff81654d80)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_capabilities
```
```
In security/keys/keyctl_pkey.c (ffffffff8165a615)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
```
```
In io_uring/net.c (ffffffff817955ba)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - io_uring/net.c:__io_compat_recvmsg_copy_hdr
```
```
In io_uring/kbuf.c (ffffffff8179f8ea)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_provide_buffers_prep
```
```
In io_uring/rw.c (ffffffff817a4096)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - io_uring/rw.c:io_prep_rw
```
```
In lib/iov_iter.c (ffffffff817d11de)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:__import_iovec
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In lib/usercopy.c (ffffffff817dbae2)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In lib/strncpy_from_user.c (ffffffff8189e2c4)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8189e419)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff819005f3)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/acpi/acpi_dbg.c (ffffffff819e344c)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
```
```
In drivers/char/mem.c (ffffffff81a921ab)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:read_mem
```
```
In drivers/usb/core/devio.c (ffffffff81c31284)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/input/evdev.c (ffffffff81caf906)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_get_mask
```
```
In drivers/md/dm-ioctl.c (ffffffff81d17de9)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-ioctl.c:copy_params
```
```
In net/core/scm.c (ffffffff81db165e)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - net/core/scm.c:put_cmsg
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff8204c21e)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In arch/x86/lib/usercopy.c (ffffffff8204fbc5)
Location: arch/x86/include/asm/page_64.h:86
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff8103b5f6)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_get_user_pgd
```
```
In arch/x86/kernel/process_64.c (ffffffff8104b64a)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
```
In arch/x86/kernel/traps.c (ffffffff8213c0ff)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_bug
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff810575b9)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8105ce20)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
  - arch/x86/kernel/hw_breakpoint.c:arch_check_bp_in_kernelspace
  - arch/x86/kernel/hw_breakpoint.c:arch_check_bp_in_kernelspace
```
```
In arch/x86/kernel/ptrace.c (ffffffff81066b6e)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:putreg
```
```
In arch/x86/mm/init.c (ffffffff836be15d)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - arch/x86/mm/init.c:poking_init
```
```
In arch/x86/mm/fault.c (ffffffff82141722)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
```
In arch/x86/mm/mmap.c (ffffffff810ca188)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:mmap_address_hint_valid
```
```
In arch/x86/mm/maccess.c (ffffffff810cd125)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - arch/x86/mm/maccess.c:copy_from_kernel_nofault_allowed
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810d3b2b)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810ed412)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
```
In kernel/sys.c (ffffffff811171a1)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:validate_prctl_map_addr
```
```
In kernel/trace/trace_eprobe.c (ffffffff812b1622)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
```
```
In kernel/trace/trace_events_synth.c (ffffffff812b542d)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/trace_events_synth.c:trace_string
```
```
In kernel/trace/bpf_trace.c (ffffffff812c8f06)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat
```
```
In kernel/trace/trace_kprobe.c (ffffffff812cf29e)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_fprobe.c (ffffffff812e1641)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
```
```
In kernel/bpf/helpers.c (ffffffff81320084)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
```
```
In kernel/events/core.c (ffffffff81378e94)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff8138023d)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_add_vma
```
```
In kernel/rseq.c (ffffffff8138847e)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_get_rseq_cs
  - kernel/rseq.c:rseq_get_rseq_cs
  - kernel/rseq.c:rseq_get_rseq_cs
  - kernel/rseq.c:rseq_get_rseq_cs
```
```
In mm/shmem.c (ffffffff813bdd40)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_unmapped_area
```
```
In mm/gup.c (ffffffff813e7ab3)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff813eeae8)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mlock.c (ffffffff813f7dd3)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_mlockall
```
```
In mm/mmap.c (ffffffff813fdea9)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - mm/mmap.c:do_vmi_munmap
  - mm/mmap.c:do_vmi_munmap
  - mm/mmap.c:get_unmapped_area
  - mm/mmap.c:get_unmapped_area
  - mm/mmap.c:generic_get_unmapped_area_topdown
  - mm/mmap.c:generic_get_unmapped_area
```
```
In mm/mmu_gather.c (ffffffff8140203b)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_gather_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mprotect.c (ffffffff81403c63)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8140622f)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
```
```
In mm/pagewalk.c (ffffffff81407fcf)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pte_range
  - mm/pagewalk.c:walk_pte_range
```
```
In mm/madvise.c (ffffffff814269ab)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
```
```
In mm/hugetlb.c (ffffffff8144346a)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/mempolicy.c (ffffffff8144df80)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In mm/memory-failure.c (ffffffff81494a23)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In fs/exec.c (ffffffff814b94f1)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:setup_new_exec
```
```
In fs/binfmt_elf.c (ffffffff81548664)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
```
```
In fs/compat_binfmt_elf.c (ffffffff8154b858)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/hugetlbfs/inode.c (ffffffff8162fe45)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
```
```
In lib/strncpy_from_user.c (ffffffff818e0854)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff818e09c9)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
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
In arch/x86/entry/common.c (ffffffff8221b7ee)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81041ab6)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_get_user_pgd
```
```
In arch/x86/kernel/process_64.c (ffffffff810528f6)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
```
In arch/x86/kernel/traps.c (ffffffff8221e0ff)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_bug
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff8105e8a2)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff81063ee0)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
  - arch/x86/kernel/hw_breakpoint.c:arch_check_bp_in_kernelspace
  - arch/x86/kernel/hw_breakpoint.c:arch_check_bp_in_kernelspace
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8106ac66)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:ssp_set
```
```
In arch/x86/kernel/ptrace.c (ffffffff8106dfee)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:putreg
```
```
In arch/x86/kernel/shstk.c (ffffffff810ca3b4)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/shstk.c:shstk_pop_sigframe
```
```
In arch/x86/mm/init.c (ffffffff838eec1d)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - arch/x86/mm/init.c:poking_init
```
```
In arch/x86/mm/fault.c (ffffffff822236a2)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
```
In arch/x86/mm/mmap.c (ffffffff810d25e8)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:mmap_address_hint_valid
```
```
In arch/x86/mm/maccess.c (ffffffff810d57f5)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - arch/x86/mm/maccess.c:copy_from_kernel_nofault_allowed
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810dc2bb)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810f5fec)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
```
In kernel/sys.c (ffffffff81120b91)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:validate_prctl_map_addr
```
```
In kernel/trace/trace_eprobe.c (ffffffff812cdbd2)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
```
```
In kernel/trace/trace_events_synth.c (ffffffff812d1a9d)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/trace_events_synth.c:trace_string
```
```
In kernel/trace/bpf_trace.c (ffffffff812e5ed6)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ecc9e)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_fprobe.c (ffffffff812ff691)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
```
```
In kernel/bpf/helpers.c (ffffffff81342574)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
```
```
In kernel/events/core.c (ffffffff813a219d)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff813a95ed)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_add_vma
```
```
In kernel/rseq.c (ffffffff813b1ede)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_get_rseq_cs
  - kernel/rseq.c:rseq_get_rseq_cs
  - kernel/rseq.c:rseq_get_rseq_cs
  - kernel/rseq.c:rseq_get_rseq_cs
```
```
In mm/shmem.c (ffffffff813e8910)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_unmapped_area
```
```
In mm/gup.c (ffffffff81412723)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff8141a5a1)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mlock.c (ffffffff814239a3)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_mlockall
```
```
In mm/mmap.c (ffffffff8142a289)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - mm/mmap.c:do_vmi_munmap
  - mm/mmap.c:do_vmi_munmap
  - mm/mmap.c:get_unmapped_area
  - mm/mmap.c:get_unmapped_area
  - mm/mmap.c:generic_get_unmapped_area_topdown
  - mm/mmap.c:generic_get_unmapped_area
```
```
In mm/mmu_gather.c (ffffffff8142e67d)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_gather_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mprotect.c (ffffffff814301d2)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8143293f)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
```
```
In mm/pagewalk.c (ffffffff8143474c)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pte_range
  - mm/pagewalk.c:walk_pte_range
```
```
In mm/madvise.c (ffffffff8146096a)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
```
```
In mm/hugetlb.c (ffffffff8147d69d)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/memory-failure.c (ffffffff814c4333)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_accessing_process
```
```
In fs/exec.c (ffffffff814ebff8)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:setup_new_exec
```
```
In fs/binfmt_elf.c (ffffffff8157daff)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_load
  - fs/binfmt_elf.c:elf_load
```
```
In fs/compat_binfmt_elf.c (ffffffff81580cc2)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:elf_load
  - fs/compat_binfmt_elf.c:elf_load
```
```
In fs/hugetlbfs/inode.c (ffffffff816692d5)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
```
```
In lib/strncpy_from_user.c (ffffffff81927394)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8192750c)
Location: arch/x86/include/asm/page_64.h:82
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
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
