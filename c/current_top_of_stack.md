# Function: <code>current_top_of_stack</code>

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
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - arch/x86/entry/common.c:syscall_trace_enter_phase2
  - arch/x86/entry/common.c:syscall_trace_enter_phase2
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81004206)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004696)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/core.c (ffffffff810076cd)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f6b6)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
```
```
In arch/x86/events/intel/lbr.c (ffffffff81011381)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/kernel/process_64.c (ffffffff8102d006)
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:copy_siginfo_to_user32
  - arch/x86/kernel/signal_compat.c:copy_siginfo_to_user32
  - arch/x86/kernel/signal_compat.c:copy_siginfo_from_user32
```
```
In arch/x86/kernel/traps.c (ffffffff8102f962)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:ist_begin_non_atomic
```
```
In arch/x86/kernel/ioport.c (ffffffff81031974)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff81033f83)
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103acd5)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103cc7f)
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810500cf)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81f6f77e)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8105ed5d)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:setjmp_pre_handler
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/kgdb.c (ffffffff81061649)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
```
In arch/x86/kernel/uprobes.c (ffffffff81065636)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:default_post_xol_op
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
```
```
In arch/x86/mm/fault.c (ffffffff8106ac65)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
```
In arch/x86/mm/extable.c (ffffffff8106bfe3)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:fixup_exception
```
```
In arch/x86/mm/mmap.c (ffffffff8106f633)
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:__get_user_pages_fast
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81072c31)
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_cmpxchg_bd_entry
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
  - arch/x86/mm/mpx.c:mpx_notify_unmap
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8107794e)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:cp_stat64
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81077eb6)
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/fork.c (ffffffff8107f437)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8108394c)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff81085902)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:irq_exit
```
```
In kernel/ptrace.c (ffffffff8108b174)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_regset
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
```
```
In kernel/signal.c (ffffffff8108d189)
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:SYSC_olduname
```
```
In kernel/sched/core.c (ffffffff818203e5)
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/sched/idle.c (ffffffff810c3ce5)
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:mutex_optimistic_spin
```
```
In kernel/locking/osq_lock.c (ffffffff810ca34f)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/rwsem-xadd.c (ffffffff810cbcc9)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_spin_on_owner
```
```
In kernel/power/user.c (ffffffff810d5e43)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_compat_ioctl
  - kernel/power/user.c:snapshot_compat_ioctl
```
```
In kernel/printk/printk.c (ffffffff810d9512)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:show_regs_print_info
```
```
In kernel/rcu/tree.c (ffffffff810e7263)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
```
```
In kernel/freezer.c (ffffffff810e9a9e)
Location: arch/x86/include/asm/processor.h:461
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff810fe6d4)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/futex.c (ffffffff810ffa7c)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:futex_wake_op
```
```
In kernel/module.c (0)
Location: arch/x86/include/asm/processor.h:461
Inline: True
```
```
In kernel/compat.c (ffffffff8110f796)
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - kernel/cpuset.c:__cpuset_node_allowed
```
```
In kernel/pid_namespace.c (ffffffff8111fcf3)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff8112990b)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_seccomp
```
```
In kernel/seccomp.c (ffffffff8113b6e6)
Location: arch/x86/include/asm/processor.h:461
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8114a777)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_generic_entry_update
```
```
In kernel/trace/trace_syscalls.c (ffffffff81161c7c)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffffffff81167481)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
  - kernel/trace/trace_kprobe.c:fetch_memory_string_size
```
```
In kernel/bpf/syscall.c (ffffffff81173602)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/events/core.c (ffffffff811817f6)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff81187202)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
```
```
In mm/oom_kill.c (ffffffff81190a75)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
  - mm/oom_kill.c:oom_killer_disable
  - mm/oom_kill.c:pagefault_out_of_memory
