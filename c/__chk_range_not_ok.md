# Function: <code>__chk_range_not_ok</code>

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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100469f)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
```
```
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
```
```
In arch/x86/kernel/signal_compat.c (0)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103acd1)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (0)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
```
```
In arch/x86/mm/gup.c (ffffffff81071add)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:__get_user_pages_fast
```
```
In arch/x86/mm/mpx.c (0)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
```
```
In arch/x86/ia32/sys_ia32.c (0)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
```
```
In kernel/ptrace.c (ffffffff8108b171)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_regset
```
```
In kernel/signal.c (0)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
```
```
In kernel/sys.c (0)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
```
```
In kernel/sched/core.c (ffffffff810add53)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_getattr
```
```
In kernel/printk/printk.c (ffffffff810d952b)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
Inline callers:
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:do_syslog
```
```
In kernel/futex.c (0)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
```
```
In kernel/compat.c (ffffffff811100e0)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_put_bitmap
```
```
In kernel/bpf/syscall.c (0)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
```
```
In kernel/events/core.c (0)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
```
```
In mm/mincore.c (ffffffff811c29d1)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
Inline callers:
  - mm/mincore.c:SyS_mincore
  - mm/mincore.c:SyS_mincore
```
```
In fs/read_write.c (ffffffff8120c70b)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
Inline callers:
  - fs/read_write.c:vfs_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:rw_copy_check_uvector
```
```
In fs/ioctl.c (ffffffff8121ff95)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/readdir.c (ffffffff812206e2)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
Inline callers:
  - fs/readdir.c:fillonedir
  - fs/readdir.c:SyS_getdents
  - fs/readdir.c:SyS_getdents64
```
```
In fs/select.c (0)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
```
```
In fs/namespace.c (ffffffff8122ea4e)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/splice.c (ffffffff8123f458)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
Inline callers:
  - fs/splice.c:vmsplice_to_pipe
```
```
In fs/eventpoll.c (ffffffff812568d5)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_pwait
  - fs/eventpoll.c:compat_SyS_epoll_pwait
```
```
In fs/aio.c (ffffffff8125d495)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
```
In fs/compat.c (ffffffff81263ef1)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
Inline callers:
  - fs/compat.c:compat_get_fd_set
  - fs/compat.c:compat_fillonedir
  - fs/compat.c:compat_rw_copy_check_uvector
  - fs/compat.c:compat_rw_copy_check_uvector
  - fs/compat.c:compat_SyS_getdents
  - fs/compat.c:compat_SyS_getdents64
```
```
In fs/compat_ioctl.c (0)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
```
```
In fs/fat/dir.c (0)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
```
```
In ipc/compat.c (0)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
```
```
In ipc/compat_mq.c (0)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
```
```
In security/tomoyo/common.c (ffffffff8136b38a)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
```
In arch/x86/lib/usercopy.c (ffffffff813f7974)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff813f79ff)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:copy_in_user
  - arch/x86/lib/usercopy_64.c:copy_in_user
  - arch/x86/lib/usercopy_64.c:clear_user
```
```
In lib/bitmap.c (ffffffff813f992c)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parse_user
  - lib/bitmap.c:bitmap_parselist_user
