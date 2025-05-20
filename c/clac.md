# Function: <code>clac</code>

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
In arch/x86/kernel/signal.c (ffffffff8102e37b)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:restore_sigcontext
  - arch/x86/kernel/signal.c:setup_sigcontext
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/signal_compat.c (ffffffff8102eed5)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:copy_siginfo_to_user32
  - arch/x86/kernel/signal_compat.c:copy_siginfo_from_user32
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81077f88)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_sigcontext
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In arch/x86/lib/usercopy_64.c (ffffffff813f79df)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__clear_user
  - arch/x86/lib/usercopy_64.c:copy_user_handle_tail
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81817bde)
Location: arch/x86/include/asm/smap.h:49
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
In arch/x86/entry/common.c (ffffffff81003cfc)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
```
```
In arch/x86/events/core.c (ffffffff810078ca)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/xen/setup.c (ffffffff81f88fb8)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/mmu.c (ffffffff8101dc63)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In arch/x86/xen/suspend.c (ffffffff810231db)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81024621)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/smp.c (ffffffff8102ada5)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In arch/x86/kernel/signal.c (ffffffff8102de77)
Location: arch/x86/include/asm/smap.h:49
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
In arch/x86/kernel/signal_compat.c (ffffffff8102e082)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:copy_siginfo_from_user32
  - arch/x86/kernel/signal_compat.c:copy_siginfo_to_user32
```
```
In arch/x86/kernel/dumpstack_64.c (ffffffff810308b1)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack_64.c:is_valid_bugaddr
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a5ca)
Location: arch/x86/include/asm/smap.h:49
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b712)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103bebb)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8103d86e)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103e56a)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff810768fe)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff81078e79)
Location: arch/x86/include/asm/smap.h:49
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
In arch/x86/ia32/ia32_signal.c (ffffffff81079c06)
Location: arch/x86/include/asm/smap.h:49
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
In kernel/ptrace.c (ffffffff8108f4c6)
Location: arch/x86/include/asm/smap.h:49
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
In kernel/signal.c (ffffffff81094948)
Location: arch/x86/include/asm/smap.h:49
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
In kernel/sys.c (ffffffff81095f04)
Location: arch/x86/include/asm/smap.h:49
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
In kernel/futex.c (ffffffff81107191)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff81119041)
Location: arch/x86/include/asm/smap.h:49
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
In kernel/trace/trace_kprobe.c (ffffffff81174a8e)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/uprobes.c (ffffffff8119b426)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/maccess.c (ffffffff811a5ea0)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In fs/readdir.c (ffffffff81248625)
Location: arch/x86/include/asm/smap.h:49
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
In fs/select.c (ffffffff81249eee)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_pselect6
```
```
In fs/namespace.c (ffffffff812572a0)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff8127d175)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/signalfd.c (ffffffff8127f9c9)
Location: arch/x86/include/asm/smap.h:49
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
In fs/aio.c (ffffffff812861f8)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
```
In fs/compat.c (ffffffff81291953)
Location: arch/x86/include/asm/smap.h:49
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
In fs/compat_ioctl.c (ffffffff8129252d)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/binfmt_elf.c (ffffffff81357305)
Location: arch/x86/include/asm/smap.h:49
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
In fs/compat_binfmt_elf.c (ffffffff8135783c)
Location: arch/x86/include/asm/smap.h:49
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
In ipc/compat.c (ffffffff813584fe)
Location: arch/x86/include/asm/smap.h:49
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
In ipc/compat_mq.c (ffffffff8136346b)
Location: arch/x86/include/asm/smap.h:49
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
In block/compat_ioctl.c (ffffffff8142bd19)
Location: arch/x86/include/asm/smap.h:49
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
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff8143e93d)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:copy_user_handle_tail
  - arch/x86/lib/usercopy_64.c:copy_user_handle_tail
  - arch/x86/lib/usercopy_64.c:copy_user_handle_tail
  - arch/x86/lib/usercopy_64.c:__clear_user
```
```
In lib/bitmap.c (ffffffff814409fa)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (ffffffff81444545)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
```
```
In lib/strncpy_from_user.c (ffffffff81461ac9)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81461cbc)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - lib/strnlen_user.c:strlen_user
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff8148dc28)
Location: arch/x86/include/asm/smap.h:49
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
In drivers/xen/xenbus/xenbus_client.c (ffffffff8151d200)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81759315)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81526193)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff815402f2)
Location: arch/x86/include/asm/smap.h:49
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
In drivers/tty/vt/selection.c (ffffffff81541fa5)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/selection.c:set_selection
```
```
In drivers/tty/vt/consolemap.c (ffffffff81546d45)
Location: arch/x86/include/asm/smap.h:49
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
In drivers/tty/vt/vt.c (ffffffff8154b3b6)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8154fde6)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/char/mem.c (ffffffff815637fc)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81600e88)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff8161ede2)
Location: arch/x86/include/asm/smap.h:49
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
In drivers/usb/core/devio.c (ffffffff8167dcda)
Location: arch/x86/include/asm/smap.h:49
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
In net/socket.c (ffffffff817663cd)
Location: arch/x86/include/asm/smap.h:49
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
In net/compat.c (ffffffff817aba3d)
Location: arch/x86/include/asm/smap.h:49
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
In arch/x86/lib/csum-wrappers_64.c (ffffffff818917ea)
Location: arch/x86/include/asm/smap.h:49
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
In arch/x86/entry/common.c (ffffffff81003cda)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
```
```
In arch/x86/events/core.c (ffffffff81007956)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/xen/setup.c (ffffffff81fc43ac)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/mmu.c (ffffffff8101e353)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In arch/x86/xen/suspend.c (ffffffff8102392b)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff81024d51)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/smp.c (ffffffff8102af50)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In arch/x86/kernel/signal.c (ffffffff8102dcd7)
Location: arch/x86/include/asm/smap.h:49
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
In arch/x86/kernel/signal_compat.c (ffffffff8102df72)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:copy_siginfo_from_user32
  - arch/x86/kernel/signal_compat.c:__copy_siginfo_to_user32
```
```
In arch/x86/kernel/dumpstack_64.c (ffffffff81030511)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack_64.c:is_valid_bugaddr
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81039eba)
Location: arch/x86/include/asm/smap.h:49
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8103afb2)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103b9ac)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8103d15e)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103deca)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff8107a4ee)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8107cc69)
Location: arch/x86/include/asm/smap.h:49
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
In arch/x86/ia32/ia32_signal.c (ffffffff8107d9d4)
Location: arch/x86/include/asm/smap.h:49
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
In kernel/ptrace.c (ffffffff81094446)
Location: arch/x86/include/asm/smap.h:49
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
In kernel/signal.c (ffffffff81099958)
Location: arch/x86/include/asm/smap.h:49
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
In kernel/sys.c (ffffffff8109aed4)
Location: arch/x86/include/asm/smap.h:49
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
In kernel/futex.c (ffffffff8110e951)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff81120971)
Location: arch/x86/include/asm/smap.h:49
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
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff8118050e)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/uprobes.c (ffffffff811aae1a)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/maccess.c (ffffffff811b6220)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In fs/readdir.c (ffffffff8125b655)
Location: arch/x86/include/asm/smap.h:49
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
In fs/select.c (ffffffff8125ceac)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_pselect6
```
```
In fs/namespace.c (ffffffff8126a73d)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff81290d12)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/signalfd.c (ffffffff81293539)
Location: arch/x86/include/asm/smap.h:49
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
In fs/aio.c (ffffffff81299618)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
```
In fs/compat.c (ffffffff812a66e3)
Location: arch/x86/include/asm/smap.h:49
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
In fs/compat_ioctl.c (ffffffff812a72ad)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/binfmt_elf.c (ffffffff8136d796)
Location: arch/x86/include/asm/smap.h:49
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
In fs/compat_binfmt_elf.c (ffffffff8136dd39)
Location: arch/x86/include/asm/smap.h:49
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
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In ipc/compat.c (ffffffff8136e9ee)
Location: arch/x86/include/asm/smap.h:49
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
In ipc/compat_mq.c (ffffffff81379c3b)
Location: arch/x86/include/asm/smap.h:49
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
In block/compat_ioctl.c (ffffffff81445b19)
Location: arch/x86/include/asm/smap.h:49
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
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff8145b98d)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:copy_user_handle_tail
  - arch/x86/lib/usercopy_64.c:copy_user_handle_tail
  - arch/x86/lib/usercopy_64.c:copy_user_handle_tail
  - arch/x86/lib/usercopy_64.c:__clear_user
