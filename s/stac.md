# Function: <code>stac</code>

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
In arch/x86/kernel/signal.c (ffffffff8102e2a2)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:restore_sigcontext
  - arch/x86/kernel/signal.c:setup_sigcontext
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/signal_compat.c (ffffffff8102eea0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:copy_siginfo_to_user32
  - arch/x86/kernel/signal_compat.c:copy_siginfo_from_user32
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81077ec9)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_sigcontext
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In arch/x86/lib/usercopy_64.c (ffffffff813f79a9)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__clear_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81817bc3)
Location: arch/x86/include/asm/smap.h:55
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
In arch/x86/entry/common.c (ffffffff81003ced)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
```
```
In arch/x86/events/core.c (ffffffff810078c1)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/xen/setup.c (ffffffff81f88fb0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/mmu.c (ffffffff8101dc5b)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In arch/x86/xen/suspend.c (ffffffff810231d3)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81024619)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/smp.c (ffffffff8102ad9f)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In arch/x86/kernel/signal.c (ffffffff8102de71)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
  - arch/x86/kernel/signal.c:setup_sigcontext
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/signal_compat.c (ffffffff8102e059)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:copy_siginfo_from_user32
  - arch/x86/kernel/signal_compat.c:copy_siginfo_to_user32
```
```
In arch/x86/kernel/dumpstack_64.c (ffffffff810308a9)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack_64.c:is_valid_bugaddr
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a5be)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b706)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103bea2)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8103d855)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103e5da)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff810768f1)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff81078e52)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81079b48)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_sigcontext
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/ptrace.c (ffffffff8108f4bd)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff81094941)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sys.c (ffffffff81095ef9)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
```
```
In kernel/futex.c (ffffffff8110718a)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff81119039)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:compat_SyS_getrlimit
  - kernel/compat.c:compat_SyS_getrlimit
  - kernel/compat.c:compat_SyS_old_getrlimit
  - kernel/compat.c:compat_SyS_old_getrlimit
  - kernel/compat.c:compat_SyS_setrlimit
  - kernel/compat.c:compat_SyS_setrlimit
  - kernel/compat.c:compat_SyS_setitimer
  - kernel/compat.c:compat_SyS_setitimer
  - kernel/compat.c:compat_SyS_setitimer
  - kernel/compat.c:compat_SyS_setitimer
  - kernel/compat.c:compat_SyS_setitimer
  - kernel/compat.c:compat_SyS_setitimer
  - kernel/compat.c:compat_SyS_setitimer
  - kernel/compat.c:compat_SyS_setitimer
  - kernel/compat.c:compat_SyS_getitimer
  - kernel/compat.c:compat_SyS_getitimer
  - kernel/compat.c:compat_SyS_getitimer
  - kernel/compat.c:compat_SyS_getitimer
  - kernel/compat.c:compat_put_timeval
  - kernel/compat.c:compat_put_timeval
  - kernel/compat.c:compat_get_timeval
  - kernel/compat.c:compat_get_timeval
  - kernel/compat.c:__compat_put_timespec
  - kernel/compat.c:__compat_put_timespec
  - kernel/compat.c:__compat_get_timespec
  - kernel/compat.c:__compat_get_timespec
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
```
```
In kernel/trace/trace_kprobe.c (ffffffff81174a83)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/uprobes.c (ffffffff8119b41c)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/maccess.c (ffffffff811a5e94)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In fs/readdir.c (ffffffff8124861c)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/readdir.c:SyS_getdents64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff81249edb)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_pselect6
```
```
In fs/namespace.c (ffffffff81257298)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff8127d16a)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/signalfd.c (ffffffff8127f9bc)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
```
```
In fs/aio.c (ffffffff812861ea)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
```
In fs/compat.c (ffffffff8129194b)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_set_fd_set
  - fs/compat.c:compat_set_fd_set
  - fs/compat.c:compat_set_fd_set
  - fs/compat.c:compat_get_fd_set
  - fs/compat.c:compat_get_fd_set
  - fs/compat.c:compat_get_fd_set
  - fs/compat.c:compat_SyS_getdents64
  - fs/compat.c:compat_filldir64
  - fs/compat.c:compat_filldir64
  - fs/compat.c:compat_filldir64
  - fs/compat.c:compat_filldir64
  - fs/compat.c:compat_filldir64
  - fs/compat.c:compat_filldir64
  - fs/compat.c:compat_filldir
  - fs/compat.c:compat_filldir
  - fs/compat.c:compat_filldir
  - fs/compat.c:compat_filldir
  - fs/compat.c:compat_filldir
  - fs/compat.c:compat_fillonedir
  - fs/compat.c:compat_fillonedir
  - fs/compat.c:compat_fillonedir
  - fs/compat.c:compat_fillonedir
  - fs/compat.c:compat_rw_copy_check_uvector
  - fs/compat.c:compat_rw_copy_check_uvector
  - fs/compat.c:put_compat_flock64
  - fs/compat.c:put_compat_flock64
  - fs/compat.c:put_compat_flock64
  - fs/compat.c:put_compat_flock64
  - fs/compat.c:put_compat_flock64
  - fs/compat.c:get_compat_flock64
  - fs/compat.c:get_compat_flock64
  - fs/compat.c:get_compat_flock64
  - fs/compat.c:get_compat_flock64
  - fs/compat.c:get_compat_flock64
  - fs/compat.c:put_compat_flock
  - fs/compat.c:put_compat_flock
  - fs/compat.c:put_compat_flock
  - fs/compat.c:put_compat_flock
  - fs/compat.c:put_compat_flock
  - fs/compat.c:get_compat_flock
  - fs/compat.c:get_compat_flock
  - fs/compat.c:get_compat_flock
  - fs/compat.c:get_compat_flock
  - fs/compat.c:get_compat_flock
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs
  - fs/compat.c:put_compat_statfs
  - fs/compat.c:put_compat_statfs
  - fs/compat.c:put_compat_statfs
  - fs/compat.c:put_compat_statfs
  - fs/compat.c:put_compat_statfs
  - fs/compat.c:put_compat_statfs
  - fs/compat.c:put_compat_statfs
  - fs/compat.c:put_compat_statfs
  - fs/compat.c:put_compat_statfs
  - fs/compat.c:put_compat_statfs
  - fs/compat.c:put_compat_statfs
```
```
In fs/compat_ioctl.c (ffffffff8129251d)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/binfmt_elf.c (ffffffff813572f5)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8135782d)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In ipc/compat.c (ffffffff813584ed)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
```
```
In ipc/compat_mq.c (ffffffff81363462)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - ipc/compat_mq.c:compat_SyS_mq_open
  - ipc/compat_mq.c:compat_SyS_mq_open
  - ipc/compat_mq.c:compat_SyS_mq_open
  - ipc/compat_mq.c:compat_SyS_mq_open
```
```
In block/compat_ioctl.c (ffffffff8142bd0e)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
```
```
In arch/x86/lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff8143e931)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:copy_user_handle_tail
  - arch/x86/lib/usercopy_64.c:copy_user_handle_tail
  - arch/x86/lib/usercopy_64.c:__clear_user
```
```
In lib/bitmap.c (ffffffff814409ef)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (ffffffff8144453d)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
```
```
In lib/strncpy_from_user.c (ffffffff81461a10)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81461c3d)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - lib/strnlen_user.c:strlen_user
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff8148dc1d)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8151d1f8)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8175930d)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8152618b)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff815402e3)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/selection.c (ffffffff81541f9a)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/selection.c:set_selection
```
```
In drivers/tty/vt/consolemap.c (ffffffff81546d3c)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
```
```
In drivers/tty/vt/vt.c (ffffffff8154b3ad)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8154fdde)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/char/mem.c (ffffffff815637f3)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81600e41)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff8161edcd)
Location: arch/x86/include/asm/smap.h:55
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
  - drivers/scsi/sg.c:sg_write
```
```
In drivers/usb/core/devio.c (ffffffff8167dcd1)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
```
```
In net/socket.c (ffffffff817663bf)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff817aba36)
Location: arch/x86/include/asm/smap.h:55
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
  - net/compat.c:compat_sock_getsockopt
  - net/compat.c:compat_sock_getsockopt
  - net/compat.c:compat_sock_setsockopt
  - net/compat.c:compat_sock_setsockopt
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff818917e2)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
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
In arch/x86/entry/common.c (ffffffff81003ccb)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
```
```
In arch/x86/events/core.c (ffffffff8100794e)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/xen/setup.c (ffffffff81fc43a4)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/mmu.c (ffffffff8101e34b)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In arch/x86/xen/suspend.c (ffffffff81023923)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81024d49)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/smp.c (ffffffff8102af4a)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In arch/x86/kernel/signal.c (ffffffff8102dcd1)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
  - arch/x86/kernel/signal.c:setup_sigcontext
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/signal_compat.c (ffffffff8102df49)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:copy_siginfo_from_user32
  - arch/x86/kernel/signal_compat.c:__copy_siginfo_to_user32
```
```
In arch/x86/kernel/dumpstack_64.c (ffffffff81030509)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack_64.c:is_valid_bugaddr
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81039ead)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103afa6)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103b99f)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8103d145)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103df3a)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff8107a4e1)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8107cc42)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107d938)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_sigcontext
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/ptrace.c (ffffffff8109443d)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff81099951)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sys.c (ffffffff8109aec9)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
```
```
In kernel/futex.c (ffffffff8110e94a)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff81120969)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:compat_SyS_getrlimit
  - kernel/compat.c:compat_SyS_getrlimit
  - kernel/compat.c:compat_SyS_old_getrlimit
  - kernel/compat.c:compat_SyS_old_getrlimit
  - kernel/compat.c:compat_SyS_setrlimit
  - kernel/compat.c:compat_SyS_setrlimit
  - kernel/compat.c:compat_SyS_setitimer
  - kernel/compat.c:compat_SyS_setitimer
  - kernel/compat.c:compat_SyS_setitimer
  - kernel/compat.c:compat_SyS_setitimer
  - kernel/compat.c:compat_SyS_setitimer
  - kernel/compat.c:compat_SyS_setitimer
  - kernel/compat.c:compat_SyS_setitimer
  - kernel/compat.c:compat_SyS_setitimer
  - kernel/compat.c:compat_SyS_getitimer
  - kernel/compat.c:compat_SyS_getitimer
  - kernel/compat.c:compat_SyS_getitimer
  - kernel/compat.c:compat_SyS_getitimer
  - kernel/compat.c:compat_put_timeval
  - kernel/compat.c:compat_put_timeval
  - kernel/compat.c:compat_get_timeval
  - kernel/compat.c:compat_get_timeval
  - kernel/compat.c:__compat_put_timespec
  - kernel/compat.c:__compat_put_timespec
  - kernel/compat.c:__compat_get_timespec
  - kernel/compat.c:__compat_get_timespec
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:compat_get_timex
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff81180503)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/uprobes.c (ffffffff811aae10)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/maccess.c (ffffffff811b6214)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In fs/readdir.c (ffffffff8125b64c)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/readdir.c:SyS_getdents64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8125ce99)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_pselect6
```
```
In fs/namespace.c (ffffffff8126a735)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff81290d07)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/signalfd.c (ffffffff8129352c)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
```
```
In fs/aio.c (ffffffff8129960a)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
```
In fs/compat.c (ffffffff812a66db)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_set_fd_set
  - fs/compat.c:compat_set_fd_set
  - fs/compat.c:compat_set_fd_set
  - fs/compat.c:compat_get_fd_set
  - fs/compat.c:compat_get_fd_set
  - fs/compat.c:compat_get_fd_set
  - fs/compat.c:compat_SyS_getdents64
  - fs/compat.c:compat_filldir64
  - fs/compat.c:compat_filldir64
  - fs/compat.c:compat_filldir64
  - fs/compat.c:compat_filldir64
  - fs/compat.c:compat_filldir64
  - fs/compat.c:compat_filldir64
  - fs/compat.c:compat_filldir
  - fs/compat.c:compat_filldir
  - fs/compat.c:compat_filldir
  - fs/compat.c:compat_filldir
  - fs/compat.c:compat_filldir
  - fs/compat.c:compat_fillonedir
  - fs/compat.c:compat_fillonedir
  - fs/compat.c:compat_fillonedir
  - fs/compat.c:compat_fillonedir
  - fs/compat.c:compat_rw_copy_check_uvector
  - fs/compat.c:compat_rw_copy_check_uvector
  - fs/compat.c:put_compat_flock64
  - fs/compat.c:put_compat_flock64
  - fs/compat.c:put_compat_flock64
  - fs/compat.c:put_compat_flock64
  - fs/compat.c:put_compat_flock64
  - fs/compat.c:get_compat_flock64
  - fs/compat.c:get_compat_flock64
  - fs/compat.c:get_compat_flock64
  - fs/compat.c:get_compat_flock64
  - fs/compat.c:get_compat_flock64
  - fs/compat.c:put_compat_flock
  - fs/compat.c:put_compat_flock
  - fs/compat.c:put_compat_flock
  - fs/compat.c:put_compat_flock
  - fs/compat.c:put_compat_flock
  - fs/compat.c:get_compat_flock
  - fs/compat.c:get_compat_flock
  - fs/compat.c:get_compat_flock
  - fs/compat.c:get_compat_flock
  - fs/compat.c:get_compat_flock
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs
  - fs/compat.c:put_compat_statfs
  - fs/compat.c:put_compat_statfs
  - fs/compat.c:put_compat_statfs
  - fs/compat.c:put_compat_statfs
  - fs/compat.c:put_compat_statfs
  - fs/compat.c:put_compat_statfs
  - fs/compat.c:put_compat_statfs
  - fs/compat.c:put_compat_statfs
  - fs/compat.c:put_compat_statfs
  - fs/compat.c:put_compat_statfs
  - fs/compat.c:put_compat_statfs