```
```
In lib/iov_iter.c (ffffffff813fdd41)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
```
```
In drivers/pci/proc.c (ffffffff81441a27)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_write
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff814efa07)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
```
```
In drivers/tty/vt/selection.c (0)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
```
```
In drivers/char/mem.c (ffffffff81511129)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:write_port
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff815c37ba)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_write
```
```
In drivers/usb/core/devio.c (ffffffff8161b18d)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/usb/core/devices.c (ffffffff8161eaef)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
```
```
In net/socket.c (0)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
```
```
In net/compat.c (ffffffff8173e9e3)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81817baf)
Location: arch/x86/include/asm/uaccess.h:44
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004926)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/core.c (ffffffff8100788b)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal.c (ffffffff8102de05)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
```
```
In arch/x86/kernel/signal_compat.c (ffffffff8102e03f)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:copy_siginfo_from_user32
  - arch/x86/kernel/signal_compat.c:copy_siginfo_to_user32
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103cc46)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103e548)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/gup.c (ffffffff81071d93)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:__get_user_pages_fast
```
```
In arch/x86/mm/mpx.c (ffffffff810775f7)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff81078e3e)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81079b2b)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
```
In kernel/ptrace.c (ffffffff8108f4a9)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff8109492d)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sys.c (ffffffff81095ee5)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:SYSC_olduname
```
```
In kernel/sched/core.c (ffffffff810b0393)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_setattr
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
```
```
In kernel/futex.c (ffffffff811080d0)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:get_futex_key
```
```
In kernel/compat.c (ffffffff81118d4d)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:compat_SyS_getrlimit
  - kernel/compat.c:compat_SyS_old_getrlimit
  - kernel/compat.c:compat_SyS_setrlimit
  - kernel/compat.c:compat_SyS_setitimer
  - kernel/compat.c:compat_SyS_setitimer
  - kernel/compat.c:compat_SyS_getitimer
  - kernel/compat.c:compat_put_timeval
  - kernel/compat.c:compat_get_timeval
  - kernel/compat.c:__compat_put_timespec
  - kernel/compat.c:__compat_get_timespec
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_get_timex
```
```
In kernel/trace/bpf_trace.c (0)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff81181805)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/events/core.c (ffffffff81193628)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
```
```
In mm/mincore.c (0)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
```
```
In fs/read_write.c (0)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
```
```
In fs/ioctl.c (0)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
```
```
In fs/readdir.c (ffffffff81248195)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff81249937)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - fs/select.c:SyS_pselect6
```
```
In fs/namespace.c (0)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
```
```
In fs/splice.c (0)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
```
```
In fs/eventpoll.c (ffffffff8127f58e)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
```
```
In fs/compat.c (ffffffff81291937)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_fillonedir
  - fs/compat.c:put_compat_flock64
  - fs/compat.c:get_compat_flock64
  - fs/compat.c:put_compat_flock
  - fs/compat.c:get_compat_flock
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs
```
```
In fs/compat_ioctl.c (ffffffff812924f8)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/fat/dir.c (ffffffff8132c68c)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
  - fs/fat/dir.c:fat_dir_ioctl
```
```
In ipc/compat.c (ffffffff813584bc)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
```
```
In ipc/compat_mq.c (ffffffff8136344e)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - ipc/compat_mq.c:compat_SyS_mq_open
```
```
In security/tomoyo/common.c (0)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
```
```
In arch/x86/lib/usercopy.c (ffffffff8143e827)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (0)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
```
```
In lib/iov_iter.c (0)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
```
```
In drivers/pci/proc.c (0)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff815402ce)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/selection.c (ffffffff81541f81)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:set_selection
```
```
In drivers/tty/vt/consolemap.c (ffffffff81546b6e)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
```
```
In drivers/char/mem.c (0)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81600e2d)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff8161e744)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff8167dcba)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:get_urb32
```
```
In drivers/usb/core/devices.c (0)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
```
```
In net/socket.c (ffffffff8176512e)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - net/socket.c:copy_msghdr_from_user
```
```
In net/compat.c (ffffffff817aba14)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_sock_getsockopt
  - net/compat.c:compat_sock_setsockopt
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_msghdr
```
```
In arch/x86/lib/csum-wrappers_64.c (0)
Location: arch/x86/include/asm/uaccess.h:45
Inline: True
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810049a6)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff8102dc65)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
```
```
In arch/x86/kernel/signal_compat.c (ffffffff8102df2f)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:copy_siginfo_from_user32
  - arch/x86/kernel/signal_compat.c:__copy_siginfo_to_user32
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103c557)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103dea8)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/gup.c (ffffffff81075903)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:__get_user_pages_fast
```
```
In arch/x86/mm/mpx.c (ffffffff8107b1a7)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8107cc2e)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107d91b)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
```
In kernel/ptrace.c (ffffffff81094429)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff8109993d)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sys.c (ffffffff8109aeb5)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:SYSC_olduname
```
```
In kernel/sched/core.c (ffffffff810b6523)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_setattr
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
```
```
In kernel/futex.c (ffffffff8110f8c0)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:get_futex_key
```
```
In kernel/compat.c (ffffffff8112046d)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:compat_SyS_getrlimit
  - kernel/compat.c:compat_SyS_old_getrlimit
  - kernel/compat.c:compat_SyS_setrlimit
  - kernel/compat.c:compat_SyS_setitimer
  - kernel/compat.c:compat_SyS_setitimer
  - kernel/compat.c:compat_SyS_getitimer
  - kernel/compat.c:compat_put_timeval
  - kernel/compat.c:compat_get_timeval
  - kernel/compat.c:__compat_put_timespec
  - kernel/compat.c:__compat_get_timespec
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_get_timex
```
```
In kernel/trace/bpf_trace.c (0)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff8118d8f5)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/events/core.c (ffffffff811a2e08)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
```
```
In mm/mincore.c (0)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
```
```
In fs/read_write.c (0)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
```
```
In fs/ioctl.c (0)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
```
```
In fs/readdir.c (ffffffff8125b1c5)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8125c917)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - fs/select.c:SyS_pselect6
```
```
In fs/namespace.c (0)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
```
```
In fs/eventpoll.c (ffffffff8129310e)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
```
```
In fs/compat.c (ffffffff812a66c7)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_fillonedir
  - fs/compat.c:put_compat_flock64
  - fs/compat.c:get_compat_flock64
  - fs/compat.c:put_compat_flock
  - fs/compat.c:get_compat_flock
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs
```
```
In fs/compat_ioctl.c (ffffffff812a7278)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/fat/dir.c (ffffffff813423cc)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
  - fs/fat/dir.c:fat_dir_ioctl