```
```
In lib/bitmap.c (ffffffff8145db1e)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (ffffffff814626b5)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
```
```
In lib/strncpy_from_user.c (ffffffff81480603)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff814807fc)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - lib/strnlen_user.c:strlen_user
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff814af418)
Location: arch/x86/include/asm/smap.h:49
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
In drivers/xen/xenbus/xenbus_client.c (ffffffff81549750)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8178588f)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815526a3)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8156c932)
Location: arch/x86/include/asm/smap.h:49
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
In drivers/tty/vt/selection.c (ffffffff8156e5e5)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/selection.c:set_selection
```
```
In drivers/tty/vt/consolemap.c (ffffffff81573466)
Location: arch/x86/include/asm/smap.h:49
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
In drivers/tty/vt/vt.c (ffffffff81577be6)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8157c996)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/char/mem.c (ffffffff8158ff5c)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81630578)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff8164f985)
Location: arch/x86/include/asm/smap.h:49
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
In drivers/usb/core/devio.c (ffffffff816aba5e)
Location: arch/x86/include/asm/smap.h:49
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
In net/socket.c (ffffffff8179344d)
Location: arch/x86/include/asm/smap.h:49
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
In net/compat.c (ffffffff817db05d)
Location: arch/x86/include/asm/smap.h:49
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
In arch/x86/lib/csum-wrappers_64.c (ffffffff818c60fa)
Location: arch/x86/include/asm/smap.h:49
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
In arch/x86/entry/common.c (ffffffff81003b6a)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
```
```
In arch/x86/events/core.c (ffffffff810076e4)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/xen/multicalls.c (ffffffff81019ecb)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/xen/setup.c (ffffffff820a4213)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101ce3d)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101df31)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81020525)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff810297a3)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In arch/x86/kernel/signal.c (ffffffff8102bf57)
Location: arch/x86/include/asm/smap.h:49
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
In arch/x86/kernel/signal_compat.c (ffffffff8102c1e2)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:copy_siginfo_from_user32
  - arch/x86/kernel/signal_compat.c:__copy_siginfo_to_user32
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81037dd5)
Location: arch/x86/include/asm/smap.h:49
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
In arch/x86/kernel/fpu/xstate.c (ffffffff81038e8a)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves
```
```
In arch/x86/kernel/ptrace.c (ffffffff810399f6)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8103b1a9)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103bf51)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff81078d5e)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8107b409)
Location: arch/x86/include/asm/smap.h:49
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
In arch/x86/ia32/ia32_signal.c (ffffffff8107c1c0)
Location: arch/x86/include/asm/smap.h:49
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
In kernel/exit.c (ffffffff8108870a)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - kernel/exit.c:C_SYSC_waitid
  - kernel/exit.c:C_SYSC_waitid
  - kernel/exit.c:SYSC_waitid
  - kernel/exit.c:SYSC_waitid
