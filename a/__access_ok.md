# Function: <code>__access_ok</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004a37)
Location: include/asm-generic/access_ok.h:31
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
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal.c (ffffffff8104242b)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff81049d72)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8105528b)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff81058f16)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8105aa9b)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff810821f5)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810bbd50)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
```
```
In kernel/fork.c (ffffffff810cbd54)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - kernel/fork.c:__do_sys_clone3
```
```
In kernel/exit.c (ffffffff810d27d8)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810dcd2b)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_regset
```
```
In kernel/signal.c (ffffffff810e6482)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
```
```
In kernel/sched/core.c (ffffffff8110bf07)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_attr_copy_to_user
```
```
In kernel/printk/printk.c (ffffffff8115e21d)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:do_syslog
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff8118a642)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:set_syscall_user_dispatch
```
```
In kernel/futex/core.c (ffffffff811b2ceb)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cmpxchg_value_locked
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/futex/waitwake.c (ffffffff811b6744)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
```
```
In kernel/compat.c (ffffffff811c05ef)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/rseq.c (ffffffff812ec56b)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
  - kernel/rseq.c:rseq_update_cpu_id
```
```
In mm/maccess.c (ffffffff812fbca0)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/gup.c (ffffffff8133b1ce)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:fault_in_readable
  - mm/gup.c:fault_in_writeable
```
```
In mm/mincore.c (ffffffff81348cfd)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
  - mm/mincore.c:__do_sys_mincore
```
```
In fs/read_write.c (ffffffff813f222b)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_read
```
```
In fs/readdir.c (ffffffff8140d2e6)
Location: include/asm-generic/access_ok.h:31
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
Location: include/asm-generic/access_ok.h:31
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
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In io_uring/io_uring.c (ffffffff816c82ad)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_compat_recvmsg_copy_hdr
  - io_uring/io_uring.c:io_provide_buffers_prep
  - io_uring/io_uring.c:__io_import_iovec
```
```
In lib/iov_iter.c (ffffffff816e0cce)
Location: include/asm-generic/access_ok.h:31
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
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In lib/strncpy_from_user.c (ffffffff8176e9b4)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8176eaf9)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff8178e8ee)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In arch/x86/lib/usercopy.c (ffffffff81791d95)
Location: include/asm-generic/access_ok.h:31
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81791f25)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:clear_user
```
```
In drivers/pci/proc.c (ffffffff817ddad3)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/acpi/acpi_dbg.c (ffffffff8189ae7c)
Location: include/asm-generic/access_ok.h:31
Inline: True
```
```
In drivers/char/mem.c (ffffffff8193303b)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7e03f)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unmap_dma
```
```
In drivers/usb/core/devio.c (ffffffff81aa9f04)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In net/core/scm.c (ffffffff81c0203f)
Location: include/asm-generic/access_ok.h:31
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810054a7)
Location: include/asm-generic/access_ok.h:31
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
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal_64.c (ffffffff8104baeb)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn
  - arch/x86/kernel/signal_64.c:x64_setup_rt_frame
```
```
In arch/x86/kernel/ldt.c (ffffffff81052901)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:read_default_ldt
  - arch/x86/kernel/ldt.c:read_ldt
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff81054f52)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/signal_32.c (ffffffff81055d36)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
  - arch/x86/kernel/signal_32.c:__do_compat_sys_rt_sigreturn
  - arch/x86/kernel/signal_32.c:__do_compat_sys_sigreturn
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81062eeb)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff810667f6)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8106886b)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81094c35)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
```
```
In kernel/fork.c (ffffffff810e9394)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - kernel/fork.c:__do_sys_clone3
```
```
In kernel/exit.c (ffffffff810f1298)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810fcf58)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_regset
```
```
In kernel/signal.c (ffffffff811070b2)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sched/core.c (ffffffff8112f9a7)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_attr_copy_to_user
```
```
In kernel/printk/printk.c (ffffffff8119110d)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:do_syslog
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff811c6bf2)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:set_syscall_user_dispatch
```
```
In kernel/futex/core.c (ffffffff811f3bbb)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cmpxchg_value_locked
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/futex/waitwake.c (ffffffff811f7894)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
```
```
In kernel/compat.c (ffffffff812029df)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/rseq.c (ffffffff8135689b)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In mm/maccess.c (ffffffff81365e80)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/gup.c (ffffffff813b2e2e)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:fault_in_readable
  - mm/gup.c:fault_in_writeable