```
```
In fs/compat_ioctl.c (ffffffff812a729d)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/binfmt_elf.c (ffffffff8136d786)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8136dd2a)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/pstore/platform.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In ipc/compat.c (ffffffff8136e9dd)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
```
```
In ipc/compat_mq.c (ffffffff81379c32)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - ipc/compat_mq.c:compat_SyS_mq_open
  - ipc/compat_mq.c:compat_SyS_mq_open
  - ipc/compat_mq.c:compat_SyS_mq_open
  - ipc/compat_mq.c:compat_SyS_mq_open
```
```
In block/compat_ioctl.c (ffffffff81445b0e)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
```
```
In arch/x86/lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff8145b981)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:copy_user_handle_tail
  - arch/x86/lib/usercopy_64.c:copy_user_handle_tail
  - arch/x86/lib/usercopy_64.c:__clear_user
```
```
In lib/bitmap.c (ffffffff8145db13)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (ffffffff814626ad)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
```
```
In lib/strncpy_from_user.c (ffffffff8148054d)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8148077d)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - lib/strnlen_user.c:strlen_user
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff814af40d)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81549748)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81785887)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8155269b)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8156c923)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/selection.c (ffffffff8156e5da)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/selection.c:set_selection
```
```
In drivers/tty/vt/consolemap.c (ffffffff8157345a)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
```
```
In drivers/tty/vt/vt.c (ffffffff81577bdd)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8157c98e)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/char/mem.c (ffffffff8158ff53)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81630531)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff8164f96f)
Location: arch/x86/include/asm/smap.h:55
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
  - drivers/scsi/sg.c:sg_write