```
```
In mm/maccess.c (ffffffff81191506)
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc_failed
  - mm/page_alloc.c:gfp_pfmemalloc_allowed
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/shmem.c (ffffffff811a87fd)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
```
```
In mm/compaction.c (ffffffff811b56a8)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:compact_zone
```
```
In mm/gup.c (ffffffff811bab42)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811bbd16)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - mm/memory.c:tlb_gather_mmu
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811c29da)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - mm/mincore.c:SyS_mincore
```
```
In mm/mlock.c (ffffffff811c3ca5)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - mm/mlock.c:SyS_mlockall
```
```
In mm/mmap.c (ffffffff811c4455)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
```
```
In mm/mremap.c (ffffffff811c9eea)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
```
```
In mm/mempolicy.c (ffffffff811e31df)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In mm/memcontrol.c (ffffffff811fb933)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In fs/read_write.c (ffffffff8120c2b4)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:vfs_read
  - fs/read_write.c:vfs_write
  - fs/read_write.c:rw_copy_check_uvector
```
```
In fs/exec.c (ffffffff81212672)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - fs/exec.c:kernel_read
  - fs/exec.c:copy_strings_kernel
  - fs/exec.c:setup_new_exec
```
```
In fs/ioctl.c (ffffffff8121ff76)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/readdir.c (ffffffff812206c7)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - fs/readdir.c:fillonedir
  - fs/readdir.c:SyS_getdents
  - fs/readdir.c:SyS_getdents64
```
```
In fs/select.c (ffffffff812211ef)
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - fs/dcache.c:select_collect
```
```
In fs/inode.c (ffffffff81228c2d)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - fs/inode.c:evict_inodes
```
```
In fs/namespace.c (ffffffff8122ea0c)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/fs-writeback.c (ffffffff8123b69d)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/splice.c (ffffffff8123da6c)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - fs/splice.c:kernel_write
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:vmsplice_to_pipe
```
```
In fs/block_dev.c (ffffffff81247fb3)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - fs/block_dev.c:ioctl_by_bdev
```
```
In fs/eventpoll.c (ffffffff812568b3)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:compat_SyS_epoll_pwait
```
```
In fs/aio.c (ffffffff8125d47e)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
```
In fs/compat.c (ffffffff812630c6)
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/dir.c (ffffffff81290a44)
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
```
```
In fs/ext4/mballoc.c (ffffffff812d57a4)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/jbd2/checkpoint.c (ffffffff812eccaa)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
```
```
In fs/fat/dir.c (ffffffff812f8a43)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
  - fs/fat/dir.c:fat_dir_ioctl
```
```
In fs/ecryptfs/inode.c (ffffffff81301619)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
```
```
In ipc/compat.c (ffffffff813232c2)
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - ipc/compat_mq.c:compat_SyS_mq_open
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
```
```
In security/keys/gc.c (ffffffff8132f00b)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In security/tomoyo/common.c (ffffffff8136b37a)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
```
In security/tomoyo/network.c (ffffffff81372382)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
```
```
In security/integrity/iint.c (ffffffff8139645f)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - security/integrity/iint.c:integrity_kernel_read
```
```
In block/blk-core.c (ffffffff813bbc0a)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - block/blk-core.c:blk_poll
```
```
In block/compat_ioctl.c (ffffffff813e5406)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_fd_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In arch/x86/lib/usercopy.c (ffffffff813f7935)
Location: arch/x86/include/asm/processor.h:461
Inline: True
```
```
In arch/x86/lib/usercopy_64.c (ffffffff813f79f5)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:copy_in_user
  - arch/x86/lib/usercopy_64.c:clear_user
  - arch/x86/lib/usercopy_64.c:copy_user_handle_tail
```
```
In lib/bitmap.c (ffffffff813f9923)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parse_user
  - lib/bitmap.c:bitmap_parselist_user
```
```
In lib/iov_iter.c (ffffffff813fb251)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - lib/iov_iter.c:import_iovec
  - lib/iov_iter.c:compat_import_iovec
  - lib/iov_iter.c:import_single_range
```
```
In lib/strncpy_from_user.c (ffffffff81419c1e)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81419d19)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
  - lib/strnlen_user.c:strlen_user