```
```
In kernel/ptrace.c (ffffffff81091526)
Location: arch/x86/include/asm/smap.h:49
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
In kernel/signal.c (ffffffff810969a8)
Location: arch/x86/include/asm/smap.h:49
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
In kernel/sys.c (ffffffff81097cd4)
Location: arch/x86/include/asm/smap.h:49
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
In kernel/futex.c (ffffffff8110fb80)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff8112127d)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
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
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff81183006)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/uprobes.c (ffffffff811b2280)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/maccess.c (ffffffff811be138)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In fs/read_write.c (ffffffff81252703)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/readdir.c (ffffffff81267f1c)
Location: arch/x86/include/asm/smap.h:49
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
In fs/select.c (ffffffff8126a8f2)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - fs/select.c:compat_SyS_pselect6
  - fs/select.c:compat_SyS_pselect6
  - fs/select.c:do_sys_poll
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_pselect6
```
```
In fs/namespace.c (ffffffff81277edc)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff8129db98)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/signalfd.c (ffffffff812a07c9)
Location: arch/x86/include/asm/smap.h:49
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
In fs/aio.c (ffffffff812a72c8)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
```
In fs/binfmt_elf.c (ffffffff812b74e7)
Location: arch/x86/include/asm/smap.h:49
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
In fs/compat_binfmt_elf.c (ffffffff812ba527)
Location: arch/x86/include/asm/smap.h:49
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
In ipc/compat.c (ffffffff81381f6e)
Location: arch/x86/include/asm/smap.h:49
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
In lib/bitmap.c (ffffffff81462a6e)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (ffffffff81465526)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
```
```
In lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In lib/strncpy_from_user.c (ffffffff814898b8)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff814899bf)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff814b9acb)
Location: arch/x86/include/asm/smap.h:49
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
In drivers/xen/xenbus/xenbus_client.c (ffffffff8155d62f)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81560dba)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81566e73)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81581080)
Location: arch/x86/include/asm/smap.h:49
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
In drivers/tty/vt/selection.c (ffffffff81582b65)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/selection.c:set_selection
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81590a5a)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/char/mem.c (ffffffff815a4022)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff816452fb)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff81664414)
Location: arch/x86/include/asm/smap.h:49
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
In net/socket.c (ffffffff817b18a6)
Location: arch/x86/include/asm/smap.h:49
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
In net/compat.c (ffffffff817fa393)
Location: arch/x86/include/asm/smap.h:49
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
In arch/x86/lib/csum-wrappers_64.c (ffffffff818fbcc1)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff818fd76c)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:copy_user_handle_tail
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
In arch/x86/entry/common.c (ffffffff81003d1f)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
```
```
In arch/x86/events/core.c (ffffffff81007b27)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/xen/multicalls.c (ffffffff8101a75e)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/xen/setup.c (ffffffff826aa8f4)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101daf7)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101ec38)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102120b)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff810299c5)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In arch/x86/kernel/signal.c (ffffffff8102cc78)
Location: arch/x86/include/asm/smap.h:49
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
In arch/x86/kernel/signal_compat.c (ffffffff8102cf55)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:copy_siginfo_from_user32
  - arch/x86/kernel/signal_compat.c:__copy_siginfo_to_user32
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a088)
Location: arch/x86/include/asm/smap.h:49
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b42e)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103c3f9)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8103dbd9)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103eb4b)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff8107f0b1)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff81081b09)
Location: arch/x86/include/asm/smap.h:49
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
In arch/x86/ia32/ia32_signal.c (ffffffff810828c0)
Location: arch/x86/include/asm/smap.h:49
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
In kernel/exit.c (ffffffff8108f48b)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - kernel/exit.c:C_SYSC_waitid
  - kernel/exit.c:C_SYSC_waitid
  - kernel/exit.c:SYSC_waitid
  - kernel/exit.c:SYSC_waitid
```
```
In kernel/ptrace.c (ffffffff810983a9)
Location: arch/x86/include/asm/smap.h:49
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
In kernel/signal.c (ffffffff8109d73b)
Location: arch/x86/include/asm/smap.h:49
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
In kernel/sys.c (ffffffff8109e9c4)
Location: arch/x86/include/asm/smap.h:49
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
In kernel/futex.c (ffffffff8111ae73)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff8112c8ed)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff81190c6e)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/uprobes.c (ffffffff811c5e93)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/maccess.c (ffffffff811d2e00)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In fs/read_write.c (ffffffff81274554)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/readdir.c (ffffffff8128a7cc)
Location: arch/x86/include/asm/smap.h:49
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
In fs/select.c (ffffffff8128d195)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - fs/select.c:compat_SyS_pselect6
  - fs/select.c:compat_SyS_pselect6
  - fs/select.c:do_sys_poll
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_pselect6
```
```
In fs/namespace.c (ffffffff8129a91f)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff812c1cc8)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/signalfd.c (ffffffff812c3ba1)
Location: arch/x86/include/asm/smap.h:49
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
In fs/aio.c (ffffffff812ca65b)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
```
In fs/binfmt_elf.c (ffffffff812dad93)
Location: arch/x86/include/asm/smap.h:49
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
In fs/compat_binfmt_elf.c (ffffffff812dde08)
Location: arch/x86/include/asm/smap.h:49
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
In lib/bitmap.c (ffffffff8148e966)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (ffffffff814938ed)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
```
```
In lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In lib/strncpy_from_user.c (ffffffff814c5a08)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff814c5b0f)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff814f9eba)
Location: arch/x86/include/asm/smap.h:49
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
In drivers/xen/xenbus/xenbus_client.c (ffffffff815c1942)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815c509d)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815cb02a)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815f573d)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/char/mem.c (ffffffff8160aa45)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff816ae28b)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff816cda7a)
Location: arch/x86/include/asm/smap.h:49
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
In net/socket.c (ffffffff81829a46)
Location: arch/x86/include/asm/smap.h:49
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
In net/compat.c (ffffffff81877ce4)
Location: arch/x86/include/asm/smap.h:49
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
In arch/x86/lib/csum-wrappers_64.c (ffffffff81982b11)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff8198525f)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:copy_user_handle_tail
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
In arch/x86/entry/common.c (ffffffff810044cf)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
```
```
In arch/x86/events/core.c (ffffffff81008133)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/xen/multicalls.c (ffffffff8101b26b)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/xen/setup.c (ffffffff826d3a5b)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk
```
```
In arch/x86/xen/suspend_pv.c (ffffffff8101e55a)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
  - arch/x86/xen/suspend_pv.c:xen_pv_pre_suspend