```
```
In drivers/usb/core/devio.c (ffffffff816aba55)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
```
```
In net/socket.c (ffffffff8179343f)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff817db056)
Location: arch/x86/include/asm/smap.h:55
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
  - net/compat.c:compat_sock_getsockopt
  - net/compat.c:compat_sock_getsockopt
  - net/compat.c:compat_sock_setsockopt
  - net/compat.c:compat_sock_setsockopt
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff818c60f2)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
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
In arch/x86/entry/common.c (ffffffff81003b5b)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
```
```
In arch/x86/events/core.c (ffffffff810076dc)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/xen/multicalls.c (ffffffff81019eba)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/xen/setup.c (ffffffff820a420b)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101ce35)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101df29)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102051d)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102979d)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In arch/x86/kernel/signal.c (ffffffff8102bf51)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
  - arch/x86/kernel/signal.c:setup_sigcontext
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/signal_compat.c (ffffffff8102c1b9)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:copy_siginfo_from_user32
  - arch/x86/kernel/signal_compat.c:__copy_siginfo_to_user32
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81037dc8)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81038e7e)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves
```
```
In arch/x86/kernel/ptrace.c (ffffffff810399eb)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8103b191)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103bf3c)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff81078d51)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8107b3e2)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107c108)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_sigcontext
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/exit.c (ffffffff810886ae)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/exit.c:C_SYSC_waitid
  - kernel/exit.c:SYSC_waitid