```
```
In fs/pstore/platform.c (0)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
```
```
In ipc/compat.c (ffffffff8136e9ac)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
```
```
In ipc/compat_mq.c (ffffffff81379c1e)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - ipc/compat_mq.c:compat_SyS_mq_open
```
```
In security/tomoyo/common.c (0)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
```
```
In arch/x86/lib/usercopy.c (ffffffff8145b87c)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (0)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
```
```
In lib/iov_iter.c (0)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
```
```
In drivers/pci/proc.c (0)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8156c90e)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/selection.c (ffffffff8156e5c1)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:set_selection
```
```
In drivers/tty/vt/consolemap.c (ffffffff815731d9)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
```
```
In drivers/char/mem.c (0)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff8163051d)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff8164f314)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff816aba3e)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:get_urb32
```
```
In drivers/usb/core/devices.c (0)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
```
```
In net/socket.c (ffffffff817921ae)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - net/socket.c:copy_msghdr_from_user
```
```
In net/compat.c (ffffffff817db034)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_sock_getsockopt
  - net/compat.c:compat_sock_setsockopt
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_msghdr
```
```
In arch/x86/lib/csum-wrappers_64.c (0)
Location: arch/x86/include/asm/uaccess.h:46
Inline: True
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004829)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff8102bee5)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
```
```
In arch/x86/kernel/signal_compat.c (ffffffff8102c19f)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:copy_siginfo_from_user32
  - arch/x86/kernel/signal_compat.c:__copy_siginfo_to_user32
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103a809)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103bf1c)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff81079993)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8107b3ce)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107c0eb)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
```
In kernel/exit.c (ffffffff8108869a)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - kernel/exit.c:C_SYSC_waitid
  - kernel/exit.c:SYSC_waitid
```
```
In kernel/ptrace.c (ffffffff81091509)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff8109698d)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sys.c (ffffffff81097cb5)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:SYSC_olduname
```
```
In kernel/sched/core.c (ffffffff810b27a3)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_setattr
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
```
```
In kernel/futex.c (ffffffff81110c95)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:get_futex_key
```
```
In kernel/compat.c (ffffffff81120e0d)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:__compat_put_timespec
  - kernel/compat.c:__compat_get_timespec
```
```
In kernel/trace/bpf_trace.c (0)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff81192588)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/events/core.c (ffffffff811aa418)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
```
```
In mm/gup.c (ffffffff811f0846)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
```
```
In mm/mincore.c (0)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
```
```
In fs/read_write.c (0)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
```
```
In fs/ioctl.c (0)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
```
```
In fs/readdir.c (ffffffff81267bbb)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8126a8d6)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - fs/select.c:compat_SyS_pselect6
  - fs/select.c:SyS_pselect6
```
```
In fs/namespace.c (0)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
```
```
In fs/eventpoll.c (0)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
```
```
In fs/compat_ioctl.c (ffffffff812b42ea)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/quota/compat.c (ffffffff812c5a1c)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
```
```
In fs/fat/dir.c (ffffffff81356bbc)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
  - fs/fat/dir.c:fat_dir_ioctl
```
```
In ipc/compat.c (ffffffff81381f2c)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
```
```
In security/tomoyo/common.c (0)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
```
```
In block/compat_ioctl.c (ffffffff814547f9)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
```
```
In lib/iov_iter.c (0)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
```
```
In lib/usercopy.c (0)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
```
```
In drivers/pci/proc.c (0)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff814e9c20)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81581060)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/selection.c (ffffffff81582b42)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:set_selection
```
```
In drivers/char/mem.c (0)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff816452a0)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff81663bde)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff816c02d4)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In drivers/usb/core/devices.c (0)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
```
```
In net/socket.c (ffffffff817afd7a)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff817fa36e)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
```
In arch/x86/lib/csum-wrappers_64.c (0)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
```
```
In arch/x86/lib/usercopy.c (ffffffff818fd4f5)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (0)
Location: arch/x86/include/asm/uaccess.h:41
Inline: True
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004a8f)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff8102cc00)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
```
```
In arch/x86/kernel/signal_compat.c (ffffffff8102cf0f)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:copy_siginfo_from_user32
  - arch/x86/kernel/signal_compat.c:__copy_siginfo_to_user32
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103d238)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103eb10)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff8107fbbb)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff81081ace)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810827eb)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
```
In kernel/exit.c (ffffffff8108f429)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/exit.c:C_SYSC_waitid
  - kernel/exit.c:SYSC_waitid
```
```
In kernel/ptrace.c (ffffffff81098389)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff8109d71d)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sys.c (ffffffff8109e9a5)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:SYSC_olduname
```
```
In kernel/sched/core.c (ffffffff810b9ba3)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_setattr
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In kernel/futex.c (ffffffff8111d570)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:get_futex_key
```
```
In kernel/compat.c (ffffffff8112c46d)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/bpf_trace.c (0)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In kernel/events/core.c (ffffffff811bdd08)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
```
```
In mm/gup.c (ffffffff81207ec2)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
```
```
In mm/mincore.c (0)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In fs/read_write.c (0)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In fs/ioctl.c (0)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In fs/readdir.c (ffffffff8128a46b)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8128d176)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - fs/select.c:compat_SyS_pselect6
  - fs/select.c:SyS_pselect6
```
```
In fs/namespace.c (0)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In fs/eventpoll.c (0)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In fs/compat_ioctl.c (ffffffff812d7a15)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/quota/compat.c (ffffffff812e98cc)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
```
```
In fs/fat/dir.c (ffffffff8137b7fc)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
  - fs/fat/dir.c:fat_dir_ioctl
```
```
In security/tomoyo/common.c (0)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In block/compat_ioctl.c (ffffffff8148048c)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In lib/iov_iter.c (0)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In lib/usercopy.c (0)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In drivers/pci/proc.c (0)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8151e786)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/acpi/acpi_dbg.c (0)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In drivers/char/mem.c (0)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff816ae230)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff816cd22e)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff8172bd04)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In drivers/usb/core/devices.c (0)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In net/socket.c (ffffffff81827ef7)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In net/compat.c (ffffffff81877cbc)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
```
In arch/x86/lib/csum-wrappers_64.c (0)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In arch/x86/lib/usercopy.c (ffffffff81984fd5)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (0)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810051d7)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff8102de50)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103b50e)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103e522)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810400de)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff81082cdc)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff81084e1e)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81085eab)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
```
In kernel/exit.c (ffffffff81092f65)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff8109bbc7)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810a26ed)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
```
```
In kernel/sys.c (ffffffff810a4282)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
```
```
In kernel/sched/core.c (ffffffff810bc8d9)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_read_attr
  - kernel/sched/core.c:sched_copy_attr
```
```
In kernel/printk/printk.c (ffffffff810f3dd3)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In kernel/futex.c (ffffffff8112b316)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:get_futex_key
```
```
In kernel/compat.c (ffffffff8113a6fb)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/bpf_trace.c (ffffffff811a4d2e)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In kernel/bpf/syscall.c (ffffffff811b4372)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In kernel/events/core.c (ffffffff811d88ea)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/events/core.c:perf_copy_attr
```
```
In kernel/rseq.c (ffffffff811ea024)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In mm/gup.c (ffffffff81228c43)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
```
```
In mm/mincore.c (ffffffff81231f64)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
```
In fs/read_write.c (ffffffff8129b3fb)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:rw_copy_check_uvector
```
```
In fs/ioctl.c (ffffffff812b01e7)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/readdir.c (ffffffff812b0ff4)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812b34cf)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6
  - fs/select.c:__ia32_compat_sys_pselect6
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In fs/namespace.c (ffffffff812c09a6)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff812ea894)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/compat_ioctl.c (ffffffff81301bc9)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
```
```
In fs/quota/compat.c (ffffffff81316801)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
```
In fs/fat/dir.c (ffffffff813aa1f3)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
  - fs/fat/dir.c:fat_dir_ioctl
```
```
In security/tomoyo/common.c (ffffffff81425df4)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
```
In block/compat_ioctl.c (ffffffff814b4ff6)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In lib/bitmap.c (ffffffff814c39d1)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist_user
  - lib/bitmap.c:bitmap_parse_user
