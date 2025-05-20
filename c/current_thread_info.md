# Function: <code>current_thread_info</code>

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
In arch/x86/entry/common.c (ffffffff8100319d)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - arch/x86/entry/common.c:syscall_trace_enter_phase2
  - arch/x86/entry/common.c:syscall_trace_enter_phase2
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81004206)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004696)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/core.c (ffffffff810076cd)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f6b6)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
```
```
In arch/x86/events/intel/lbr.c (ffffffff81011381)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/kernel/process_64.c (ffffffff8102d006)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:compat_start_thread
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/signal.c (ffffffff8102e285)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:restore_sigcontext
  - arch/x86/kernel/signal.c:setup_sigcontext
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
```
```
In arch/x86/kernel/signal_compat.c (ffffffff8102ee76)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:copy_siginfo_to_user32
  - arch/x86/kernel/signal_compat.c:copy_siginfo_to_user32
  - arch/x86/kernel/signal_compat.c:copy_siginfo_from_user32
```
```
In arch/x86/kernel/ioport.c (ffffffff81031974)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff81033f83)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
```
```
In arch/x86/kernel/process.c (ffffffff81038fa6)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:exit_thread
  - arch/x86/kernel/process.c:disable_TSC
  - arch/x86/kernel/process.c:get_tsc_mode
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/init.c (ffffffff81f698d3)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103acd5)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103cc7f)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103e6f7)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810500cf)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81f6f77e)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8105ed5d)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:setjmp_pre_handler
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/kgdb.c (ffffffff81061649)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
```
In arch/x86/kernel/uprobes.c (ffffffff81065636)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:default_post_xol_op
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
```
```
In arch/x86/mm/fault.c (ffffffff8106ac65)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
```
In arch/x86/mm/extable.c (ffffffff8106bfe3)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:fixup_exception
```
```
In arch/x86/mm/mmap.c (ffffffff8106f633)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_mmap_rnd
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
```
```
In arch/x86/mm/gup.c (ffffffff81071ad4)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:__get_user_pages_fast
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81072c31)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In arch/x86/mm/mpx.c (ffffffff81075023)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8107794e)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81077eb6)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_sigcontext
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff8107c57a)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/fork.c (ffffffff8107f437)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8108394c)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff81085902)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:irq_exit
```
```
In kernel/ptrace.c (ffffffff8108b174)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_regset
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
```
```
In kernel/signal.c (ffffffff8108d189)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:do_sigaltstack
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:compat_restore_altstack
  - kernel/signal.c:compat_restore_altstack
```
```
In kernel/sys.c (ffffffff81092d3c)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:SYSC_olduname
```
```
In kernel/sched/core.c (ffffffff818203e5)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:preempt_schedule_common
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:SyS_sched_setattr
  - kernel/sched/core.c:SyS_sched_getattr
```
```
In kernel/sched/fair.c (ffffffff810be381)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/sched/idle.c (ffffffff810c3ce5)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In kernel/locking/mutex.c (ffffffff810c9a95)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:mutex_optimistic_spin
```
```
In kernel/locking/osq_lock.c (ffffffff810ca34f)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810cbcc9)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_spin_on_owner
```
```
In kernel/power/user.c (ffffffff810d5e43)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/printk/printk.c (ffffffff810d9512)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:show_regs_print_info
```
```
In kernel/rcu/tree.c (ffffffff810e7263)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
```
```
In kernel/freezer.c (ffffffff810e9a9e)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff810fe6d4)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/futex.c (ffffffff810ffa7c)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:futex_wake_op
```
```
In kernel/module.c (0)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
```
```
In kernel/compat.c (ffffffff8110f796)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - kernel/compat.c:__compat_get_timespec
  - kernel/compat.c:__compat_put_timespec
  - kernel/compat.c:compat_put_timex
  - kernel/compat.c:compat_get_timex
  - kernel/compat.c:C_SYSC_clock_adjtime
  - kernel/compat.c:compat_nanosleep_restart
  - kernel/compat.c:compat_clock_nanosleep_restart
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_SyS_nanosleep
  - kernel/compat.c:compat_SyS_getitimer
  - kernel/compat.c:compat_SyS_setitimer
  - kernel/compat.c:compat_SyS_setitimer
  - kernel/compat.c:compat_SyS_sigpending
  - kernel/compat.c:compat_SyS_setrlimit
  - kernel/compat.c:compat_SyS_old_getrlimit
  - kernel/compat.c:compat_SyS_old_getrlimit
  - kernel/compat.c:compat_SyS_getrlimit
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:C_SYSC_wait4
  - kernel/compat.c:C_SYSC_waitid
  - kernel/compat.c:compat_SyS_timer_settime
  - kernel/compat.c:compat_SyS_timer_gettime
  - kernel/compat.c:compat_SyS_clock_settime
  - kernel/compat.c:compat_SyS_clock_gettime
  - kernel/compat.c:compat_SyS_clock_getres
  - kernel/compat.c:compat_SyS_clock_nanosleep
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_SyS_sched_rr_get_interval
```
```
In kernel/cpuset.c (ffffffff8111b635)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - kernel/cpuset.c:__cpuset_node_allowed
```
```
In kernel/pid_namespace.c (ffffffff8111fcf3)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff8112990b)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_seccomp
```
```
In kernel/seccomp.c (ffffffff8113b6e6)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8114a777)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_generic_entry_update
```
```
In kernel/trace/trace_syscalls.c (ffffffff81161c7c)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff81167481)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/bpf/syscall.c (ffffffff81173602)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/events/core.c (ffffffff811817f6)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff81187202)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
```
```
In mm/oom_kill.c (ffffffff81190a75)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:pagefault_out_of_memory
```
```
In mm/maccess.c (ffffffff81191506)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
```
```
In mm/page_alloc.c (ffffffff81192f46)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc_failed
  - mm/page_alloc.c:gfp_pfmemalloc_allowed
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/shmem.c (ffffffff811a87fd)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
```
```
In mm/compaction.c (ffffffff811b56a8)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:compact_zone
```
```
In mm/gup.c (ffffffff811bab42)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811bbd16)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - mm/memory.c:tlb_gather_mmu
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811c29da)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - mm/mincore.c:SyS_mincore
```
```
In mm/mlock.c (ffffffff811c3ca5)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - mm/mlock.c:SyS_mlockall
```
```
In mm/mmap.c (ffffffff811c4455)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
```
```
In mm/mremap.c (ffffffff811c9eea)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
```
```
In mm/mempolicy.c (ffffffff811e31df)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In mm/memcontrol.c (ffffffff811fb933)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In fs/read_write.c (ffffffff8120c2b4)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:vfs_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:rw_copy_check_uvector
```
```
In fs/exec.c (ffffffff81212672)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - fs/exec.c:kernel_read
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:setup_new_exec
```
```
In fs/ioctl.c (ffffffff8121ff76)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/readdir.c (ffffffff812206c7)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - fs/readdir.c:fillonedir
  - fs/readdir.c:SyS_getdents
  - fs/readdir.c:SyS_getdents64
```
```
In fs/select.c (ffffffff812211ef)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - fs/select.c:do_select
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_pselect6
  - fs/select.c:do_sys_poll
  - fs/select.c:SyS_ppoll
```
```
In fs/dcache.c (ffffffff812232ce)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - fs/dcache.c:select_collect
```
```
In fs/inode.c (ffffffff81228c2d)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - fs/inode.c:evict_inodes
```
```
In fs/namespace.c (ffffffff8122ea0c)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/fs-writeback.c (ffffffff8123b69d)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/splice.c (ffffffff8123da6c)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - fs/splice.c:kernel_write
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:vmsplice_to_pipe
```
```
In fs/block_dev.c (ffffffff81247fb3)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
```
```
In fs/eventpoll.c (ffffffff812568b3)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:compat_SyS_epoll_pwait
```
```
In fs/aio.c (ffffffff8125d47e)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
```
In fs/compat.c (ffffffff812630c6)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - fs/compat.c:get_compat_flock
  - fs/compat.c:put_compat_flock
  - fs/compat.c:get_compat_flock64
  - fs/compat.c:put_compat_flock64
  - fs/compat.c:put_compat_statfs
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:compat_get_fd_set
  - fs/compat.c:compat_fillonedir
  - fs/compat.c:compat_SyS_fcntl
  - fs/compat.c:compat_SyS_io_setup
  - fs/compat.c:compat_rw_copy_check_uvector
  - fs/compat.c:compat_rw_copy_check_uvector
  - fs/compat.c:compat_SyS_getdents
  - fs/compat.c:compat_SyS_getdents64
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_SyS_ppoll
```
```
In fs/compat_ioctl.c (ffffffff812659f3)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
```
```
In fs/binfmt_elf.c (ffffffff81321b7a)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - fs/binfmt_elf.c:set_brk
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffffffff81269a99)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:set_brk
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/coredump.c (ffffffff8126f494)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/dir.c (ffffffff81290a44)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/ioctl.c (ffffffff812a17af)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
```
In fs/ext4/mballoc.c (ffffffff812d57a4)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/jbd2/checkpoint.c (ffffffff812eccaa)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
```
```
In fs/fat/dir.c (ffffffff812f8a43)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
  - fs/fat/dir.c:fat_dir_ioctl
```
```
In fs/ecryptfs/inode.c (ffffffff81301619)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
```
```
In ipc/compat.c (ffffffff813232c2)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
```
```
In ipc/compat_mq.c (ffffffff8132e517)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - ipc/compat_mq.c:compat_SyS_mq_open
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
```
```
In security/keys/gc.c (ffffffff8132f00b)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/tomoyo/common.c (ffffffff8136b37a)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
```
In security/tomoyo/network.c (ffffffff81372382)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
```
```
In security/integrity/iint.c (ffffffff8139645f)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
```
```
In block/blk-core.c (ffffffff813bbc0a)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - block/blk-core.c:blk_poll
```
```
In block/compat_ioctl.c (ffffffff813e5406)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In arch/x86/lib/usercopy.c (ffffffff813f7935)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff813f79f5)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:copy_in_user
  - arch/x86/lib/usercopy_64.c:clear_user
  - arch/x86/lib/usercopy_64.c:copy_user_handle_tail
```
```
In lib/bitmap.c (ffffffff813f9923)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parse_user
  - lib/bitmap.c:bitmap_parselist_user
```
```
In lib/iov_iter.c (ffffffff813fb251)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - lib/iov_iter.c:import_iovec
  - lib/iov_iter.c:compat_import_iovec
  - lib/iov_iter.c:import_single_range
```
```
In lib/strncpy_from_user.c (ffffffff81419c1e)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81419d19)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
  - lib/strnlen_user.c:strlen_user
```
```
In drivers/pci/proc.c (ffffffff81441a14)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_write
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8146d1ce)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/idle/intel_idle.c (ffffffff8147942c)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle_freeze
```
```
In drivers/acpi/processor_idle.c (ffffffff814acc62)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_safe_halt
```
```
In drivers/xen/preempt.c (ffffffff814c7641)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
```
```
In drivers/tty/tty_io.c (ffffffff814e022c)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff814ef6b7)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
```
```
In drivers/tty/vt/selection.c (ffffffff814f1315)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:set_selection
```
```
In drivers/tty/vt/consolemap.c (ffffffff814f6025)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
```
```
In drivers/char/mem.c (ffffffff8151112c)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:write_port
```
```
In drivers/char/random.c (ffffffff8151355c)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - drivers/char/random.c:extract_entropy_user
```
```
In drivers/char/hw_random/core.c (ffffffff8151a613)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff81523732)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff815289bb)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff815a8f62)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff815c37c6)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_write
```
```
In drivers/usb/core/devio.c (ffffffff816197a6)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_do_ioctl
```
```
In drivers/usb/core/devices.c (ffffffff8161eae6)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
```
```
In drivers/input/input.c (ffffffff816683c6)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff8166a0b6)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
```
```
In drivers/input/evdev.c (ffffffff8166d944)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
```
```
In drivers/input/misc/uinput.c (ffffffff81671cf0)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
```
```
In drivers/cpuidle/driver.c (ffffffff816bc070)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
  - drivers/cpuidle/driver.c:poll_idle
```
```
In drivers/firmware/efi/efivars.c (ffffffff816d2256)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/socket.c (ffffffff816fb7dc)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - net/socket.c:kernel_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_recvmsg
  - net/socket.c:sock_poll
  - net/socket.c:copy_msghdr_from_user
```
```
In net/core/datagram.c (ffffffff8170ca3c)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/compat.c (ffffffff8173e5cd)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - net/compat.c:compat_sock_getsockopt
  - net/compat.c:compat_sock_setsockopt
  - net/compat.c:compat_sock_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:get_compat_msghdr
```
```
In net/sched/sch_generic.c (ffffffff8174161d)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/inetpeer.c (ffffffff81757da1)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
```
```
In net/ipv4/tcp.c (ffffffff81766e8c)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/ipmr.c (ffffffff817a7ff2)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/addrconf.c (ffffffff817d11e0)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
```
```
In net/packet/af_packet.c (ffffffff81807bd9)
Location: arch/x86/include/asm/thread_info.h:164
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81817b9f)
Location: arch/x86/include/asm/thread_info.h:164
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
In arch/x86/entry/common.c (ffffffff8100322d)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81004366)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:vdso_mremap
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004a5c)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/core.c (ffffffff810078a5)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f116)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
```
```
In arch/x86/events/intel/lbr.c (ffffffff81010c8d)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/kernel/process_64.c (ffffffff8102c006)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:compat_start_thread
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/signal.c (ffffffff8102d57f)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/signal_compat.c (ffffffff8102dec6)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:copy_siginfo_to_user32
```
```
In arch/x86/kernel/ioport.c (ffffffff81030a84)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff81033439)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/kernel/process.c (ffffffff8103802d)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:get_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
  - arch/x86/kernel/process.c:exit_thread
```
```
In arch/x86/kernel/fpu/init.c (ffffffff81f917e6)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103cbd0)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8105024c)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81052970)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8105f4c0)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/kgdb.c (ffffffff81061469)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
```
In arch/x86/kernel/uprobes.c (ffffffff81065db3)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:default_post_xol_op
```
```
In arch/x86/mm/mmap.c (ffffffff8106f419)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810734c4)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In arch/x86/mm/mpx.c (ffffffff81076d98)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810795d9)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff810815ed)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
```
```
In kernel/exit.c (ffffffff81086c58)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff81088a94)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
```
```
In kernel/ptrace.c (ffffffff8108e2c6)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff81093c11)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:ptrace_stop
```
```
In kernel/sys.c (ffffffff810965a2)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
```
```
In kernel/sched/core.c (ffffffff8189ab1f)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_common
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810c1b6c)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/sched/idle.c (ffffffff810c7aea)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In kernel/locking/mutex.c (ffffffff810ce4b2)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:mutex_optimistic_spin
```
```
In kernel/locking/osq_lock.c (ffffffff810cecdf)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/rwsem-xadd.c (ffffffff8189d8fa)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_spin_on_owner
```
```
In kernel/rcu/tree.c (ffffffff810ed4cc)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
```
```
In kernel/time/tick-sched.c (ffffffff81105a5d)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/compat.c (ffffffff81117902)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
```
```
In kernel/cpuset.c (ffffffff811255ee)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - kernel/cpuset.c:__cpuset_node_allowed
```
```
In kernel/pid_namespace.c (ffffffff81127c40)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff81131abb)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_seccomp
```
```
In kernel/seccomp.c (ffffffff81144487)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
```
```
In kernel/trace/trace.c (ffffffff811531d6)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_generic_entry_update
```
```
In kernel/trace/trace_syscalls.c (ffffffff8116c56e)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/events/core.c (ffffffff81195686)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff8119bdd5)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/oom_kill.c (ffffffff811a5c7e)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - mm/oom_kill.c:pagefault_out_of_memory
```
```
In mm/page_alloc.c (ffffffff811aa6ea)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc_failed
```
```
In mm/shmem.c (ffffffff811bf5e8)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (ffffffff811d211e)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff811d53b2)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811dcafc)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:tlb_gather_mmu
```
```
In mm/mlock.c (ffffffff811dfad3)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - mm/mlock.c:SyS_mlockall
```
```
In mm/mmap.c (ffffffff811e1f06)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
```
```
In mm/mremap.c (ffffffff811e6318)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
```
```
In mm/mempolicy.c (ffffffff81201c16)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In mm/khugepaged.c (ffffffff8121c696)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff8121f9f2)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In fs/exec.c (ffffffff8123b3f8)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - fs/exec.c:setup_new_exec
```
```
In fs/select.c (ffffffff8124a37a)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - fs/select.c:SyS_ppoll
  - fs/select.c:do_sys_poll
  - fs/select.c:SyS_pselect6
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff8124b0f1)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - fs/dcache.c:select_collect
```
```
In fs/inode.c (ffffffff81251326)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - fs/inode.c:evict_inodes
```
```
In fs/namespace.c (ffffffff81257218)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/fs-writeback.c (ffffffff81263517)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/eventpoll.c (ffffffff8127f62d)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
```
```
In fs/compat.c (ffffffff81291c97)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_ppoll
  - fs/compat.c:compat_SyS_pselect6
```
```
In fs/binfmt_elf.c (ffffffff812939e2)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
```
```
In fs/compat_binfmt_elf.c (ffffffff81296632)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/ext4/dir.c (ffffffff812be054)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/mballoc.c (ffffffff8130543f)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/jbd2/checkpoint.c (ffffffff8131ada6)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In security/keys/gc.c (ffffffff81363cd9)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In block/blk-core.c (ffffffff813ffa1a)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
```
```
In arch/x86/lib/usercopy.c (ffffffff8143e7e5)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff814c78f6)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff814fc4fd)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_safe_halt
```
```
In drivers/xen/preempt.c (ffffffff81517ed2)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
```
```
In drivers/tty/tty_io.c (ffffffff81531aa7)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
```
```
In drivers/char/random.c (ffffffff81567ef7)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hw_random/core.c (ffffffff8156d307)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff81576671)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8157be11)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
```
```
In drivers/input/input.c (ffffffff816c8376)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff816ca38c)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
```
```
In drivers/input/evdev.c (ffffffff816cdc9d)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
```
```
In drivers/input/misc/uinput.c (ffffffff816d244c)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/cpuidle/driver.c (ffffffff8171d980)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
  - drivers/cpuidle/driver.c:poll_idle