```
```
In kernel/ptrace.c (ffffffff8109151d)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810969a1)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sys.c (ffffffff81097cc9)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
```
```
In kernel/futex.c (ffffffff8110fb79)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff8112122d)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:__compat_put_timespec
  - kernel/compat.c:__compat_put_timespec
  - kernel/compat.c:__compat_get_timespec
  - kernel/compat.c:__compat_get_timespec
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff81182ffd)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/uprobes.c (ffffffff811b2277)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/maccess.c (ffffffff811be12b)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In fs/read_write.c (ffffffff812526fa)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/readdir.c (ffffffff81267f14)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:SyS_getdents64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8126a8ea)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/select.c:compat_SyS_pselect6
  - fs/select.c:compat_SyS_pselect6
  - fs/select.c:do_sys_poll
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_pselect6
```
```
In fs/namespace.c (ffffffff81277ed5)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff8129db8d)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/signalfd.c (ffffffff812a07bc)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
```
```
In fs/aio.c (ffffffff812a72b8)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
```
In fs/binfmt_elf.c (ffffffff812b74d7)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff812ba516)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In ipc/compat.c (ffffffff81381f5d)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:put_compat_msqid64_ds
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
```
```
In lib/bitmap.c (ffffffff81462a63)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (ffffffff8146551d)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
```
```
In lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In lib/strncpy_from_user.c (ffffffff814897ed)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81489939)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff814b9ac3)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8155d627)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81560db2)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81566e6b)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81581074)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/selection.c (ffffffff81582b5b)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/selection.c:set_selection
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81590a52)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/char/mem.c (ffffffff815a4019)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff816452b4)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff816643fe)
Location: arch/x86/include/asm/smap.h:55
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
  - drivers/scsi/sg.c:sg_write
```
```
In net/socket.c (ffffffff817b1898)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff817fa38c)
Location: arch/x86/include/asm/smap.h:55
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
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff818fbcb7)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff818fd760)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:copy_user_handle_tail
  - arch/x86/lib/usercopy_64.c:copy_user_handle_tail
  - arch/x86/lib/usercopy_64.c:__clear_user
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
In arch/x86/entry/common.c (ffffffff81003d0d)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
```
```
In arch/x86/events/core.c (ffffffff81007b1b)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/xen/multicalls.c (ffffffff8101a74a)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/xen/setup.c (ffffffff826aa8e9)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101dae9)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101ec30)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81021200)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff810299bc)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In arch/x86/kernel/signal.c (ffffffff8102cc6f)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
  - arch/x86/kernel/signal.c:setup_sigcontext
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/signal_compat.c (ffffffff8102cf29)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:copy_siginfo_from_user32
  - arch/x86/kernel/signal_compat.c:__copy_siginfo_to_user32
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a078)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b419)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103c3eb)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8103dbc1)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103eb33)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff8107f0a1)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff81081ae2)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81082808)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_sigcontext
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/exit.c (ffffffff8108f43d)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/exit.c:C_SYSC_waitid
  - kernel/exit.c:SYSC_waitid
```
```
In kernel/ptrace.c (ffffffff8109839d)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff8109d731)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sys.c (ffffffff8109e9b9)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SYSC_olduname
```
```
In kernel/futex.c (ffffffff8111ae69)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff8112c89d)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff81190c62)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/uprobes.c (ffffffff811c5e87)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/maccess.c (ffffffff811d2df0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In fs/read_write.c (ffffffff81274548)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/readdir.c (ffffffff8128a7c4)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:SyS_getdents64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8128d18a)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/select.c:compat_SyS_pselect6
  - fs/select.c:compat_SyS_pselect6
  - fs/select.c:do_sys_poll
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_pselect6
```
```
In fs/namespace.c (ffffffff8129a915)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff812c1cbd)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/signalfd.c (ffffffff812c3b90)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
```
```
In fs/aio.c (ffffffff812ca648)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
```
In fs/binfmt_elf.c (ffffffff812dad83)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff812dddf8)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In lib/bitmap.c (ffffffff8148e956)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (ffffffff814938e1)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
```
```
In lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In lib/strncpy_from_user.c (ffffffff814c593d)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff814c5a89)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff814f9eaf)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815c1937)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815c5092)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815cb01f)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815f5732)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/char/mem.c (ffffffff8160aa39)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff816ae244)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff816cda64)
Location: arch/x86/include/asm/smap.h:55
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
  - drivers/scsi/sg.c:sg_write
```
```
In net/socket.c (ffffffff81829a38)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff81877cda)
Location: arch/x86/include/asm/smap.h:55
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
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81982b07)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81985250)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:copy_user_handle_tail
  - arch/x86/lib/usercopy_64.c:copy_user_handle_tail
  - arch/x86/lib/usercopy_64.c:__clear_user
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
In arch/x86/entry/common.c (ffffffff810044bd)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
```
```
In arch/x86/events/core.c (ffffffff81008127)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/xen/multicalls.c (ffffffff8101b257)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/xen/setup.c (ffffffff826d3a50)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101e54c)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101f6d0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81021ce0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a403)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In arch/x86/kernel/signal.c (ffffffff8102de6f)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:setup_sigcontext
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103b591)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103c8c4)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103d8ed)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8103f168)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81040101)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff81081c01)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff81084e32)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81085ec8)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_sigcontext
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/exit.c (ffffffff81092f75)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff8109bbdb)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810a2701)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
```
```
In kernel/sys.c (ffffffff810a4296)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
```
```
In kernel/futex.c (ffffffff81127c49)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff8113af66)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff811a6182)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/uprobes.c (ffffffff811e6405)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/maccess.c (ffffffff811f4174)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In fs/read_write.c (ffffffff8129b3ba)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/readdir.c (ffffffff812b139e)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812b34df)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6
  - fs/select.c:__x32_compat_sys_pselect6
  - fs/select.c:__ia32_compat_sys_pselect6
  - fs/select.c:__ia32_compat_sys_pselect6
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In fs/namespace.c (ffffffff812c09d2)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff812eaeb5)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/binfmt_elf.c (ffffffff81303bb4)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff813072ae)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In lib/bitmap.c (ffffffff814c3736)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (ffffffff814c6074)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
```
```
In lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In lib/strncpy_from_user.c (ffffffff814f681f)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff814f697b)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff8152a97c)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815f99c7)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815fd703)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8160387c)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162e4d2)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/char/mem.c (ffffffff8164436f)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff816ea550)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff8170a298)
Location: arch/x86/include/asm/smap.h:55
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
```
```
In net/socket.c (ffffffff81873c95)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff818c98ba)
Location: arch/x86/include/asm/smap.h:55
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
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff819df020)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff819e1740)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:copy_user_handle_tail
  - arch/x86/lib/usercopy_64.c:copy_user_handle_tail
  - arch/x86/lib/usercopy_64.c:__clear_user
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
In arch/x86/entry/common.c (ffffffff810044ed)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
```
```
In arch/x86/events/core.c (ffffffff81008007)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal.c (ffffffff8102f0af)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:setup_sigcontext
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103cab6)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103dde4)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103ee7d)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8104075f)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810416c1)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff81088811)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108bb09)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8108cc58)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_sigcontext
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/exit.c (ffffffff8109b245)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810a3de5)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810ab2d1)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
```
```
In kernel/sys.c (ffffffff810ad06a)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
```
```
In kernel/futex.c (ffffffff81133329)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff811467e6)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff811f6f55)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/maccess.c (ffffffff81206504)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In fs/read_write.c (ffffffff812b02ba)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/readdir.c (ffffffff812c65bf)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812c862f)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6
  - fs/select.c:__x32_compat_sys_pselect6
  - fs/select.c:__ia32_compat_sys_pselect6
  - fs/select.c:__ia32_compat_sys_pselect6
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In fs/namespace.c (ffffffff812d5c22)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff812ff8e3)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/binfmt_elf.c (ffffffff813192d8)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8131ca93)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In lib/bitmap.c (ffffffff814d7b66)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (ffffffff814da834)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
```
```
In lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In lib/strncpy_from_user.c (ffffffff8150ac47)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8150adbe)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff815407fc)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/char/mem.c (ffffffff8166264f)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff8170e04c)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff8172c72d)
Location: arch/x86/include/asm/smap.h:55
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
```
```
In net/socket.c (ffffffff81892c60)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff818f4784)
Location: arch/x86/include/asm/smap.h:55
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
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a19f57)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:55
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a1c6f6)
Location: arch/x86/include/asm/smap.h:55
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:copy_user_handle_tail
  - arch/x86/lib/usercopy_64.c:copy_user_handle_tail
  - arch/x86/lib/usercopy_64.c:__clear_user
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
In arch/x86/entry/common.c (ffffffff81004716)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
```
```
In arch/x86/events/core.c (ffffffff81008301)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user32
  - arch/x86/events/core.c:perf_callchain_user32