```
```
In lib/iov_iter.c (ffffffff814c6167)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff814cdba1)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In drivers/pci/proc.c (ffffffff8152a914)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8155431e)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/acpi/acpi_dbg.c (ffffffff815d3914)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In drivers/char/mem.c (ffffffff8164432c)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff816ea53c)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff81709cf5)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff8176b151)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
```
```
In drivers/usb/core/devices.c (ffffffff8176ce6a)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
```
```
In net/socket.c (ffffffff81870c07)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
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
In net/compat.c (ffffffff818c989c)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_setsockopt
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff819defa5)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (ffffffff819e145c)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff819e1536)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:clear_user
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810050d7)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff8102f090)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103ca20)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103fae2)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8104169e)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff8108988c)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_notify_unmap
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108baf0)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8108cc3b)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
```
In kernel/exit.c (ffffffff8109b235)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810a3dd1)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810ab2bd)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
```
```
In kernel/sys.c (ffffffff810ad052)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
```
```
In kernel/sched/core.c (ffffffff810c3e99)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_read_attr
  - kernel/sched/core.c:sched_read_attr
  - kernel/sched/core.c:sched_copy_attr
```
```
In kernel/printk/printk.c (ffffffff810fefc1)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In kernel/futex.c (ffffffff81134f65)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:get_futex_key
```
```
In kernel/compat.c (ffffffff81145f6b)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/bpf_trace.c (ffffffff811b2dfb)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In kernel/bpf/syscall.c (ffffffff811c2392)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In kernel/events/core.c (ffffffff811e9a7a)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/events/core.c:perf_copy_attr
```
```
In kernel/rseq.c (ffffffff811fab94)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In mm/gup.c (ffffffff8123c4e3)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
```
```
In mm/mincore.c (ffffffff81245734)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
```
In fs/read_write.c (ffffffff812b02fb)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:rw_copy_check_uvector
  - fs/read_write.c:rw_copy_check_uvector
```
```
In fs/ioctl.c (ffffffff812c5334)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/readdir.c (ffffffff812c61f4)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812c861f)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6
  - fs/select.c:__ia32_compat_sys_pselect6
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In fs/namespace.c (ffffffff812d5bf6)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff81300ab4)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/compat_ioctl.c (ffffffff81317592)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
```
```
In fs/quota/compat.c (ffffffff8132d7b1)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
```
In fs/fat/dir.c (ffffffff813c2fd3)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
  - fs/fat/dir.c:fat_dir_ioctl
```
```
In security/tomoyo/common.c (ffffffff814424e4)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
```
In block/compat_ioctl.c (ffffffff814c88b6)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In lib/bitmap.c (ffffffff814d7fd1)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist_user
  - lib/bitmap.c:bitmap_parselist_user
  - lib/bitmap.c:bitmap_parse_user
  - lib/bitmap.c:bitmap_parse_user
```
```
In lib/iov_iter.c (ffffffff814da8e1)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff814e2471)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
  - lib/usercopy.c:_copy_from_user
```
```
In lib/strncpy_from_user.c (ffffffff8150ac36)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8150adbe)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff81540794)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8156bd79)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/acpi/acpi_dbg.c (ffffffff815ed0c4)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
```
```
In drivers/char/mem.c (ffffffff8166260c)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff8170dffc)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff8172c1e5)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff8178f6e1)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
```
```
In drivers/usb/core/devices.c (ffffffff817914ba)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
```
```
In net/socket.c (ffffffff81891d80)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
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
In net/compat.c (ffffffff818f4766)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_setsockopt
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a19ed6)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (ffffffff81a1c40c)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a1c4e6)
Location: arch/x86/include/asm/uaccess.h:47
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:clear_user
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810053dd)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff81030e5f)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f087)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff810421e5)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In arch/x86/mm/mpx.c (ffffffff8108cd99)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108f8f0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81090b0b)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
```
In kernel/fork.c (ffffffff81096daa)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/fork.c:copy_clone_args_from_user
```
```
In kernel/exit.c (ffffffff8109f895)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810a8af5)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810b07ad)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
```
```
In kernel/sys.c (ffffffff810b2892)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
```
```
In kernel/sched/core.c (ffffffff810cb725)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_attr_copy_to_user
  - kernel/sched/core.c:sched_attr_copy_to_user
  - kernel/sched/core.c:sched_copy_attr
```
```
In kernel/printk/printk.c (ffffffff81107685)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In kernel/futex.c (ffffffff81140358)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:get_futex_key
```
```
In kernel/compat.c (ffffffff8115133b)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/bpf_trace.c (ffffffff811c1b28)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In kernel/bpf/syscall.c (ffffffff811d2f11)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In kernel/events/core.c (ffffffff81200d9a)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_copy_attr
```
```
In kernel/rseq.c (ffffffff812122b0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In mm/maccess.c (ffffffff8121d87a)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_read
```
```
In mm/gup.c (ffffffff8124db71)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
```
```
In mm/mincore.c (ffffffff812577e4)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
```
In fs/read_write.c (ffffffff812ccc45)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:rw_copy_check_uvector
  - fs/read_write.c:rw_copy_check_uvector
```
```
In fs/ioctl.c (ffffffff812e1b6b)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/readdir.c (ffffffff812e2ca4)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812e50eb)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__do_sys_pselect6
```
```
In fs/namespace.c (ffffffff812f43d7)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff81321d5a)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/compat_ioctl.c (ffffffff8133f457)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
```
```
In fs/quota/compat.c (ffffffff813554f1)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
```
In fs/fat/dir.c (ffffffff813ed82d)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
  - fs/fat/dir.c:fat_dir_ioctl
```
```
In security/tomoyo/common.c (ffffffff814700a5)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
```
In block/compat_ioctl.c (ffffffff814f70bc)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
```
```
In lib/bitmap.c (ffffffff81503fc3)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parse_user
```
```
In lib/iov_iter.c (ffffffff815060a7)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff8150e333)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
  - lib/usercopy.c:_copy_from_user