```
```
In drivers/pci/proc.c (ffffffff81441a14)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_write
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8146d1ce)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
```
```
In drivers/idle/intel_idle.c (ffffffff8147942c)
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_safe_halt
```
```
In drivers/xen/preempt.c (ffffffff814c7641)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
```
```
In drivers/tty/tty_io.c (ffffffff814e022c)
Location: arch/x86/include/asm/processor.h:461
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff814ef6b7)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
```
```
In drivers/tty/vt/selection.c (ffffffff814f1315)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:set_selection
```
```
In drivers/tty/vt/consolemap.c (ffffffff814f6025)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
```
```
In drivers/char/mem.c (ffffffff8151112c)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:write_port
```
```
In drivers/char/random.c (ffffffff8151355c)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - drivers/char/random.c:extract_entropy_user
```
```
In drivers/char/hw_random/core.c (ffffffff8151a613)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff81523732)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff815289bb)
Location: arch/x86/include/asm/processor.h:461
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff815a8f62)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffffffff815c37c6)
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_read
```
```
In drivers/input/input.c (ffffffff816683c6)
Location: arch/x86/include/asm/processor.h:461
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff8166a0b6)
Location: arch/x86/include/asm/processor.h:461
Inline: True
```
```
In drivers/input/evdev.c (ffffffff8166d944)
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
  - drivers/cpuidle/driver.c:poll_idle