```
```
In arch/x86/kernel/signal.c (ffffffff81030e7f)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
  - arch/x86/kernel/signal.c:setup_sigcontext
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f106)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040647)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/ptrace.c (ffffffff81041535)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff81042e0f)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81043bc6)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/mpx.c (ffffffff8108ca5c)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108f90b)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81090b28)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_sigcontext
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/exit.c (ffffffff8109f8a5)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810a8b09)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810b07c1)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
```
```
In kernel/sys.c (ffffffff810b28aa)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
```
```
In kernel/futex.c (ffffffff8113e3c9)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff81151926)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8120f0d1)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/maccess.c (ffffffff8121d948)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In fs/read_write.c (ffffffff812ccc11)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/readdir.c (ffffffff812e307f)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812e50fb)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:__do_sys_pselect6
  - fs/select.c:__do_sys_pselect6
```
```
In fs/namespace.c (ffffffff812f4404)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff81320a88)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/binfmt_elf.c (ffffffff81340c09)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8134431c)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In lib/bitmap.c (ffffffff81503e46)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (ffffffff815061a0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
```
```
In lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In lib/strncpy_from_user.c (ffffffff815393b8)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff815394e9)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff815700ed)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/char/mem.c (ffffffff816981fc)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff817498cb)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff81767fc4)
Location: arch/x86/include/asm/smap.h:50
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
```
```
In net/socket.c (ffffffff818dcf42)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff81954298)
Location: arch/x86/include/asm/smap.h:50
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
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a89c69)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a8c135)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__clear_user
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
In arch/x86/entry/common.c (ffffffff81004776)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
```
```
In arch/x86/events/core.c (ffffffff81008519)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal.c (ffffffff8103173f)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:setup_sigcontext
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f76f)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040e17)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/ptrace.c (ffffffff81041cbe)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff81043574)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81044316)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/mpx.c (ffffffff8108d6bc)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff81090569)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81091828)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_sigcontext
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/exit.c (ffffffff810a5f25)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810af129)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810b72cf)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
```
```
In kernel/sys.c (ffffffff810b8f7a)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
```
```
In kernel/futex.c (ffffffff81149f59)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff8115d576)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8121c3b9)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/maccess.c (ffffffff8122b3e8)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In fs/read_write.c (ffffffff812de631)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/readdir.c (ffffffff812f3def)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812f6b1b)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In fs/namespace.c (ffffffff81305fb4)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff81333838)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/binfmt_elf.c (ffffffff81359109)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff8135c683)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In lib/bitmap.c (ffffffff81521de3)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (ffffffff815241d0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
```
```
In lib/usercopy.c (ffffffff8152c1db)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff8155a1dd)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8155a30b)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff81591185)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/char/mem.c (ffffffff816bae0c)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff8176d9fb)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff8178bfb4)
Location: arch/x86/include/asm/smap.h:50
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
```
```
In net/socket.c (ffffffff8190dc46)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff8198a7b8)
Location: arch/x86/include/asm/smap.h:50
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
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81ac0f08)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81ac33f5)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__clear_user
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
In arch/x86/entry/common.c (ffffffff81bbc7cd)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
```
```
In arch/x86/events/core.c (ffffffff810095b0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user32
  - arch/x86/events/core.c:perf_callchain_user32
```
```
In arch/x86/kernel/signal.c (ffffffff81033f84)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff8103a396)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042a9e)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_user_to_fpregs_zeroing
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/ptrace.c (ffffffff81044d92)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81047d57)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81096faf)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
```
```
In kernel/exit.c (ffffffff810adace)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810b6de9)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810bee21)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
```
```
In kernel/futex.c (ffffffff8115a99a)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff8116dfb6)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/events/uprobes.c (ffffffff81246ed0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/events/uprobes.c:is_trap_at_addr
```
```
In fs/read_write.c (ffffffff81315395)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/readdir.c (ffffffff8132c680)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8132eacb)
Location: arch/x86/include/asm/smap.h:50
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
In fs/eventpoll.c (ffffffff8136dab6)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/io_uring.c (ffffffff8137b7ac)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/io_uring.c:__io_compat_recvmsg_copy_hdr
  - fs/io_uring.c:io_compat_import