```
```
In mm/mincore.c (ffffffff813c139d)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mempolicy.c (ffffffff81414b9a)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - mm/mempolicy.c:copy_nodes_to_user
```
```
In fs/read_write.c (ffffffff8147ac5c)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_read
```
```
In fs/readdir.c (ffffffff81497d9d)
Location: include/asm-generic/access_ok.h:31
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
Location: include/asm-generic/access_ok.h:31
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
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e399f)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
```
```
In fs/eventpoll.c (ffffffff814e7d22)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/binfmt_elf.c (ffffffff81510f1e)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:padzero
```
```
In fs/compat_binfmt_elf.c (ffffffff81513fc3)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:padzero
```
```
In fs/proc/kcore.c (ffffffff81545c8e)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In security/keys/keyctl.c (ffffffff81654d80)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_capabilities
```
```
In security/keys/keyctl_pkey.c (ffffffff8165a615)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
```
```
In io_uring/net.c (ffffffff817955ba)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - io_uring/net.c:__io_compat_recvmsg_copy_hdr
```
```
In io_uring/kbuf.c (ffffffff8179f8ea)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_provide_buffers_prep
```
```
In io_uring/rw.c (ffffffff817a4096)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - io_uring/rw.c:io_prep_rw
```
```
In lib/iov_iter.c (ffffffff817d11de)
Location: include/asm-generic/access_ok.h:31
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
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In lib/strncpy_from_user.c (ffffffff8189e2c4)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8189e419)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff819005f3)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/acpi/acpi_dbg.c (ffffffff819e344c)
Location: include/asm-generic/access_ok.h:31
Inline: True
```
```
In drivers/char/mem.c (ffffffff81a921ab)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:read_mem
```
```
In drivers/usb/core/devio.c (ffffffff81c31284)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/input/evdev.c (ffffffff81caf906)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_get_mask
```
```
In drivers/md/dm-ioctl.c (ffffffff81d17de9)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-ioctl.c:copy_params
```
```
In net/core/scm.c (ffffffff81db165e)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - net/core/scm.c:put_cmsg
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff8204c21e)
Location: include/asm-generic/access_ok.h:31
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In arch/x86/lib/usercopy.c (ffffffff8204fbc5)
Location: include/asm-generic/access_ok.h:31
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004cdd)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/core.c (ffffffff8100a3cb)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal_64.c (ffffffff8104c377)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn
  - arch/x86/kernel/signal_64.c:x64_setup_rt_frame
```
```
In arch/x86/kernel/ldt.c (ffffffff810539e1)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:read_default_ldt
  - arch/x86/kernel/ldt.c:read_ldt
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff81056180)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/signal_32.c (ffffffff81056d23)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
  - arch/x86/kernel/signal_32.c:__do_compat_sys_rt_sigreturn
  - arch/x86/kernel/signal_32.c:__do_compat_sys_sigreturn
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106483b)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff81067c4c)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8106a183)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81097b65)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
```
```
In kernel/fork.c (ffffffff810f4fa4)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - kernel/fork.c:__do_sys_clone3
```
```
In kernel/exit.c (ffffffff810fd208)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff81108687)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_regset
```
```
In kernel/signal.c (ffffffff8111203d)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sched/core.c (ffffffff8113d415)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_attr_copy_to_user
```
```
In kernel/printk/printk.c (ffffffff811a2980)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:do_syslog
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff811d96e7)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:task_set_syscall_user_dispatch
```
```
In kernel/futex/core.c (ffffffff8120835b)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cmpxchg_value_locked
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/futex/waitwake.c (ffffffff8120c2e4)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
```
```
In kernel/compat.c (ffffffff81217d98)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/trace_events_user.c (ffffffff812c6c9d)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
```
```
In kernel/rseq.c (ffffffff8138835f)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - kernel/rseq.c:__x64_sys_rseq
  - kernel/rseq.c:rseq_update_cpu_node_id
```
```
In mm/maccess.c (ffffffff81398330)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/gup.c (ffffffff813e7ac6)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:fault_in_readable
  - mm/gup.c:fault_in_writeable