```
```
In drivers/firmware/efi/efivars.c (ffffffff816d2256)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/socket.c (ffffffff816fb7dc)
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/compat.c (ffffffff8173e5cd)
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/inetpeer.c (ffffffff81757da1)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
```
```
In net/ipv4/tcp.c (ffffffff81766e8c)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/ipmr.c (ffffffff817a7ff2)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv6/addrconf.c (ffffffff817d11e0)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
```
```
In net/packet/af_packet.c (ffffffff81807bd9)
Location: arch/x86/include/asm/processor.h:461
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81817b9f)
Location: arch/x86/include/asm/processor.h:461
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
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/entry/vdso/vma.c (ffffffff81004366)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:compat_arch_setup_additional_pages
  - arch/x86/entry/vdso/vma.c:vdso_mremap
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004a5c)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/core.c (ffffffff810078a5)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f116)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
```
```
In arch/x86/events/intel/lbr.c (ffffffff81010c8d)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/kernel/process_64.c (ffffffff8102c006)
Location: arch/x86/include/asm/processor.h:479
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
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:restore_sigcontext
```
```
In arch/x86/kernel/signal_compat.c (ffffffff8102dec6)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:copy_siginfo_to_user32
```
```
In arch/x86/kernel/traps.c (ffffffff8102ea22)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:ist_begin_non_atomic
```
```
In arch/x86/kernel/ioport.c (ffffffff81030a84)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff81033439)
Location: arch/x86/include/asm/processor.h:479
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
Location: arch/x86/include/asm/processor.h:479
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
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103cbd0)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8105024c)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81052970)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8105edfd)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/kprobes/core.c:setjmp_pre_handler
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
```
In arch/x86/kernel/kgdb.c (ffffffff81061469)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:__kgdb_notify
```
```
In arch/x86/kernel/uprobes.c (ffffffff81065db3)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:default_post_xol_op
```
```
In arch/x86/mm/mmap.c (ffffffff8106f419)
Location: arch/x86/include/asm/processor.h:479
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
Location: arch/x86/include/asm/processor.h:479
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
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_generate_siginfo
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810795d9)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext
```
```
In kernel/fork.c (ffffffff810815ed)
Location: arch/x86/include/asm/processor.h:479
Inline: True
```
```
In kernel/exit.c (ffffffff81086c58)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffff81088a94)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
```
```
In kernel/ptrace.c (ffffffff8108e2c6)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff81093c11)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:ptrace_stop
```
```
In kernel/sys.c (ffffffff810965a2)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
```
```
In kernel/sched/core.c (ffffffff8189ab1f)
Location: arch/x86/include/asm/processor.h:479
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
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/sched/idle.c (ffffffff810c7aea)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In kernel/locking/mutex.c (ffffffff810ce4b2)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:mutex_optimistic_spin
```
```
In kernel/locking/osq_lock.c (ffffffff810cecdf)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/rwsem-xadd.c (ffffffff8189d8fa)
Location: arch/x86/include/asm/processor.h:479
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
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
```
```
In kernel/time/tick-sched.c (ffffffff81105a5d)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/compat.c (ffffffff81117902)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
```
```
In kernel/cpuset.c (ffffffff811255ee)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - kernel/cpuset.c:__cpuset_node_allowed
```
```
In kernel/pid_namespace.c (ffffffff81127c40)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - kernel/pid_namespace.c:zap_pid_ns_processes
```
```
In kernel/auditsc.c (ffffffff81131abb)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_seccomp
```
```
In kernel/seccomp.c (ffffffff81144487)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
```
```
In kernel/trace/trace.c (ffffffff811531d6)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_generic_entry_update
```
```
In kernel/trace/trace_syscalls.c (ffffffff8116c56e)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/events/core.c (ffffffff81195686)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/events/uprobes.c (ffffffff8119bdd5)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_post_sstep_notifier
  - kernel/events/uprobes.c:uprobe_pre_sstep_notifier
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:__create_xol_area
```
```
In mm/oom_kill.c (ffffffff811a5c7e)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - mm/oom_kill.c:pagefault_out_of_memory
```
```
In mm/page_alloc.c (ffffffff811aa6ea)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc_failed
```
```
In mm/shmem.c (ffffffff811bf5e8)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/compaction.c (ffffffff811d211e)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff811d53b2)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811dcafc)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
  - mm/memory.c:tlb_gather_mmu
```
```
In mm/mlock.c (ffffffff811dfad3)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - mm/mlock.c:SyS_mlockall
```
```
In mm/mmap.c (ffffffff811e1f06)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - mm/mmap.c:do_munmap
  - mm/mmap.c:do_munmap
```
```
In mm/mremap.c (ffffffff811e6318)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
```
```
In mm/mempolicy.c (ffffffff81201c16)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In mm/khugepaged.c (ffffffff8121c696)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff8121f9f2)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
```
In fs/exec.c (ffffffff8123b3f8)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - fs/exec.c:setup_new_exec
```
```
In fs/select.c (ffffffff8124a37a)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - fs/select.c:SyS_ppoll
  - fs/select.c:do_sys_poll
  - fs/select.c:SyS_pselect6
  - fs/select.c:do_select
```
```
In fs/dcache.c (ffffffff8124b0f1)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - fs/dcache.c:select_collect
```
```
In fs/inode.c (ffffffff81251326)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - fs/inode.c:evict_inodes
```
```
In fs/namespace.c (ffffffff81257218)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/fs-writeback.c (ffffffff81263517)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - fs/fs-writeback.c:writeback_sb_inodes
```
```
In fs/eventpoll.c (ffffffff8127f62d)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
```
```
In fs/compat.c (ffffffff81291c97)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_ppoll
  - fs/compat.c:compat_SyS_pselect6