```
```
In lib/iov_iter.c (ffffffff81586e50)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
```
```
In lib/usercopy.c (ffffffff8158faab)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff815e3b0d)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff815e3c2e)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff815fd2f3)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In arch/x86/lib/usercopy_64.c (ffffffff815ff965)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__clear_user
```
```
In drivers/pci/proc.c (ffffffff8163f0b0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/char/mem.c (ffffffff8176ef3f)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In net/socket.c (ffffffff819e21c6)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:move_addr_to_user
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
In arch/x86/kernel/signal.c (ffffffff81033d9e)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff8103ab9a)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042892)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_user_to_fpregs_zeroing
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81096208)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In kernel/exit.c (ffffffff810a9147)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/futex.c (ffffffff811569ce)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff8116a5c1)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In fs/readdir.c (ffffffff81337c9b)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8133aa30)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In lib/iov_iter.c (ffffffff815a411b)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_compat_iovec_from_user
```
```
In lib/usercopy.c (ffffffff815ac5e6)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff81607fcd)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81608119)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In arch/x86/lib/copy_mc.c (ffffffff81621783)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81621ff5)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81624895)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__clear_user
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
In arch/x86/kernel/signal.c (ffffffff8103589c)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff8103c599)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81044273)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_user_to_fpregs_zeroing
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff810694e7)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81096af9)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In kernel/exit.c (ffffffff810aa1bf)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/futex.c (ffffffff81157ded)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff8116b223)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In kernel/rseq.c (ffffffff8125adee)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In fs/readdir.c (ffffffff8133e3fd)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff813408c4)
Location: arch/x86/include/asm/smap.h:47
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
In lib/iov_iter.c (ffffffff815ab087)
Location: arch/x86/include/asm/smap.h:47
Inline: True
```
```
In lib/usercopy.c (ffffffff815b72a5)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff815eac98)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff815eadbe)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In arch/x86/lib/copy_mc.c (ffffffff81605083)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff816058f4)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81608265)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__clear_user
```
```
In net/core/scm.c (ffffffff819dc58f)
Location: arch/x86/include/asm/smap.h:47
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
In arch/x86/kernel/signal.c (ffffffff8103ab7c)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff81042099)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104a607)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81073b97)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810a6a99)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In kernel/exit.c (ffffffff810bbcff)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/futex.c (ffffffff8117cc6d)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff81190e23)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In kernel/rseq.c (ffffffff81296be3)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In fs/readdir.c (ffffffff8138bd8d)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8138e294)
Location: arch/x86/include/asm/smap.h:47
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
In lib/iov_iter.c (ffffffff81614997)
Location: arch/x86/include/asm/smap.h:47
Inline: True
```
```
In lib/usercopy.c (ffffffff8161d8d5)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff81657198)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff816572be)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In arch/x86/lib/copy_mc.c (ffffffff81673970)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff816741e4)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81676ea5)
Location: arch/x86/include/asm/smap.h:47
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__clear_user
```
```
In net/core/scm.c (ffffffff81a8c7cf)
Location: arch/x86/include/asm/smap.h:47
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
In arch/x86/kernel/signal.c (ffffffff81041e1c)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff81049da5)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81054a3f)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81082263)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810bbda3)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In kernel/exit.c (ffffffff810d2844)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/futex/core.c (ffffffff811b2d09)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cmpxchg_value_locked
```
```
In kernel/futex/waitwake.c (ffffffff811b67a0)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
```
```
In kernel/compat.c (ffffffff811c0606)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In kernel/rseq.c (ffffffff812eca7e)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_update_cpu_id
```
```
In mm/gup.c (ffffffff81336d60)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - mm/gup.c:fault_in_readable
  - mm/gup.c:fault_in_writeable
```
```
In fs/readdir.c (ffffffff8140d30b)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8140f587)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In lib/iov_iter.c (ffffffff816e1709)
Location: arch/x86/include/asm/smap.h:36
Inline: True
```
```
In lib/usercopy.c (ffffffff816eb43f)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff8176e9d3)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8176eb1a)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In arch/x86/lib/copy_mc.c (ffffffff8178df50)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff8178e907)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81791e55)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__clear_user
```
```
In net/core/scm.c (ffffffff81c020c0)
Location: arch/x86/include/asm/smap.h:36
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
In arch/x86/kernel/signal_64.c (ffffffff8104bca0)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/signal_64.c:x64_setup_rt_frame
```
```
In arch/x86/kernel/ldt.c (ffffffff8105292d)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:read_default_ldt
  - arch/x86/kernel/ldt.c:read_ldt
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff81054f85)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/signal_32.c (ffffffff81055d86)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81062598)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81094ca3)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
```
```
In kernel/exit.c (ffffffff810f1304)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/signal.c (ffffffff81105d79)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/futex/core.c (ffffffff811f3bd9)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cmpxchg_value_locked
```
```
In kernel/futex/waitwake.c (ffffffff811f78f0)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
```
```
In kernel/compat.c (ffffffff812029f6)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In kernel/rseq.c (ffffffff81356ffb)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In mm/gup.c (ffffffff813ae1f0)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - mm/gup.c:fault_in_readable
  - mm/gup.c:fault_in_writeable