```
```
In arch/x86/xen/p2m.c (ffffffff8101f6d8)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81021ceb)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a40c)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In arch/x86/kernel/signal.c (ffffffff8102de78)
Location: arch/x86/include/asm/smap.h:49
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
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103b5a0)
Location: arch/x86/include/asm/smap.h:49
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8103c8d9)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103d8fb)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8103f181)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81040119)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff81081c11)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff81084e59)
Location: arch/x86/include/asm/smap.h:49
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
In arch/x86/ia32/ia32_signal.c (ffffffff81085f80)
Location: arch/x86/include/asm/smap.h:49
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
In kernel/exit.c (ffffffff81092fb6)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff8109bbe7)
Location: arch/x86/include/asm/smap.h:49
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
In kernel/signal.c (ffffffff810a270b)
Location: arch/x86/include/asm/smap.h:49
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
In kernel/sys.c (ffffffff810a42a1)
Location: arch/x86/include/asm/smap.h:49
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
In kernel/futex.c (ffffffff81127c53)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff8113afb0)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff811a618e)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/events/uprobes.c (ffffffff811e640f)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/maccess.c (ffffffff811f4184)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In fs/read_write.c (ffffffff8129b3c6)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/readdir.c (ffffffff812b13a6)
Location: arch/x86/include/asm/smap.h:49
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
In fs/select.c (ffffffff812b34ea)
Location: arch/x86/include/asm/smap.h:49
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
In fs/namespace.c (ffffffff812c09e3)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff812eaec0)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/binfmt_elf.c (ffffffff81303bc5)
Location: arch/x86/include/asm/smap.h:49
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
In fs/compat_binfmt_elf.c (ffffffff813072bf)
Location: arch/x86/include/asm/smap.h:49
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
In lib/bitmap.c (ffffffff814c3746)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (ffffffff814c607e)
Location: arch/x86/include/asm/smap.h:49
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
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In lib/strncpy_from_user.c (ffffffff814f68e5)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff814f6a02)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff8152a988)
Location: arch/x86/include/asm/smap.h:49
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
In drivers/xen/xenbus/xenbus_client.c (ffffffff815f99d2)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815fd70e)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:mfn_to_pfn
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81603887)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162e4dd)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init
```
```
In drivers/char/mem.c (ffffffff8164437b)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff816ea597)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff8170a2ae)
Location: arch/x86/include/asm/smap.h:49
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
In net/socket.c (ffffffff81873ca3)
Location: arch/x86/include/asm/smap.h:49
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
In net/compat.c (ffffffff818c98c4)
Location: arch/x86/include/asm/smap.h:49
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
In arch/x86/lib/csum-wrappers_64.c (ffffffff819df02a)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff819e174f)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:copy_user_handle_tail
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
In arch/x86/entry/common.c (ffffffff810044ff)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
```
```
In arch/x86/events/core.c (ffffffff81008013)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal.c (ffffffff8102f0b8)
Location: arch/x86/include/asm/smap.h:49
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
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103cac5)
Location: arch/x86/include/asm/smap.h:49
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8103ddf9)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103ee8b)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff81040774)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810416d9)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/mm/mpx.c (ffffffff81088821)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108bb2b)
Location: arch/x86/include/asm/smap.h:49
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
In arch/x86/ia32/ia32_signal.c (ffffffff8108cd10)
Location: arch/x86/include/asm/smap.h:49
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
In kernel/exit.c (ffffffff8109b26f)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810a3df1)
Location: arch/x86/include/asm/smap.h:49
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
In kernel/signal.c (ffffffff810ab2db)
Location: arch/x86/include/asm/smap.h:49
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
In kernel/sys.c (ffffffff810ad071)
Location: arch/x86/include/asm/smap.h:49
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
In kernel/futex.c (ffffffff81133333)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff8114681e)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff811f6f5f)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
```
In mm/maccess.c (ffffffff81206514)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In fs/read_write.c (ffffffff812b02c6)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/readdir.c (ffffffff812c65c7)
Location: arch/x86/include/asm/smap.h:49
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
In fs/select.c (ffffffff812c863a)
Location: arch/x86/include/asm/smap.h:49
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
In fs/namespace.c (ffffffff812d5c33)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff812ff8ec)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/binfmt_elf.c (ffffffff813192e7)
Location: arch/x86/include/asm/smap.h:49
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
In fs/compat_binfmt_elf.c (ffffffff8131ca9f)
Location: arch/x86/include/asm/smap.h:49
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
In lib/bitmap.c (ffffffff814d7b76)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (ffffffff814da83e)
Location: arch/x86/include/asm/smap.h:49
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
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In lib/strncpy_from_user.c (ffffffff8150ad15)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8150ae42)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff81540808)
Location: arch/x86/include/asm/smap.h:49
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
In drivers/char/mem.c (ffffffff8166265b)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff8170e053)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff8172c734)
Location: arch/x86/include/asm/smap.h:49
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
```
```
In net/socket.c (ffffffff81892c68)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff818f478e)
Location: arch/x86/include/asm/smap.h:49
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
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a19f5f)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:49
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a1c705)
Location: arch/x86/include/asm/smap.h:49
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:copy_user_handle_tail
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
In arch/x86/entry/common.c (ffffffff81004721)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
```
```
In arch/x86/events/core.c (ffffffff8100830d)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user32
  - arch/x86/events/core.c:perf_callchain_user32
```
```
In arch/x86/kernel/signal.c (ffffffff81030e8a)
Location: arch/x86/include/asm/smap.h:44
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
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f110)
Location: arch/x86/include/asm/smap.h:44
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8104065f)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104153c)
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff81042e24)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81043bd9)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/mpx.c (ffffffff8108ca6f)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108f92c)
Location: arch/x86/include/asm/smap.h:44
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
In arch/x86/ia32/ia32_signal.c (ffffffff81090bed)
Location: arch/x86/include/asm/smap.h:44
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
In kernel/exit.c (ffffffff8109f8cf)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810a8b15)
Location: arch/x86/include/asm/smap.h:44
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
In kernel/signal.c (ffffffff810b07cb)
Location: arch/x86/include/asm/smap.h:44
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
In kernel/sys.c (ffffffff810b28b1)
Location: arch/x86/include/asm/smap.h:44
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
In kernel/futex.c (ffffffff8113e3d3)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff8115195e)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8120f0db)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/maccess.c (ffffffff8121d954)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In fs/read_write.c (ffffffff812ccc1d)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/readdir.c (ffffffff812e3087)
Location: arch/x86/include/asm/smap.h:44
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
In fs/select.c (ffffffff812e5106)
Location: arch/x86/include/asm/smap.h:44
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
In fs/namespace.c (ffffffff812f4416)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff81320a91)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/binfmt_elf.c (ffffffff81340c13)
Location: arch/x86/include/asm/smap.h:44
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
In fs/compat_binfmt_elf.c (ffffffff81344322)
Location: arch/x86/include/asm/smap.h:44
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
In lib/bitmap.c (ffffffff81503e51)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (ffffffff815061ae)
Location: arch/x86/include/asm/smap.h:44
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
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In lib/strncpy_from_user.c (ffffffff8153944c)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff815395af)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff815700f7)
Location: arch/x86/include/asm/smap.h:44
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
In drivers/char/mem.c (ffffffff81698208)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff817498d1)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff81767fcb)
Location: arch/x86/include/asm/smap.h:44
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
```
```
In net/socket.c (ffffffff818dcf4a)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff819542a4)
Location: arch/x86/include/asm/smap.h:44
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
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a89c39)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a8c16e)
Location: arch/x86/include/asm/smap.h:44
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
In arch/x86/entry/common.c (ffffffff81004781)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
```
```
In arch/x86/events/core.c (ffffffff81008524)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal.c (ffffffff8103174a)
Location: arch/x86/include/asm/smap.h:44
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
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f779)
Location: arch/x86/include/asm/smap.h:44
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
In arch/x86/kernel/fpu/xstate.c (ffffffff81040e2f)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/ptrace.c (ffffffff81041cc3)
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff81043587)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81044329)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/mpx.c (ffffffff8108d6cf)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff81090589)
Location: arch/x86/include/asm/smap.h:44
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
In arch/x86/ia32/ia32_signal.c (ffffffff810918ed)
Location: arch/x86/include/asm/smap.h:44
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
In kernel/exit.c (ffffffff810a5f4f)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810af135)
Location: arch/x86/include/asm/smap.h:44
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
In kernel/signal.c (ffffffff810b72d9)
Location: arch/x86/include/asm/smap.h:44
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
In kernel/sys.c (ffffffff810b8f7f)
Location: arch/x86/include/asm/smap.h:44
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
In kernel/futex.c (ffffffff81149f63)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff8115d5ae)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff8121c3c3)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/maccess.c (ffffffff8122b3f4)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In fs/read_write.c (ffffffff812de63d)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/readdir.c (ffffffff812f3df5)
Location: arch/x86/include/asm/smap.h:44
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
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812f6b26)
Location: arch/x86/include/asm/smap.h:44
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
In fs/namespace.c (ffffffff81305fc6)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff8133383f)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/binfmt_elf.c (ffffffff81359112)
Location: arch/x86/include/asm/smap.h:44
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
In fs/compat_binfmt_elf.c (ffffffff8135c689)
Location: arch/x86/include/asm/smap.h:44
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
In lib/bitmap.c (ffffffff81521dee)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (ffffffff815241de)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
```
```
In lib/usercopy.c (ffffffff8152c214)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff8155a25e)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8155a3cb)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff81591191)
Location: arch/x86/include/asm/smap.h:44
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
In drivers/char/mem.c (ffffffff816bae18)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff8176da01)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff8178bfbb)
Location: arch/x86/include/asm/smap.h:44
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
```
```
In net/socket.c (ffffffff8190dc4c)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff8198a7c4)
Location: arch/x86/include/asm/smap.h:44
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
In arch/x86/lib/csum-wrappers_64.c (ffffffff81ac0f10)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81ac342e)
Location: arch/x86/include/asm/smap.h:44
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
In arch/x86/entry/common.c (ffffffff81bbc7d8)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
```
```
In arch/x86/events/core.c (ffffffff810095bb)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user32
  - arch/x86/events/core.c:perf_callchain_user32
```
```
In arch/x86/kernel/signal.c (ffffffff81033f94)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff8103a450)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042aa9)
Location: arch/x86/include/asm/smap.h:44
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
In arch/x86/kernel/ptrace.c (ffffffff81044d9d)
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81047d62)
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8109717b)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
```
```
In kernel/exit.c (ffffffff810adb01)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810b6df5)
Location: arch/x86/include/asm/smap.h:44
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
In kernel/signal.c (ffffffff810bee2b)
Location: arch/x86/include/asm/smap.h:44
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
In kernel/futex.c (ffffffff8115a9e8)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff8116dfee)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/events/uprobes.c (ffffffff81246ed8)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/events/uprobes.c:is_trap_at_addr
```
```
In fs/read_write.c (ffffffff813153a4)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/readdir.c (ffffffff8132c6fc)
Location: arch/x86/include/asm/smap.h:44
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
In fs/select.c (ffffffff8132eae1)
Location: arch/x86/include/asm/smap.h:44
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
In fs/eventpoll.c (ffffffff8136dabd)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/io_uring.c (ffffffff8137b7b5)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - fs/io_uring.c:__io_compat_recvmsg_copy_hdr
  - fs/io_uring.c:io_compat_import
```
```
In lib/iov_iter.c (ffffffff81586e5e)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
```
```
In lib/usercopy.c (ffffffff8158fae4)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff815e3b87)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff815e3cf1)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff815fd31c)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In arch/x86/lib/usercopy_64.c (ffffffff815ff9a0)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__clear_user
```
```
In drivers/pci/proc.c (ffffffff8163f0bc)
Location: arch/x86/include/asm/smap.h:44
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
In drivers/char/mem.c (ffffffff8176ef4a)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In net/socket.c (ffffffff819e21cc)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
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
In arch/x86/kernel/signal.c (ffffffff81033f5a)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff8103ac54)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810428a5)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_user_to_fpregs_zeroing
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810963d6)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In kernel/exit.c (ffffffff810a917a)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/futex.c (ffffffff81156a0e)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff8116a5f9)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In fs/readdir.c (ffffffff81337d17)
Location: arch/x86/include/asm/smap.h:44
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
In fs/select.c (ffffffff8133aa03)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
```
```
In lib/iov_iter.c (ffffffff815a4175)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_compat_iovec_from_user
```
```
In lib/usercopy.c (ffffffff815ac633)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff81608055)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8160821c)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In arch/x86/lib/copy_mc.c (ffffffff8162178b)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81622009)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In arch/x86/lib/usercopy_64.c (ffffffff816248d0)
Location: arch/x86/include/asm/smap.h:44
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
In arch/x86/kernel/signal.c (ffffffff81035a3c)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff8103c653)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81044288)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_user_to_fpregs_zeroing
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff810694fd)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81096cc1)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In kernel/exit.c (ffffffff810aa1e9)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/futex.c (ffffffff81157e3b)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff8116b25b)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In kernel/rseq.c (ffffffff8125adf9)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In fs/readdir.c (ffffffff8133e477)
Location: arch/x86/include/asm/smap.h:41
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
In fs/select.c (ffffffff813408d0)
Location: arch/x86/include/asm/smap.h:41
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
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In lib/iov_iter.c (ffffffff815ab182)
Location: arch/x86/include/asm/smap.h:41
Inline: True
```
```
In lib/usercopy.c (ffffffff815b72db)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff815ead10)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff815eae57)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In arch/x86/lib/copy_mc.c (ffffffff8160508b)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81605908)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In arch/x86/lib/usercopy_64.c (ffffffff816082a0)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__clear_user
```
```
In net/core/scm.c (ffffffff819dc600)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - net/core/scm.c:put_cmsg
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
In arch/x86/kernel/signal.c (ffffffff8103ad16)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff81042153)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104a61b)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81073bad)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810a6c59)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In kernel/exit.c (ffffffff810bbd29)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/futex.c (ffffffff8117ccbb)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff81190e5b)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In kernel/rseq.c (ffffffff81296bee)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In fs/readdir.c (ffffffff8138be07)
Location: arch/x86/include/asm/smap.h:41
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
In fs/select.c (ffffffff8138e2a0)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - fs/select.c:__x64_compat_sys_pselect6_time32
  - fs/select.c:__x64_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x64_compat_sys_pselect6_time64
  - fs/select.c:__x64_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In lib/iov_iter.c (ffffffff81614a92)
Location: arch/x86/include/asm/smap.h:41
Inline: True
```
```
In lib/usercopy.c (ffffffff8161d90b)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff81657210)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81657358)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In arch/x86/lib/copy_mc.c (ffffffff81673978)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff816741f8)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81676ee0)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__clear_user
```
```
In net/core/scm.c (ffffffff81a8c840)
Location: arch/x86/include/asm/smap.h:41
Inline: True
Inline callers:
  - net/core/scm.c:put_cmsg
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
In arch/x86/kernel/signal.c (ffffffff81041fb3)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:__setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff81049e5f)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81054a58)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81082279)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810bbf49)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In kernel/exit.c (ffffffff810d286e)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/futex/core.c (ffffffff811b2d15)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cmpxchg_value_locked
```
```
In kernel/futex/waitwake.c (ffffffff811b67ef)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
```
```
In kernel/compat.c (ffffffff811c063e)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In kernel/rseq.c (ffffffff812eca89)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_update_cpu_id
  - kernel/rseq.c:rseq_update_cpu_id
```
```
In mm/gup.c (ffffffff81336db3)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - mm/gup.c:fault_in_readable
  - mm/gup.c:fault_in_writeable
```
```
In fs/readdir.c (ffffffff8140d386)
Location: arch/x86/include/asm/smap.h:30
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
In fs/select.c (ffffffff8140f593)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In lib/iov_iter.c (ffffffff816e1797)
Location: arch/x86/include/asm/smap.h:30
Inline: True
```
```
In lib/usercopy.c (ffffffff816eb486)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff8176ea4f)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8176ebb5)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In arch/x86/lib/copy_mc.c (ffffffff8178df58)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff8178e91a)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81791e90)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__clear_user
```
```
In net/core/scm.c (ffffffff81c02131)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - net/core/scm.c:put_cmsg
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
In arch/x86/kernel/signal_64.c (ffffffff8104be38)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/signal_64.c:x64_setup_rt_frame
  - arch/x86/kernel/signal_64.c:x64_setup_rt_frame
```
```
In arch/x86/kernel/ldt.c (ffffffff8105293b)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:read_default_ldt
  - arch/x86/kernel/ldt.c:read_ldt
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff81055041)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/signal_32.c (ffffffff81055f24)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810625ae)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81094cb9)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
```
```
In kernel/exit.c (ffffffff810f132e)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/signal.c (ffffffff81105d88)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/futex/core.c (ffffffff811f3be5)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cmpxchg_value_locked
```
```
In kernel/futex/waitwake.c (ffffffff811f793f)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
```
```
In kernel/compat.c (ffffffff81202a2e)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In kernel/rseq.c (ffffffff81357006)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In mm/gup.c (ffffffff813ae243)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - mm/gup.c:fault_in_readable
  - mm/gup.c:fault_in_writeable
```
```
In mm/mempolicy.c (ffffffff81414bcd)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - mm/mempolicy.c:copy_nodes_to_user
```
```
In fs/readdir.c (ffffffff81497e41)
Location: arch/x86/include/asm/smap.h:30
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
In fs/select.c (ffffffff8149a193)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814e0476)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e39ce)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
```
```
In fs/binfmt_elf.c (ffffffff81510f48)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:padzero
```
```
In fs/compat_binfmt_elf.c (ffffffff81513fed)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:padzero
```
```
In fs/proc/kcore.c (ffffffff81545cbd)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In security/keys/keyctl.c (ffffffff81654da9)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_capabilities
```
```
In security/keys/keyctl_pkey.c (ffffffff8165a641)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
```
```
In lib/iov_iter.c (ffffffff817d4f84)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
```
In lib/usercopy.c (ffffffff817dbb4d)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff8189e35f)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8189e4b3)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/char/mem.c (ffffffff81a921de)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_mem
```
```
In drivers/input/evdev.c (ffffffff81caf92e)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_get_mask
```
```
In drivers/md/dm-ioctl.c (ffffffff81d17f5a)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-ioctl.c:copy_params
```
```
In net/core/scm.c (ffffffff81db1766)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
```
```
In arch/x86/lib/copy_mc.c (ffffffff8204b788)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff8204c24a)
Location: arch/x86/include/asm/smap.h:30
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
In arch/x86/kernel/signal_64.c (ffffffff8104c675)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/signal_64.c:x64_setup_rt_frame
  - arch/x86/kernel/signal_64.c:x64_setup_rt_frame