```
```
In drivers/firmware/efi/efivars.c (ffffffff8173622b)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/socket.c (ffffffff81763518)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff817742bb)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/core/dev.c (ffffffff817833c6)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - net/core/dev.c:sk_busy_loop
```
```
In net/sched/sch_generic.c (ffffffff817ae3dd)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/inetpeer.c (ffffffff817c404b)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
```
```
In net/ipv4/tcp.c (ffffffff817d338c)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81878c8c)
Location: arch/x86/include/asm/thread_info.h:163
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
```
</details>
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
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (c1501228)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
  - init/main.c:trace_initcall_start_cb
  - init/main.c:rest_init
  - init/main.c:start_kernel
```
```
In init/do_mounts.c (c150180c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In init/do_mounts_initrd.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In init/do_mounts_md.c (c15025b8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (c1502efc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - init/initramfs.c:do_copy
```
```
In init/calibrate.c (c0304048)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - init/calibrate.c:calibrate_delay
```
```
In arch/arm/vfp/vfpmodule.c (c0304f84)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/vfp/vfpmodule.c:vfp_restore_user_hwstate
  - arch/arm/vfp/vfpmodule.c:vfp_restore_user_hwstate
  - arch/arm/vfp/vfpmodule.c:vfp_preserve_user_clear_hwstate
  - arch/arm/vfp/vfpmodule.c:vfp_preserve_user_clear_hwstate
  - arch/arm/vfp/vfpmodule.c:vfp_sync_hwstate
  - arch/arm/vfp/vfpmodule.c:vfp_raise_sigfpe
```
```
In arch/arm/kernel/elf.c (c030ac20)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/kernel/elf.c:elf_set_personality
```
```
In arch/arm/kernel/process.c (c030b61c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/kernel/process.c:arch_setup_additional_pages
  - arch/arm/kernel/process.c:sigpage_mremap
  - arch/arm/kernel/process.c:get_wchan
  - arch/arm/kernel/process.c:dump_fpu
  - arch/arm/kernel/process.c:flush_thread
  - arch/arm/kernel/process.c:flush_thread
  - arch/arm/kernel/process.c:__show_regs
  - arch/arm/kernel/process.c:arch_cpu_idle
```
```
In arch/arm/kernel/ptrace.c (c030d060)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/kernel/ptrace.c:syscall_trace_exit
  - arch/arm/kernel/ptrace.c:syscall_trace_exit
  - arch/arm/kernel/ptrace.c:syscall_trace_exit
  - arch/arm/kernel/ptrace.c:syscall_trace_enter
  - arch/arm/kernel/ptrace.c:syscall_trace_enter
  - arch/arm/kernel/ptrace.c:syscall_trace_enter
  - arch/arm/kernel/ptrace.c:arch_ptrace
  - arch/arm/kernel/ptrace.c:arch_ptrace
  - arch/arm/kernel/ptrace.c:arch_ptrace
  - arch/arm/kernel/ptrace.c:arch_ptrace
  - arch/arm/kernel/ptrace.c:arch_ptrace
  - arch/arm/kernel/ptrace.c:arch_ptrace
  - arch/arm/kernel/ptrace.c:arch_ptrace
  - arch/arm/kernel/ptrace.c:arch_ptrace
  - arch/arm/kernel/ptrace.c:arch_ptrace
  - arch/arm/kernel/ptrace.c:arch_ptrace
  - arch/arm/kernel/ptrace.c:arch_ptrace
  - arch/arm/kernel/ptrace.c:arch_ptrace
  - arch/arm/kernel/ptrace.c:arch_ptrace
  - arch/arm/kernel/ptrace.c:vfp_set
  - arch/arm/kernel/ptrace.c:vfp_set
  - arch/arm/kernel/ptrace.c:vfp_get
  - arch/arm/kernel/ptrace.c:vfp_get
  - arch/arm/kernel/ptrace.c:fpa_set
  - arch/arm/kernel/ptrace.c:fpa_get
  - arch/arm/kernel/ptrace.c:gpr_set
  - arch/arm/kernel/ptrace.c:gpr_get
  - arch/arm/kernel/ptrace.c:ptrace_sethbpregs
  - arch/arm/kernel/ptrace.c:ptrace_sethbpregs
  - arch/arm/kernel/ptrace.c:ptrace_hbptriggered
  - arch/arm/kernel/ptrace.c:perf_trace_sys_exit
  - arch/arm/kernel/ptrace.c:trace_event_raw_event_sys_exit
```
```
In arch/arm/kernel/reboot.c (c030d200)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/kernel/reboot.c:__soft_restart
  - arch/arm/kernel/reboot.c:__soft_restart
```
```
In arch/arm/kernel/setup.c (c1503edc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/kernel/setup.c:setup_processor
  - arch/arm/kernel/setup.c:cpu_init
  - arch/arm/kernel/setup.c:cpu_init
```
```
In arch/arm/kernel/signal.c (c030ed18)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/kernel/signal.c:addr_limit_check_failed
  - arch/arm/kernel/signal.c:do_work_pending
  - arch/arm/kernel/signal.c:do_work_pending
  - arch/arm/kernel/signal.c:do_work_pending
  - arch/arm/kernel/signal.c:do_work_pending
  - arch/arm/kernel/signal.c:do_work_pending
  - arch/arm/kernel/signal.c:do_work_pending
  - arch/arm/kernel/signal.c:do_work_pending
  - arch/arm/kernel/signal.c:do_work_pending
  - arch/arm/kernel/signal.c:do_work_pending
  - arch/arm/kernel/signal.c:do_work_pending
  - arch/arm/kernel/signal.c:do_work_pending
  - arch/arm/kernel/signal.c:do_work_pending
  - arch/arm/kernel/signal.c:do_work_pending
  - arch/arm/kernel/signal.c:do_work_pending
  - arch/arm/kernel/signal.c:do_work_pending
  - arch/arm/kernel/signal.c:setup_return
  - arch/arm/kernel/signal.c:setup_return
  - arch/arm/kernel/signal.c:setup_return
  - arch/arm/kernel/signal.c:setup_return
  - arch/arm/kernel/signal.c:setup_return
  - arch/arm/kernel/signal.c:setup_return
  - arch/arm/kernel/signal.c:setup_return
  - arch/arm/kernel/signal.c:setup_return
  - arch/arm/kernel/signal.c:setup_return
  - arch/arm/kernel/signal.c:setup_return
  - arch/arm/kernel/signal.c:setup_return
  - arch/arm/kernel/signal.c:setup_return
  - arch/arm/kernel/signal.c:setup_return
  - arch/arm/kernel/signal.c:setup_return
  - arch/arm/kernel/signal.c:setup_return
  - arch/arm/kernel/signal.c:setup_return
  - arch/arm/kernel/signal.c:setup_return
  - arch/arm/kernel/signal.c:setup_sigframe
  - arch/arm/kernel/signal.c:setup_sigframe
  - arch/arm/kernel/signal.c:setup_sigframe
  - arch/arm/kernel/signal.c:setup_sigframe
  - arch/arm/kernel/signal.c:sys_rt_sigreturn
  - arch/arm/kernel/signal.c:sys_sigreturn
  - arch/arm/kernel/signal.c:restore_sigframe
  - arch/arm/kernel/signal.c:restore_sigframe
  - arch/arm/kernel/signal.c:restore_vfp_context
  - arch/arm/kernel/signal.c:preserve_vfp_context
  - arch/arm/kernel/signal.c:restore_iwmmxt_context
  - arch/arm/kernel/signal.c:restore_iwmmxt_context
  - arch/arm/kernel/signal.c:preserve_iwmmxt_context
```
```
In arch/arm/kernel/stacktrace.c (c030ef94)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/kernel/stacktrace.c:save_stack_trace
  - arch/arm/kernel/stacktrace.c:__save_stack_trace
```
```
In arch/arm/kernel/traps.c (c030fa20)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/kernel/traps.c:arm_syscall
  - arch/arm/kernel/traps.c:arm_syscall
  - arch/arm/kernel/traps.c:arm_syscall
  - arch/arm/kernel/traps.c:arm_syscall
  - arch/arm/kernel/traps.c:arm_syscall
  - arch/arm/kernel/traps.c:handle_fiq_as_nmi
  - arch/arm/kernel/traps.c:handle_fiq_as_nmi
  - arch/arm/kernel/traps.c:do_undefinstr
  - arch/arm/kernel/traps.c:do_undefinstr
  - arch/arm/kernel/traps.c:do_undefinstr
  - arch/arm/kernel/traps.c:do_undefinstr
  - arch/arm/kernel/traps.c:die
  - arch/arm/kernel/traps.c:die
  - arch/arm/kernel/traps.c:die
  - arch/arm/kernel/traps.c:die
  - arch/arm/kernel/traps.c:die
  - arch/arm/kernel/traps.c:die
  - arch/arm/kernel/traps.c:die
  - arch/arm/kernel/traps.c:dump_backtrace
  - arch/arm/kernel/traps.c:dump_backtrace
  - arch/arm/kernel/traps.c:dump_mem
  - arch/arm/kernel/traps.c:dump_mem
  - arch/arm/kernel/traps.c:dump_mem
  - arch/arm/kernel/traps.c:dump_mem
```
```
In arch/arm/kernel/bugs.c (c15057b8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/kernel/bugs.c:check_bugs
```
```
In arch/arm/kernel/cpuidle.c (c0310490)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/kernel/cpuidle.c:arm_cpuidle_suspend
  - arch/arm/kernel/cpuidle.c:arm_cpuidle_simple_enter
```
```
In arch/arm/kernel/suspend.c (c0311c6c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/kernel/suspend.c:__cpu_suspend_save
  - arch/arm/kernel/suspend.c:cpu_suspend
  - arch/arm/kernel/suspend.c:cpu_suspend
```
```
In arch/arm/kernel/hibernate.c (c0311cf8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/kernel/hibernate.c:arch_restore_image
```
```
In arch/arm/kernel/smp.c (c03138ec)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:smp_send_stop
  - arch/arm/kernel/smp.c:smp_send_stop
  - arch/arm/kernel/smp.c:smp_send_reschedule
  - arch/arm/kernel/smp.c:handle_IPI
  - arch/arm/kernel/smp.c:handle_IPI
  - arch/arm/kernel/smp.c:handle_IPI
  - arch/arm/kernel/smp.c:tick_broadcast
  - arch/arm/kernel/smp.c:arch_irq_work_raise
  - arch/arm/kernel/smp.c:arch_send_call_function_single_ipi
  - arch/arm/kernel/smp.c:arch_send_wakeup_ipi_mask
  - arch/arm/kernel/smp.c:arch_send_call_function_ipi_mask
  - arch/arm/kernel/smp.c:smp_prepare_cpus
  - arch/arm/kernel/smp.c:smp_prepare_boot_cpu
  - arch/arm/kernel/smp.c:secondary_start_kernel
  - arch/arm/kernel/smp.c:secondary_start_kernel
  - arch/arm/kernel/smp.c:secondary_start_kernel
  - arch/arm/kernel/smp.c:secondary_start_kernel
  - arch/arm/kernel/smp.c:arch_cpu_idle_dead
  - arch/arm/kernel/smp.c:arch_cpu_idle_dead
  - arch/arm/kernel/smp.c:__cpu_disable
```
```
In arch/arm/kernel/smp_tlb.c (c0313e68)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/kernel/smp_tlb.c:broadcast_tlb_mm_a15_erratum
  - arch/arm/kernel/smp_tlb.c:ipi_flush_tlb_range
  - arch/arm/kernel/smp_tlb.c:ipi_flush_tlb_page
```
```
In arch/arm/kernel/smp_scu.c (c0314574)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/kernel/smp_scu.c:scu_power_mode
```
```
In arch/arm/kernel/smp_twd.c (c0314870)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/kernel/smp_twd.c:twd_timer_setup
```
```
In arch/arm/kernel/ftrace.c (c0314fa8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/arm/kernel/machine_kexec.c (c03153b0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/kernel/machine_kexec.c:machine_crash_shutdown
  - arch/arm/kernel/machine_kexec.c:machine_crash_nonpanic_core
  - arch/arm/kernel/machine_kexec.c:machine_crash_nonpanic_core
  - arch/arm/kernel/machine_kexec.c:machine_crash_nonpanic_core
  - arch/arm/kernel/machine_kexec.c:machine_kexec_prepare
  - arch/arm/kernel/machine_kexec.c:machine_kexec_prepare
```
```
In arch/arm/kernel/thumbee.c (c0315678)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In arch/arm/kernel/crash_dump.c (c0315b34)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/kernel/crash_dump.c:copy_oldmem_page
```
```
In arch/arm/kernel/swp_emulate.c (c0315ce8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In arch/arm/kernel/hw_breakpoint.c (c0316974)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/kernel/hw_breakpoint.c:reset_ctrl_regs
  - arch/arm/kernel/hw_breakpoint.c:debug_reg_trap
```
```
In arch/arm/kernel/perf_regs.c (c0317b20)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/arm/kernel/perf_callchain.c (c0317c70)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/kernel/perf_callchain.c:perf_callchain_user
  - arch/arm/kernel/perf_callchain.c:perf_callchain_user
  - arch/arm/kernel/perf_callchain.c:perf_callchain_user
  - arch/arm/kernel/perf_callchain.c:perf_callchain_user
```
```
In arch/arm/kernel/perf_event_v7.c (c0318684)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/kernel/perf_event_v7.c:armv7pmu_disable_event
  - arch/arm/kernel/perf_event_v7.c:armv7pmu_enable_event
  - arch/arm/kernel/perf_event_v7.c:armv7pmu_write_counter
  - arch/arm/kernel/perf_event_v7.c:armv7pmu_read_counter
```
```
In arch/arm/kernel/vdso.c (c0319b50)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/kernel/vdso.c:vdso_mremap
```
```
In arch/arm/mm/fault.c (c031a4e4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mm/fault.c:do_DataAbort
  - arch/arm/mm/fault.c:do_page_fault
  - arch/arm/mm/fault.c:do_page_fault
```
```
In arch/arm/mm/init.c (c031aad0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mm/init.c:set_kernel_text_ro
  - arch/arm/mm/init.c:set_kernel_text_rw
  - arch/arm/mm/init.c:update_sections_early
```
```
In arch/arm/mm/dma-mapping.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In arch/arm/mm/fault-armv.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In arch/arm/mm/flush.c (c031ea74)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mm/flush.c:copy_to_user_page
```
```
In arch/arm/mm/idmap.c (c031ee64)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mm/idmap.c:setup_mm_for_reboot
```
```
In arch/arm/mm/mmap.c (c031f5e4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mm/mmap.c:arch_get_unmapped_area_topdown
  - arch/arm/mm/mmap.c:arch_get_unmapped_area
```
```
In arch/arm/mm/alignment.c (c0321204)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mm/alignment.c:do_alignment
  - arch/arm/mm/alignment.c:do_alignment
  - arch/arm/mm/alignment.c:do_alignment
  - arch/arm/mm/alignment.c:do_alignment
  - arch/arm/mm/alignment.c:alignment_get_thumb
  - arch/arm/mm/alignment.c:alignment_get_thumb
  - arch/arm/mm/alignment.c:do_alignment_ldmstm
  - arch/arm/mm/alignment.c:alignment_proc_write
  - arch/arm/mm/alignment.c:alignment_proc_write
```
```
In arch/arm/mm/highmem.c (c0321ccc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mm/highmem.c:kmap_atomic_pfn
  - arch/arm/mm/highmem.c:kmap_atomic_pfn
  - arch/arm/mm/highmem.c:__kunmap_atomic
```
```
In arch/arm/mm/context.c (c0322278)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mm/context.c:check_and_switch_context
  - arch/arm/mm/context.c:check_and_switch_context
```
```
In arch/arm/mm/proc-v7-bugs.c (c0322fd4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mm/proc-v7-bugs.c:cpu_v7_ca15_ibe
  - arch/arm/mm/proc-v7-bugs.c:cpu_v7_ca8_ibe
  - arch/arm/mm/proc-v7-bugs.c:cpu_v7_spectre_init
  - arch/arm/mm/proc-v7-bugs.c:cpu_v7_spectre_init
  - arch/arm/mm/proc-v7-bugs.c:cpu_v7_spectre_init
  - arch/arm/mm/proc-v7-bugs.c:cpu_v7_spectre_init
```
```
In arch/arm/common/mcpm_entry.c (c150bb7c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/common/mcpm_entry.c:nocache_trampoline
  - arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down
```
```
In arch/arm/common/bL_switcher.c (c0326810)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_trace_trigger_cpu
  - arch/arm/common/bL_switcher.c:bL_switcher_thread
  - arch/arm/common/bL_switcher.c:bL_switcher_thread
  - arch/arm/common/bL_switcher.c:bL_switch_to
  - arch/arm/common/bL_switcher.c:bL_switch_to
  - arch/arm/common/bL_switcher.c:bL_switch_to
  - arch/arm/common/bL_switcher.c:bL_switchpoint
  - arch/arm/common/bL_switcher.c:bL_do_switch
```
```
In arch/arm/probes/uprobes/core.c (c0327d20)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/probes/uprobes/core.c:arch_uprobe_abort_xol
  - arch/arm/probes/uprobes/core.c:arch_uprobe_post_xol
  - arch/arm/probes/uprobes/core.c:arch_uprobe_pre_xol
```
```
In arch/arm/probes/kprobes/core.c (c0ea0974)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/probes/kprobes/core.c:trampoline_handler
  - arch/arm/probes/kprobes/core.c:trampoline_handler
  - arch/arm/probes/kprobes/core.c:trampoline_handler
```
```
In arch/arm/net/bpf_jit_32.c (c032c79c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/net/bpf_jit_32.c:bpf_int_jit_compile
```
```
In arch/arm/mach-berlin/platsmp.c (c032cac8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-berlin/platsmp.c:berlin_cpu_die
```
```
In arch/arm/mach-exynos/pm.c (c032d0bc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-exynos/pm.c:exynos_wfi_finisher
```
```
In arch/arm/mach-exynos/suspend.c (c032d82c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-exynos/suspend.c:exynos_cpu_do_idle
```
```
In arch/arm/mach-highbank/highbank.c (c032eedc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-highbank/highbank.c:highbank_power_off
  - arch/arm/mach-highbank/highbank.c:highbank_power_off
```
```
In arch/arm/mach-highbank/system.c (c032f1b4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-highbank/system.c:highbank_restart
  - arch/arm/mach-highbank/system.c:highbank_set_core_pwr
```
```
In arch/arm/mach-hisi/hotplug.c (c032fe04)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-hisi/hotplug.c:hi3xxx_cpu_die
```
```
In arch/arm/mach-mvebu/pmsu.c (c0330eb0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/pmsu.c:mvebu_pmsu_dfs_request_local
  - arch/arm/mach-mvebu/pmsu.c:mvebu_v7_pmsu_idle_exit
  - arch/arm/mach-mvebu/pmsu.c:armada_38x_do_cpu_suspend
  - arch/arm/mach-mvebu/pmsu.c:mvebu_v7_pmsu_idle_prepare
```
```
In arch/arm/mach-mvebu/pm.c (c03315c4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In arch/arm/mach-mvebu/platsmp.c (c150e484)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/platsmp.c:armada_xp_smp_prepare_cpus
```
```
In arch/arm/mach-imx/pm-imx5.c (c0332050)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-imx/pm-imx5.c:imx5_pm_idle
```
```
In arch/arm/mach-imx/tzic.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In arch/arm/mach-imx/cpuidle-imx6q.c (c0332378)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-imx/cpuidle-imx6q.c:imx6q_enter_wait
```
```
In arch/arm/mach-imx/cpuidle-imx6sl.c (c0332420)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-imx/cpuidle-imx6sl.c:imx6sl_enter_wait
```
```
In arch/arm/mach-imx/cpuidle-imx6sx.c (c03324ec)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-imx/cpuidle-imx6sx.c:imx6sx_enter_wait
  - arch/arm/mach-imx/cpuidle-imx6sx.c:imx6sx_idle_finish
```
```
In arch/arm/mach-imx/cpuidle-imx7ulp.c (c0332580)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-imx/cpuidle-imx7ulp.c:imx7ulp_enter_wait
```
```
In arch/arm/mach-imx/mmdc.c (c033336c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-imx/mmdc.c:imx_mmdc_probe
```
```
In arch/arm/mach-imx/hotplug.c (c0333afc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-imx/hotplug.c:imx_cpu_die
```
```
In arch/arm/mach-imx/pm-imx6.c (c033490c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-imx/pm-imx6.c:imx6q_pm_enter
```
```
In arch/arm/mach-milbeaut/platsmp.c (c0334cbc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-milbeaut/platsmp.c:m10v_die
```
```
In arch/arm/mach-omap2/omap-wakeupgen.c (c1514f78)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_init
```
```
In arch/arm/mach-omap2/omap-smp.c (c033c960)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In arch/arm/mach-omap2/omap-hotplug.c (c033cab0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-hotplug.c:omap4_cpu_die
```
```
In arch/arm/mach-omap2/omap-mpuss-lowpower.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In arch/arm/mach-omap2/pm34xx.c (c033d644)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In arch/arm/mach-omap2/pm44xx.c (c033dec8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-omap2/pm44xx.c:omap4_pm_suspend
```
```
In arch/arm/mach-omap2/cpuidle34xx.c (c033ec8c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-omap2/cpuidle34xx.c:omap3_enter_idle_bm
```
```
In arch/arm/mach-omap2/powerdomain.c (c03451bc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-omap2/powerdomain.c:pwrdm_set_next_pwrst
  - arch/arm/mach-omap2/powerdomain.c:_pwrdm_state_switch
```
```
In arch/arm/mach-qcom/platsmp.c (c1518ed8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-qcom/platsmp.c:qcom_smp_prepare_cpus
```
```
In arch/arm/mach-rockchip/pm.c (c03490bc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-rockchip/pm.c:rockchip_lpmode_enter
```
```
In arch/arm/mach-rockchip/platsmp.c (c0349304)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-rockchip/platsmp.c:rockchip_cpu_die
```
```
In arch/arm/mach-shmobile/platsmp-apmu.c (c0349714)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/platsmp-apmu.c:shmobile_smp_apmu_enter_suspend
  - arch/arm/mach-shmobile/platsmp-apmu.c:shmobile_smp_apmu_do_suspend
```
```
In arch/arm/mach-shmobile/suspend.c (c034a2d4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/suspend.c:shmobile_suspend_default_enter
```
```
In arch/arm/mach-tegra/pm.c (c034acb8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-tegra/pm.c:tegra_cpu_do_idle
  - arch/arm/mach-tegra/pm.c:tegra_set_cpu_in_lp2
  - arch/arm/mach-tegra/pm.c:tegra_clear_cpu_in_lp2
```
```
In arch/arm/mach-tegra/cpuidle-tegra30.c (c034c724)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - arch/arm/mach-tegra/cpuidle-tegra30.c:tegra30_idle_lp2
```
```
In kernel/fork.c (c03540ec)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:unshare_fd
  - kernel/fork.c:__se_sys_clone3
  - kernel/fork.c:copy_clone_args_from_user
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:__se_sys_set_tid_address
  - kernel/fork.c:mm_release
  - kernel/fork.c:mm_release
  - kernel/fork.c:mm_access
  - kernel/fork.c:mm_alloc
  - kernel/fork.c:mm_init
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:dup_mmap
```
```
In kernel/exec_domain.c (c035429c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/exec_domain.c:__se_sys_personality
```
```
In kernel/panic.c (c03549c4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:nmi_panic
```
```
In kernel/cpu.c (c151c2b0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_hotplug_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_report_idle_dead
  - kernel/cpu.c:take_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
```
```
In kernel/exit.c (c035b230)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/exit.c:__se_sys_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_wait
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:is_current_pgrp_orphaned
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/softirq.c (c035c32c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:tasklet_kill
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:__raise_softirq_irqoff
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/resource.c (c035d21c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/resource.c:__request_region
  - kernel/resource.c:__request_region
```
```
In kernel/sysctl.c (c035edbc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_put_long
  - kernel/sysctl.c:_proc_do_string
  - kernel/sysctl.c:_proc_do_string
  - kernel/sysctl.c:_proc_do_string
  - kernel/sysctl.c:_proc_do_string
  - kernel/sysctl.c:_proc_do_string
```
```
In kernel/sysctl_binary.c (c036095c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__se_sys_sysctl
  - kernel/sysctl_binary.c:__se_sys_sysctl
  - kernel/sysctl_binary.c:__se_sys_sysctl
  - kernel/sysctl_binary.c:__se_sys_sysctl
  - kernel/sysctl_binary.c:__se_sys_sysctl
  - kernel/sysctl_binary.c:__se_sys_sysctl
  - kernel/sysctl_binary.c:__se_sys_sysctl
  - kernel/sysctl_binary.c:__se_sys_sysctl
```
```
In kernel/capability.c (c0361530)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:__se_sys_capset
  - kernel/capability.c:__se_sys_capset
  - kernel/capability.c:__se_sys_capset
  - kernel/capability.c:__se_sys_capset
  - kernel/capability.c:__se_sys_capset
  - kernel/capability.c:__se_sys_capset
  - kernel/capability.c:__se_sys_capget
  - kernel/capability.c:__se_sys_capget
  - kernel/capability.c:__se_sys_capget
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
```
```
In kernel/ptrace.c (c03629d8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/ptrace.c:generic_ptrace_peekdata
  - kernel/ptrace.c:generic_ptrace_peekdata
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_writedata
  - kernel/ptrace.c:ptrace_readdata
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:ptrace_access_vm
```
```
In kernel/signal.c (c036a900)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigsuspend
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:sys_pause
  - kernel/signal.c:__se_sys_ssetmask
  - kernel/signal.c:sys_sgetmask
  - kernel/signal.c:__do_sys_sigaction
  - kernel/signal.c:__do_sys_sigaction
  - kernel/signal.c:__do_sys_sigaction
  - kernel/signal.c:__do_sys_sigaction
  - kernel/signal.c:__do_sys_sigaction
  - kernel/signal.c:__do_sys_sigaction
  - kernel/signal.c:__do_sys_sigaction
  - kernel/signal.c:__do_sys_sigaction
  - kernel/signal.c:__do_sys_sigaction
  - kernel/signal.c:__do_sys_sigaction
  - kernel/signal.c:__do_sys_sigaction
  - kernel/signal.c:__do_sys_sigaction
  - kernel/signal.c:__do_sys_sigaction
  - kernel/signal.c:__do_sys_sigaction
  - kernel/signal.c:__do_sys_sigaction
  - kernel/signal.c:__do_sys_sigaction
  - kernel/signal.c:__se_sys_rt_sigaction
  - kernel/signal.c:__se_sys_rt_sigaction
  - kernel/signal.c:__se_sys_sigprocmask
  - kernel/signal.c:__se_sys_sigprocmask
  - kernel/signal.c:__se_sys_sigprocmask
  - kernel/signal.c:__se_sys_sigpending
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__se_sys_sigaltstack
  - kernel/signal.c:__se_sys_sigaltstack
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:__se_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__se_sys_rt_sigqueueinfo
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_tkill
  - kernel/signal.c:__se_sys_pidfd_send_signal
  - kernel/signal.c:__se_sys_pidfd_send_signal
  - kernel/signal.c:__se_sys_pidfd_send_signal
  - kernel/signal.c:__se_sys_pidfd_send_signal
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:__se_sys_kill
  - kernel/signal.c:__se_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__se_sys_rt_sigtimedwait
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:__se_sys_rt_sigpending
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:do_sigpending
  - kernel/signal.c:__se_sys_rt_sigprocmask
  - kernel/signal.c:__se_sys_rt_sigprocmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:__set_current_blocked
  - kernel/signal.c:__set_task_blocked
  - kernel/signal.c:sys_restart_syscall
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_notify
  - kernel/signal.c:ptrace_notify
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:sigqueue_alloc
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_sigsegv
  - kernel/signal.c:force_sig
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:flush_itimer_signals
  - kernel/signal.c:__sigqueue_alloc
  - kernel/signal.c:task_join_group_stop
  - kernel/signal.c:calculate_sigpending
  - kernel/signal.c:calculate_sigpending
  - kernel/signal.c:calculate_sigpending
```
```
In kernel/sys.c (c036eadc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_sysinfo
  - kernel/sys.c:__se_sys_getcpu
  - kernel/sys.c:__se_sys_getcpu
  - kernel/sys.c:__se_sys_getcpu
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:__se_sys_umask
  - kernel/sys.c:__se_sys_getrusage
  - kernel/sys.c:__se_sys_getrusage
  - kernel/sys.c:getrusage
  - kernel/sys.c:__se_sys_setrlimit
  - kernel/sys.c:__se_sys_setrlimit
  - kernel/sys.c:__se_sys_prlimit64
  - kernel/sys.c:__se_sys_prlimit64
  - kernel/sys.c:__se_sys_prlimit64
  - kernel/sys.c:__se_sys_prlimit64
  - kernel/sys.c:__se_sys_getrlimit
  - kernel/sys.c:__se_sys_getrlimit
  - kernel/sys.c:__se_sys_setdomainname
  - kernel/sys.c:__se_sys_setdomainname
  - kernel/sys.c:__se_sys_setdomainname
  - kernel/sys.c:__se_sys_gethostname
  - kernel/sys.c:__se_sys_gethostname
  - kernel/sys.c:__se_sys_sethostname
  - kernel/sys.c:__se_sys_sethostname
  - kernel/sys.c:__se_sys_sethostname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__se_sys_getsid
  - kernel/sys.c:do_getpgid
  - kernel/sys.c:__se_sys_setpgid
  - kernel/sys.c:__se_sys_times
  - kernel/sys.c:__se_sys_times
  - kernel/sys.c:__se_sys_times
  - kernel/sys.c:sys_getegid
  - kernel/sys.c:sys_getgid
  - kernel/sys.c:sys_geteuid
  - kernel/sys.c:sys_getuid
  - kernel/sys.c:sys_getppid
  - kernel/sys.c:sys_gettid
  - kernel/sys.c:sys_getpid
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__se_sys_getresgid
  - kernel/sys.c:__se_sys_getresgid
  - kernel/sys.c:__se_sys_getresgid
  - kernel/sys.c:__se_sys_getresgid
  - kernel/sys.c:__se_sys_getresgid
  - kernel/sys.c:__se_sys_getresgid
  - kernel/sys.c:__se_sys_getresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__se_sys_getresuid
  - kernel/sys.c:__se_sys_getresuid
  - kernel/sys.c:__se_sys_getresuid
  - kernel/sys.c:__se_sys_getresuid
  - kernel/sys.c:__se_sys_getresuid
  - kernel/sys.c:__se_sys_getresuid
  - kernel/sys.c:__se_sys_getresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:set_user
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
  - kernel/sys.c:__se_sys_setpriority
  - kernel/sys.c:__se_sys_setpriority
  - kernel/sys.c:set_one_prio
```
```
In kernel/umh.c (c036edbc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In kernel/workqueue.c (c03765b0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:set_worker_desc
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:current_is_workqueue_rescuer
  - kernel/workqueue.c:current_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:check_flush_dependency
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:set_pf_worker
  - kernel/workqueue.c:set_pf_worker
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/pid.c (c03773ec)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_task_by_vpid
  - kernel/pid.c:find_vpid
```
```
In kernel/task_work.c (c0377dcc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_run
```
```
In kernel/kthread.c (c0379a1c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_blkcg
  - kernel/kthread.c:kthread_associate_blkcg
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread_parkme
  - kernel/kthread.c:__kthread_parkme
  - kernel/kthread.c:__kthread_parkme
  - kernel/kthread.c:__kthread_parkme
  - kernel/kthread.c:__kthread_parkme
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/kthread.c:kthread_should_park
  - kernel/kthread.c:kthread_should_stop
```
```
In kernel/nsproxy.c (c037bcac)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/nsproxy.c:__se_sys_setns
  - kernel/nsproxy.c:__se_sys_setns
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
```
```
In kernel/cred.c (c037d008)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/cred.c:revert_creds
  - kernel/cred.c:revert_creds
  - kernel/cred.c:override_creds
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:__put_cred
```
```
In kernel/reboot.c (c037df74)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/async.c (c037e954)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/async.c:current_is_async
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_schedule_node_domain
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/smpboot.c (c037f7ac)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_report_death
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:idle_threads_init
  - kernel/smpboot.c:idle_thread_set_boot_cpu
```
```
In kernel/ucount.c (c037f86c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/ucount.c:set_is_seen
  - kernel/ucount.c:set_lookup
```
```
In kernel/kmod.c (c03800e0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/groups.c (c0380320)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/groups.c:in_egroup_p
  - kernel/groups.c:in_group_p
  - kernel/groups.c:__se_sys_setgroups
  - kernel/groups.c:__se_sys_setgroups
  - kernel/groups.c:__se_sys_setgroups
  - kernel/groups.c:may_setgroups
  - kernel/groups.c:__se_sys_getgroups
  - kernel/groups.c:__se_sys_getgroups
  - kernel/groups.c:__se_sys_getgroups
```
```
In kernel/sched/core.c (c151ef70)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:migration_init
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:io_schedule
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/core.c:io_schedule_prepare
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield
  - kernel/sched/core.c:_cond_resched
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__se_sys_sched_getaffinity
  - kernel/sched/core.c:__se_sys_sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__se_sys_sched_getattr
  - kernel/sched/core.c:__se_sys_sched_getattr
  - kernel/sched/core.c:__se_sys_sched_getparam
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__se_sys_nice
  - kernel/sched/core.c:__se_sys_nice
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_common
  - kernel/sched/core.c:schedule_idle
  - kernel/sched/core.c:schedule_idle
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:do_task_dead
  - kernel/sched/core.c:do_task_dead
  - kernel/sched/core.c:do_task_dead
  - kernel/sched/core.c:do_task_dead
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule_bug
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:perf_trace_sched_process_wait
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_process_wait
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/cputime.c (c038f388)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_process_tick
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/idle.c (c038fe08)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
  - kernel/sched/idle.c:play_idle
  - kernel/sched/idle.c:play_idle
  - kernel/sched/idle.c:idle_inject_timer_fn
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:do_idle
  - kernel/sched/idle.c:call_cpuidle
  - kernel/sched/idle.c:default_idle_call
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/sched/fair.c (c0393858)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (c039b4b8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (c039f2e4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/sched/deadline.c:find_later_rq
```
```
In kernel/sched/wait.c (c03a619c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/sched/wait.c:wait_woken
  - kernel/sched/wait.c:wait_woken
  - kernel/sched/wait.c:wait_woken
  - kernel/sched/wait.c:finish_wait
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr_irq
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:do_wait_intr
  - kernel/sched/wait.c:prepare_to_wait_event
  - kernel/sched/wait.c:init_wait_entry
  - kernel/sched/wait.c:prepare_to_wait_exclusive
  - kernel/sched/wait.c:prepare_to_wait
```
```
In kernel/sched/wait_bit.c (c0e9a828)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:bit_wait_io_timeout
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/wait_bit.c:bit_wait_io
  - kernel/sched/wait_bit.c:bit_wait
  - kernel/sched/wait_bit.c:init_wait_var_entry
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
```
```
In kernel/sched/swait.c (c03a66d0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/sched/swait.c:finish_swait
  - kernel/sched/swait.c:__finish_swait
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:prepare_to_swait_event
  - kernel/sched/swait.c:prepare_to_swait_exclusive
  - kernel/sched/swait.c:prepare_to_swait_exclusive
```
```
In kernel/sched/completion.c (c0e9aa70)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io_timeout
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_io
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/sched/completion.c:wait_for_completion
```
```
In kernel/sched/pelt.c (c03ab648)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
```
In kernel/sched/autogroup.c (c03abc58)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
```
```
In kernel/sched/debug.c (c03ac370)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/sched/cpufreq.c (c03b10ec)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/sched/cpufreq.c:cpufreq_this_cpu_can_update
```
```
In kernel/sched/cpufreq_schedutil.c (c03b1414)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
```
In kernel/sched/membarrier.c (c03b27d4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_private_expedited
```
```
In kernel/sched/isolation.c (c151f5dc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/sched/psi.c (c03b46a8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
  - kernel/sched/psi.c:psi_memstall_enter
```
```
In kernel/locking/mutex.c (c0e9c008)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_unlock
  - kernel/locking/mutex.c:mutex_spin_on_owner
  - kernel/locking/mutex.c:__ww_mutex_wound
  - kernel/locking/mutex.c:mutex_lock
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
```
In kernel/locking/semaphore.c (c0e9caac)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
  - kernel/locking/semaphore.c:__down