```
```
In lib/strncpy_from_user.c (ffffffff815393a7)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff815394e9)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff81570084)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8159c04a)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/acpi/acpi_dbg.c (ffffffff8161ee84)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In drivers/char/mem.c (ffffffff816981bc)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81749882)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff817679de)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff817cd8d6)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
```
```
In drivers/usb/core/devices.c (ffffffff817cfd6a)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
```
```
In net/socket.c (ffffffff818dbcda)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
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
In net/compat.c (ffffffff81954272)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a89bf6)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (ffffffff81a8c0bc)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a8c195)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:clear_user
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100545d)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff8103171f)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f6f0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff81042965)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In arch/x86/mm/mpx.c (ffffffff8108d9f9)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff81090550)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8109180b)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
```
In kernel/fork.c (ffffffff8109d242)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/fork.c:clone3_args_valid
```
```
In kernel/exit.c (ffffffff810a5f15)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810af115)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810b72bb)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
```
```
In kernel/sys.c (ffffffff810b8f62)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
```
```
In kernel/sched/core.c (ffffffff810d3955)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_attr_copy_to_user
```
```
In kernel/printk/printk.c (ffffffff81113a45)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In kernel/futex.c (ffffffff8114c3c8)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:get_futex_key
```
```
In kernel/compat.c (ffffffff8115cf8b)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/bpf/syscall.c (ffffffff811df211)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In kernel/rseq.c (ffffffff8121fa90)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In mm/maccess.c (ffffffff8122b1c5)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
```
```
In mm/gup.c (ffffffff8125c0a1)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
```
```
In mm/mincore.c (ffffffff81265d25)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
```
In fs/read_write.c (ffffffff812de665)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:rw_copy_check_uvector
  - fs/read_write.c:rw_copy_check_uvector
```
```
In fs/ioctl.c (ffffffff812f363b)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/readdir.c (ffffffff812f4a14)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812f6b0b)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In fs/namespace.c (ffffffff81305f87)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff813342ba)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/compat_ioctl.c (ffffffff81357681)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
```
```
In fs/quota/compat.c (ffffffff8136d831)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
```
In fs/ext4/ioctl.c (ffffffff813b6c36)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/fat/dir.c (ffffffff8140794d)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
  - fs/fat/dir.c:fat_dir_ioctl
```
```
In security/tomoyo/common.c (ffffffff81489e75)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
```
In block/compat_ioctl.c (ffffffff81515570)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In lib/bitmap.c (ffffffff81521f63)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parse_user
```
```
In lib/iov_iter.c (ffffffff81524080)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff8152c1c6)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
  - lib/usercopy.c:_copy_from_user
```
```
In lib/strncpy_from_user.c (ffffffff8155a1c8)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8155a2ef)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff81591157)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815bd64a)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/acpi/acpi_dbg.c (ffffffff81640930)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In drivers/char/mem.c (ffffffff816badcc)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff8176d9b2)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff8178b9ce)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff817fe324)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
```
```
In drivers/usb/core/devices.c (ffffffff81800bea)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
```
```
In net/socket.c (ffffffff8190e834)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
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
In net/compat.c (ffffffff8198a792)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81ac0e96)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (ffffffff81ac337c)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81ac3455)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:clear_user
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810062f4)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff81033f7f)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff8103a382)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042a20)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff81045970)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81096f99)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
```
```
In kernel/fork.c (ffffffff810a76f2)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/fork.c:__do_sys_clone3
```
```
In kernel/exit.c (ffffffff810adaba)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810b6dd5)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_regset
  - kernel/ptrace.c:ptrace_regset
```
```
In kernel/signal.c (ffffffff810bee0d)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
```
```
In kernel/sched/core.c (ffffffff810dd965)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_attr_copy_to_user
```
```
In kernel/printk/printk.c (ffffffff8111f639)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In kernel/futex.c (ffffffff8115a986)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:get_futex_key
```
```
In kernel/compat.c (ffffffff8116dabb)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/rseq.c (ffffffff8124bd7e)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In mm/maccess.c (ffffffff812580b8)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/gup.c (ffffffff8128b3e2)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
```
```
In mm/mincore.c (ffffffff81296157)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
  - mm/mincore.c:__do_sys_mincore
  - mm/mincore.c:__do_sys_mincore
  - mm/mincore.c:__do_sys_mincore
```
```
In fs/read_write.c (ffffffff813153d4)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:rw_copy_check_uvector
  - fs/read_write.c:rw_copy_check_uvector
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_read
  - fs/read_write.c:vfs_read
```
```
In fs/readdir.c (ffffffff8132c66e)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8132eabb)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In fs/eventpoll.c (ffffffff8136e86a)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/io_uring.c (ffffffff8137b79c)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/io_uring.c:__io_compat_recvmsg_copy_hdr
  - fs/io_uring.c:io_provide_buffers_prep
  - fs/io_uring.c:io_provide_buffers_prep
  - fs/io_uring.c:io_compat_import
```
```
In fs/quota/compat.c (ffffffff813b532c)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/quota/compat.c:__do_compat_sys_quotactl32
  - fs/quota/compat.c:__do_compat_sys_quotactl32
  - fs/quota/compat.c:__do_compat_sys_quotactl32
  - fs/quota/compat.c:__do_compat_sys_quotactl32
  - fs/quota/compat.c:__do_compat_sys_quotactl32
  - fs/quota/compat.c:__do_compat_sys_quotactl32
  - fs/quota/compat.c:__do_compat_sys_quotactl32
  - fs/quota/compat.c:__do_compat_sys_quotactl32
  - fs/quota/compat.c:__do_compat_sys_quotactl32
  - fs/quota/compat.c:__do_compat_sys_quotactl32
  - fs/quota/compat.c:__do_compat_sys_quotactl32
  - fs/quota/compat.c:__do_compat_sys_quotactl32
```
```
In lib/iov_iter.c (ffffffff81587c40)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_from_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
```
```
In lib/usercopy.c (ffffffff8158fa96)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
  - lib/usercopy.c:_copy_from_user
```
```
In lib/strncpy_from_user.c (ffffffff815e3af8)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff815e3c12)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff815fd2e6)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In arch/x86/lib/usercopy.c (ffffffff815ff937)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff815ffa15)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:clear_user
```
```
In drivers/pci/proc.c (ffffffff8163f082)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81666851)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
```
```
In drivers/acpi/acpi_dbg.c (ffffffff816ed3ac)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In drivers/char/mem.c (ffffffff8176eeff)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:read_port
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818a17d6)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff818ce732)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In net/socket.c (ffffffff819e04ee)
Location: arch/x86/include/asm/uaccess.h:43
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810051b4)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:write_ok_or_segv
```
```
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
```
```
In arch/x86/kernel/sys_ia32.c (0)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042959)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (0)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
```
```
In arch/x86/kernel/sev-es.c (ffffffff81082eeb)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/sev-es.c:vc_read_mem
  - arch/x86/kernel/sev-es.c:vc_read_mem
  - arch/x86/kernel/sev-es.c:vc_write_mem
  - arch/x86/kernel/sev-es.c:vc_write_mem
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
```
```
In kernel/fork.c (ffffffff810a34d1)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - kernel/fork.c:__do_sys_clone3
```
```
In kernel/exit.c (0)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
```
```
In kernel/ptrace.c (ffffffff810b018b)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_regset
  - kernel/ptrace.c:ptrace_regset