```
```
In mm/mincore.c (ffffffff813f610a)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
```
In mm/mempolicy.c (ffffffff8144815b)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - mm/mempolicy.c:copy_nodes_to_user
```
```
In fs/read_write.c (ffffffff814af7bf)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_read
```
```
In fs/readdir.c (ffffffff814ccd10)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff814cf89f)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:__x64_sys_pselect6
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81516c61)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151a2c2)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
```
```
In fs/eventpoll.c (ffffffff8151dfce)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/binfmt_elf.c (ffffffff81548851)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:padzero
```
```
In fs/compat_binfmt_elf.c (ffffffff8154ba1f)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:padzero
```
```
In security/keys/keyctl.c (ffffffff8168d5c1)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_capabilities
```
```
In security/keys/keyctl_pkey.c (ffffffff81692ef5)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
```
```
In io_uring/net.c (0)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
```
```
In io_uring/kbuf.c (ffffffff817e0a13)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_provide_buffers_prep
```
```
In io_uring/rw.c (ffffffff817e50c9)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - io_uring/rw.c:io_prep_rw
```
```
In lib/iov_iter.c (ffffffff818157bc)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - lib/iov_iter.c:import_ubuf
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:__import_iovec
  - lib/iov_iter.c:copy_iovec_from_user
  - lib/iov_iter.c:copy_compat_iovec_from_user
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff8181ae96)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In lib/strncpy_from_user.c (ffffffff818e0890)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff818e09f5)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff81943b9b)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/acpi/acpi_dbg.c (ffffffff81a2ba4c)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
```
```
In drivers/char/mem.c (ffffffff81adda3c)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:read_mem
```
```
In drivers/usb/core/devio.c (ffffffff81c98513)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/input/evdev.c (ffffffff81d16e90)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_get_mask
```
```
In drivers/md/dm-ioctl.c (ffffffff81d81070)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-ioctl.c:copy_params
```
```
In net/core/scm.c (ffffffff81e21baa)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - net/core/scm.c:put_cmsg
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff820cab1c)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In arch/x86/lib/usercopy.c (ffffffff820ce115)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810075ed)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/core.c (ffffffff8100faeb)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal_64.c (ffffffff810535f7)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn
  - arch/x86/kernel/signal_64.c:x64_setup_rt_frame
```
```
In arch/x86/kernel/ldt.c (ffffffff8105ac01)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:read_default_ldt
  - arch/x86/kernel/ldt.c:read_ldt
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff8105d3d0)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/signal_32.c (ffffffff8105df73)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
  - arch/x86/kernel/signal_32.c:__do_compat_sys_rt_sigreturn
  - arch/x86/kernel/signal_32.c:__do_compat_sys_sigreturn
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106bcfb)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff8106f0cc)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81071653)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109f0d5)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
```
```
In kernel/fork.c (ffffffff810fe344)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - kernel/fork.c:__do_sys_clone3
```
```
In kernel/exit.c (ffffffff81107748)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff81112017)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_regset
```
```
In kernel/signal.c (ffffffff8111ba2d)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sched/core.c (ffffffff81148585)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_attr_copy_to_user
```
```
In kernel/printk/printk.c (ffffffff811b0840)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:do_syslog
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff811ef397)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:task_set_syscall_user_dispatch
```
```
In kernel/futex/core.c (ffffffff8121f1eb)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cmpxchg_value_locked
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/futex/waitwake.c (ffffffff812235e4)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
```
```
In kernel/compat.c (ffffffff8122f958)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/trace_events_user.c (ffffffff812e3766)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
```
```
In kernel/rseq.c (ffffffff813b1dbf)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - kernel/rseq.c:__x64_sys_rseq
  - kernel/rseq.c:rseq_update_cpu_node_id
```
```
In mm/maccess.c (ffffffff813c2150)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/gup.c (ffffffff81412736)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:fault_in_readable
  - mm/gup.c:fault_in_writeable
```
```
In mm/mincore.c (ffffffff81421dba)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
```
In mm/mempolicy.c (ffffffff81481b5b)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - mm/mempolicy.c:copy_nodes_to_user
```
```
In fs/read_write.c (ffffffff814e0f3f)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_read
```
```
In fs/readdir.c (ffffffff814ff300)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff815021df)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:__x64_sys_pselect6
```
```
In fs/namespace.c (ffffffff81514211)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - fs/namespace.c:__x64_sys_listmount
  - fs/namespace.c:__do_sys_statmount
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154b051)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154e692)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
```
```
In fs/eventpoll.c (ffffffff815525ae)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/binfmt_elf.c (ffffffff8157cead)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_load
```
```
In fs/compat_binfmt_elf.c (ffffffff8157fee8)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_load
```
```
In fs/proc/task_mmu.c (ffffffff8159bb56)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:do_pagemap_scan
  - fs/proc/task_mmu.c:do_pagemap_scan