```
```
In kernel/locking/rwsem.c (c03b561c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/percpu-rwsem.c (c03b6318)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_down_write
```
```
In kernel/locking/spinlock.c (c0e9f248)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/locking/osq_lock.c (c03b6770)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/rtmutex.c (c03b7c8c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_wait_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_timed_lock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
```
```
In kernel/power/qos.c (c03b8810)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_write
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/main.c (c03b9bd4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/power/main.c:pm_test_store
  - kernel/power/main.c:pm_test_store
```
```
In kernel/power/process.c (c03ba9d8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:freeze_kernel_threads
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/power/suspend.c (c03bb7d0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
```
```
In kernel/power/hibernate.c (c03bcb44)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/power/snapshot.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In kernel/power/user.c (c03c3a74)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
```
```
In kernel/printk/printk.c (c15208f4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:devkmsg_release
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_write
  - kernel/printk/printk.c:check_syslog_permissions
```
```
In kernel/irq/irqdesc.c (c03c96a0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:handle_domain_nmi
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/handle.c (c03c9f40)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/manage.c (c03cacc8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:disable_percpu_irq
  - kernel/irq/manage.c:irq_percpu_is_enabled
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/irq/spurious.c (c03cdc90)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:poll_spurious_irqs
  - kernel/irq/spurious.c:irq_wait_for_poll
```
```
In kernel/irq/chip.c (c03cfe08)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
```
```
In kernel/irq/cpuhotplug.c (c03d522c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In kernel/rcu/update.c (c03d79bc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/rcu/update.c:exit_tasks_rcu_finish
  - kernel/rcu/update.c:exit_tasks_rcu_start
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (c03d82ec)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (c03dd8a4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:__note_gp_changes
```
```
In kernel/dma/direct.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In kernel/kcmp.c (c03e2d44)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
```
```
In kernel/freezer.c (c03e327c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:__refrigerator
  - kernel/freezer.c:__refrigerator
  - kernel/freezer.c:__refrigerator
```
```
In kernel/profile.c (c03e3db0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/profile.c:write_profile
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/profile.c:read_profile
  - kernel/profile.c:read_profile
  - kernel/profile.c:read_profile
  - kernel/profile.c:profile_tick
  - kernel/profile.c:__profile_flip_buffers
```
```
In kernel/stacktrace.c (c03e4480)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/time/time.c (c03e4e5c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:get_old_itimerspec32
  - kernel/time/time.c:get_old_itimerspec32
  - kernel/time/time.c:put_old_timespec32
  - kernel/time/time.c:get_old_timespec32
  - kernel/time/time.c:put_timespec64
  - kernel/time/time.c:get_timespec64
  - kernel/time/time.c:put_old_timex32
  - kernel/time/time.c:get_old_timex32
  - kernel/time/time.c:__se_sys_settimeofday
  - kernel/time/time.c:__se_sys_settimeofday
  - kernel/time/time.c:__se_sys_gettimeofday
  - kernel/time/time.c:__se_sys_gettimeofday
  - kernel/time/time.c:__se_sys_gettimeofday
  - kernel/time/time.c:__se_sys_gettimeofday
  - kernel/time/time.c:__se_sys_gettimeofday
```
```
In kernel/time/timer.c (c0e9dec4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/time/timer.c:usleep_range
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout_idle
  - kernel/time/timer.c:schedule_timeout_killable
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:update_process_times
  - kernel/time/timer.c:get_next_timer_interrupt
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:detach_if_pending
  - kernel/time/timer.c:enqueue_timer
  - kernel/time/timer.c:round_jiffies_up_relative
  - kernel/time/timer.c:round_jiffies_up
  - kernel/time/timer.c:round_jiffies_relative
  - kernel/time/timer.c:round_jiffies
```
```
In kernel/time/hrtimer.c (c0e9e644)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__se_sys_nanosleep_time32
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_init
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/hrtimer.c:hrtimers_init
```
```
In kernel/time/timekeeping.c (c03f06a0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/time/alarmtimer.c (c03f546c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-timers.c (c03f7be0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__se_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__se_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__se_sys_timer_delete
  - kernel/time/posix-timers.c:__se_sys_timer_delete
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:__se_sys_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (c03f92b8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In kernel/time/itimer.c (c03fad2c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/time/itimer.c:__se_sys_setitimer
  - kernel/time/itimer.c:__se_sys_setitimer
  - kernel/time/itimer.c:__se_sys_setitimer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
  - kernel/time/itimer.c:__se_sys_getitimer
  - kernel/time/itimer.c:do_getitimer
```
```
In kernel/time/clockevents.c (c03fb2a8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
  - kernel/time/clockevents.c:__clockevents_unbind
```
```
In kernel/time/tick-common.c (c03fc9a8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_handover_do_timer
  - kernel/time/tick-common.c:tick_check_new_device
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_install_replacement
  - kernel/time/tick-common.c:tick_handle_periodic
```
```
In kernel/time/tick-broadcast.c (c03fcd04)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu
  - kernel/time/tick-broadcast.c:tick_check_broadcast_expired
  - kernel/time/tick-broadcast.c:tick_resume_check_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/time/tick-sched.c (c03ffca0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_get_sleep_length
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/time/tick-sched.c:can_stop_idle_tick
  - kernel/time/tick-sched.c:tick_sched_handle
  - kernel/time/tick-sched.c:tick_sched_do_timer
```
```
In kernel/futex.c (c0402fe0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:__se_sys_get_robust_list
  - kernel/futex.c:__se_sys_get_robust_list
  - kernel/futex.c:__se_sys_get_robust_list
  - kernel/futex.c:__se_sys_get_robust_list
  - kernel/futex.c:__se_sys_get_robust_list
  - kernel/futex.c:__se_sys_set_robust_list
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_wait_queue_me
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:fault_in_user_writeable
  - kernel/futex.c:fault_in_user_writeable
  - kernel/futex.c:get_futex_key
```
```
In kernel/smp.c (c04051f4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:on_each_cpu_mask
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:flush_smp_call_function_queue
  - kernel/smp.c:generic_exec_single
  - kernel/smp.c:call_function_init
```
```
In kernel/uid16.c (c04066e4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/uid16.c:sys_getegid16
  - kernel/uid16.c:sys_getegid16
  - kernel/uid16.c:sys_getgid16
  - kernel/uid16.c:sys_getgid16
  - kernel/uid16.c:sys_geteuid16
  - kernel/uid16.c:sys_geteuid16
  - kernel/uid16.c:sys_getuid16
  - kernel/uid16.c:sys_getuid16
  - kernel/uid16.c:__se_sys_setgroups16
  - kernel/uid16.c:__se_sys_setgroups16
  - kernel/uid16.c:__se_sys_setgroups16
  - kernel/uid16.c:__se_sys_getgroups16
  - kernel/uid16.c:__se_sys_getgroups16
  - kernel/uid16.c:__se_sys_getgroups16
  - kernel/uid16.c:__se_sys_getresgid16
  - kernel/uid16.c:__se_sys_getresgid16
  - kernel/uid16.c:__se_sys_getresgid16
  - kernel/uid16.c:__se_sys_getresgid16
  - kernel/uid16.c:__se_sys_getresgid16
  - kernel/uid16.c:__se_sys_getresgid16
  - kernel/uid16.c:__se_sys_getresgid16
  - kernel/uid16.c:__se_sys_getresuid16
  - kernel/uid16.c:__se_sys_getresuid16
  - kernel/uid16.c:__se_sys_getresuid16
  - kernel/uid16.c:__se_sys_getresuid16
  - kernel/uid16.c:__se_sys_getresuid16
  - kernel/uid16.c:__se_sys_getresuid16
  - kernel/uid16.c:__se_sys_getresuid16
```
```
In kernel/module.c (c040cc48)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/module.c:__se_sys_init_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
  - kernel/module.c:module_memfree
  - kernel/module.c:try_module_get
  - kernel/module.c:__se_sys_delete_module
```
```
In kernel/kallsyms.c (c040e38c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In kernel/acct.c (c040f248)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_collect
  - kernel/acct.c:acct_collect
  - kernel/acct.c:acct_collect
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:fill_ac
  - kernel/acct.c:fill_ac
  - kernel/acct.c:fill_ac
  - kernel/acct.c:fill_ac
  - kernel/acct.c:fill_ac
  - kernel/acct.c:fill_ac
  - kernel/acct.c:__se_sys_acct
  - kernel/acct.c:__se_sys_acct
```
```
In kernel/kexec_core.c (c0410cf0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_save_cpu
  - kernel/kexec_core.c:crash_kexec
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_alloc_pages
  - kernel/kexec_core.c:kexec_should_crash
```
```
In kernel/kexec.c (c0410f1c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
```
```
In kernel/cgroup/cgroup.c (c041ba18)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_kn_set_ugid
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/rstat.c (c041c6f4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
```
```
In kernel/cgroup/namespace.c (c041ca44)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (c041ec2c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (c041fa14)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_leave_frozen
  - kernel/cgroup/freezer.c:cgroup_enter_frozen
  - kernel/cgroup/freezer.c:cgroup_enter_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/cgroup/pids.c (c042095c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_cancel_fork
  - kernel/cgroup/pids.c:pids_can_fork
```
```
In kernel/cgroup/rdma.c (c0421404)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
```
In kernel/cgroup/cpuset.c (c04257e8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:__cpuset_memory_pressure_bump
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_init_current_mems_allowed
  - kernel/cgroup/cpuset.c:current_cpuset_is_being_rebound
```
```
In kernel/utsname.c (c0425cb0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (c0426024)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:current_in_userns
  - kernel/user_namespace.c:proc_setgroups_write
```
```
In kernel/pid_namespace.c (c04275b8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:zap_pid_ns_processes
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/stop_machine.c (c0428d54)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:cpu_stop_init
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/audit.c (c042c188)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_signal_info
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_link_denied
  - kernel/audit.c:audit_get_tty
  - kernel/audit.c:audit_get_tty
  - kernel/audit.c:audit_log_task_context
  - kernel/audit.c:audit_log_session_info
  - kernel/audit.c:audit_receive
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:audit_log_config_change
```
```
In kernel/auditfilter.c (c042e874)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_data_to_entry
```
```
In kernel/auditsc.c (c04334d8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_killed_trees
  - kernel/auditsc.c:audit_seccomp_actions_logged
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_core_dumps
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_ntp_val
  - kernel/auditsc.c:__audit_tk_injoffset
  - kernel/auditsc.c:__audit_fanotify
  - kernel/auditsc.c:__audit_log_kern_module
  - kernel/auditsc.c:__audit_mmap_fd
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:__audit_sockaddr
  - kernel/auditsc.c:__audit_fd_pair
  - kernel/auditsc.c:__audit_socketcall
  - kernel/auditsc.c:__audit_bprm
  - kernel/auditsc.c:__audit_ipc_set_perm
  - kernel/auditsc.c:__audit_ipc_obj
  - kernel/auditsc.c:__audit_mq_getsetattr
  - kernel/auditsc.c:__audit_mq_notify
  - kernel/auditsc.c:__audit_mq_sendrecv
  - kernel/auditsc.c:__audit_mq_open
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_inode
  - kernel/auditsc.c:__audit_getname
  - kernel/auditsc.c:__audit_getname
  - kernel/auditsc.c:__audit_reusename
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_exit
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:__audit_free
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_log_execve_info
```
```
In kernel/audit_watch.c (c0433a08)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_fsnotify.c (c0434300)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In kernel/audit_tree.c (c0434b0c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_thread
```
```
In kernel/kprobes.c (c043892c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
```
```
In kernel/debug/debug_core.c (c043aa78)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_flush_swbreak_addr
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
```
In kernel/debug/gdbstub.c (c043c980)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In kernel/debug/kdb/kdb_io.c (c043cdd8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/debug/kdb/kdb_main.c (c043e9e8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_print_state
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/debug/kdb/kdb_support.c (c0442bf0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In kernel/debug/kdb/kdb_debugger.c (c04451dc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
```
```
In kernel/hung_task.c (c0445dfc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/watchdog.c (c0446450)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/watchdog.c:softlockup_start_fn
  - kernel/watchdog.c:softlockup_stop_fn
  - kernel/watchdog.c:watchdog_disable
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/seccomp.c (c0449294)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:prctl_get_seccomp
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/relay.c (c044a0ac)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
  - kernel/relay.c:relay_late_setup_files
```
```
In kernel/utsname_sysctl.c (c044b108)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - kernel/utsname_sysctl.c:proc_do_uts_string
```
```
In kernel/delayacct.c (c044b7b4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
```
```
In kernel/taskstats.c (c044c318)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/trace_clock.c (c044da30)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_global
  - kernel/trace/trace_clock.c:trace_clock_global
```
```
In kernel/trace/ftrace.c (c044ec80)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ignore_task_cpu
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:profile_graph_return
  - kernel/trace/ftrace.c:profile_graph_return
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/trace/ring_buffer.c (c04582f8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_peek
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_nest_end
  - kernel/trace/ring_buffer.c:ring_buffer_nest_start
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:ring_buffer_wait
  - kernel/trace/ring_buffer.c:ring_buffer_wait
```
```
In kernel/trace/trace.c (c0467cc0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:tracing_trace_options_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:tracing_generic_entry_update
  - kernel/trace/trace.c:tracing_generic_entry_update
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
```
In kernel/trace/trace_sched_switch.c (c046b298)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:probe_sched_wakeup
```
```
In kernel/trace/trace_functions.c (c046b664)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_init
```
```
In kernel/trace/trace_sched_wakeup.c (c046c634)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_return
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_hwlat.c (c046d7ac)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:trace_hwlat_callback
```
```
In kernel/trace/trace_stack.c (c046e144)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_functions_graph.c (c046ea78)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (c0471d38)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
```
In kernel/trace/fgraph.c (c0473e5c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:ftrace_return_to_handler
  - kernel/trace/fgraph.c:ftrace_return_to_handler
  - kernel/trace/fgraph.c:ftrace_suspend_notifier_call
  - kernel/trace/fgraph.c:ftrace_suspend_notifier_call
  - kernel/trace/fgraph.c:function_graph_enter
  - kernel/trace/fgraph.c:function_graph_enter
  - kernel/trace/fgraph.c:function_graph_enter
  - kernel/trace/fgraph.c:function_graph_enter
  - kernel/trace/fgraph.c:function_graph_enter
  - kernel/trace/fgraph.c:function_graph_enter
```
```
In kernel/trace/trace_events.c (c0475524)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (c0478984)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (c047a288)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_events_filter.c (c047ab28)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:filter_pred_comm
  - kernel/trace/trace_events_filter.c:filter_pred_cpu
```
```
In kernel/trace/bpf_trace.c (c0481968)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
  - kernel/trace/bpf_trace.c:bpf_get_current_task
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_read_value
  - kernel/trace/bpf_trace.c:bpf_perf_event_read
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In kernel/trace/trace_kprobe.c (c0483158)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/trace/trace_uprobe.c (c048d840)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In kernel/irq_work.c (c048e448)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/core.c (c048f66c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_enqueue
  - kernel/bpf/core.c:perf_trace_xdp_cpumap_kthread
  - kernel/bpf/core.c:trace_event_raw_event_xdp_cpumap_enqueue
  - kernel/bpf/core.c:trace_event_raw_event_xdp_cpumap_kthread
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
```
```
In kernel/bpf/syscall.c (c049704c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_charge
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:bpf_map_charge_init
  - kernel/bpf/syscall.c:bpf_charge_memlock
```
```
In kernel/bpf/verifier.c (c04a53ec)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:bpf_verifier_vlog
```
```
In kernel/bpf/helpers.c (c04a89c8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
  - kernel/bpf/helpers.c:bpf_get_current_comm
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - kernel/bpf/helpers.c:bpf_get_current_pid_tgid
  - kernel/bpf/helpers.c:bpf_get_smp_processor_id
```
```
In kernel/bpf/percpu_freelist.c (c04ade18)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
```
```
In kernel/bpf/bpf_lru_list.c (c04ae7dc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/bpf/btf.c (c04b6370)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/devmap.c (c04b6b4c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:bq_xmit_all
```
```
In kernel/bpf/cpumap.c (c04b79c4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (c04b9878)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_map_offload_map_alloc
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In kernel/bpf/stackmap.c (c04bb154)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/bpf/cgroup.c (c04bd3c0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
```
In kernel/events/core.c (c152be5c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_log_itrace_start
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_task_output
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_callchain
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:__perf_event_header__init_id
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_pending_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_stop
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:event_function
```
```
In kernel/events/ring_buffer.c (c04d2abc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/callchain.c (c04d3248)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
  - kernel/events/callchain.c:get_perf_callchain
```
```
In kernel/events/hw_breakpoint.c (c04d3f60)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
```
In kernel/events/uprobes.c (c04d7790)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_deny_signal
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:get_utask
  - kernel/events/uprobes.c:uprobe_get_trap_addr
  - kernel/events/uprobes.c:get_xol_area
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:uprobe_mmap
```
```
In kernel/padata.c (c04d7e00)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In kernel/rseq.c (c04d9b64)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - kernel/rseq.c:__se_sys_rseq
  - kernel/rseq.c:__se_sys_rseq
  - kernel/rseq.c:__se_sys_rseq
  - kernel/rseq.c:__se_sys_rseq
  - kernel/rseq.c:__se_sys_rseq
  - kernel/rseq.c:__se_sys_rseq
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:perf_trace_rseq_update
  - kernel/rseq.c:trace_event_raw_event_rseq_update
```
```
In certs/system_keyring.c (c152c394)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
```
```
In certs/blacklist.c (c152c67c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - certs/blacklist.c:blacklist_init
```
```
In mm/filemap.c (c04e0aa0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:__generic_file_write_iter
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_write_check_limits
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:__lock_page
  - mm/filemap.c:__lock_page
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/mempool.c (c04e23dc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc
```
```
In mm/oom_kill.c (c04e4fc8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:dump_header
```
```
In mm/maccess.c (c04e60a8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strnlen_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe_user
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/page-writeback.c (c04e7ab0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/readahead.c (c04eacc8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (c04ed558)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
```
```
In mm/vmscan.c (c04f7744)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node_memcg
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/shmem.c (c04f9690)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/shmem.c:shmem_init_fs_context
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_charge
```
```
In mm/util.c (c04ffed0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/util.c:arch_pick_mmap_layout
  - mm/util.c:randomize_stack_top
  - mm/util.c:vma_is_stack_for_current
  - mm/util.c:memdup_user_nul
  - mm/util.c:vmemdup_user
  - mm/util.c:memdup_user
```
```
In mm/vmstat.c (c0502808)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/vmstat.c:quiet_vmstat
```
```
In mm/backing-dev.c (c0503324)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:bdi_register_va
```
```
In mm/mmu_context.c (c0504970)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/percpu.c (c0507388)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (c0509d54)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/compaction.c (c0511188)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_suitable
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:compact_unlock_should_abort
  - mm/compaction.c:compaction_deferred
  - mm/compaction.c:defer_compaction
```
```
In mm/vmacache.c (c0511a9c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/vmacache.c:vmacache_find
  - mm/vmacache.c:vmacache_update
```
```
In mm/gup.c (c05157c4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_locked
  - mm/gup.c:get_user_pages
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:get_dump_page
  - mm/gup.c:__mm_populate
  - mm/gup.c:populate_vma_page_range
  - mm/gup.c:__get_user_pages
```
```
In mm/highmem.c (c0516240)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In mm/memory.c (c051c290)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/memory.c:print_vma_addr
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:sync_mm_rss
```
```
In mm/mincore.c (c051c73c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/mincore.c:__se_sys_mincore
  - mm/mincore.c:__se_sys_mincore
  - mm/mincore.c:__se_sys_mincore
  - mm/mincore.c:__se_sys_mincore
  - mm/mincore.c:__se_sys_mincore
```
```
In mm/mlock.c (c051dd7c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
  - mm/mlock.c:sys_munlockall
  - mm/mlock.c:sys_munlockall
  - mm/mlock.c:__se_sys_mlockall
  - mm/mlock.c:__se_sys_mlockall
  - mm/mlock.c:__se_sys_mlockall
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:__se_sys_munlock
  - mm/mlock.c:__se_sys_munlock
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
  - mm/mlock.c:do_mlock
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mlock.c:mlock_fixup
```
```
In mm/mmap.c (c0522bec)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:mm_take_all_locks
  - mm/mmap.c:special_mapping_mremap
  - mm/mmap.c:may_expand_vm
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:__vm_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:unmapped_area_topdown
  - mm/mmap.c:unmapped_area
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__se_sys_old_mmap
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - mm/mmap.c:__se_sys_brk
  - mm/mmap.c:__se_sys_brk
```
```
In mm/mprotect.c (c0523978)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/mprotect.c:__se_sys_mprotect
  - mm/mprotect.c:__se_sys_mprotect
  - mm/mprotect.c:__se_sys_mprotect
```
```
In mm/mremap.c (c05244d8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:vma_to_resize
  - mm/mremap.c:vma_to_resize
  - mm/mremap.c:vma_to_resize
```
```
In mm/msync.c (c0524a60)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/msync.c:__se_sys_msync
```
```
In mm/vmalloc.c (c052a84c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/page_alloc.c (c0534c10)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:warn_alloc
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:drain_local_pages
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:bad_page
```
```
In mm/madvise.c (c0537da4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/page_io.c (c053951c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/swap_state.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In mm/swapfile.c (c0540110)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/frontswap.c (c0540bf8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_shrink
```
```
In mm/ksm.c (c0545d58)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:run_store
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:unmerge_ksm_pages
```
```
In mm/slub.c (c0550388)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:bootstrap
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:flush_cpu_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:set_track
```
```
In mm/migrate.c (c05527e0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/memcontrol.c (c055c880)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:__unlock_page_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
```
In mm/swap_cgroup.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In mm/page_isolation.c (c055eeec)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/zbud.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In mm/zsmalloc.c (c0562314)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/cma.c (c0562f7c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/cma.c:cma_release
  - mm/cma.c:cma_alloc
```
```
In mm/balloon_compaction.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In mm/userfaultfd.c (c05641f4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/frame_vector.c (c0564c38)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/frame_vector.c:get_vaddr_frames
```
```
In mm/usercopy.c (c0565024)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/usercopy.c:check_stack_object
```
```
In mm/memfd.c (c0566fe8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - mm/memfd.c:__se_sys_memfd_create
```
```
In fs/open.c (c0569b64)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/open.c:__se_sys_close
  - fs/open.c:do_sys_open
  - fs/open.c:ksys_fchown
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/open.c:ksys_fchmod
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chroot
  - fs/open.c:__se_sys_fchdir
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/read_write.c (c056abb4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:__se_sys_sendfile64
  - fs/read_write.c:__se_sys_sendfile64
  - fs/read_write.c:__se_sys_sendfile64
  - fs/read_write.c:__se_sys_sendfile
  - fs/read_write.c:__se_sys_sendfile
  - fs/read_write.c:__se_sys_sendfile
  - fs/read_write.c:__se_sys_sendfile
  - fs/read_write.c:rw_copy_check_uvector
  - fs/read_write.c:rw_copy_check_uvector
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:kernel_write
  - fs/read_write.c:kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:new_sync_write
  - fs/read_write.c:kernel_read
  - fs/read_write.c:kernel_read
  - fs/read_write.c:__se_sys_llseek
```
```
In fs/file_table.c (c056e590)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
```
In fs/super.c (c056f448)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:sget
```
```
In fs/stat.c (c0573234)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat64
  - fs/stat.c:cp_new_stat64
  - fs/stat.c:cp_new_stat64
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
```
```
In fs/exec.c (c05742b0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/exec.c:set_binfmt
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
  - fs/exec.c:__do_execve_file
  - fs/exec.c:prepare_binprm
  - fs/exec.c:prepare_binprm
  - fs/exec.c:install_exec_creds
  - fs/exec.c:install_exec_creds
  - fs/exec.c:free_bprm
  - fs/exec.c:finalize_exec
  - fs/exec.c:finalize_exec
  - fs/exec.c:setup_new_exec
  - fs/exec.c:setup_new_exec
  - fs/exec.c:setup_new_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:do_open_execat
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:copy_strings
  - fs/exec.c:copy_strings
  - fs/exec.c:copy_strings
  - fs/exec.c:get_user_arg_ptr
  - fs/exec.c:get_user_arg_ptr
  - fs/exec.c:acct_arg_size
```
```
In fs/pipe.c (c0576c9c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:pipe_ioctl
  - fs/pipe.c:pipe_ioctl
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_wait
```
```
In fs/namei.c (c0581240)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/namei.c:readlink_copy
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_filp_open
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
  - fs/namei.c:nd_jump_link
  - fs/namei.c:set_root
  - fs/namei.c:restore_nameidata
  - fs/namei.c:getname_kernel
```
```
In fs/fcntl.c (c058238c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/fcntl.c:__se_sys_fcntl64
  - fs/fcntl.c:__se_sys_fcntl64
  - fs/fcntl.c:__se_sys_fcntl64
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_modown
```
```
In fs/ioctl.c (c0583b44)
Location: arch/arm/include/asm/thread_info.h:88
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
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:file_ioctl
  - fs/ioctl.c:file_ioctl
  - fs/ioctl.c:file_ioctl
  - fs/ioctl.c:file_ioctl
  - fs/ioctl.c:file_ioctl
  - fs/ioctl.c:file_ioctl
  - fs/ioctl.c:ioctl_preallocate
  - fs/ioctl.c:__generic_block_fiemap
  - fs/ioctl.c:fiemap_fill_next_extent
```
```
In fs/readdir.c (c05848e0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:__se_sys_getdents
  - fs/readdir.c:__se_sys_getdents
  - fs/readdir.c:__se_sys_getdents
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
```
```
In fs/select.c (c0586a8c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/select.c:__se_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:__se_sys_old_select
  - fs/select.c:__se_sys_pselect6_time32
  - fs/select.c:__se_sys_pselect6_time32
  - fs/select.c:__se_sys_pselect6_time32
  - fs/select.c:__se_sys_pselect6_time32
  - fs/select.c:__se_sys_pselect6
  - fs/select.c:__se_sys_pselect6
  - fs/select.c:__se_sys_pselect6
  - fs/select.c:__se_sys_pselect6
  - fs/select.c:kern_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/select.c:do_select
  - fs/select.c:poll_select_finish
  - fs/select.c:poll_select_finish
  - fs/select.c:poll_select_finish
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - fs/select.c:select_estimate_accuracy
```
```
In fs/dcache.c (c058b928)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
```
```
In fs/inode.c (c058d164)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/inode.c:vfs_ioc_fssetxattr_check
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:inode_owner_or_capable
  - fs/inode.c:inode_init_owner
  - fs/inode.c:__wait_on_freeing_inode
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:invalidate_inodes
  - fs/inode.c:evict_inodes
```
```
In fs/attr.c (c058f9ec)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
```
```
In fs/file.c (c0591c78)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:f_dupfd
  - fs/file.c:ksys_dup
  - fs/file.c:__se_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:ksys_dup3
  - fs/file.c:replace_fd
  - fs/file.c:get_close_on_exec
  - fs/file.c:set_close_on_exec
  - fs/file.c:__fget
  - fs/file.c:__close_fd_get_file
  - fs/file.c:put_unused_fd
  - fs/file.c:get_unused_fd_flags
  - fs/file.c:reset_files_struct
```
```
In fs/filesystems.c (c05922ac)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/filesystems.c:__se_sys_sysfs
```
```
In fs/namespace.c (c0598ad4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:our_mnt
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:copy_mount_options
  - fs/namespace.c:copy_mount_options
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:is_current_mnt_ns
  - fs/namespace.c:__is_local_mountpoint
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mnt_init
```
```
In fs/seq_file.c (c0599f5c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
```
```
In fs/xattr.c (c059c2b8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:__se_sys_flistxattr
  - fs/xattr.c:listxattr
  - fs/xattr.c:__se_sys_fgetxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:__se_sys_fsetxattr
  - fs/xattr.c:setxattr
```
```
In fs/libfs.c (c059db48)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/libfs.c:alloc_anon_inode
  - fs/libfs.c:simple_attr_write
  - fs/libfs.c:simple_write_to_buffer
  - fs/libfs.c:simple_read_from_buffer
  - fs/libfs.c:scan_positives
```
```
In fs/fs-writeback.c (c05a5424)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:sb_mark_inode_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
```
```
In fs/splice.c (c05ab1ec)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
  - fs/splice.c:add_to_pipe
  - fs/splice.c:splice_to_pipe
```
```
In fs/utimes.c (c05abe4c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:__se_sys_utime32
  - fs/utimes.c:__se_sys_utime32
  - fs/utimes.c:__se_sys_utime32
  - fs/utimes.c:__se_sys_utime32
```
```
In fs/d_path.c (c05aceb0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/d_path.c:__se_sys_getcwd
  - fs/d_path.c:__se_sys_getcwd
  - fs/d_path.c:d_path
```
```
In fs/fs_struct.c (c05ad24c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/fs_struct.c:current_umask
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:unshare_fs_struct
```
```
In fs/statfs.c (c05ada0c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
```
```
In fs/fs_pin.c (c05ae368)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_kill
  - fs/fs_pin.c:pin_kill
```
```
In fs/nsfs.c (c05ae850)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:open_related_ns
```
```
In fs/fs_context.c (c05af178)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/fsopen.c (c05b0984)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/fsopen.c:__se_sys_fspick
  - fs/fsopen.c:__se_sys_fsopen
  - fs/fsopen.c:fscontext_read
```
```
In fs/buffer.c (c05b7654)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/buffer.c:__se_sys_bdflush
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (c05b9144)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:ioctl_by_bdev
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:__blkdev_direct_IO
  - fs/block_dev.c:blkdev_bio_end_io
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:__blkdev_direct_IO_simple
  - fs/block_dev.c:blkdev_bio_end_io_simple
```
```
In fs/direct-io.c (c05bcda0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (c05bd790)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/mpage.c:mpage_alloc
```
```
In fs/notify/dnotify/dnotify.c (c05c23ec)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/inotify/inotify_fsnotify.c (c05c285c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/inotify/inotify_user.c (c05c2e28)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify.c (c05c450c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (c05c56c4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_ioctl
  - fs/notify/fanotify/fanotify_user.c:fanotify_ioctl
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (c05c85b8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/eventpoll.c:__se_sys_epoll_pwait
  - fs/eventpoll.c:__se_sys_epoll_pwait
  - fs/eventpoll.c:__se_sys_epoll_pwait
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:ep_loop_check_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:reverse_path_check_proc
```
```
In fs/signalfd.c (c05c908c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/signalfd.c:__se_sys_signalfd
  - fs/signalfd.c:__se_sys_signalfd4
  - fs/signalfd.c:do_signalfd4
  - fs/signalfd.c:do_signalfd4
  - fs/signalfd.c:do_signalfd4
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_read
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (c05c9868)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (c05caed8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (c05cdc5c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/userfaultfd.c:__se_sys_userfaultfd
  - fs/userfaultfd.c:__se_sys_userfaultfd
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:userfaultfd_event_wait_completion
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/aio.c (c05d1c5c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_getevents_time32
  - fs/aio.c:__se_sys_io_pgetevents_time32
  - fs/aio.c:__se_sys_io_pgetevents_time32
  - fs/aio.c:__se_sys_io_pgetevents_time32
  - fs/aio.c:__se_sys_io_pgetevents
  - fs/aio.c:__se_sys_io_pgetevents
  - fs/aio.c:__se_sys_io_pgetevents
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:aio_prep_rw
  - fs/aio.c:__se_sys_io_destroy
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:aio_read_events
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_setup_ring
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (c05d78d0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_uring_setup
  - fs/io_uring.c:io_uring_setup
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/io_uring.c:io_account_mem
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_prep_rw
  - fs/io_uring.c:io_iopoll_getevents
```
```
In fs/crypto/keyring.c (c05dadfc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:format_mk_user_description
```
```
In fs/crypto/policy.c (c05dcfb0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (c05ddff4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/measure.c (c05dea0c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
```
```
In fs/verity/signature.c (c1538238)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/verity/signature.c:fsverity_init_signature
```
```
In fs/locks.c (c05e3270)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk64
  - fs/locks.c:fcntl_setlk64
  - fs/locks.c:fcntl_getlk64
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlk
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:leases_conflict
  - fs/locks.c:time_out_leases
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:locks_mandatory_area
  - fs/locks.c:locks_mandatory_locked
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_insert_global_locks
  - fs/locks.c:lease_alloc
  - fs/locks.c:lease_setup
  - fs/locks.c:flock64_to_posix_lock
  - fs/locks.c:flock_make_lock
  - fs/locks.c:locks_get_lock_context
```
```
In fs/binfmt_elf.c (c05e8fa0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:fill_psinfo
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:set_brk
```
```
In fs/binfmt_elf_fdpic.c (c05e9a20)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump
  - fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump
  - fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump
  - fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump
  - fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump
  - fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump
  - fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump
  - fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump
  - fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump
  - fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump
  - fs/binfmt_elf_fdpic.c:fill_psinfo
  - fs/binfmt_elf_fdpic.c:elf_fdpic_map_file
  - fs/binfmt_elf_fdpic.c:elf_fdpic_map_file
  - fs/binfmt_elf_fdpic.c:elf_fdpic_map_file
  - fs/binfmt_elf_fdpic.c:elf_fdpic_map_file
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:load_elf_fdpic_binary
  - fs/binfmt_elf_fdpic.c:load_elf_fdpic_binary
  - fs/binfmt_elf_fdpic.c:load_elf_fdpic_binary
  - fs/binfmt_elf_fdpic.c:load_elf_fdpic_binary
  - fs/binfmt_elf_fdpic.c:load_elf_fdpic_binary
  - fs/binfmt_elf_fdpic.c:load_elf_fdpic_binary
```
```
In fs/binfmt_flat.c (c05ed848)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/binfmt_flat.c:load_flat_binary
  - fs/binfmt_flat.c:load_flat_binary
  - fs/binfmt_flat.c:load_flat_binary
  - fs/binfmt_flat.c:load_flat_binary
  - fs/binfmt_flat.c:load_flat_binary
  - fs/binfmt_flat.c:load_flat_binary
  - fs/binfmt_flat.c:load_flat_binary
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:calc_reloc
  - fs/binfmt_flat.c:calc_reloc
  - fs/binfmt_flat.c:create_flat_tables
  - fs/binfmt_flat.c:create_flat_tables
  - fs/binfmt_flat.c:create_flat_tables
  - fs/binfmt_flat.c:create_flat_tables
  - fs/binfmt_flat.c:create_flat_tables
  - fs/binfmt_flat.c:create_flat_tables
  - fs/binfmt_flat.c:create_flat_tables
  - fs/binfmt_flat.c:create_flat_tables
  - fs/binfmt_flat.c:create_flat_tables
  - fs/binfmt_flat.c:create_flat_tables
  - fs/binfmt_flat.c:create_flat_tables
  - fs/binfmt_flat.c:create_flat_tables
  - fs/binfmt_flat.c:create_flat_tables
  - fs/binfmt_flat.c:create_flat_tables
  - fs/binfmt_flat.c:create_flat_tables
  - fs/binfmt_flat.c:flat_core_dump
```
```
In fs/posix_acl.c (c05eff34)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_to_user
  - fs/posix_acl.c:posix_acl_fix_xattr_from_user
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
```
```
In fs/coredump.c (c05f06fc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:umh_pipe_setup
  - fs/coredump.c:zap_process
  - fs/coredump.c:format_corename
  - fs/coredump.c:format_corename
  - fs/coredump.c:format_corename
  - fs/coredump.c:format_corename
  - fs/coredump.c:format_corename
  - fs/coredump.c:format_corename
  - fs/coredump.c:format_corename
  - fs/coredump.c:format_corename
  - fs/coredump.c:format_corename
  - fs/coredump.c:format_corename
  - fs/coredump.c:format_corename
```
```
In fs/drop_caches.c (c05f1d80)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In fs/fhandle.c (c05f215c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_open_by_handle_at
  - fs/fhandle.c:__se_sys_open_by_handle_at
  - fs/fhandle.c:__se_sys_open_by_handle_at
  - fs/fhandle.c:do_sys_name_to_handle
  - fs/fhandle.c:do_sys_name_to_handle
  - fs/fhandle.c:do_sys_name_to_handle
  - fs/fhandle.c:do_sys_name_to_handle
```
```
In fs/iomap/buffered-io.c (c05f4094)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In fs/iomap/direct-io.c (c05f64ec)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In fs/quota/quota.c (c05fe628)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
```
```
In fs/quota/netlink.c (c05ff2a0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/quota/netlink.c:quota_send_warning
```
```
In fs/proc/task_mmu.c (c06006d8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/inode.c (c0602194)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_reg_get_unmapped_area
```
```
In fs/proc/root.c (c0602864)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_reconfigure
  - fs/proc/root.c:proc_fill_super
```
```
In fs/proc/base.c (c060421c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:mem_rw
  - fs/proc/base.c:mem_rw
```
```
In fs/proc/fd.c (c060b8c4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
```
```
In fs/proc/loadavg.c (c060ca20)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/proc/loadavg.c:loadavg_proc_show
```
```
In fs/proc/version.c (c060dc94)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/proc/version.c:version_proc_show
```
```
In fs/proc/self.c (c060e314)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (c060e520)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In fs/proc/proc_sysctl.c (c060f588)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:sysctl_perm
```
```
In fs/proc/vmcore.c (c0611ec0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In fs/proc/page.c (c0612fa4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
  - fs/proc/page.c:kpagecount_read
```
```
In fs/kernfs/dir.c (c0616898)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_remove_self
```
```
In fs/kernfs/file.c (c0617ae8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
```
```
In fs/configfs/file.c (c061ad68)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_write_file
```
```
In fs/devpts/inode.c (c061f68c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:parse_mount_options
  - fs/devpts/inode.c:parse_mount_options
  - fs/devpts/inode.c:parse_mount_options
```
```
In fs/dcookies.c (c061fdac)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/dcookies.c:__se_sys_lookup_dcookie
```
```
In fs/ext4/balloc.c (c0620008)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/dir.c (c0622938)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/ext4_jbd2.c (c0624244)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_stop
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/extents.c (c062db94)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/extents_status.c (c0631820)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/fsmap.c (c0633730)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/fsync.c (c0633d78)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (c06369b4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (c063952c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (c0645cec)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:__ext4_journalled_invalidatepage
  - fs/ext4/inode.c:ext4_alloc_da_blocks
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (c064d43c)
Location: arch/arm/include/asm/thread_info.h:88
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
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/ext4/ioctl.c:ext4_getfsmap_format
```
```
In fs/ext4/mballoc.c (c0655b28)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_release_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_release_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/namei.c (c0663a88)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_tmpfile
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_create
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:__ext4_read_dirblock
```
```
In fs/ext4/super.c (c067d834)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:ext4_nfs_commit_metadata
  - fs/ext4/super.c:ext4_drop_inode
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_warning_inode
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
  - fs/ext4/super.c:__ext4_error
```
```
In fs/jbd2/transaction.c (c068e26c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_lock_updates
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:start_this_handle
  - fs/jbd2/transaction.c:wait_transaction_locked
```
```
In fs/jbd2/commit.c (c0690cb4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
```
In fs/jbd2/checkpoint.c (c0693bac)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (c0699190)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ramfs/file-mmu.c (c06a1fc4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/ramfs/file-mmu.c:ramfs_mmu_get_unmapped_area
```
```
In fs/fat/dir.c (c06a5e68)
Location: arch/arm/include/asm/thread_info.h:88
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
In fs/fat/fatent.c (c06a7eec)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
```
```
In fs/fat/file.c (c06a8acc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fat/inode.c (c06aa900)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
  - fs/fat/inode.c:parse_options
```
```
In fs/ecryptfs/file.c (c06afed8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In fs/ecryptfs/main.c (c06b278c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_get_lower_file
```
```
In fs/ecryptfs/read_write.c (c06b411c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In fs/ecryptfs/kthread.c (c06b9f6c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In fs/ecryptfs/messaging.c (c06baa44)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
```
```
In fs/ecryptfs/miscdev.c (c06bb494)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/exportfs/expfs.c (c06bb968)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:get_name
```
```
In fs/fuse/dev.c (c06be570)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dev.c:fuse_get_req
```
```
In fs/fuse/dir.c (c06c56e4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (c06c8938)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_direct_io
```
```
In fs/fuse/inode.c (c06cc100)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/fuse/readdir.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In fs/debugfs/inode.c (c06d16d4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/debugfs/inode.c:debugfs_parse_options
```
```
In fs/tracefs/inode.c (c06d3f0c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
```
```
In fs/pstore/platform.c (c06d5480)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
```
```
In fs/pstore/ram.c (c06d5d4c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/pstore/ram.c:ramoops_pstore_write
```
```
In fs/pstore/ram_core.c (c06d77e8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/pstore/ram_core.c:persistent_ram_write_user
  - fs/pstore/ram_core.c:persistent_ram_update_user
```
```
In fs/efivarfs/file.c (c06d84d0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In ipc/util.c (c06d900c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
  - ipc/util.c:sysvipc_proc_open
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipc_update_perm
  - ipc/util.c:ipc_update_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:kernel_to_ipc64_perm
  - ipc/util.c:ipcperms
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In ipc/msgutil.c (c06da554)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:load_msg
```
```
In ipc/msg.c (c06dacd4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - ipc/msg.c:do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/msg.c:ksys_msgsnd
  - ipc/msg.c:ksys_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:ksys_msgctl
  - ipc/msg.c:ksys_msgctl
  - ipc/msg.c:ksys_msgctl
  - ipc/msg.c:copy_msqid_from_user
  - ipc/msg.c:copy_msqid_from_user
  - ipc/msg.c:copy_msqid_to_user
  - ipc/msg.c:copy_msqid_to_user
  - ipc/msg.c:ksys_msgget
```
```
In ipc/sem.c (c06dfea4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:find_alloc_undo
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:copy_semid_from_user
  - ipc/sem.c:copy_semid_from_user
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:copy_semid_to_user
  - ipc/sem.c:copy_semid_to_user
  - ipc/sem.c:ksys_semget
```
```
In ipc/shm.c (c06e1f84)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:do_shmat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmget
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:__shm_open
```
```
In ipc/ipc_sysctl.c (c06e21d4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
  - ipc/ipc_sysctl.c:proc_ipc_doulongvec_minmax
  - ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax_orphans
  - ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax
```
```
In ipc/mqueue.c (c06e4e44)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_getsetattr
  - ipc/mqueue.c:__se_sys_mq_getsetattr
  - ipc/mqueue.c:__se_sys_mq_getsetattr
  - ipc/mqueue.c:__se_sys_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:__se_sys_mq_open
  - ipc/mqueue.c:__se_sys_mq_open
  - ipc/mqueue.c:__se_sys_mq_open
  - ipc/mqueue.c:mqueue_flush_file
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_get_inode
  - ipc/mqueue.c:mqueue_get_inode
  - ipc/mqueue.c:mqueue_get_inode
```
```
In ipc/namespace.c (c06e54e4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:copy_ipcs
```
```
In ipc/mq_sysctl.c (c06e57fc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - ipc/mq_sysctl.c:proc_mq_dointvec_minmax
  - ipc/mq_sysctl.c:proc_mq_dointvec
```
```
In security/keys/gc.c (c06e5cf8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/keys/key.c (c06e6288)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (c06e8d1c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/keyring.c:keyring_search
  - security/keys/keyring.c:keyring_read_iterator
  - security/keys/keyring.c:keyring_read_iterator
  - security/keys/keyring.c:key_set_index_key
  - security/keys/keyring.c:keyring_instantiate
```
```
In security/keys/keyctl.c (c06eb318)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__se_sys_add_key
```
```
In security/keys/process_keys.c (c06ec844)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_process_keyrings_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (c06ecb78)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (c06edd2c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_read
```
```
In security/keys/user_defined.c (c06edff4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_read
```
```
In security/keys/persistent.c (c06ee90c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/keys/dh.c (c06ef5f4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/keys/dh.c:keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute_kdf
```
```
In security/keys/keyctl_pkey.c (c06efc1c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
```
```
In security/keys/big_key.c (c06f04f8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_read
```
```
In security/keys/trusted.c (c06f252c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (c06f34fc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
```
In security/commoncap.c (c06f435c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/commoncap.c:cap_vm_enough_memory
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:rootid_owns_currentns
  - security/commoncap.c:cap_capset
  - security/commoncap.c:cap_ptrace_traceme
  - security/commoncap.c:cap_ptrace_access_check
```
```
In security/security.c (c06fb0d4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/security.c:security_socket_getpeersec_stream
  - security/security.c:security_setprocattr
  - security/security.c:security_getprocattr
  - security/security.c:security_mmap_file
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_init
```
```
In security/selinux/hooks.c (c1542f48)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_init
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_bpf_prog
  - security/selinux/hooks.c:selinux_bpf_map
  - security/selinux/hooks.c:selinux_bpf
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_sem_associate
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_sem_alloc_security
  - security/selinux/hooks.c:selinux_shm_associate
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_shm_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_msgsnd
  - security/selinux/hooks.c:selinux_msg_queue_associate
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:selinux_msg_queue_alloc_security
  - security/selinux/hooks.c:ipc_has_perm
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_tun_dev_open
  - security/selinux/hooks.c:selinux_tun_dev_attach_queue
  - security/selinux/hooks.c:selinux_tun_dev_create
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:selinux_secmark_relabel_packet
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_socket_create
  - security/selinux/hooks.c:sock_has_perm
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_setscheduler
  - security/selinux/hooks.c:selinux_task_getioprio
  - security/selinux/hooks.c:selinux_task_setnice
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_module_request
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_kernel_act_as
  - security/selinux/hooks.c:selinux_task_alloc
  - security/selinux/hooks.c:selinux_file_receive
  - security/selinux/hooks.c:selinux_file_set_fowner
  - security/selinux/hooks.c:selinux_file_fcntl
  - security/selinux/hooks.c:selinux_file_lock
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:selinux_mmap_file
  - security/selinux/hooks.c:file_map_prot_check
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_alloc_security
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:has_cap_mac_admin
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_move_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_committed_creds
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:ptrace_parent_sid
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_ptrace_traceme
  - security/selinux/hooks.c:selinux_ptrace_access_check
  - security/selinux/hooks.c:selinux_binder_transaction
  - security/selinux/hooks.c:selinux_binder_set_context_mgr
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
```
In security/selinux/selinuxfs.c (c0709c0c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_read_policy
  - security/selinux/selinuxfs.c:sel_open_policy
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/selinuxfs.c:sel_write_enforce
```
```
In security/selinux/ss/services.c (c071ba88)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_sid_mls_copy
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_bounded_transition
```
```
In security/selinux/ss/status.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In security/selinux/xfrm.c (c071ef20)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_delete
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
```
In security/smack/smack_lsm.c (c1543580)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_setprocattr
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_netlabel
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
```
In security/smack/smack_access.c (c0726350)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_privileged
  - security/smack/smack_access.c:smk_curacc
```
```
In security/smack/smackfs.c (c07295f8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_relabel_self
  - security/smack/smackfs.c:relabel_self_seq_next
  - security/smack/smackfs.c:relabel_self_seq_start
  - security/smack/smackfs.c:smk_write_load_self2
  - security/smack/smackfs.c:smk_write_load_self
  - security/smack/smackfs.c:load_self_seq_next
  - security/smack/smackfs.c:load_self_seq_start
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/lsm_audit.c (c072a85c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
  - security/lsm_audit.c:dump_common_audit_data
  - security/lsm_audit.c:dump_common_audit_data
```
```
In security/tomoyo/audit.c (c072a914)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/common.c (c072f7c4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
```
```
In security/tomoyo/condition.c (c0731708)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
```
```
In security/tomoyo/domain.c (c0732700)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
```
In security/tomoyo/memory.c (c0735b00)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_warn_oom
```
```
In security/tomoyo/network.c (c0737674)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
```
In security/tomoyo/realpath.c (c07378a4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
```
```
In security/tomoyo/securityfs_if.c (c0737e2c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
```
In security/tomoyo/tomoyo.c (c1543da8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_init
  - security/tomoyo/tomoyo.c:tomoyo_task_alloc
  - security/tomoyo/tomoyo.c:tomoyo_bprm_committed_creds
  - security/tomoyo/tomoyo.c:tomoyo_cred_prepare
  - security/tomoyo/tomoyo.c:tomoyo_domain
```
```
In security/tomoyo/util.c (c0739fd8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_get_exe
```
```
In security/apparmor/apparmorfs.c (c073a2c8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:attr_write
  - security/apparmor/apparmorfs.c:attr_write
  - security/apparmor/apparmorfs.c:attr_read
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/audit.c (c073f100)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit
```
```
In security/apparmor/task.c (c073f990)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/path.c (c0742138)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In security/apparmor/domain.c (c07461a4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/apparmor/policy.c (c0748080)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
```
```
In security/apparmor/policy_unpack.c (c0749664)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In security/apparmor/procattr.c (c074b674)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_setprocattr_changehat
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (c1544528)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committing_creds
  - security/apparmor/lsm.c:apparmor_bprm_committing_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_task_alloc
```
```
In security/apparmor/resource.c (c074fb04)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
```
```
In security/apparmor/file.c (c0750300)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_compute_fperms
  - security/apparmor/file.c:file_audit_cb
```
```
In security/apparmor/label.c (c0754be8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
```
```
In security/apparmor/net.c (c07575c4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (c0758fa8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In security/yama/yama_lsm.c (c075a3d0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In security/lockdown/lockdown.c (c075b334)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In security/device_cgroup.c (c075b55c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/device_cgroup.c:__devcgroup_check_permission
```
```
In security/integrity/iint.c (c075c350)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
```
In security/integrity/integrity_audit.c (c075c3fc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In security/integrity/digsig.c (c1544b78)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_init_keyring
```
```
In security/integrity/ima/ima_main.c (c075e794)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_main.c:ima_post_read_file
  - security/integrity/ima/ima_main.c:ima_post_read_file
  - security/integrity/ima/ima_main.c:ima_file_check
  - security/integrity/ima/ima_main.c:ima_file_check
  - security/integrity/ima/ima_main.c:ima_bprm_check
  - security/integrity/ima/ima_main.c:ima_bprm_check
  - security/integrity/ima/ima_main.c:ima_file_mmap
  - security/integrity/ima/ima_main.c:ima_file_mmap
```
```
In security/integrity/ima/ima_api.c (c0760474)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_audit_measurement
```
```
In security/integrity/ima/ima_policy.c (c0760c60)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
```
In security/integrity/ima/ima_appraise.c (c0763260)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In security/integrity/evm/evm_secfs.c (c07656bc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In crypto/api.c (c0766694)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/ablkcipher.c (c076a90c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
```
```
In crypto/blkcipher.c (c076b5e0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
```
```
In crypto/skcipher.c (c076d128)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
```
```
In crypto/algboss.c (c0772738)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/bio.c (c07885d4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
  - block/bio.c:bio_endio
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:update_io_ticks
  - block/bio.c:bio_uncopy_user
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (c078c4e8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - block/blk-core.c:blk_start_plug
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-core.c:perf_trace_block_split
  - block/blk-core.c:perf_trace_block_unplug
  - block/blk-core.c:perf_trace_block_plug
  - block/blk-core.c:perf_trace_block_get_rq
  - block/blk-core.c:perf_trace_block_bio_queue
  - block/blk-core.c:perf_trace_block_bio_merge
  - block/blk-core.c:perf_trace_block_bio_bounce
  - block/blk-core.c:perf_trace_block_rq
  - block/blk-core.c:trace_event_raw_event_block_split
  - block/blk-core.c:trace_event_raw_event_block_unplug
  - block/blk-core.c:trace_event_raw_event_block_plug
  - block/blk-core.c:trace_event_raw_event_block_get_rq
  - block/blk-core.c:trace_event_raw_event_block_bio_queue
  - block/blk-core.c:trace_event_raw_event_block_bio_merge
  - block/blk-core.c:trace_event_raw_event_block_bio_bounce
  - block/blk-core.c:trace_event_raw_event_block_rq
```
```
In block/blk-ioc.c (c079554c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
```
```
In block/blk-map.c (c0795dc8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In block/blk-merge.c (c0796d44)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-softirq.c (c07985d8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - block/blk-softirq.c:__blk_complete_request
```
```
In block/blk-mq.c (c079d498)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_complete_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (c07a018c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (c07a1c30)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
```
In block/ioctl.c (c07a38a4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_pr_preempt
  - block/ioctl.c:put_uint
  - block/ioctl.c:put_uint
  - block/ioctl.c:put_int
  - block/ioctl.c:put_int
  - block/ioctl.c:put_ushort
  - block/ioctl.c:put_ushort
  - block/ioctl.c:blk_ioctl_discard
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/genhd.c (c07a5d38)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_dec_in_flight
  - block/genhd.c:part_inc_in_flight
  - block/genhd.c:part_inc_in_flight
```
```
In block/ioprio.c (c07a9020)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_set
  - block/ioprio.c:__se_sys_ioprio_set
  - block/ioprio.c:__se_sys_ioprio_set
  - block/ioprio.c:__se_sys_ioprio_set
```
```
In block/blk-rq-qos.c (c07b29d0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_qos_wait
  - block/blk-rq-qos.c:rq_qos_wait
```
```
In block/bounce.c (c07b37b4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/scsi_ioctl.c (c07b484c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (c07b511c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_scsi_complete_rq
  - block/bsg.c:bsg_scsi_fill_hdr
```
```
In block/bsg-lib.c (c07b5b80)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_transport_complete_rq
```
```
In block/blk-cgroup.c (c07b9308)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
```
```
In block/blk-iocost.c (c07c32f4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_activate
```
```
In block/blk-zoned.c (c07c7870)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In block/blk-wbt.c (c07c8c68)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_inflight_cb
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:rwb_trace_step
```
```
In block/blk-mq-debugfs.c (c07cad28)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In block/sed-opal.c (c07cea24)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - block/sed-opal.c:write_shadow_mbr
```
```
In lib/bitmap.c (c07d23ec)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parse_user
  - lib/bitmap.c:__bitmap_parse
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/scatterlist.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In lib/iov_iter.c (c07d403c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:iov_iter_init
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
```
```
In lib/kfifo.c (c07da7d4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_from_user
  - lib/kfifo.c:kfifo_copy_from_user
```
```
In lib/rhashtable.c (c07dc870)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/usercopy.c (c07dd994)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/kstrtox.c (c07e0628)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtos8_from_user
  - lib/kstrtox.c:kstrtou8_from_user
  - lib/kstrtox.c:kstrtos16_from_user
  - lib/kstrtox.c:kstrtou16_from_user
  - lib/kstrtox.c:kstrtoint_from_user
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/kstrtox.c:kstrtol_from_user
  - lib/kstrtox.c:kstrtoul_from_user
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:kstrtoull_from_user
  - lib/kstrtox.c:kstrtobool_from_user
```
```
In lib/genalloc.c (c07eabb0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_free_owner
  - lib/genalloc.c:gen_pool_alloc_algo_owner
```
```
In lib/syscall.c (c0808704)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - lib/syscall.c:task_current_syscall
```
```
In lib/dynamic_debug.c (c08088c8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - lib/dynamic_debug.c:dynamic_emit_prefix
```
```
In lib/nlattr.c (c080ac9c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_validate_parse
  - lib/nlattr.c:validate_nla
```
```
In lib/strncpy_from_user.c (c080f620)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
  - lib/strncpy_from_user.c:strncpy_from_user
  - lib/strncpy_from_user.c:strncpy_from_user
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (c080f844)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
  - lib/strnlen_user.c:strnlen_user
  - lib/strnlen_user.c:strnlen_user
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/irqchip/irq-hip04.c (c0813e9c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/irqchip/irq-hip04.c:hip04_irq_starting_cpu
```
```
In drivers/irqchip/irq-gic.c (c0815c48)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_migrate_target
  - drivers/irqchip/irq-gic.c:gic_cpu_init
```
```
In drivers/irqchip/irq-gic-v3.c (c154bb90)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_cpu_sys_reg_init
  - drivers/irqchip/irq-gic-v3.c:gic_populate_rdist
  - drivers/irqchip/irq-gic-v3.c:__gic_populate_rdist
  - drivers/irqchip/irq-gic-v3.c:__gic_populate_rdist
```
```
In drivers/irqchip/irq-gic-v3-its.c (c081cbec)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_restore_enable
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
```
```
In drivers/irqchip/irq-gic-v4.c (c081d568)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v4.c:its_alloc_vcpu_irqs
```
```
In drivers/irqchip/irq-partition-percpu.c (c081de54)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/irqchip/irq-partition-percpu.c:partition_handle_irq
  - drivers/irqchip/irq-partition-percpu.c:partition_irq_get_irqchip_state
  - drivers/irqchip/irq-partition-percpu.c:partition_irq_set_irqchip_state
  - drivers/irqchip/irq-partition-percpu.c:partition_irq_unmask
  - drivers/irqchip/irq-partition-percpu.c:partition_irq_mask
```
```
In drivers/irqchip/irq-armada-370-xp.c (c081e754)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_handle_cascade_irq
  - drivers/irqchip/irq-armada-370-xp.c:armada_xp_mpic_perf_init
```
```
In drivers/gpio/gpiolib.c (c0862364)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_ioctl
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/gpio/gpio-mvebu.c (c086b450)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_write_edge_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_write_edge_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_read_edge_mask
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_read_edge_mask
```
```
In drivers/gpio/gpio-mxc.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In drivers/pci/access.c (c0877598)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_wait_cfg
  - drivers/pci/access.c:pci_wait_cfg
```
```
In drivers/pci/search.c (c08880dc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/pci/search.c:pci_get_slot
  - drivers/pci/search.c:pci_find_next_bus
```
```
In drivers/pci/vpd.c (c088b9bc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/pci/proc.c (c08907a8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
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
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/pci/quirks.c (c0892ea4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_do_fixups
```
```
In drivers/pci/pcie/aer.c (c089c984)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_error
```
```
In drivers/pci/syscall.c (c08a3254)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/pci/syscall.c:__se_sys_pciconfig_write
  - drivers/pci/syscall.c:__se_sys_pciconfig_write
  - drivers/pci/syscall.c:__se_sys_pciconfig_write
  - drivers/pci/syscall.c:__se_sys_pciconfig_write
  - drivers/pci/syscall.c:__se_sys_pciconfig_write
  - drivers/pci/syscall.c:__se_sys_pciconfig_write
  - drivers/pci/syscall.c:__se_sys_pciconfig_read
  - drivers/pci/syscall.c:__se_sys_pciconfig_read
  - drivers/pci/syscall.c:__se_sys_pciconfig_read
  - drivers/pci/syscall.c:__se_sys_pciconfig_read
  - drivers/pci/syscall.c:__se_sys_pciconfig_read
  - drivers/pci/syscall.c:__se_sys_pciconfig_read
  - drivers/pci/syscall.c:__se_sys_pciconfig_read
  - drivers/pci/syscall.c:__se_sys_pciconfig_read
  - drivers/pci/syscall.c:__se_sys_pciconfig_read
  - drivers/pci/syscall.c:__se_sys_pciconfig_read
  - drivers/pci/syscall.c:__se_sys_pciconfig_read
  - drivers/pci/syscall.c:__se_sys_pciconfig_read
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In drivers/rapidio/rio.c (c08c0a20)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_get_asm
```
```
In drivers/video/fbdev/core/fbmem.c (c08c8c54)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/video/fbdev/core/fbcmap.c (c08cbd08)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
```
```
In drivers/video/fbdev/core/fbcon.c (c08d58ec)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
```
```
In drivers/video/fbdev/imsttfb.c (c08dd644)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
```
```
In drivers/video/fbdev/amba-clcd.c (c08df508)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_enable
  - drivers/video/fbdev/amba-clcd.c:clcdfb_disable
```
```
In drivers/clk/clk.c (c08e8000)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_enable_unlock
  - drivers/clk/clk.c:clk_enable_lock
  - drivers/clk/clk.c:clk_enable_lock
  - drivers/clk/clk.c:clk_prepare_lock
  - drivers/clk/clk.c:clk_prepare_lock
```
```
In drivers/dma/mv_xor.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In drivers/dma/ipu/ipu_irq.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In drivers/dma/tegra20-apb-dma.c (c092a404)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_isr
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_tasklet
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In drivers/regulator/core.c (c094c654)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_dependent
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/regulator/core.c:regulator_lock_recursive
```
```
In drivers/tty/tty_io.c (c095cde0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_write
```
```
In drivers/tty/n_tty.c (c095f058)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
```
In drivers/tty/tty_ioctl.c (c0963c54)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
```
```
In drivers/tty/tty_port.c (c0965ef8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
```
```
In drivers/tty/tty_ldsem.c (c0e9eba0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/tty/tty_jobctrl.c (c09679a4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:no_tty
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
  - drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (c0968ea8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/tty/pty.c:ptm_open_peer
  - drivers/tty/pty.c:pty_get_pktmode
  - drivers/tty/pty.c:pty_get_pktmode
  - drivers/tty/pty.c:pty_set_pktmode
  - drivers/tty/pty.c:pty_set_pktmode
  - drivers/tty/pty.c:pty_get_lock
  - drivers/tty/pty.c:pty_get_lock
  - drivers/tty/pty.c:pty_set_lock
  - drivers/tty/pty.c:pty_set_lock
```
```
In drivers/tty/tty_audit.c (c0969304)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
  - drivers/tty/tty_audit.c:tty_audit_fork
  - drivers/tty/tty_audit.c:tty_audit_exit
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/tty/sysrq.c (c096a500)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
```
In drivers/tty/vt/vt_ioctl.c (c096ad84)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:reset_vc
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
```
```
In drivers/tty/vt/vc_screen.c (c096cebc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
```
```
In drivers/tty/vt/selection.c (c096de1c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_user
  - drivers/tty/vt/selection.c:sel_loadlut
```
```
In drivers/tty/vt/keyboard.c (c0972874)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kbkeycode_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kbkeycode_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kbkeycode_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
```
```
In drivers/tty/vt/consolemap.c (c09734c0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_old
```
```
In drivers/tty/vt/vt.c (c097b93c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:con_put_char
  - drivers/tty/vt/vt.c:con_write
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
```
```
In drivers/tty/hvc/hvc_console.c (c097cda0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/tty/serial/serial_core.c (c097f190)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/char/mem.c (c09a7090)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/char/mem.c:read_iter_zero
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
  - drivers/char/mem.c:read_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (c09ab344)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/random.c:mix_pool_bytes
  - drivers/char/random.c:__mix_pool_bytes
```
```
In drivers/char/virtio_console.c (c09aef70)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:port_fops_read
```
```
In drivers/char/hw_random/core.c (c09b09f8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/char/tpm/tpm-dev-common.c (c09b234c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
```
```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In drivers/char/tpm/tpm2-space.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In drivers/char/tpm/tpm-sysfs.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (c09b963c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/iommu/iommu.c (c09bc3a8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_aux_detach_device
  - drivers/iommu/iommu.c:iommu_aux_attach_device
  - drivers/iommu/iommu.c:report_iommu_fault
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
  - drivers/iommu/iommu.c:__iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
```
```
In drivers/iommu/io-pgtable-arm.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In drivers/iommu/tegra-smmu.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In drivers/connector/cn_proc.c (c09cda8c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In drivers/lightnvm/core.c (c09d0100)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
```
```
In drivers/base/core.c (c09d4804)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In drivers/base/syscore.c (c09d98cc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/devtmpfs.c (c09e2df0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In drivers/base/power/qos.c (c09e5594)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (c09e6298)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_callback
  - drivers/base/power/runtime.c:rpm_callback
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/main.c (c09ed26c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_run_callback
```
```
In drivers/base/power/wakeup.c (c09eefcc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/base/power/wakeup.c:pm_get_wakeup_count
  - drivers/base/power/wakeup.c:wakeup_source_report_event
```
```
In drivers/base/firmware_loader/main.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In drivers/base/regmap/regmap.c (c09f8a24)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/base/regmap/regcache.c (c09fdfc4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_cache_bypass
  - drivers/base/regmap/regcache.c:regcache_cache_only
  - drivers/base/regmap/regcache.c:regcache_drop_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync
```
```
In drivers/base/regmap/regmap-debugfs.c (c0a00afc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
```
```
In drivers/block/loop.c (c0a07ddc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
  - drivers/block/loop.c:loop_set_status64
  - drivers/block/loop.c:loop_set_status_old
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_kthread_worker_fn
```
```
In drivers/misc/vexpress-syscfg.c (c0a0a518)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec
```
```
In drivers/mfd/ab3100-core.c (c0a32e50)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
```
```
In drivers/mfd/aat2870-core.c (c0a366f8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/dma-buf/dma-buf.c (c0a3c020)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
```
In drivers/dma-buf/dma-fence.c (c0a3d364)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/sync_file.c (c0a409c8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
```
```
In drivers/dma-buf/sw_sync.c (c0a412a8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/dma-buf/udmabuf.c (c0a42520)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
```
```
In drivers/scsi/scsi_ioctl.c (c0a453ac)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/scsi_error.c (c0a495bc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (c0a4ab38)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
```
In drivers/scsi/scsi_devinfo.c (c0a53380)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
```
```
In drivers/scsi/scsi_proc.c (c0a53f18)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
```
```
In drivers/scsi/sd_zbc.c (c0a5d4f0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
```
```
In drivers/scsi/sr.c (c0a5e534)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/scsi/sg.c (c0a64b78)
Location: arch/arm/include/asm/thread_info.h:88
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
  - drivers/scsi/sg.c:sg_new_write
  - drivers/scsi/sg.c:sg_new_write
  - drivers/scsi/sg.c:sg_new_write
  - drivers/scsi/sg.c:sg_new_write
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_check_file_access
  - drivers/scsi/sg.c:sg_check_file_access
  - drivers/scsi/sg.c:sg_check_file_access
```
```
In drivers/ata/libata-core.c (c0a67eb4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-scsi.c (c0a7565c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
```
```
In drivers/ata/libata-eh.c (c0a79bd0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-eh.c:ata_eh_release
  - drivers/ata/libata-eh.c:ata_eh_acquire
```
```
In drivers/gpu/vga/vgaarb.c (c0a8d8e4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/gpu/vga/vgaarb.c:vga_get
```
```
In drivers/mtd/mtdchar.c (c0a95ed8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_readoob
  - drivers/mtd/mtdchar.c:mtdchar_readoob
  - drivers/mtd/mtdchar.c:mtdchar_readoob
  - drivers/mtd/mtdchar.c:mtdchar_writeoob
  - drivers/mtd/mtdchar.c:mtdchar_write
  - drivers/mtd/mtdchar.c:mtdchar_read
```
```
In drivers/mtd/nand/raw/nand_legacy.c (c0aa3234)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In drivers/spi/spi.c (c0ab340c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/net/phy/mdio_bus.c (c0abeea8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/net/tun.c (c0ac1ba4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_open
  - drivers/net/tun.c:tun_chr_fasync
  - drivers/net/tun.c:tun_set_ebpf
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/tun.c:tun_flow_update
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0accb64)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (c0aceeb0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_get
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_set
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_set
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad3f6c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_ioctl
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_ioctl
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_ioctl
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
```
```
In drivers/net/ppp/ppp_generic.c (c0add814)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_channel
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/cdrom/cdrom.c (c0ae71ec)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_play_blk
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_play_msf
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
  - drivers/cdrom/cdrom.c:open_for_data
```
```
In drivers/usb/core/hub.c (c0aede40)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/usb/core/hcd.c (c0af57d8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/message.c (c0af80cc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (c0b053dc)
Location: arch/arm/include/asm/thread_info.h:88
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
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:checkintf
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (c0b083c8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/host/xhci.c (c0b4a088)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (c0b4ec88)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
```
In drivers/usb/host/xhci-ring.c (c0b511f0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_set_deq
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_set_deq
  - drivers/usb/host/xhci-ring.c:xhci_giveback_urb_in_irq
  - drivers/usb/host/xhci-ring.c:inc_enq
  - drivers/usb/host/xhci-ring.c:inc_deq
```
```
In drivers/usb/host/xhci-hub.c (c0b595d8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/usb/host/xhci-dbgcap.c (c0b5e580)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:dbc_free_request
  - drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/usb/host/xhci-debugfs.c (c0b61efc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
```
```
In drivers/usb/host/xhci-pci.c (c0b632f4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In drivers/usb/musb/musb_core.c (c0b67a44)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_interrupt
  - drivers/usb/musb/musb_core.c:musb_writel
  - drivers/usb/musb/musb_core.c:musb_readl
  - drivers/usb/musb/musb_core.c:musb_default_writew
  - drivers/usb/musb/musb_core.c:musb_default_readw
  - drivers/usb/musb/musb_core.c:musb_default_writeb
  - drivers/usb/musb/musb_core.c:musb_default_readb
```
```
In drivers/usb/musb/musb_trace.c (c0b6911c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/usb/musb/musb_trace.c:musb_dbg
```
```
In drivers/usb/musb/musb_host.c (c0b6b5d0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/usb/musb/musb_host.c:musb_urb_dequeue
  - drivers/usb/musb/musb_host.c:musb_urb_enqueue
  - drivers/usb/musb/musb_host.c:musb_host_rx
  - drivers/usb/musb/musb_host.c:musb_host_tx
  - drivers/usb/musb/musb_host.c:musb_giveback
  - drivers/usb/musb/musb_host.c:musb_start_urb
```
```
In drivers/usb/musb/musb_gadget.c (c0b6fe4c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/usb/musb/musb_gadget.c:musb_gadget_dequeue
  - drivers/usb/musb/musb_gadget.c:musb_gadget_queue
  - drivers/usb/musb/musb_gadget.c:musb_ep_restart
  - drivers/usb/musb/musb_gadget.c:musb_free_request
  - drivers/usb/musb/musb_gadget.c:musb_alloc_request
  - drivers/usb/musb/musb_gadget.c:musb_g_rx
  - drivers/usb/musb/musb_gadget.c:musb_g_tx
  - drivers/usb/musb/musb_gadget.c:musb_g_giveback
```
```
In drivers/usb/musb/musb_debugfs.c (c0b714f0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/usb/musb/musb_debugfs.c:musb_softconnect_write
  - drivers/usb/musb/musb_debugfs.c:musb_test_mode_write
```
```
In drivers/usb/gadget/udc/core.c (c0b739a8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/usb/gadget/udc/core.c:usb_gadget_giveback_request
  - drivers/usb/gadget/udc/core.c:usb_gadget_map_request_by_dev
  - drivers/usb/gadget/udc/core.c:usb_gadget_activate
  - drivers/usb/gadget/udc/core.c:usb_gadget_deactivate
  - drivers/usb/gadget/udc/core.c:usb_gadget_disconnect
  - drivers/usb/gadget/udc/core.c:usb_gadget_connect
  - drivers/usb/gadget/udc/core.c:usb_gadget_vbus_disconnect
  - drivers/usb/gadget/udc/core.c:usb_gadget_vbus_draw
  - drivers/usb/gadget/udc/core.c:usb_gadget_vbus_connect
  - drivers/usb/gadget/udc/core.c:usb_gadget_clear_selfpowered
  - drivers/usb/gadget/udc/core.c:usb_gadget_set_selfpowered
  - drivers/usb/gadget/udc/core.c:usb_gadget_wakeup
  - drivers/usb/gadget/udc/core.c:usb_gadget_frame_number
  - drivers/usb/gadget/udc/core.c:usb_ep_fifo_flush
  - drivers/usb/gadget/udc/core.c:usb_ep_fifo_status
  - drivers/usb/gadget/udc/core.c:usb_ep_set_wedge
  - drivers/usb/gadget/udc/core.c:usb_ep_clear_halt
  - drivers/usb/gadget/udc/core.c:usb_ep_set_halt
  - drivers/usb/gadget/udc/core.c:usb_ep_dequeue
  - drivers/usb/gadget/udc/core.c:usb_ep_queue
  - drivers/usb/gadget/udc/core.c:usb_ep_free_request
  - drivers/usb/gadget/udc/core.c:usb_ep_alloc_request
  - drivers/usb/gadget/udc/core.c:usb_ep_disable
  - drivers/usb/gadget/udc/core.c:usb_ep_enable
  - drivers/usb/gadget/udc/core.c:usb_ep_set_maxpacket_limit
```
```
In drivers/input/input-compat.c (c0b7b3ec)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_ff_effect_from_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/mousedev.c (c0b7d32c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_write
```
```
In drivers/input/evdev.c (c0b7f6d0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_handle_set_keycode_v2
  - drivers/input/evdev.c:evdev_handle_set_keycode
  - drivers/input/evdev.c:evdev_handle_set_keycode
  - drivers/input/evdev.c:evdev_handle_set_keycode
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:evdev_handle_get_keycode
  - drivers/input/evdev.c:evdev_handle_get_keycode
  - drivers/input/evdev.c:evdev_handle_get_keycode
  - drivers/input/evdev.c:str_to_user
```
```
In drivers/input/misc/uinput.c (c0b84a3c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ff_upload_from_user
  - drivers/input/misc/uinput.c:uinput_dev_setup
```
```
In drivers/rtc/interface.c (c0b88eb8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_set_offset
  - drivers/rtc/interface.c:rtc_read_offset
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_alarm_disable
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
```
In drivers/rtc/dev.c (c0b89798)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/rtc/rtc-pcf8523.c (c0b8d420)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_ioctl
```
```
In drivers/i2c/i2c-core-base.c (c0b92314)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (c0b95944)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In drivers/i2c/i2c-dev.c (c0b97d60)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
```
In drivers/media/cec/cec-api.c (c0ba413c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
```
```
In drivers/pps/pps.c (c0ba5bc4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
```
```
In drivers/ptp/ptp_chardev.c (c0ba80a4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
```
```
In drivers/power/reset/hisi-reboot.c (c0baa790)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/power/reset/hisi-reboot.c:hisi_restart_handler
```
```
In drivers/hwmon/hwmon.c (c0bb19b4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/hwmon/hwmon.c:hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:hwmon_attr_show
```
```
In drivers/thermal/thermal_core.c (c0bb39c4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (c0bb8cdc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:thermal_cdev_update
```
```
In drivers/thermal/fair_share.c (c0bba20c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
```
```
In drivers/thermal/step_wise.c (c0bba8b8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/thermal/step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/power_allocator.c (c0bbbc90)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/thermal/cpu_cooling.c (c0bbc28c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/thermal/cpu_cooling.c:cpufreq_power2state
  - drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power
```
```
In drivers/thermal/devfreq_cooling.c (c0bbd1a0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
```
In drivers/watchdog/watchdog_dev.c (c0bc1ce4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_write
  - drivers/watchdog/watchdog_dev.c:watchdog_write
```
```
In drivers/md/md.c (c0bd3978)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:get_array_info
  - drivers/md/md.c:md_make_request
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/md-bitmap.c (c0bd74e8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
```
```
In drivers/md/dm.c (c0bdd1d8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In drivers/md/dm-table.c (c0be1e44)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In drivers/md/dm-ioctl.c (c0be79b4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
```
In drivers/md/dm-kcopyd.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In drivers/md/dm-stats.c (c0beab80)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__dm_stat_clear
  - drivers/md/dm-stats.c:__dm_stat_clear
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/md/dm-rq.c (c0beceec)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/edac/edac_mc.c (c0bee514)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
```
In drivers/cpufreq/cpufreq.c (c0bfb724)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
```
In drivers/cpufreq/cpufreq_ondemand.c (c0bfdb50)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
```
In drivers/cpufreq/cpufreq_governor.c (c0bff258)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_irq_work
```
```
In drivers/cpuidle/cpuidle.c (c0c01e3c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In drivers/cpuidle/driver.c (c0c029d8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_driver_unref
  - drivers/cpuidle/driver.c:cpuidle_driver_ref
```
```
In drivers/cpuidle/coupled.c (c0c04fb4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/cpuidle/coupled.c:coupled_cpu_up_prepare
  - drivers/cpuidle/coupled.c:coupled_cpu_online
  - drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled
  - drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled
  - drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled
```
```
In drivers/cpuidle/cpuidle-arm.c (c0c05f14)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In drivers/cpuidle/cpuidle-psci.c (c0c05fa4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In drivers/mmc/core/core.c (c0c06adc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/mmc/core/sdio_irq.c (c0c178ec)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
```
In drivers/mmc/core/block.c (c0c1b78c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_ioctl_multi_cmd
  - drivers/mmc/core/block.c:mmc_blk_ioctl_copy_from_user
```
```
In drivers/firmware/efi/capsule.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In drivers/firmware/efi/memmap.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In drivers/firmware/efi/arm-runtime.c (c0c40384)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/firmware/efi/arm-runtime.c:efi_virtmap_unload
```
```
In drivers/firmware/tegra/bpmp-debugfs.c (c0c42a04)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_store
```
```
In drivers/clocksource/arm_arch_timer.c (c0c4b33c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_dying_cpu
  - drivers/clocksource/arm_arch_timer.c:arch_timer_dying_cpu
  - drivers/clocksource/arm_arch_timer.c:arch_timer_evtstrm_available
  - drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu
  - drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu
```
```
In drivers/platform/chrome/cros_ec_proto.c (c0c5e630)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:send_command
```
```
In drivers/remoteproc/remoteproc_debugfs.c (c0c65b5c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
```
```
In drivers/devfreq/devfreq.c (c0c6760c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In drivers/powercap/idle_inject.c (c0c7a0dc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_setup
```
```
In drivers/perf/arm-cci.c (c0c7aba0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_probe
```
```
In drivers/perf/arm-ccn.c (c0c7cba4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_probe
```
```
In drivers/perf/arm_pmu.c (c0c7e870)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:cpu_pm_pmu_notify
  - drivers/perf/arm_pmu.c:armpmu_filter_match
  - drivers/perf/arm_pmu.c:armpmu_enable
  - drivers/perf/arm_pmu.c:armpmu_add
```
```
In drivers/perf/arm_pmu_platform.c (c0c7ef98)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe
```
```
In drivers/ras/ras.c (c0c80470)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - drivers/ras/ras.c:log_arm_hw_error
  - drivers/ras/ras.c:log_non_standard_event
```
```
In sound/core/init.c (c0c8415c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In sound/core/memory.c (c0c84c80)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - sound/core/memory.c:copy_from_user_toio
  - sound/core/memory.c:copy_to_user_fromio
```
```
In sound/core/control.c (c0c85d50)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - sound/core/control.c:snd_ctl_get_preferred_subdevice
  - sound/core/control.c:snd_ctl_read
  - sound/core/control.c:snd_ctl_read
  - sound/core/control.c:snd_ctl_read
  - sound/core/control.c:snd_ctl_read
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_tlv_ioctl
  - sound/core/control.c:snd_ctl_tlv_ioctl
  - sound/core/control.c:snd_ctl_elem_add_user
  - sound/core/control.c:snd_ctl_elem_add_user
  - sound/core/control.c:snd_ctl_elem_user_tlv
  - sound/core/control.c:snd_ctl_elem_info_user
  - sound/core/control.c:snd_ctl_elem_info_user
  - sound/core/control.c:snd_ctl_elem_list
  - sound/core/control.c:snd_ctl_elem_list
  - sound/core/control.c:snd_ctl_elem_list
```
```
In sound/core/info.c (c0c89740)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - sound/core/info.c:snd_info_text_entry_write
```
```
In sound/core/timer.c (c0c8e428)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - sound/core/timer.c:snd_timer_user_read
  - sound/core/timer.c:snd_timer_user_read
  - sound/core/timer.c:snd_timer_user_read
  - sound/core/timer.c:snd_timer_user_read
  - sound/core/timer.c:snd_timer_user_read
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
```
```
In sound/core/pcm.c (c0c90b18)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - sound/core/pcm.c:snd_pcm_attach_substream
  - sound/core/pcm.c:snd_pcm_control_ioctl
  - sound/core/pcm.c:snd_pcm_control_ioctl
  - sound/core/pcm.c:snd_pcm_control_ioctl
  - sound/core/pcm.c:snd_pcm_control_ioctl
  - sound/core/pcm.c:snd_pcm_control_ioctl
  - sound/core/pcm.c:snd_pcm_control_ioctl
  - sound/core/pcm.c:snd_pcm_control_ioctl
  - sound/core/pcm.c:snd_pcm_control_ioctl
  - sound/core/pcm.c:snd_pcm_control_ioctl
  - sound/core/pcm.c:snd_pcm_control_ioctl
  - sound/core/pcm.c:snd_pcm_control_ioctl
  - sound/core/pcm.c:snd_pcm_control_ioctl
```
```
In sound/core/pcm_native.c (c0c95dec)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_rewind_ioctl
  - sound/core/pcm_native.c:snd_pcm_rewind_ioctl
  - sound/core/pcm_native.c:snd_pcm_rewind_ioctl
  - sound/core/pcm_native.c:snd_pcm_rewind_ioctl
  - sound/core/pcm_native.c:snd_pcm_rewind_ioctl
  - sound/core/pcm_native.c:snd_pcm_rewind_ioctl
  - sound/core/pcm_native.c:snd_pcm_sync_ptr
  - sound/core/pcm_native.c:snd_pcm_sync_ptr
  - sound/core/pcm_native.c:snd_pcm_sync_ptr
  - sound/core/pcm_native.c:snd_pcm_sync_ptr
  - sound/core/pcm_native.c:snd_pcm_drain
  - sound/core/pcm_native.c:snd_pcm_drain
  - sound/core/pcm_native.c:snd_pcm_status_user
  - sound/core/pcm_native.c:snd_pcm_status_user
  - sound/core/pcm_native.c:snd_pcm_status_user
  - sound/core/pcm_native.c:snd_pcm_sw_params_user
  - sound/core/pcm_native.c:snd_pcm_sw_params_user
  - sound/core/pcm_native.c:snd_pcm_info_user
```
```
In sound/core/pcm_lib.c (c0c988fc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - sound/core/pcm_lib.c:pcm_chmap_ctl_tlv
  - sound/core/pcm_lib.c:pcm_chmap_ctl_tlv
  - sound/core/pcm_lib.c:pcm_chmap_ctl_tlv
  - sound/core/pcm_lib.c:pcm_chmap_ctl_tlv
  - sound/core/pcm_lib.c:pcm_chmap_ctl_tlv
  - sound/core/pcm_lib.c:pcm_chmap_ctl_tlv
  - sound/core/pcm_lib.c:pcm_chmap_ctl_tlv
  - sound/core/pcm_lib.c:pcm_chmap_ctl_tlv
  - sound/core/pcm_lib.c:pcm_chmap_ctl_tlv
  - sound/core/pcm_lib.c:pcm_chmap_ctl_tlv
  - sound/core/pcm_lib.c:__snd_pcm_lib_xfer
  - sound/core/pcm_lib.c:__snd_pcm_lib_xfer
  - sound/core/pcm_lib.c:__snd_pcm_lib_xfer
  - sound/core/pcm_lib.c:default_read_copy
  - sound/core/pcm_lib.c:default_write_copy
```
```
In sound/core/compress_offload.c (c0c9e728)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - sound/core/compress_offload.c:snd_compr_ioctl
  - sound/core/compress_offload.c:snd_compr_ioctl
  - sound/core/compress_offload.c:snd_compr_ioctl
  - sound/core/compress_offload.c:snd_compr_ioctl
  - sound/core/compress_offload.c:snd_compr_ioctl
  - sound/core/compress_offload.c:snd_compr_ioctl
  - sound/core/compress_offload.c:snd_compr_ioctl
  - sound/core/compress_offload.c:snd_compr_ioctl
  - sound/core/compress_offload.c:snd_compr_ioctl
  - sound/core/compress_offload.c:snd_compr_get_caps
  - sound/core/compress_offload.c:snd_compr_write
  - sound/core/compress_offload.c:snd_compr_write
  - sound/core/compress_offload.c:snd_compr_write
```
```
In sound/soc/soc-dapm.c (c0caa4c4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - sound/soc/soc-dapm.c:dapm_power_widgets
  - sound/soc/soc-dapm.c:dapm_power_widgets
  - sound/soc/soc-dapm.c:dapm_power_widgets
  - sound/soc/soc-dapm.c:dapm_power_widgets
  - sound/soc/soc-dapm.c:dapm_seq_check_event
  - sound/soc/soc-dapm.c:dapm_seq_check_event
  - sound/soc/soc-dapm.c:snd_soc_dapm_dai_get_connected_widgets
  - sound/soc/soc-dapm.c:snd_soc_dapm_set_bias_level
  - sound/soc/soc-dapm.c:snd_soc_dapm_set_bias_level
```
```
In sound/soc/soc-jack.c (c0cad404)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - sound/soc/soc-jack.c:gpio_handler
```
```
In sound/soc/soc-generic-dmaengine-pcm.c (c0cbb62c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - sound/soc/soc-generic-dmaengine-pcm.c:dmaengine_copy_user
  - sound/soc/soc-generic-dmaengine-pcm.c:dmaengine_copy_user
```
```
In net/socket.c (c0cc3c88)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_setsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:kernel_getsockopt
  - net/socket.c:do_recvmmsg
  - net/socket.c:do_recvmmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:__se_sys_getsockopt
  - net/socket.c:__se_sys_getsockopt
  - net/socket.c:__se_sys_setsockopt
  - net/socket.c:__se_sys_setsockopt
  - net/socket.c:__se_sys_setsockopt
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socket
  - net/socket.c:__sock_create
  - net/socket.c:sock_poll
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
  - net/socket.c:sock_alloc
  - net/socket.c:move_addr_to_user
  - net/socket.c:move_addr_to_user
  - net/socket.c:move_addr_to_user
  - net/socket.c:move_addr_to_user
  - net/socket.c:move_addr_to_kernel
  - net/socket.c:move_addr_to_kernel
```
```
In net/core/sock.c (c0cc89b4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sock_warn_obsolete_bsdism
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_set_timeout
```
```
In net/core/skbuff.c (c0cd2580)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/datagram.c (c0cd81a4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (c0cd92b4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_error
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/scm.c (c0cda0b8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
```
```
In net/core/gen_estimator.c (c0cdb39c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (c0cdc340)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/flow_dissector.c (c0cde79c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissector_bpf_prog_detach
  - net/core/flow_dissector.c:skb_flow_dissector_bpf_prog_attach
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
```
In net/core/sysctl_net_core.c (c0ce0ec8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (c0cea224)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:netif_rx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netdev_core_pick_tx
  - net/core/dev.c:dev_pick_tx_cpu_id
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:__dev_kfree_skb_any
```
```
In net/core/ethtool.c (c0cf6e58)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_set_per_queue
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:ethtool_flash_device
  - net/core/ethtool.c:ethtool_get_value
  - net/core/ethtool.c:ethtool_set_channels
  - net/core/ethtool.c:ethtool_get_channels
  - net/core/ethtool.c:ethtool_set_coalesce
  - net/core/ethtool.c:ethtool_get_coalesce
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_set_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_copy_validate_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_set_rxnfc
  - net/core/ethtool.c:ethtool_set_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:load_link_ksettings_from_user
```
```
In net/core/neighbour.c (c0cfc64c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/rtnetlink.c (c0d0a42c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_link_unregister
```
```
In net/core/filter.c (c0d1c67c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect_slow
  - net/core/filter.c:xdp_do_redirect_slow
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_get_raw_cpu_id
```
```
In net/core/dev_ioctl.c (c0d1d348)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/xdp.c (c0d1fbe0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (c0d2170c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/net-sysfs.c (c0d22934)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_grab_current_ns
  - net/core/net-sysfs.c:net_current_may_mount
  - net/core/net-sysfs.c:tx_maxrate_store
```
```
In net/core/page_pool.c (c0d25378)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_clean_page
  - net/core/page_pool.c:page_pool_alloc_pages
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (c0d26a98)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/core/netpoll.c (c0d28548)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:netpoll_poll_dev
  - net/core/netpoll.c:queue_process
```
```
In net/core/fib_rules.c (c0d2a824)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl2rule
  - net/core/fib_rules.c:fib_nl2rule
```
```
In net/core/devlink.c (c0d3c5dc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_report
  - net/core/devlink.c:devlink_health_report
```
```
In net/sched/sch_generic.c (c0d4c2ac)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:__qdisc_run
  - net/sched/sch_generic.c:sch_direct_xmit
```
```
In net/netlink/af_netlink.c (c0d5c750)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
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
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_autobind
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/bpf/test_run.c (c0d6370c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_ctx_finish
  - net/bpf/test_run.c:bpf_ctx_finish
  - net/bpf/test_run.c:bpf_test_init
  - net/bpf/test_run.c:bpf_test_finish
  - net/bpf/test_run.c:bpf_test_finish
  - net/bpf/test_run.c:bpf_test_finish
  - net/bpf/test_run.c:bpf_test_finish
  - net/bpf/test_run.c:bpf_test_finish
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/netfilter/nf_log.c (c0d65380)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (c0d65b48)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (c0d6c2b4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_input.c (c0d6dab8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (c0d6f50c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (c0d6fcf0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_options.c (c0d71168)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_get_from_user
```
```
In net/ipv4/ip_output.c (c0d754d0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_make_skb
  - net/ipv4/ip_output.c:ip_send_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/ip_sockglue.c (c0d75d0c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In net/ipv4/inet_hashtables.c (c0d78fb0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (c0d7adb0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (c0d7bfe0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (c0d84964)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_input.c (c0d901a8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_output.c (c0d96df8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_ipv4.c (c0d99e10)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (c0d9e3fc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/datagram.c (c0da4838)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c0da4d38)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (c0da7b24)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:udp_ioctl
  - net/ipv4/udp.c:udp_ioctl
  - net/ipv4/udp.c:udp_ioctl
  - net/ipv4/udp.c:udp_ioctl
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv4/arp.c (c0dafe44)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
```
```
In net/ipv4/icmp.c (c0db0be4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/devinet.c (c0db6368)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:inet_gifconf
```
```
In net/ipv4/af_inet.c (c0db910c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_state_store
  - net/ipv4/af_inet.c:inet_sk_set_state
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:inet_release
```
```
In net/ipv4/igmp.c (c0dbe4c8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
```
```
In net/ipv4/fib_frontend.c (c0dbf378)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
```
```
In net/ipv4/fib_semantics.c (c0dc567c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/fib_trie.c (c0dc8200)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/inet_fragment.c (c0dcade0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ping.c (c0dcccd8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/nexthop.c (c0dcf1d4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/bpfilter/sockopt.c (c0dd1af0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
```
```
In net/ipv4/sysctl_net_ipv4.c (c0dd2414)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
```
In net/ipv4/ipmr.c (c0dd74b4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_new_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
  - net/ipv4/ipmr.c:ipmr_del_tunnel
```
```
In net/ipv4/tcp_bpf.c (c0dde5b0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (c0de47c8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_state.c (c0deca64)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
```
In net/xfrm/xfrm_device.c (c0df5d54)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_resume
```
```
In net/unix/af_unix.c (c0df7550)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:init_peercred
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/unix/scm.c (c0dfbe5c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/unix/scm.c:unix_attach_fds
```
```
In net/ipv6/af_inet6.c (c0dfc2ec)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
```
```
In net/ipv6/ip6_output.c (c0e03f20)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (c0e04540)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (c0e06cd4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_disable_policy
  - net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown
  - net/ipv6/addrconf.c:addrconf_sysctl_stable_secret
  - net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode
  - net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp
  - net/ipv6/addrconf.c:addrconf_sysctl_disable
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (c0e1d9d0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (c0e1ee94)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (c0e215b4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In net/ipv6/ndisc.c (c0e255c0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
```
```
In net/ipv6/udp.c (c0e29b88)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/raw.c (c0e2cca4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
  - net/ipv6/raw.c:rawv6_ioctl
  - net/ipv6/raw.c:rawv6_ioctl
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/icmp.c (c0e304c8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (c0e33b00)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
```
```
In net/ipv6/reassembly.c (c0e37754)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (c0e3c338)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
```
In net/ipv6/exthdrs.c (c0e3f11c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6_flowlabel.c (c0e4182c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (c0e4941c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/netfilter.c (0)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In net/ipv6/seg6_hmac.c (c0e52f18)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (c0e55ec8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
```
In net/packet/af_packet.c (c0e56dac)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_rcv_fanout
  - net/packet/af_packet.c:packet_direct_xmit
```
```
In net/wireless/wext-core.c (c0e60e98)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
```
```
In net/wireless/wext-priv.c (c0e61860)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:ioctl_private_iw_point
  - net/wireless/wext-priv.c:ioctl_private_iw_point
```
```
In net/netlabel/netlabel_user.c (c0e61c7c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
```
In net/netlabel/netlabel_mgmt.c (c0e65ce4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_removedef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_adddef
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_remove
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add
```
```
In net/netlabel/netlabel_unlabeled.c (c15baaa8)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremovedef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticremove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadddef
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticadd
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_accept
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e68354)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (c0e69064)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
```
```
In net/rfkill/core.c (c0e6a40c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_read
```
```
In net/sysctl_net.c (c0e6f45c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/sysctl_net.c:is_seen
  - net/sysctl_net.c:net_ctl_header_lookup
```
```
In net/dns_resolver/dns_key.c (c15baed4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
  - net/dns_resolver/dns_key.c:dns_resolver_cmp
  - net/dns_resolver/dns_key.c:dns_resolver_cmp
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
```
In net/dns_resolver/dns_query.c (c0e7003c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/dns_resolver/dns_query.c:dns_query
  - net/dns_resolver/dns_query.c:dns_query
  - net/dns_resolver/dns_query.c:dns_query
```
```
In net/xdp/xsk.c (c0e79134)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xdp_umem.c (c0e7b914)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/dump_stack.c (c0e7fe58)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - lib/dump_stack.c:dump_stack
  - lib/dump_stack.c:dump_stack_print_info
  - lib/dump_stack.c:dump_stack_print_info
```
```
In lib/is_single_threaded.c (c0e8444c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - lib/is_single_threaded.c:current_is_single_threaded
```
```
In lib/klist.c (c0e8482c)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - lib/klist.c:klist_remove
  - lib/klist.c:klist_remove
  - lib/klist.c:klist_remove
```
```
In lib/nmi_backtrace.c (c0e873cc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/radix-tree.c (c0e889c4)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
```
```
In lib/seq_buf.c (c0e8a8ac)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - lib/seq_buf.c:seq_buf_to_user
```
```
In lib/vsprintf.c (c0e92ebc)
Location: arch/arm/include/asm/thread_info.h:88
Inline: True
Inline callers:
  - lib/vsprintf.c:restricted_pointer
```
</details>
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