```
```
In arch/x86/kernel/ldt.c (ffffffff81053a0d)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:read_default_ldt
  - arch/x86/kernel/ldt.c:read_ldt
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff81056247)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/signal_32.c (ffffffff81056ed6)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff810632fe)
Location: arch/x86/include/asm/smap.h:30
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106437f)
Location: arch/x86/include/asm/smap.h:30
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
In arch/x86/kernel/tls.c (ffffffff81068ec8)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81097b89)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
```
```
In kernel/exit.c (ffffffff810fd238)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/signal.c (ffffffff8111206b)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/futex/core.c (ffffffff8120836c)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cmpxchg_value_locked
```
```
In kernel/futex/waitwake.c (ffffffff8120c33a)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
```
```
In kernel/compat.c (ffffffff81217dec)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In kernel/trace/trace.c (ffffffff81282fd3)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/rseq.c (ffffffff81388144)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_update_cpu_node_id
  - kernel/rseq.c:rseq_update_cpu_node_id
```
```
In mm/maccess.c (ffffffff8139838c)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/gup.c (ffffffff813e2561)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - mm/gup.c:fault_in_readable
  - mm/gup.c:fault_in_writeable
```
```
In mm/memory.c (ffffffff813e9912)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - mm/memory.c:__wp_page_copy_user
  - mm/memory.c:__wp_page_copy_user