```
```
In security/keys/keyctl.c (ffffffff816c9b11)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_capabilities
```
```
In security/keys/keyctl_pkey.c (ffffffff816cf4c5)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
```
```
In io_uring/net.c (0)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
```
```
In io_uring/kbuf.c (ffffffff81824f12)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_provide_buffers_prep
```
```
In io_uring/rw.c (ffffffff818295c1)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - io_uring/rw.c:io_prep_rwv
```
```
In io_uring/waitid.c (ffffffff8182a668)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - io_uring/waitid.c:io_waitid_copy_si
```
```
In lib/iov_iter.c (ffffffff81855d7c)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - lib/iov_iter.c:import_ubuf
  - lib/iov_iter.c:__import_iovec
  - lib/iov_iter.c:copy_iovec_from_user
  - lib/iov_iter.c:copy_compat_iovec_from_user
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
In lib/usercopy.c (ffffffff818601e6)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In lib/strncpy_from_user.c (ffffffff819273d0)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81927538)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff8198ce6b)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/acpi/acpi_dbg.c (ffffffff81a76c1c)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
```
```
In drivers/char/mem.c (ffffffff81b30e2c)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:read_mem
```
```
In drivers/gpu/drm/drm_ioc32.c (ffffffff81cb9445)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_ioc32.c:compat_drm_getstats
```
```
In drivers/usb/core/devio.c (ffffffff81d4d023)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/input/evdev.c (ffffffff81dccb40)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_get_mask
```
```
In drivers/md/dm-ioctl.c (ffffffff81e38714)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-ioctl.c:copy_params
```
```
In net/core/scm.c (ffffffff81edfaca)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - net/core/scm.c:put_cmsg
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff821a535c)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In arch/x86/lib/usercopy.c (ffffffff821a8945)
Location: arch/x86/include/asm/uaccess_64.h:85
Inline: True
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
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/signal.c (ffffffe0000b6634)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - arch/riscv/kernel/signal.c:handle_signal
  - arch/riscv/kernel/signal.c:sys_rt_sigreturn
```
```
In arch/riscv/kernel/perf_callchain.c (ffffffe0000b98c0)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - arch/riscv/kernel/perf_callchain.c:user_backtrace
```
```
In kernel/fork.c (ffffffe0000c186a)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - kernel/fork.c:__se_sys_clone3
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_release
```
```
In kernel/exit.c (ffffffe0000c6620)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/sysctl.c (ffffffe0000c9398)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dostring
  - kernel/sysctl.c:proc_dostring
```
```
In kernel/sysctl_binary.c (ffffffe0000cadee)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__se_sys_sysctl
  - kernel/sysctl_binary.c:__se_sys_sysctl
```
```
In kernel/capability.c (ffffffe0000cb306)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - kernel/capability.c:__se_sys_capset
  - kernel/capability.c:__se_sys_capget
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
```
```
In kernel/ptrace.c (ffffffe0000cc77a)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - kernel/ptrace.c:generic_ptrace_peekdata
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffe0000d12ae)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sys.c (ffffffe0000d4daa)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_getcpu
  - kernel/sys.c:__se_sys_getcpu
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:__se_sys_getresgid
  - kernel/sys.c:__se_sys_getresgid
  - kernel/sys.c:__se_sys_getresgid
  - kernel/sys.c:__se_sys_getresuid
  - kernel/sys.c:__se_sys_getresuid
  - kernel/sys.c:__se_sys_getresuid
```
```
In kernel/groups.c (ffffffe0000e4286)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - kernel/groups.c:__se_sys_setgroups
  - kernel/groups.c:__se_sys_getgroups
```
```
In kernel/sched/core.c (ffffffe0000ebd12)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_getattr
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/printk/printk.c (ffffffe0001104c6)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
```
```
In kernel/profile.c (ffffffe0001297e4)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/time/time.c (ffffffe00012aa06)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - kernel/time/time.c:__se_sys_gettimeofday
  - kernel/time/time.c:__se_sys_gettimeofday