```
```
In fs/binfmt_elf.c (ffffffff812939e2)
Location: arch/x86/include/asm/processor.h:479
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
Location: arch/x86/include/asm/processor.h:479
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
Location: arch/x86/include/asm/processor.h:479
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
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/jbd2/checkpoint.c (ffffffff8131ada6)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_clean_checkpoint_list
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In security/keys/gc.c (ffffffff81363cd9)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
```
```
In block/blk-core.c (ffffffff813ffa1a)
Location: arch/x86/include/asm/processor.h:479
Inline: True
```
```
In arch/x86/lib/usercopy.c (ffffffff8143e7e5)
Location: arch/x86/include/asm/processor.h:479
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff814c78f6)
Location: arch/x86/include/asm/processor.h:479
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
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_safe_halt
```
```
In drivers/xen/preempt.c (ffffffff81517ed2)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - drivers/xen/preempt.c:xen_maybe_preempt_hcall
```
```
In drivers/tty/tty_io.c (ffffffff81531aa7)
Location: arch/x86/include/asm/processor.h:479
Inline: True
```
```
In drivers/char/random.c (ffffffff81567ef7)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/hw_random/core.c (ffffffff8156d307)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff81576671)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8157be11)
Location: arch/x86/include/asm/processor.h:479
Inline: True
```
```
In drivers/input/input.c (ffffffff816c8376)
Location: arch/x86/include/asm/processor.h:479
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff816ca38c)
Location: arch/x86/include/asm/processor.h:479
Inline: True
```
```
In drivers/input/evdev.c (ffffffff816cdc9d)
Location: arch/x86/include/asm/processor.h:479
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
Location: arch/x86/include/asm/processor.h:479
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
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
  - drivers/cpuidle/driver.c:poll_idle
```
```
In drivers/firmware/efi/efivars.c (ffffffff8173622b)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/socket.c (ffffffff81763518)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff817742bb)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/core/dev.c (ffffffff817833c6)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - net/core/dev.c:sk_busy_loop
```
```
In net/sched/sch_generic.c (ffffffff817ae3dd)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/inetpeer.c (ffffffff817c404b)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
```
```
In net/ipv4/tcp.c (ffffffff817d338c)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/packet/af_packet.c (ffffffff81878c8c)
Location: arch/x86/include/asm/processor.h:479
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
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
In arch/x86/kernel/traps.c (ffffffff8102e962)
Location: arch/x86/include/asm/processor.h:521
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:ist_begin_non_atomic
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81061ead)
Location: arch/x86/include/asm/processor.h:521
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/kprobes/core.c:setjmp_pre_handler
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
In arch/x86/kernel/traps.c (ffffffff8102c822)
Location: arch/x86/include/asm/processor.h:532
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:ist_begin_non_atomic
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81060e56)
Location: arch/x86/include/asm/processor.h:532
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/kprobes/core.c:setjmp_pre_handler
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
In arch/x86/kernel/traps.c (ffffffff8102d992)
Location: arch/x86/include/asm/processor.h:549
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:ist_begin_non_atomic
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81064ea6)
Location: arch/x86/include/asm/processor.h:549
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/kprobes/core.c:setjmp_pre_handler
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
In arch/x86/kernel/traps.c (ffffffff8102e952)
Location: arch/x86/include/asm/processor.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:ist_begin_non_atomic
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81067a8a)
Location: arch/x86/include/asm/processor.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/kprobes/core.c:setjmp_pre_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102fb32)
Location: arch/x86/include/asm/processor.h:560
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:ist_begin_non_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff810318fe)
Location: arch/x86/include/asm/processor.h:550
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:ist_begin_non_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff810321be)
Location: arch/x86/include/asm/processor.h:550
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:ist_begin_non_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81bbe80f)
Location: arch/x86/include/asm/processor.h:585
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c37001)
Location: arch/x86/include/asm/processor.h:568
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c29666)
Location: arch/x86/include/asm/processor.h:550
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81d47de9)
Location: arch/x86/include/asm/processor.h:562
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81f168ce)
Location: arch/x86/include/asm/processor.h:562
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff820bde76)
Location: arch/x86/include/asm/processor.h:507
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8213f913)
Location: arch/x86/include/asm/processor.h:507
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82221933)
Location: arch/x86/include/asm/processor.h:529
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8103231e)
Location: arch/x86/include/asm/processor.h:550
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:ist_begin_non_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81021c7e)
Location: arch/x86/include/asm/processor.h:550
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:ist_begin_non_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8103217e)
Location: arch/x86/include/asm/processor.h:550
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:ist_begin_non_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8103309e)
Location: arch/x86/include/asm/processor.h:550
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:ist_begin_non_atomic
```
</details>
</li>
</ul>

## Differences