```
```
In mm/mempolicy.c (ffffffff81448182)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - mm/mempolicy.c:copy_nodes_to_user
```
```
In fs/readdir.c (ffffffff814ccd9e)
Location: arch/x86/include/asm/smap.h:30
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
In fs/select.c (ffffffff814cf249)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81516c7e)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151a315)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
```
```
In fs/binfmt_elf.c (ffffffff8154887e)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:padzero
```
```
In fs/compat_binfmt_elf.c (ffffffff8154ba4c)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:padzero
```
```
In security/keys/keyctl.c (ffffffff8168d5e3)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_capabilities
```
```
In security/keys/keyctl_pkey.c (ffffffff81692f52)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
```
```
In lib/iov_iter.c (ffffffff81810a37)
Location: arch/x86/include/asm/smap.h:30
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
In lib/usercopy.c (ffffffff8181aed8)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In lib/strncpy_from_user.c (ffffffff818e0927)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff818e0a8c)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/char/mem.c (ffffffff81adda88)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_mem
```
```
In drivers/input/evdev.c (ffffffff81d16eba)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_get_mask
```
```
In drivers/md/dm-ioctl.c (ffffffff81d810a0)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-ioctl.c:copy_params
```
```
In net/core/scm.c (ffffffff81e21c41)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
```
```
In arch/x86/lib/copy_mc.c (ffffffff820ca068)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff820cab46)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In arch/x86/lib/insn-eval.c (ffffffff820ccb9f)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
```
```
In arch/x86/lib/usercopy.c (ffffffff820ce167)
Location: arch/x86/include/asm/smap.h:30
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff820ce402)
Location: arch/x86/include/asm/smap.h:30
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
In arch/x86/kernel/signal_64.c (ffffffff810538f5)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/signal_64.c:x64_setup_rt_frame
  - arch/x86/kernel/signal_64.c:x64_setup_rt_frame