```
```
In kernel/signal.c (0)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
```
```
In kernel/sched/core.c (ffffffff810da886)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_attr_copy_to_user
```
```
In kernel/printk/printk.c (ffffffff8111a5a1)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
```
```
In kernel/entry/syscall_user_dispatch.c (0)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
```
```
In kernel/futex.c (0)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
```
```
In kernel/compat.c (ffffffff8116a091)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In kernel/rseq.c (0)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
```
```
In mm/maccess.c (ffffffff812627b5)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/gup.c (ffffffff812951ae)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
```
```
In mm/mincore.c (ffffffff812a0e92)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
  - mm/mincore.c:__do_sys_mincore
  - mm/mincore.c:__do_sys_mincore
  - mm/mincore.c:__do_sys_mincore
```
```
In fs/read_write.c (ffffffff8131dc05)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_read
  - fs/read_write.c:vfs_read
```
```
In fs/readdir.c (ffffffff81337c7a)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8133aa11)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
```
```
In fs/eventpoll.c (ffffffff8137bc37)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/io_uring.c (ffffffff813950c5)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_req_prep
```
```
In lib/iov_iter.c (ffffffff815a4ca1)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:__import_iovec
  - lib/iov_iter.c:__import_iovec
  - lib/iov_iter.c:copy_compat_iovec_from_user
  - lib/iov_iter.c:copy_compat_iovec_from_user
  - lib/iov_iter.c:copyout_mc
  - lib/iov_iter.c:copyout_mc
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff815ac5c1)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
  - lib/usercopy.c:_copy_from_user
```
```
In lib/strncpy_from_user.c (ffffffff81607fbb)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81608100)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81621fde)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In arch/x86/lib/usercopy.c (ffffffff81624867)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81624946)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:clear_user
```
```
In drivers/pci/proc.c (ffffffff81665478)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/acpi/acpi_dbg.c (ffffffff8170a844)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
```
```
In drivers/char/mem.c (ffffffff817897df)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:read_port
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ae9b1)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unmap_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unmap_dma
```
```
In drivers/usb/core/devio.c (ffffffff818d783b)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In net/socket.c (ffffffff819df8dd)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
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
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100525a)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/core.c (ffffffff81009030)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal.c (ffffffff8103649d)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8103a179)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_opcodes
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff8103c58c)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104433e)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104709d)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81048daa)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff810694af)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81096aea)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
```
```
In kernel/fork.c (ffffffff810a411c)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - kernel/fork.c:__do_sys_clone3
```
```
In kernel/exit.c (ffffffff810aa1b6)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810b35ed)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_regset
  - kernel/ptrace.c:ptrace_regset
```
```
In kernel/signal.c (ffffffff810bbced)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
```
```
In kernel/sched/core.c (ffffffff810dbf3f)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_attr_copy_to_user
```
```
In kernel/printk/printk.c (ffffffff8111a8be)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff8113d048)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:set_syscall_user_dispatch
```
```
In kernel/futex.c (ffffffff81157de0)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:get_futex_key
```
```
In kernel/compat.c (ffffffff8116ad6a)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/rseq.c (ffffffff8125a7ed)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In mm/maccess.c (ffffffff81267218)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/gup.c (ffffffff8129ab78)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
```
```
In mm/mincore.c (ffffffff812a65ce)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
  - mm/mincore.c:__do_sys_mincore
  - mm/mincore.c:__do_sys_mincore
  - mm/mincore.c:__do_sys_mincore
```
```
In fs/read_write.c (ffffffff81325f98)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_read
  - fs/read_write.c:vfs_read
```
```
In fs/readdir.c (ffffffff8133e3e6)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff813408bb)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In fs/eventpoll.c (ffffffff813823a4)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/io_uring.c (ffffffff8139cd52)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:__io_compat_recvmsg_copy_hdr
  - fs/io_uring.c:io_import_iovec
```
```
In lib/iov_iter.c (ffffffff815ab4c8)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:__import_iovec
  - lib/iov_iter.c:__import_iovec
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In lib/usercopy.c (ffffffff815b7290)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
  - lib/usercopy.c:_copy_from_user
```
```
In lib/strncpy_from_user.c (ffffffff815eac7e)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff815eada3)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff816058e7)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In arch/x86/lib/usercopy.c (ffffffff816081f2)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff8160830f)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:clear_user
```
```
In drivers/pci/proc.c (ffffffff81647a71)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/acpi/acpi_dbg.c (ffffffff816ec056)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
```
```
In drivers/char/mem.c (ffffffff8176d098)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:read_port
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81892cd2)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unmap_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unmap_dma
```
```
In drivers/usb/core/devio.c (ffffffff818ba759)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In net/socket.c (ffffffff819c5aae)
Location: arch/x86/include/asm/uaccess.h:19
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
In net/core/scm.c (ffffffff819dc57a)
Location: arch/x86/include/asm/uaccess.h:19
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100586c)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/core.c (ffffffff81009f09)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal.c (ffffffff8103b73d)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8103fb29)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_opcodes
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff8104208c)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104ae56)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104d4f5)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8104f79a)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81073b5f)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810a6a8a)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
```
```
In kernel/fork.c (ffffffff810b593c)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - kernel/fork.c:__do_sys_clone3
```
```
In kernel/exit.c (ffffffff810bbcf6)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810c578d)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_regset
  - kernel/ptrace.c:ptrace_regset
```
```
In kernel/signal.c (ffffffff810ce74d)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - kernel/signal.c:__x64_compat_sys_sigaction
  - kernel/signal.c:__x64_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
```
```
In kernel/sched/core.c (ffffffff810ef0af)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_attr_copy_to_user
```
```
In kernel/printk/printk.c (ffffffff81139f65)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff81160178)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:set_syscall_user_dispatch
```
```
In kernel/futex.c (ffffffff8117cc60)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:get_futex_key
```
```
In kernel/compat.c (ffffffff81190e15)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/rseq.c (ffffffff812965dd)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In mm/maccess.c (ffffffff812a3c58)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/gup.c (ffffffff812db528)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
```
```
In mm/mincore.c (ffffffff812e7a9e)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
  - mm/mincore.c:__do_sys_mincore
  - mm/mincore.c:__do_sys_mincore
  - mm/mincore.c:__do_sys_mincore