```
```
In kernel/futex.c (ffffffe00013d46a)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:handle_futex_death
  - kernel/futex.c:__se_sys_get_robust_list
  - kernel/futex.c:__se_sys_get_robust_list
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:get_futex_key
```
```
In kernel/trace/trace.c (ffffffe00017f882)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_get_user
```
```
In kernel/bpf/syscall.c (ffffffe00019efec)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
```
```
In kernel/bpf/verifier.c (ffffffe0001a4660)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
```
```
In kernel/bpf/btf.c (ffffffe0001bafba)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_info_by_fd
```
```
In kernel/bpf/cgroup.c (ffffffe0001c15d6)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
```
```
In kernel/events/core.c (ffffffe0001c7f52)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:perf_copy_attr
```
```
In mm/maccess.c (ffffffe0001dd0f8)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_read
```
```
In mm/gup.c (ffffffe0002056ea)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_fast
```
```
In mm/mincore.c (ffffffe00020bcb0)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - mm/mincore.c:__se_sys_mincore
  - mm/mincore.c:__se_sys_mincore
```
```
In fs/read_write.c (ffffffe000257dec)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/read_write.c:__se_sys_sendfile64
  - fs/read_write.c:__se_sys_sendfile
  - fs/read_write.c:__se_sys_sendfile
  - fs/read_write.c:rw_copy_check_uvector
```
```
In fs/exec.c (ffffffe00025cf16)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/exec.c:get_user_arg_ptr
```
```
In fs/pipe.c (ffffffe00025f628)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/pipe.c:pipe_ioctl
```
```
In fs/fcntl.c (ffffffe000268d4c)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/fcntl.c:__se_sys_fcntl
  - fs/fcntl.c:__se_sys_fcntl
```
```
In fs/ioctl.c (ffffffe000269a2a)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/readdir.c (ffffffe00026a568)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:filldir64
  - fs/readdir.c:__se_sys_getdents
  - fs/readdir.c:__se_sys_getdents
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffffffe00026b888)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/select.c:__se_sys_pselect6
```
```
In fs/namespace.c (ffffffe00027b97a)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/nsfs.c (ffffffe00028ed1a)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/nsfs.c:ns_ioctl
```
```
In fs/notify/inotify/inotify_user.c (ffffffe0002a079e)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffe0002a1fe4)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_ioctl
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
```
```
In fs/eventpoll.c (ffffffe0002a323a)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/timerfd.c (ffffffe0002a595c)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffffffe0002a6998)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffffffe0002a7812)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
```
```
In fs/aio.c (ffffffe0002ac324)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:lookup_ioctx
```
```
In fs/crypto/keyring.c (ffffffe0002b7040)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
```
```
In fs/crypto/policy.c (ffffffe0002b8cc4)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/measure.c (ffffffe0002ba37e)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/verity/measure.c:fsverity_ioctl_measure
```
```
In fs/binfmt_elf.c (ffffffe0002c1a9a)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/binfmt_flat.c (ffffffe0002c3a9c)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/binfmt_flat.c:load_flat_binary
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
```
```
In fs/fhandle.c (ffffffe0002c739a)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_name_to_handle_at
```
```
In fs/proc/kcore.c (ffffffe0002e2c5c)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/page.c (ffffffe0002e309a)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In fs/ext4/ioctl.c (ffffffe0003124ee)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/fat/dir.c (ffffffe00035909a)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_dir_ioctl
  - fs/fat/dir.c:fat_dir_ioctl
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
```
```
In fs/fat/file.c (ffffffe00035ba3e)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/ecryptfs/miscdev.c (ffffffe00036c48c)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/fuse/dev.c (ffffffe00036ee8a)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_ioctl
```
```
In ipc/msg.c (ffffffe000385af6)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - ipc/msg.c:do_msg_fill
  - ipc/msg.c:ksys_msgsnd
```
```
In ipc/mqueue.c (ffffffe00038e0e6)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_timedreceive
```
```
In security/keys/keyring.c (ffffffe00039164a)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
```
```
In security/keys/keyctl.c (ffffffe000392910)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
```
```
In security/keys/keyctl_pkey.c (ffffffe000397b1c)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
```
```
In security/selinux/hooks.c (ffffffe0003a5c00)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
```
```
In security/smack/smack_lsm.c (ffffffe0003c250a)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
```
```
In security/tomoyo/common.c (ffffffe0003ce76e)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
```
```
In security/apparmor/lsm.c (ffffffe0003e9ad4)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
```
```
In block/ioctl.c (ffffffe0004352be)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:put_uint
  - block/ioctl.c:put_int
  - block/ioctl.c:put_ushort