```
```
In arch/x86/kernel/ldt.c (ffffffff8105ac2d)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:read_default_ldt
  - arch/x86/kernel/ldt.c:read_ldt
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff8105d497)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/signal_32.c (ffffffff8105e126)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8106a600)
Location: arch/x86/include/asm/smap.h:30
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106b855)
Location: arch/x86/include/asm/smap.h:30
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
In arch/x86/kernel/tls.c (ffffffff8107033e)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_set
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109f0f9)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
```
```
In kernel/exit.c (ffffffff81107778)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/signal.c (ffffffff8111ba5b)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/futex/core.c (ffffffff8121f1fc)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cmpxchg_value_locked
```
```
In kernel/futex/waitwake.c (ffffffff8122363a)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
  - kernel/futex/waitwake.c:futex_atomic_op_inuser
```
```
In kernel/compat.c (ffffffff8122f9ac)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
```
```
In kernel/trace/trace.c (ffffffff8129e362)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
```
```
In kernel/rseq.c (ffffffff813b1ba4)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_update_cpu_node_id
  - kernel/rseq.c:rseq_update_cpu_node_id
```
```
In mm/maccess.c (ffffffff813c21ac)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/gup.c (ffffffff8140cd91)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - mm/gup.c:fault_in_readable
  - mm/gup.c:fault_in_writeable
```
```
In mm/memory.c (ffffffff81414908)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - mm/memory.c:__wp_page_copy_user
  - mm/memory.c:__wp_page_copy_user