```
```
In fs/read_write.c (ffffffff81371248)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_read
  - fs/read_write.c:vfs_read
```
```
In fs/readdir.c (ffffffff8138bd76)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8138e28b)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - fs/select.c:__x64_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x64_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In fs/eventpoll.c (ffffffff813cf614)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/io_uring.c (ffffffff813e6a6e)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:__io_compat_recvmsg_copy_hdr
  - fs/io_uring.c:io_import_iovec
```
```
In lib/iov_iter.c (ffffffff81614ae8)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:__import_iovec
  - lib/iov_iter.c:__import_iovec
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_from_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:copy_page_to_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In lib/usercopy.c (ffffffff8161d8c0)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
  - lib/usercopy.c:_copy_from_user
```
```
In lib/strncpy_from_user.c (ffffffff8165717e)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff816572a3)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff816741d7)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In arch/x86/lib/usercopy.c (ffffffff81676e32)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81676f4f)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:clear_user
```
```
In drivers/pci/proc.c (ffffffff816b93d1)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/acpi/acpi_dbg.c (ffffffff81766176)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
```
```
In drivers/char/mem.c (ffffffff817f2868)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:read_port
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff819256f4)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unmap_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unmap_dma
```
```
In drivers/usb/core/devio.c (ffffffff81950ed9)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In net/core/scm.c (ffffffff81a8c7ba)
Location: arch/x86/include/asm/uaccess.h:19
Inline: True
Inline callers:
  - net/core/scm.c:put_cmsg
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100545d)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff8103187f)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f870)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff81042ae5)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In arch/x86/mm/mpx.c (ffffffff8108c9b9)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108f510)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810907cb)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
```
In kernel/fork.c (ffffffff81096b62)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/fork.c:clone3_args_valid
```
```
In kernel/exit.c (ffffffff8109f835)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810a9485)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810b162b)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
```
```
In kernel/sys.c (ffffffff810b32d2)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
```
```
In kernel/sched/core.c (ffffffff810cdc45)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_attr_copy_to_user
```
```
In kernel/printk/printk.c (ffffffff8110c025)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In kernel/futex.c (ffffffff811449e8)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:get_futex_key
```
```
In kernel/compat.c (ffffffff811555ab)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/bpf/syscall.c (ffffffff811d7831)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In kernel/rseq.c (ffffffff812180e0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In mm/maccess.c (ffffffff81223815)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
```
```
In mm/gup.c (ffffffff812546f1)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
```
```
In mm/mincore.c (ffffffff8125e375)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
```
In fs/read_write.c (ffffffff812d6c45)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:rw_copy_check_uvector
  - fs/read_write.c:rw_copy_check_uvector
```
```
In fs/ioctl.c (ffffffff812ebc1b)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/readdir.c (ffffffff812ecff4)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812ef0eb)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In fs/namespace.c (ffffffff812fe567)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff8132c89a)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/compat_ioctl.c (ffffffff8134fc61)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
```
```
In fs/quota/compat.c (ffffffff81365e11)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
```
In fs/ext4/ioctl.c (ffffffff813af216)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/fat/dir.c (ffffffff813fff2d)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
  - fs/fat/dir.c:fat_dir_ioctl
```
```
In security/tomoyo/common.c (ffffffff81482455)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
```
In block/compat_ioctl.c (ffffffff8150db50)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In lib/bitmap.c (ffffffff8151a543)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parse_user
```
```
In lib/iov_iter.c (ffffffff8151c660)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff815247a6)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
  - lib/usercopy.c:_copy_from_user
```
```
In lib/strncpy_from_user.c (ffffffff815527a8)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff815528cf)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff81584fe7)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b179a)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/char/mem.c (ffffffff8168082c)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff817220a2)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff817400be)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff817b6704)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
```
```
In drivers/usb/core/devices.c (ffffffff817b8fca)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
```
```
In net/socket.c (ffffffff818ae834)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
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
In net/compat.c (ffffffff8192a602)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a5fce6)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (ffffffff81a621cc)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a622a5)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:clear_user
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81003b3d)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff8102125f)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f070)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff81032155)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In arch/x86/mm/mpx.c (ffffffff8107b4e9)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8107e020)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107f2db)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
```
In kernel/fork.c (ffffffff810855e2)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/fork.c:clone3_args_valid
```
```
In kernel/exit.c (ffffffff8108e265)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff81097e45)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff8109ff4b)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
```
```
In kernel/sys.c (ffffffff810a1c02)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
```
```
In kernel/sched/core.c (ffffffff810bc4d5)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_attr_copy_to_user
```
```
In kernel/printk/printk.c (ffffffff810fce29)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In kernel/futex.c (ffffffff81137cf8)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:get_futex_key
```
```
In kernel/compat.c (ffffffff811488cb)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/bpf/syscall.c (ffffffff811ca5f1)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In kernel/rseq.c (ffffffff8120b2f0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In mm/maccess.c (ffffffff812169c5)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
```
```
In mm/gup.c (ffffffff81247341)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
```
```
In mm/mincore.c (ffffffff81250805)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
```
In fs/read_write.c (ffffffff812c78c5)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:rw_copy_check_uvector
  - fs/read_write.c:rw_copy_check_uvector
```
```
In fs/ioctl.c (ffffffff812dc84b)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/readdir.c (ffffffff812ddc24)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812dfd1b)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In fs/namespace.c (ffffffff812ef187)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff8131c16a)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/compat_ioctl.c (ffffffff81340941)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
```
```
In fs/quota/compat.c (ffffffff81356ab1)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
```
In fs/ext4/ioctl.c (ffffffff8139fca6)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/fat/dir.c (ffffffff813f09ad)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
  - fs/fat/dir.c:fat_dir_ioctl
```
```
In security/tomoyo/common.c (ffffffff81472e75)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
```
In block/compat_ioctl.c (ffffffff814fdf80)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In lib/bitmap.c (ffffffff8150a833)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parse_user
```
```
In lib/iov_iter.c (ffffffff8150c950)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff81514a86)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
  - lib/usercopy.c:_copy_from_user