```
```
In block/scsi_ioctl.c (ffffffe000442c58)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
```
```
In block/bsg.c (ffffffe000443518)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_ioctl
```
```
In lib/bitmap.c (ffffffe00045bc4c)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parse_user
```
```
In lib/iov_iter.c (ffffffe00045d38e)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffe000464e7c)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In lib/strncpy_from_user.c (ffffffe000492a70)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffe000492bc8)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffe0004c88aa)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/tty/tty_io.c (ffffffe00052f4a8)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/tty/n_tty.c (ffffffe000530e88)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (ffffffe000534e32)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/tty_ioctl.c:get_termio
```
```
In drivers/tty/tty_jobctrl.c (ffffffe00053877e)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
```
In drivers/tty/pty.c (ffffffe000538cdc)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_get_pktmode
  - drivers/tty/pty.c:pty_set_pktmode
  - drivers/tty/pty.c:pty_get_lock
  - drivers/tty/pty.c:pty_set_lock
```
```
In drivers/tty/sysrq.c (ffffffe00053b20a)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:write_sysrq_trigger
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffe00053bd74)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffe000541a2a)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kbkeycode_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
```
```
In drivers/tty/vt/consolemap.c (ffffffe000542644)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/tty/vt/vt.c (ffffffe0005473ea)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
```
```
In drivers/tty/serial/serial_core.c (ffffffe00054eeca)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/char/mem.c (ffffffe00055fca0)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/char/random.c (ffffffe0005635e0)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
```
```
In drivers/scsi/scsi_ioctl.c (ffffffe0005da124)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/scsi_error.c (ffffffe0005dd686)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
```
```
In drivers/scsi/sg.c (ffffffe0005f6322)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/ata/libata-scsi.c (ffffffe000604412)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
```
```
In drivers/net/tun.c (ffffffe00062962c)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062f434)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/usb/core/devio.c (ffffffe00065023a)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
```
```
In drivers/usb/core/devices.c (ffffffe000652514)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
```
```
In drivers/input/mousedev.c (ffffffe0006ac4f0)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_write
```
```
In drivers/input/evdev.c (ffffffe0006ad36a)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_handle_set_keycode
  - drivers/input/evdev.c:evdev_handle_get_keycode
```
```
In drivers/input/misc/uinput.c (ffffffe0006b1874)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
```
```
In drivers/rtc/dev.c (ffffffe0006b5b92)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/i2c/i2c-dev.c (ffffffe0006bd758)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
```
In drivers/pps/pps.c (ffffffe0006c4be6)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_ioctl
```
```
In drivers/watchdog/watchdog_dev.c (ffffffe0006d7c3a)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_write
```
```
In drivers/md/md.c (ffffffe0006e7acc)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-ioctl.c (ffffffe0006f7a92)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
```
In net/socket.c (ffffffe00073a97a)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__se_sys_getsockopt
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:move_addr_to_user
```
```
In net/core/sock.c (ffffffe000740b50)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/scm.c (ffffffe00074c416)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/ethtool.c (ffffffe000764f8e)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/netlink/af_netlink.c (ffffffe0007b859c)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cd714)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
```
```
In net/ipv4/tcp.c (ffffffe0007d5dac)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/raw.c (ffffffe0007f58ea)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/raw.c:raw_ioctl
```
```
In net/ipv4/udp.c (ffffffe0007f7236)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
```
```
In net/ipv4/igmp.c (ffffffe00080aeea)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
```
```
In net/ipv4/bpfilter/sockopt.c (ffffffe00081ad88)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
```
```
In net/ipv4/ipmr.c (ffffffe00082190c)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
```
In net/unix/af_unix.c (ffffffe00083ca02)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/ipv6_sockglue.c (ffffffe00085ffe8)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
```
```
In net/ipv6/raw.c (ffffffe000869aa8)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/mcast.c (ffffffe000870812)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
```
```
In net/ipv6/ip6mr.c (ffffffe000881618)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffe00088e05c)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/xdp/xsk.c (ffffffe0008ab8b6)
Location: arch/riscv/include/asm/uaccess.h:76
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
```
</details>
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