```
```
In mm/mempolicy.c (ffffffff81414bc3)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - mm/mempolicy.c:copy_nodes_to_user
```
```
In fs/readdir.c (ffffffff81497dc2)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8149a187)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814e046c)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e39be)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
```
```
In fs/binfmt_elf.c (ffffffff81510f3d)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:padzero
```
```
In fs/compat_binfmt_elf.c (ffffffff81513fe2)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:padzero
```
```
In fs/proc/kcore.c (ffffffff81545cad)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In security/keys/keyctl.c (ffffffff81654d9f)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_capabilities
```
```
In security/keys/keyctl_pkey.c (ffffffff8165a632)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
```
```
In lib/iov_iter.c (ffffffff817d4f77)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
```
In lib/usercopy.c (ffffffff817dbb0f)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff8189e2e3)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8189e43a)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/char/mem.c (ffffffff81a921d1)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_mem
```
```
In drivers/input/evdev.c (ffffffff81caf924)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_get_mask
```
```
In drivers/md/dm-ioctl.c (ffffffff81d17f4d)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-ioctl.c:copy_params
```
```
In net/core/scm.c (ffffffff81db16f8)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - net/core/scm.c:put_cmsg
```
```
In arch/x86/lib/copy_mc.c (ffffffff8204b780)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff8204c237)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
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
In arch/x86/kernel/signal_64.c (ffffffff8104c4dd)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/signal_64.c:x64_setup_rt_frame
```
```
In arch/x86/kernel/ldt.c (ffffffff810539ff)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:read_default_ldt
  - arch/x86/kernel/ldt.c:read_ldt
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff8105618b)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/signal_32.c (ffffffff81056d2f)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff810632eb)
Location: arch/x86/include/asm/smap.h:36
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106436c)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
  - arch/x86/kernel/fpu/signal.c:check_xstate_in_sigframe
```
```
In arch/x86/kernel/tls.c (ffffffff81068eb5)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81097b74)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
```
```
In kernel/exit.c (ffffffff810fd20e)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/signal.c (ffffffff81112059)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/futex/core.c (ffffffff81208360)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cmpxchg_value_locked
```
```
In kernel/futex/waitwake.c (ffffffff8120c2ed)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
```
```
In kernel/compat.c (ffffffff81217db4)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In kernel/trace/trace.c (ffffffff81282fc1)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/rseq.c (ffffffff81388131)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_update_cpu_node_id
```
```
In mm/maccess.c (ffffffff8139837b)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/gup.c (ffffffff813e251e)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - mm/gup.c:fault_in_readable
  - mm/gup.c:fault_in_writeable
```
```
In mm/memory.c (ffffffff813e98fb)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - mm/memory.c:__wp_page_copy_user
  - mm/memory.c:__wp_page_copy_user
```
```
In mm/mempolicy.c (ffffffff81448178)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - mm/mempolicy.c:copy_nodes_to_user
```
```
In fs/readdir.c (ffffffff814ccd2d)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff814cf23d)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81516c74)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151a305)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
```
```
In fs/binfmt_elf.c (ffffffff8154885a)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:padzero
```
```
In fs/compat_binfmt_elf.c (ffffffff8154ba28)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:padzero
```
```
In security/keys/keyctl.c (ffffffff8168d5d6)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_capabilities
```
```
In security/keys/keyctl_pkey.c (ffffffff81692f40)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
```
```
In lib/iov_iter.c (ffffffff81810a09)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_iovec_from_user
  - lib/iov_iter.c:copy_compat_iovec_from_user
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff8181aeab)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In lib/strncpy_from_user.c (ffffffff818e08ad)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff818e0a0f)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/char/mem.c (ffffffff81adda7b)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_mem
```
```
In drivers/input/evdev.c (ffffffff81d16ead)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_get_mask
```
```
In drivers/md/dm-ioctl.c (ffffffff81d81093)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-ioctl.c:copy_params
```
```
In net/core/scm.c (ffffffff81e21bd3)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - net/core/scm.c:put_cmsg
```
```
In arch/x86/lib/copy_mc.c (ffffffff820ca060)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff820cab32)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In arch/x86/lib/insn-eval.c (ffffffff820ccb8f)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
```
```
In arch/x86/lib/usercopy.c (ffffffff820ce156)
Location: arch/x86/include/asm/smap.h:36
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff820ce3f2)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
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
In arch/x86/kernel/signal_64.c (ffffffff8105375d)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/signal_64.c:x64_setup_rt_frame
```
```
In arch/x86/kernel/ldt.c (ffffffff8105ac1f)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:read_default_ldt
  - arch/x86/kernel/ldt.c:read_ldt
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff8105d3db)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/signal_32.c (ffffffff8105df7f)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8106a5eb)
Location: arch/x86/include/asm/smap.h:36
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106b842)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
  - arch/x86/kernel/fpu/signal.c:check_xstate_in_sigframe
```
```
In arch/x86/kernel/tls.c (ffffffff8107032b)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109f0e4)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
```
```
In kernel/exit.c (ffffffff8110774e)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/signal.c (ffffffff8111ba49)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/futex/core.c (ffffffff8121f1f0)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cmpxchg_value_locked
```
```
In kernel/futex/waitwake.c (ffffffff812235ed)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
```
```
In kernel/compat.c (ffffffff8122f974)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In kernel/trace/trace.c (ffffffff8129e351)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/rseq.c (ffffffff813b1b91)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_update_cpu_node_id
```
```
In mm/maccess.c (ffffffff813c219b)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/gup.c (ffffffff8140cd4e)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - mm/gup.c:fault_in_readable
  - mm/gup.c:fault_in_writeable
```
```
In mm/memory.c (ffffffff814148f1)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - mm/memory.c:__wp_page_copy_user
  - mm/memory.c:__wp_page_copy_user
```
```
In mm/mempolicy.c (ffffffff81481b78)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - mm/mempolicy.c:copy_nodes_to_user
```
```
In fs/readdir.c (ffffffff814ff31d)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff81501b7d)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154b064)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154e6d5)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
```
```
In fs/binfmt_elf.c (ffffffff8157cef2)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_load
```
```
In fs/compat_binfmt_elf.c (ffffffff8157ff2d)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_load
```
```
In security/keys/keyctl.c (ffffffff816c9b26)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_capabilities
```
```
In security/keys/keyctl_pkey.c (ffffffff816cf510)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
```
```
In io_uring/waitid.c (ffffffff8182a625)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - io_uring/waitid.c:io_waitid_copy_si
  - io_uring/waitid.c:io_waitid_copy_si
```
```
In lib/iov_iter.c (ffffffff81856d89)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_iovec_from_user
  - lib/iov_iter.c:copy_compat_iovec_from_user
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:copy_page_from_iter_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In lib/usercopy.c (ffffffff81860203)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In lib/strncpy_from_user.c (ffffffff819273ed)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81927552)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/char/mem.c (ffffffff81b30e6b)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_mem
```
```
In drivers/gpu/drm/drm_ioc32.c (ffffffff81cb945a)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_ioc32.c:compat_drm_getstats
```
```
In drivers/input/evdev.c (ffffffff81dccb5d)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_get_mask
```
```
In drivers/md/dm-ioctl.c (ffffffff81e38737)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-ioctl.c:copy_params
```
```
In net/core/scm.c (ffffffff81edfaf3)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - net/core/scm.c:put_cmsg
```
```
In arch/x86/lib/copy_mc.c (ffffffff821a49e0)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff821a5372)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In arch/x86/lib/insn-eval.c (ffffffff821a73bf)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
```
```
In arch/x86/lib/usercopy.c (ffffffff821a8986)
Location: arch/x86/include/asm/smap.h:36
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff821a8c02)
Location: arch/x86/include/asm/smap.h:36
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
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
In arch/x86/entry/common.c (ffffffff81004776)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
```
```
In arch/x86/events/core.c (ffffffff81008519)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal.c (ffffffff8103189f)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:setup_sigcontext
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f8ef)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040f97)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/ptrace.c (ffffffff81041e3e)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff810436f4)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81044496)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/mpx.c (ffffffff8108c67c)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108f529)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810907e8)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_sigcontext
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/exit.c (ffffffff8109f845)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810a9499)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810b163f)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
```
```
In kernel/sys.c (ffffffff810b32ea)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
```
```
In kernel/futex.c (ffffffff81142579)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff81155b96)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81214a09)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/maccess.c (ffffffff81223a38)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In fs/read_write.c (ffffffff812d6c11)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/readdir.c (ffffffff812ec3cf)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812ef0fb)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In fs/namespace.c (ffffffff812fe594)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff8132be18)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/binfmt_elf.c (ffffffff813516e9)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff81354c63)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In lib/bitmap.c (ffffffff8151a3c3)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (ffffffff8151c7b0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
```
```
In lib/usercopy.c (ffffffff815247bb)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff815527bd)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff815528eb)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff81585015)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/char/mem.c (ffffffff8168086c)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff817220eb)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff817406a4)
Location: arch/x86/include/asm/smap.h:50
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
```
```
In net/socket.c (ffffffff818adc46)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff8192a628)
Location: arch/x86/include/asm/smap.h:50
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
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a5fd58)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a62245)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__clear_user
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
In arch/x86/entry/common.c (ffffffff81002dbb)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
```
```
In arch/x86/events/core.c (ffffffff81006d09)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal.c (ffffffff8102127f)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:setup_sigcontext
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f0ef)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81030777)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/ptrace.c (ffffffff810314fe)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff81032d14)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81033ab6)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/mpx.c (ffffffff8107b1ac)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8107e039)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107f2f8)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_sigcontext
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/exit.c (ffffffff8108e275)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff81097e59)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff8109ff5f)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
```
```
In kernel/sys.c (ffffffff810a1c1a)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
```
```
In kernel/futex.c (ffffffff811358d9)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff81148eb6)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81207779)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/maccess.c (ffffffff81216be8)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In fs/read_write.c (ffffffff812c7891)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/readdir.c (ffffffff812dcfff)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812dfd2b)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In fs/namespace.c (ffffffff812ef1b4)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff8131c578)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/binfmt_elf.c (ffffffff813423c9)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff81345923)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In lib/bitmap.c (ffffffff8150a6b3)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (ffffffff8150caa0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
```
```
In lib/usercopy.c (ffffffff81514a9b)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff81542a9d)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81542bcb)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff81573de5)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/char/mem.c (ffffffff8165e53c)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff816fb51b)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff81722338)
Location: arch/x86/include/asm/smap.h:50
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
```
```
In net/socket.c (ffffffff81867b96)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff818e43d8)
Location: arch/x86/include/asm/smap.h:50
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
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a1ce28)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a1f2b5)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__clear_user
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
In arch/x86/entry/common.c (ffffffff81004736)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
```
```
In arch/x86/events/core.c (ffffffff810084d9)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal.c (ffffffff810316ff)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:setup_sigcontext
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f72f)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040dd7)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/ptrace.c (ffffffff81041c7e)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff81043534)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810442d6)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/mpx.c (ffffffff8108c62c)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108f4d9)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81090798)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_sigcontext
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/exit.c (ffffffff8109f7f5)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810a89f9)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810b0b9f)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
```
```
In kernel/sys.c (ffffffff810b284a)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
```
```
In kernel/futex.c (ffffffff81140429)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff81153966)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff812127a9)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/maccess.c (ffffffff812217d8)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In fs/read_write.c (ffffffff812d4a21)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/readdir.c (ffffffff812ea1df)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812ecf0b)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In fs/namespace.c (ffffffff812fc384)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff813298e8)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/binfmt_elf.c (ffffffff8134f1b9)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff81352733)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In lib/bitmap.c (ffffffff81516453)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (ffffffff81518840)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
```
```
In lib/usercopy.c (ffffffff8152084b)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff8154e4fd)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8154e62b)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff81584ed5)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/char/mem.c (ffffffff816aec4c)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81760ebb)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff81780e34)
Location: arch/x86/include/asm/smap.h:50
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
```
```
In net/socket.c (ffffffff818fec46)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff8197b7b8)
Location: arch/x86/include/asm/smap.h:50
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
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81acc148)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81ace635)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__clear_user
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
In arch/x86/entry/common.c (ffffffff81004876)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
```
```
In arch/x86/events/core.c (ffffffff81008639)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal.c (ffffffff810325af)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:setup_sigcontext
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81040a1f)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810421b7)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104305e)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff81044934)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810456d6)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/mpx.c (ffffffff8108e98c)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff810918b9)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81092b78)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_sigcontext
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/exit.c (ffffffff810a7755)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810b0b19)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810b8e6f)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
```
```
In kernel/sys.c (ffffffff810bae4a)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
```
```
In kernel/futex.c (ffffffff8114cf59)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff81160866)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81221729)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/maccess.c (ffffffff81230998)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In fs/read_write.c (ffffffff812e5881)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/readdir.c (ffffffff812fb1cf)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812fdf0b)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In fs/namespace.c (ffffffff8130d6e4)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff8133b248)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/binfmt_elf.c (ffffffff81362739)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffffffff81365ef3)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In lib/bitmap.c (ffffffff8152fbe3)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (ffffffff81532000)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
```
```
In lib/usercopy.c (ffffffff8153a1cb)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff8156834d)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8156847b)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff8159f385)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/char/mem.c (ffffffff816c91dc)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff8177c51b)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff8179a8fc)
Location: arch/x86/include/asm/smap.h:50
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
```
```
In net/socket.c (ffffffff8191fcae)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff8199dd08)
Location: arch/x86/include/asm/smap.h:50
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
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81ad864c)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:50
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81adab45)
Location: arch/x86/include/asm/smap.h:50
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__clear_user
```
</details>
</li>
</ul>

## Differences