```
```
In lib/strncpy_from_user.c (ffffffff81542a88)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81542baf)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff81573db7)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815a092a)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/char/mem.c (ffffffff8165e4fc)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff816fb4d2)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff81721d5e)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff817a8124)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
```
```
In drivers/usb/core/devices.c (ffffffff817aa9fa)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
```
```
In net/socket.c (ffffffff81868784)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
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
In net/compat.c (ffffffff818e43b2)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a1cdb6)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (ffffffff81a1f23c)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a1f315)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:clear_user
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100541d)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff810316df)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f6b0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff81042925)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In arch/x86/mm/mpx.c (ffffffff8108c969)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108f4c0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8109077b)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
```
In kernel/fork.c (ffffffff81096b12)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/fork.c:clone3_args_valid
```
```
In kernel/exit.c (ffffffff8109f7e5)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810a89e5)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810b0b8b)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
```
```
In kernel/sys.c (ffffffff810b2832)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
```
```
In kernel/sched/core.c (ffffffff810cd0b5)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_attr_copy_to_user
```
```
In kernel/printk/printk.c (ffffffff81109f15)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In kernel/futex.c (ffffffff81142898)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:get_futex_key
```
```
In kernel/compat.c (ffffffff8115337b)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/bpf/syscall.c (ffffffff811d5601)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In kernel/rseq.c (ffffffff81215e80)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In mm/maccess.c (ffffffff812215b5)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
```
```
In mm/gup.c (ffffffff81252491)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
```
```
In mm/mincore.c (ffffffff8125c115)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
```
In fs/read_write.c (ffffffff812d4a55)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:rw_copy_check_uvector
  - fs/read_write.c:rw_copy_check_uvector
```
```
In fs/ioctl.c (ffffffff812e9a2b)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/readdir.c (ffffffff812eae04)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812ecefb)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In fs/namespace.c (ffffffff812fc357)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff8132a36a)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/compat_ioctl.c (ffffffff8134d731)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
```
```
In fs/quota/compat.c (ffffffff813638e1)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
```
In fs/ext4/ioctl.c (ffffffff813aca76)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/fat/dir.c (ffffffff813fd2ad)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
  - fs/fat/dir.c:fat_dir_ioctl
```
```
In security/tomoyo/common.c (ffffffff8147e4f5)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
```
In block/compat_ioctl.c (ffffffff81509be0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In lib/bitmap.c (ffffffff815165d3)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parse_user
```
```
In lib/iov_iter.c (ffffffff815186f0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff81520836)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
  - lib/usercopy.c:_copy_from_user
```
```
In lib/strncpy_from_user.c (ffffffff8154e4e8)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8154e60f)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff81584ea7)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b1d2a)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/acpi/acpi_dbg.c (ffffffff81634770)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In drivers/char/mem.c (ffffffff816aec0c)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81760e72)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff8178084e)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff817f31a4)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
```
```
In drivers/usb/core/devices.c (ffffffff817f5a6a)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
```
```
In net/socket.c (ffffffff818ff834)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
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
In net/compat.c (ffffffff8197b792)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81acc0d6)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (ffffffff81ace5bc)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81ace695)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:clear_user
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8100555f)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/core.c (0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff8103258f)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810409a0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff81043d05)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In arch/x86/mm/mpx.c (ffffffff8108ecd9)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff810918a0)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81092b5b)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
```
In kernel/fork.c (ffffffff8109e9b2)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/fork.c:clone3_args_valid
```
```
In kernel/exit.c (ffffffff810a7745)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810b0b05)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810b8e5b)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
```
```
In kernel/sys.c (ffffffff810bae32)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
```
```
In kernel/sched/core.c (ffffffff810d5a45)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_attr_copy_to_user
```
```
In kernel/printk/printk.c (ffffffff811150a3)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In kernel/futex.c (ffffffff8114ecdc)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:get_futex_key
```
```
In kernel/compat.c (ffffffff8116027b)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/bpf/syscall.c (ffffffff811e3971)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In kernel/rseq.c (ffffffff81225280)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In mm/maccess.c (ffffffff81230775)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
```
```
In mm/gup.c (ffffffff81261e41)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
```
```
In mm/mincore.c (ffffffff8126bb05)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
```
In fs/read_write.c (ffffffff812e58b5)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:rw_copy_check_uvector
  - fs/read_write.c:rw_copy_check_uvector
```
```
In fs/ioctl.c (ffffffff812faa2b)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/readdir.c (ffffffff812fbdf4)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__ia32_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:__x64_sys_getdents
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812fdefb)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In fs/namespace.c (ffffffff8130d6b7)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff8133ae3a)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/compat_ioctl.c (ffffffff81360cb1)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:compat_ioctl_preallocate
```
```
In fs/quota/compat.c (ffffffff81376f91)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
```
```
In fs/ext4/ioctl.c (ffffffff813c1416)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/fat/dir.c (ffffffff81412edd)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
  - fs/fat/dir.c:fat_dir_ioctl
```
```
In security/tomoyo/common.c (ffffffff81496005)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
```
In block/compat_ioctl.c (ffffffff81523250)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In lib/bitmap.c (ffffffff8152fd63)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parse_user
```
```
In lib/iov_iter.c (ffffffff81531a30)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff8153a1b6)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
  - lib/usercopy.c:_copy_from_user
```
```
In lib/strncpy_from_user.c (ffffffff81568338)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8156845f)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff8159f357)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815cb79a)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/acpi/acpi_dbg.c (ffffffff8164ea90)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
```
```
In drivers/char/mem.c (ffffffff816c919c)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff8177c4d2)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff8179a629)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff8180d424)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
```
```
In drivers/usb/core/devices.c (ffffffff8180fcaa)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
```
```
In net/socket.c (ffffffff81920824)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
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
In net/compat.c (ffffffff8199dce2)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81ad85f8)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (ffffffff81adaacc)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81adaba5)
Location: arch/x86/include/asm/uaccess.h:43
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:clear_user
```
</details>
</li>
</ul>

## Differences