```
```
In mm/mempolicy.c (ffffffff81481b82)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - mm/mempolicy.c:copy_nodes_to_user
```
```
In fs/readdir.c (ffffffff814ff38e)
Location: arch/x86/include/asm/smap.h:30
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
In fs/select.c (ffffffff81501b89)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154b06e)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154e6e5)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
```
```
In fs/binfmt_elf.c (ffffffff8157cf07)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_load
```
```
In fs/compat_binfmt_elf.c (ffffffff8157ff42)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_load
```
```
In security/keys/keyctl.c (ffffffff816c9b33)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_capabilities
```
```
In security/keys/keyctl_pkey.c (ffffffff816cf522)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
```
```
In io_uring/waitid.c (ffffffff8182a659)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - io_uring/waitid.c:io_waitid_copy_si
```
```
In lib/iov_iter.c (ffffffff81856db7)
Location: arch/x86/include/asm/smap.h:30
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
In lib/usercopy.c (ffffffff81860239)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In lib/strncpy_from_user.c (ffffffff81927467)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff819275f3)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/char/mem.c (ffffffff81b30e78)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_mem
```
```
In drivers/gpu/drm/drm_ioc32.c (ffffffff81cb9470)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_ioc32.c:compat_drm_getstats
```
```
In drivers/input/evdev.c (ffffffff81dccb6a)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_get_mask
```
```
In drivers/md/dm-ioctl.c (ffffffff81e38744)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-ioctl.c:copy_params
```
```
In net/core/scm.c (ffffffff81edfb61)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
```
```
In arch/x86/lib/copy_mc.c (ffffffff821a49e8)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff821a5386)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In arch/x86/lib/insn-eval.c (ffffffff821a73cf)
Location: arch/x86/include/asm/smap.h:30
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic
```
```
In arch/x86/lib/usercopy.c (ffffffff821a8997)
Location: arch/x86/include/asm/smap.h:30
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff821a8c12)
Location: arch/x86/include/asm/smap.h:30
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
In arch/x86/entry/common.c (ffffffff81004781)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
```
```
In arch/x86/events/core.c (ffffffff81008524)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal.c (ffffffff810318aa)
Location: arch/x86/include/asm/smap.h:44
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
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f8f9)
Location: arch/x86/include/asm/smap.h:44
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
In arch/x86/kernel/fpu/xstate.c (ffffffff81040faf)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/ptrace.c (ffffffff81041e43)
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff81043707)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810444a9)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/mpx.c (ffffffff8108c68f)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108f549)
Location: arch/x86/include/asm/smap.h:44
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
In arch/x86/ia32/ia32_signal.c (ffffffff810908ad)
Location: arch/x86/include/asm/smap.h:44
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
In kernel/exit.c (ffffffff8109f86f)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810a94a5)
Location: arch/x86/include/asm/smap.h:44
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
In kernel/signal.c (ffffffff810b1649)
Location: arch/x86/include/asm/smap.h:44
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
In kernel/sys.c (ffffffff810b32ef)
Location: arch/x86/include/asm/smap.h:44
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
In kernel/futex.c (ffffffff81142583)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff81155bce)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81214a13)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/maccess.c (ffffffff81223a44)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In fs/read_write.c (ffffffff812d6c1d)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/readdir.c (ffffffff812ec3d5)
Location: arch/x86/include/asm/smap.h:44
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
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812ef106)
Location: arch/x86/include/asm/smap.h:44
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
In fs/namespace.c (ffffffff812fe5a6)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff8132be1f)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/binfmt_elf.c (ffffffff813516f2)
Location: arch/x86/include/asm/smap.h:44
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
In fs/compat_binfmt_elf.c (ffffffff81354c69)
Location: arch/x86/include/asm/smap.h:44
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
In lib/bitmap.c (ffffffff8151a3ce)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (ffffffff8151c7be)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
```
```
In lib/usercopy.c (ffffffff815247f4)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff8155283e)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff815529ab)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff81585021)
Location: arch/x86/include/asm/smap.h:44
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
In drivers/char/mem.c (ffffffff81680878)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff817220f1)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff817406ab)
Location: arch/x86/include/asm/smap.h:44
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
```
```
In net/socket.c (ffffffff818adc4c)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff8192a634)
Location: arch/x86/include/asm/smap.h:44
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
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a5fd60)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a6227e)
Location: arch/x86/include/asm/smap.h:44
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
In arch/x86/entry/common.c (ffffffff81002dc6)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
```
```
In arch/x86/events/core.c (ffffffff81006d14)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal.c (ffffffff8102128a)
Location: arch/x86/include/asm/smap.h:44
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
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f0f9)
Location: arch/x86/include/asm/smap.h:44
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8103078f)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/ptrace.c (ffffffff81031503)
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff81032d27)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81033ac9)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/mpx.c (ffffffff8107b1bf)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8107e059)
Location: arch/x86/include/asm/smap.h:44
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
In arch/x86/ia32/ia32_signal.c (ffffffff8107f3bd)
Location: arch/x86/include/asm/smap.h:44
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
In kernel/exit.c (ffffffff8108e29f)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff81097e65)
Location: arch/x86/include/asm/smap.h:44
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
In kernel/signal.c (ffffffff8109ff69)
Location: arch/x86/include/asm/smap.h:44
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
In kernel/sys.c (ffffffff810a1c1f)
Location: arch/x86/include/asm/smap.h:44
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
In kernel/futex.c (ffffffff811358e3)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff81148eee)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81207783)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/maccess.c (ffffffff81216bf4)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In fs/read_write.c (ffffffff812c789d)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/readdir.c (ffffffff812dd005)
Location: arch/x86/include/asm/smap.h:44
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
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812dfd36)
Location: arch/x86/include/asm/smap.h:44
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
In fs/namespace.c (ffffffff812ef1c6)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff8131c57f)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/binfmt_elf.c (ffffffff813423d2)
Location: arch/x86/include/asm/smap.h:44
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
In fs/compat_binfmt_elf.c (ffffffff81345929)
Location: arch/x86/include/asm/smap.h:44
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
In lib/bitmap.c (ffffffff8150a6be)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (ffffffff8150caae)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
```
```
In lib/usercopy.c (ffffffff81514ad4)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff81542b1e)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81542c8b)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff81573df1)
Location: arch/x86/include/asm/smap.h:44
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
In drivers/char/mem.c (ffffffff8165e548)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff816fb521)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff8172233f)
Location: arch/x86/include/asm/smap.h:44
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
```
```
In net/socket.c (ffffffff81867b9c)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff818e43e4)
Location: arch/x86/include/asm/smap.h:44
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
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a1ce30)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81a1f2ee)
Location: arch/x86/include/asm/smap.h:44
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
In arch/x86/entry/common.c (ffffffff81004741)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
```
```
In arch/x86/events/core.c (ffffffff810084e4)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal.c (ffffffff8103170a)
Location: arch/x86/include/asm/smap.h:44
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
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f739)
Location: arch/x86/include/asm/smap.h:44
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
In arch/x86/kernel/fpu/xstate.c (ffffffff81040def)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/ptrace.c (ffffffff81041c83)
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff81043547)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810442e9)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/mpx.c (ffffffff8108c63f)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108f4f9)
Location: arch/x86/include/asm/smap.h:44
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
In arch/x86/ia32/ia32_signal.c (ffffffff8109085d)
Location: arch/x86/include/asm/smap.h:44
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
In kernel/exit.c (ffffffff8109f81f)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810a8a05)
Location: arch/x86/include/asm/smap.h:44
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
In kernel/signal.c (ffffffff810b0ba9)
Location: arch/x86/include/asm/smap.h:44
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
In kernel/sys.c (ffffffff810b284f)
Location: arch/x86/include/asm/smap.h:44
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
In kernel/futex.c (ffffffff81140433)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff8115399e)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff812127b3)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/maccess.c (ffffffff812217e4)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In fs/read_write.c (ffffffff812d4a2d)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/readdir.c (ffffffff812ea1e5)
Location: arch/x86/include/asm/smap.h:44
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
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812ecf16)
Location: arch/x86/include/asm/smap.h:44
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
In fs/namespace.c (ffffffff812fc396)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff813298ef)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/binfmt_elf.c (ffffffff8134f1c2)
Location: arch/x86/include/asm/smap.h:44
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
In fs/compat_binfmt_elf.c (ffffffff81352739)
Location: arch/x86/include/asm/smap.h:44
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
In lib/bitmap.c (ffffffff8151645e)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (ffffffff8151884e)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
```
```
In lib/usercopy.c (ffffffff81520884)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff8154e57e)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8154e6eb)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff81584ee1)
Location: arch/x86/include/asm/smap.h:44
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
In drivers/char/mem.c (ffffffff816aec58)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81760ec1)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff81780e3b)
Location: arch/x86/include/asm/smap.h:44
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
```
```
In net/socket.c (ffffffff818fec4c)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff8197b7c4)
Location: arch/x86/include/asm/smap.h:44
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
In arch/x86/lib/csum-wrappers_64.c (ffffffff81acc150)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81ace66e)
Location: arch/x86/include/asm/smap.h:44
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
In arch/x86/entry/common.c (ffffffff81004881)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
```
```
In arch/x86/events/core.c (ffffffff81008644)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/kernel/signal.c (ffffffff810325ba)
Location: arch/x86/include/asm/smap.h:44
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
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81040a29)
Location: arch/x86/include/asm/smap.h:44
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
In arch/x86/kernel/fpu/xstate.c (ffffffff810421cf)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
```
```
In arch/x86/kernel/ptrace.c (ffffffff81043063)
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff81044947)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810456e9)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_user
```
```
In arch/x86/mm/mpx.c (ffffffff8108e99f)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff810918d9)
Location: arch/x86/include/asm/smap.h:44
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
In arch/x86/ia32/ia32_signal.c (ffffffff81092c3d)
Location: arch/x86/include/asm/smap.h:44
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
In kernel/exit.c (ffffffff810a777f)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810b0b25)
Location: arch/x86/include/asm/smap.h:44
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
In kernel/signal.c (ffffffff810b8e79)
Location: arch/x86/include/asm/smap.h:44
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
In kernel/sys.c (ffffffff810bae4f)
Location: arch/x86/include/asm/smap.h:44
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
In kernel/futex.c (ffffffff8114cf63)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (ffffffff8116089e)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81221733)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In mm/maccess.c (ffffffff812309a4)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In fs/read_write.c (ffffffff812e588d)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/readdir.c (ffffffff812fb1d5)
Location: arch/x86/include/asm/smap.h:44
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
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff812fdf16)
Location: arch/x86/include/asm/smap.h:44
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
In fs/namespace.c (ffffffff8130d6f6)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/eventpoll.c (ffffffff8133b24f)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/binfmt_elf.c (ffffffff81362742)
Location: arch/x86/include/asm/smap.h:44
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
In fs/compat_binfmt_elf.c (ffffffff81365ef9)
Location: arch/x86/include/asm/smap.h:44
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
In lib/bitmap.c (ffffffff8152fbee)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (ffffffff8153200e)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
```
```
In lib/usercopy.c (ffffffff8153a204)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/strncpy_from_user.c (ffffffff815683ce)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8156853b)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (ffffffff8159f391)
Location: arch/x86/include/asm/smap.h:44
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
In drivers/char/mem.c (ffffffff816c91e8)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff8177c521)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff8179a903)
Location: arch/x86/include/asm/smap.h:44
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
```
```
In net/socket.c (ffffffff8191fcb4)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:move_addr_to_user
```
```
In net/compat.c (ffffffff8199dd14)
Location: arch/x86/include/asm/smap.h:44
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
In arch/x86/lib/csum-wrappers_64.c (ffffffff81ad8653)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
  - arch/x86/lib/csum-wrappers_64.c:csum_partial_copy_from_user
```
```
In arch/x86/lib/usercopy.c (0)
Location: arch/x86/include/asm/smap.h:44
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81adab7e)
Location: arch/x86/include/asm/smap.h:44
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__clear_user
```
</details>
</li>
</ul>

## Differences
