# Function: <code>task_stack_page</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/sched.h:3190
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/sched.h:3190
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81030ad1)
Location: include/linux/sched.h:3190
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:in_task_stack
```
```
In arch/x86/kernel/process.c (ffffffff81038246)
Location: include/linux/sched.h:3190
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: include/linux/sched.h:3190
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/sched.h:3190
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:3190
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/sched.h:3190
Inline: True
```
```
In kernel/trace/trace_stack.c (ffffffff8116ddd1)
Location: include/linux/sched.h:3190
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In mm/usercopy.c (ffffffff81240a7e)
Location: include/linux/sched.h:3190
Inline: True
Inline callers:
  - mm/usercopy.c:check_stack_object
```
```
In block/blk-map.c (ffffffff8141d47e)
Location: include/linux/sched.h:3190
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In lib/syscall.c (0)
Location: include/linux/sched.h:3190
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
In arch/x86/kernel/process_64.c (0)
Location: include/linux/sched/task_stack.h:18
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/sched/task_stack.h:18
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8102edab)
Location: include/linux/sched/task_stack.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:in_task_stack
```
```
In arch/x86/kernel/process.c (ffffffff810363b5)
Location: include/linux/sched/task_stack.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: include/linux/sched/task_stack.h:18
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/sched/task_stack.h:18
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched/task_stack.h:18
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/sched/task_stack.h:18
Inline: True
```
```
In kernel/trace/trace_stack.c (ffffffff811710c5)
Location: include/linux/sched/task_stack.h:18
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In mm/usercopy.c (ffffffff8124c7ce)
Location: include/linux/sched/task_stack.h:18
Inline: True
Inline callers:
  - mm/usercopy.c:check_stack_object
```
```
In block/blk-map.c (ffffffff8142b4d1)
Location: include/linux/sched/task_stack.h:18
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In lib/syscall.c (0)
Location: include/linux/sched/task_stack.h:18
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff816b004c)
Location: include/linux/sched/task_stack.h:18
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
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
In arch/x86/entry/vdso/vma.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/kernel/process_64.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/kernel/signal_compat.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81030ba5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:in_task_stack
```
```
In arch/x86/kernel/sys_x86_64.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81038745)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/kernel/ptrace.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/kernel/step.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/kernel/stacktrace.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/kernel/perf_regs.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/kernel/unwind_frame.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/mm/mmap.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/mm/hugetlbpage.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/signal.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/sched/cpuacct.c (ffffffff810dafc5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/compat.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/trace/trace_stack.c (ffffffff8117e285)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In mm/usercopy.c (ffffffff8126cc92)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - mm/usercopy.c:check_stack_object
```
```
In fs/binfmt_elf.c (ffffffff812d84b5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff812db525)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/coredump.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In fs/proc/array.c (ffffffff812f494f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/dir.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In block/blk-map.c (ffffffff814566c8)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In lib/syscall.c (ffffffff814bf2e8)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/usb/core/hcd.c (ffffffff8171b590)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/input/input.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In drivers/input/input-compat.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In drivers/input/evdev.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In drivers/firmware/efi/efivars.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In net/compat.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/sched/task_stack.h:19
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
In arch/x86/entry/vdso/vma.c (ffffffff81004b4a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_mremap
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a22d)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In arch/x86/kernel/process_64.c (ffffffff8102ce55)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:KSTK_ESP
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/signal.c (ffffffff8102de2c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/signal_compat.c (ffffffff8102dfa8)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:sigaction_compat_abi
```
```
In arch/x86/kernel/traps.c (ffffffff8102ec2c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_double_fault
```
```
In arch/x86/kernel/ioport.c (ffffffff8103177f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81031cd5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:in_task_stack
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff810348a1)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/kernel/process.c (ffffffff81039bf5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103b0c1)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:convert_from_fxsr
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103e66d)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff8103f5c3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810400a5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105aa5f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/perf_regs.c (ffffffff8106f946)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff81070629)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff8107ab49)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff8107eb59)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81085bda)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
```
In kernel/fork.c (ffffffff8108aeb5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/exit.c (ffffffff81092f24)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
```
```
In kernel/ptrace.c (ffffffff8109a2fd)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff8109cbd9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_to_user32
  - kernel/signal.c:get_signal
```
```
In kernel/sched/core.c (ffffffff810bacb7)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/sched/cpuacct.c (ffffffff810e3135)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/time/time.c (ffffffff81110eb9)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/compat.c (ffffffff8113a6da)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_alloc_user_space
```
```
In kernel/auditsc.c (ffffffff811585b9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff8116c0c9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:seccomp_init_siginfo
  - kernel/seccomp.c:populate_seccomp_data
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_stack.c (ffffffff8118d339)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_syscalls.c (ffffffff811967b3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/events/callchain.c (ffffffff811e36f5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/usercopy.c (ffffffff81291852)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - mm/usercopy.c:check_stack_object
```
```
In fs/binfmt_elf.c (ffffffff81304385)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81307c85)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/coredump.c (ffffffff8130c32a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff81321fb8)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/dir.c (ffffffff813379bd)
Location: include/linux/sched/task_stack.h:19
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
In block/blk-map.c (ffffffff81489b0e)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In lib/syscall.c (ffffffff814f0344)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/usb/core/hcd.c (ffffffff8175a396)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/input/input.c (ffffffff817be1a3)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff817c024f)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In drivers/input/evdev.c (ffffffff817c36ec)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
```
```
In drivers/input/misc/uinput.c (ffffffff817c96bb)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/firmware/efi/efivars.c (ffffffff818475ee)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/compat.c (ffffffff818c917f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:compat_sock_get_timestampns
  - net/compat.c:compat_sock_get_timestamp
  - net/compat.c:__compat_sys_setsockopt
  - net/compat.c:put_cmsg_compat
```
```
In net/xfrm/xfrm_state.c (ffffffff819512fc)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In arch/x86/entry/vdso/vma.c (ffffffff81004a8a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_mremap
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a87d)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In arch/x86/kernel/process_64.c (ffffffff8102e0a5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:KSTK_ESP
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/signal.c (ffffffff8102f06c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/signal_compat.c (ffffffff8102f1e8)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:sigaction_compat_abi
```
```
In arch/x86/kernel/traps.c (ffffffff8102fe5c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_double_fault
```
```
In arch/x86/kernel/ioport.c (ffffffff81032a8f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81032fd5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:in_task_stack
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff81035a81)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/kernel/process.c (ffffffff8103b150)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103c5c1)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:convert_from_fxsr
```
```
In arch/x86/kernel/ptrace.c (ffffffff8103fbde)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81040bc3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81041665)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_user
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk
```
```
In arch/x86/kernel/smpboot.c (ffffffff810606df)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810759a6)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff810765f9)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff81081489)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810856d9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8108c94a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
```
In kernel/fork.c (ffffffff81093025)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/exit.c (ffffffff8109b1f4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810a266f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810a4e99)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_to_user32
  - kernel/signal.c:get_signal
```
```
In kernel/sched/core.c (ffffffff810c4137)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/sched/cpuacct.c (ffffffff810ed865)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/time/time.c (ffffffff8111c479)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/compat.c (ffffffff81145f4a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_alloc_user_space
```
```
In kernel/auditsc.c (ffffffff811655ca)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff81179ae9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:seccomp_init_siginfo
```
```
In kernel/trace/trace_stack.c (ffffffff8119acb9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_syscalls.c (ffffffff811a48f3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/events/callchain.c (ffffffff811f3bc3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/usercopy.c (ffffffff812a6872)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - mm/usercopy.c:check_stack_object
```
```
In fs/binfmt_elf.c (ffffffff81319ad5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8131d495)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/coredump.c (ffffffff81321b8a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff813390c8)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/dir.c (ffffffff8134ec0d)
Location: include/linux/sched/task_stack.h:19
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
In block/blk-map.c (ffffffff814a394e)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In lib/syscall.c (ffffffff81504264)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/usb/core/hcd.c (ffffffff8177e916)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/input/input.c (ffffffff817e5603)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff817e773f)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In drivers/input/evdev.c (ffffffff817ea98f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
```
```
In drivers/input/misc/uinput.c (ffffffff817f0d6b)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/firmware/efi/efivars.c (ffffffff8187384e)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/compat.c (ffffffff818f402f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/compat.c:put_cmsg_compat
```
```
In net/xfrm/xfrm_state.c (ffffffff819847dc)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In arch/x86/entry/vdso/vma.c (ffffffff81004cfa)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_mremap
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102c6cc)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/kernel/process_64.c (ffffffff8102fe05)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:KSTK_ESP
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/signal.c (ffffffff81030e3c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/signal_compat.c (ffffffff81030fb8)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:sigaction_compat_abi
```
```
In arch/x86/kernel/traps.c (ffffffff81031c29)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_double_fault
```
```
In arch/x86/kernel/ioport.c (ffffffff8103489f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81034de5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:in_task_stack
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff81037bf0)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/kernel/process.c (ffffffff8103d73a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103eb21)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:convert_from_fxsr
```
```
In arch/x86/kernel/ptrace.c (ffffffff810422ac)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff810432a3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/smpboot.c (ffffffff81063e7c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/perf_regs.c (ffffffff81079596)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff8107a1a9)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff810850f9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810892d8)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8109081a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
```
In kernel/fork.c (ffffffff81097165)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/exit.c (ffffffff8109f854)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810a6b8b)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810a9b5a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:copy_siginfo_from_user_any
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_to_user32
  - kernel/signal.c:get_signal
```
```
In kernel/sched/core.c (ffffffff810c9f26)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/sched/cpuacct.c (ffffffff810f4605)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/stacktrace.c (ffffffff81126142)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/time/time.c (ffffffff81126b8f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/compat.c (ffffffff8115131a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_alloc_user_space
```
```
In kernel/auditsc.c (ffffffff8117212a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff81186164)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:seccomp_init_siginfo
```
```
In kernel/trace/trace_stack.c (ffffffff811a8893)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b2833)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/events/callchain.c (ffffffff8120b8ac)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/usercopy.c (ffffffff812c1f4e)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - mm/usercopy.c:check_stack_object
```
```
In fs/io_uring.c (ffffffff813310c0)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/binfmt_elf.c (ffffffff81341e04)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81345783)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/coredump.c (ffffffff813499bf)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff81361774)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/dir.c (ffffffff81377a47)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_dir_llseek
```
```
In fs/fuse/file.c (ffffffff8140cee9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In block/blk-map.c (ffffffff814d1b4f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In lib/syscall.c (ffffffff815323d1)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/usb/core/hcd.c (ffffffff817bce94)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/input/input.c (ffffffff81825d60)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff81828367)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff8182b2d9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
```
```
In drivers/input/misc/uinput.c (ffffffff818319fb)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/firmware/efi/efivars.c (ffffffff818b795e)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/socket.c (ffffffff818dbb99)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
```
```
In net/core/sock.c (ffffffff818df988)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/compat.c (ffffffff81954e61)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/compat.c:put_cmsg_compat
```
```
In net/xfrm/xfrm_state.c (ffffffff819ee4c3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In arch/x86/entry/vdso/vma.c (ffffffff81004d7a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_mremap
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102cf9c)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/kernel/process_64.c (ffffffff81030765)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:KSTK_ESP
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/signal.c (ffffffff810316fc)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/signal_compat.c (ffffffff81031878)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:sigaction_compat_abi
```
```
In arch/x86/kernel/traps.c (ffffffff810324e9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_double_fault
```
```
In arch/x86/kernel/ioport.c (ffffffff8103512f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81035615)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:in_task_stack
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff810383c0)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/kernel/process.c (ffffffff8103defa)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f231)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:convert_from_fxsr
```
```
In arch/x86/kernel/ptrace.c (ffffffff81042a2c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81043a03)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064521)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/perf_regs.c (ffffffff8107a5e6)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff8107b299)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff81085de9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81089f48)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8109145a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
```
In kernel/fork.c (ffffffff8109cc45)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/exit.c (ffffffff810a5ed4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810ad44f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810b013a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:copy_siginfo_from_user_any
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_to_user32
  - kernel/signal.c:get_signal
```
```
In kernel/sched/core.c (ffffffff810d3136)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/sched/cpuacct.c (ffffffff81100295)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/stacktrace.c (ffffffff81132112)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/time/time.c (ffffffff81132b2f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/compat.c (ffffffff8115cf6a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_alloc_user_space
```
```
In kernel/auditsc.c (ffffffff8117dfda)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff81191e34)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:seccomp_init_siginfo
```
```
In kernel/trace/trace_stack.c (ffffffff811b40b3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_syscalls.c (ffffffff811bde23)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/events/callchain.c (ffffffff81218b8c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/usercopy.c (ffffffff812d3e7e)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - mm/usercopy.c:check_stack_object
```
```
In fs/io_uring.c (ffffffff81344c64)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/binfmt_elf.c (ffffffff8135a234)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8135da6b)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/coredump.c (ffffffff81361c5f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff813799d4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/dir.c (ffffffff8138fdc7)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_dir_llseek
```
```
In fs/fuse/file.c (ffffffff81428344)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In block/blk-map.c (ffffffff814eaeff)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In lib/syscall.c (ffffffff81553211)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/usb/core/hcd.c (ffffffff817ed8c9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/input/input.c (ffffffff81857290)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff818598d7)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff8185cc49)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
```
```
In drivers/input/misc/uinput.c (ffffffff8186333b)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/firmware/efi/efivars.c (ffffffff818ea34e)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/socket.c (ffffffff8190ec4d)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
```
```
In net/core/sock.c (ffffffff81911b58)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/compat.c (ffffffff8198b2e1)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/compat.c:put_cmsg_compat
```
```
In net/xfrm/xfrm_state.c (ffffffff81a253a3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In arch/x86/entry/vdso/vma.c (ffffffff810056ba)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_mremap
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ef1e)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/process_64.c (ffffffff81032d85)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:KSTK_ESP
  - arch/x86/kernel/process_64.c:__set_personality_ia32
  - arch/x86/kernel/process_64.c:__set_personality_x32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/signal.c (ffffffff81033f5c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:copy_siginfo_to_user32
```
```
In arch/x86/kernel/signal_compat.c (ffffffff810340d8)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:sigaction_compat_abi
```
```
In arch/x86/kernel/traps.c (ffffffff81bbcfa3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_double_fault
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81037525)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:in_task_stack
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff8103ad7e)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/kernel/process.c (ffffffff81040fbf)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:copy_thread_tls
  - arch/x86/kernel/process.c:copy_thread_tls
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff810423e0)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:convert_from_fxsr
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104592e)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:set_flags
  - arch/x86/kernel/ptrace.c:set_segment_reg
  - arch/x86/kernel/ptrace.c:set_segment_reg
```
```
In arch/x86/kernel/step.c (ffffffff810472a3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106af81)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/perf_regs.c (ffffffff81081a39)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff810826bd)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff81089539)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff8109168f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81096b3a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
```
```
In kernel/fork.c (ffffffff810a3885)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/exit.c (ffffffff810ada77)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810b5351)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810b7cfa)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:get_signal
```
```
In kernel/sched/core.c (ffffffff810dcdd4)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/sched/cpuacct.c (ffffffff8110a972)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/power/user.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/stacktrace.c (ffffffff81141563)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/time/time.c (ffffffff81141d6f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/compat.c (ffffffff8116da9a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_alloc_user_space
```
```
In kernel/auditsc.c (ffffffff811913ca)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff811a7044)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:populate_seccomp_data
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_stack.c (ffffffff811cc8b8)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d7bbf)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/events/callchain.c (ffffffff8124485f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/usercopy.c (ffffffff81309bee)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - mm/usercopy.c:check_stack_object
```
```
In fs/io_uring.c (ffffffff81385885)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/binfmt_elf.c (ffffffff813a17a2)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff813a4a7a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/coredump.c (ffffffff813a7eef)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff813c2a88)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/dir.c (ffffffff813db397)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_dir_llseek
```
```
In fs/fuse/file.c (ffffffff81475ff2)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In block/blk-map.c (ffffffff81549ef3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In block/scsi_ioctl.c (ffffffff815670f1)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_put_cdrom_generic_arg
  - block/scsi_ioctl.c:scsi_get_cdrom_generic_arg
  - block/scsi_ioctl.c:get_sg_io_hdr
  - block/scsi_ioctl.c:put_sg_io_hdr
  - block/scsi_ioctl.c:sg_io
```
```
In lib/syscall.c (ffffffff815dc5f3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/scsi/sg.c (ffffffff8184f4b7)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_read
```
```
In drivers/ata/libata-scsi.c (ffffffff8185eeb0)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
```
```
In drivers/cdrom/cdrom.c (ffffffff818ae913)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
```
In drivers/usb/core/hcd.c (ffffffff818bcdb6)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/input/input.c (ffffffff81929280)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff8192c3ad)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_ff_effect_from_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff8192fdee)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
```
```
In drivers/input/misc/uinput.c (ffffffff8193722a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ff_upload_from_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_events_to_user
  - drivers/input/misc/uinput.c:uinput_events_to_user
  - drivers/input/misc/uinput.c:uinput_events_to_user
  - drivers/input/misc/uinput.c:uinput_events_to_user
  - drivers/input/misc/uinput.c:uinput_inject_events
  - drivers/input/misc/uinput.c:uinput_inject_events
  - drivers/input/misc/uinput.c:uinput_inject_events
  - drivers/input/misc/uinput.c:uinput_inject_events
  - drivers/input/misc/uinput.c:uinput_inject_events
  - drivers/input/misc/uinput.c:uinput_inject_events
```
```
In drivers/firmware/efi/efivars.c (ffffffff819bddbb)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/socket.c (ffffffff819e05d7)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
```
```
In net/core/sock.c (ffffffff819e39f7)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/compat.c (ffffffff81a62fc3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/compat.c:put_cmsg_compat
```
```
In net/xfrm/xfrm_state.c (ffffffff81b17323)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In arch/x86/entry/vdso/vma.c (ffffffff8100464a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_mremap
```
```
In arch/x86/events/intel/lbr.c (ffffffff810136a4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102fd2e)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/process_64.c (ffffffff81033a45)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:KSTK_ESP
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/signal.c (ffffffff810349db)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:copy_siginfo_to_user32
```
```
In arch/x86/kernel/signal_compat.c (ffffffff81034ade)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:sigaction_compat_abi
```
```
In arch/x86/kernel/traps.c (ffffffff81c35672)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_double_fault
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81038624)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_opcodes
  - arch/x86/kernel/dumpstack.c:in_task_stack
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff8103b58e)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/kernel/process.c (ffffffff81040f1f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:copy_thread
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff810423c0)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:convert_from_fxsr
```
```
In arch/x86/kernel/ptrace.c (ffffffff810453da)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:set_flags
  - arch/x86/kernel/ptrace.c:set_segment_reg
  - arch/x86/kernel/ptrace.c:set_segment_reg
```
```
In arch/x86/kernel/step.c (ffffffff81046af8)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_single_step
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106cbf1)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810814c1)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff8108216d)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff81089719)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81090fbf)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81095d69)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
```
```
In kernel/fork.c (ffffffff8109fbf5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/exit.c (ffffffff810a90f5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810b054b)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810b2faa)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:get_signal
```
```
In kernel/sched/core.c (ffffffff810d9654)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/sched/cpuacct.c (ffffffff81107846)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/power/user.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff8113bcd3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/stacktrace.c (ffffffff8113d7d5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/time/time.c (ffffffff8113df7f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/compat.c (ffffffff8116a06b)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
```
```
In kernel/auditsc.c (ffffffff8118e5ea)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff811a4724)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:populate_seccomp_data
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_stack.c (ffffffff811c9df8)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d4c8f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/bpf/stackmap.c (ffffffff81233eb0)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/events/callchain.c (ffffffff8124ef12)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/process_vm_access.c (ffffffff812b8e08)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - mm/process_vm_access.c:process_vm_rw
```
```
In mm/usercopy.c (ffffffff81315a0e)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - mm/usercopy.c:check_stack_object
```
```
In fs/io_uring.c (ffffffff813968b7)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/binfmt_elf.c (ffffffff813b29b0)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff813b5828)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/coredump.c (ffffffff813b8f6f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff813d4c16)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/dir.c (ffffffff813ecdc7)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_dir_llseek
```
```
In fs/fuse/file.c (ffffffff81490a4b)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In block/blk-map.c (ffffffff81565ca3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In block/scsi_ioctl.c (ffffffff81581f81)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_put_cdrom_generic_arg
  - block/scsi_ioctl.c:scsi_get_cdrom_generic_arg
  - block/scsi_ioctl.c:get_sg_io_hdr
  - block/scsi_ioctl.c:put_sg_io_hdr
```
```
In lib/iov_iter.c (ffffffff815a8fb9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - lib/iov_iter.c:import_iovec
```
```
In lib/syscall.c (ffffffff815fa273)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/scsi/sg.c (ffffffff81861355)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_read
```
```
In drivers/ata/libata-scsi.c (ffffffff8186ded9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
```
```
In drivers/cdrom/cdrom.c (ffffffff818bd6a3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
```
In drivers/usb/core/hcd.c (ffffffff818c9aa8)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/input/input.c (ffffffff81930880)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff8193389d)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_ff_effect_from_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff819370b8)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
```
```
In drivers/input/misc/uinput.c (ffffffff8193d61a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ff_upload_from_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_events_to_user
  - drivers/input/misc/uinput.c:uinput_events_to_user
  - drivers/input/misc/uinput.c:uinput_events_to_user
  - drivers/input/misc/uinput.c:uinput_events_to_user
  - drivers/input/misc/uinput.c:uinput_inject_events
  - drivers/input/misc/uinput.c:uinput_inject_events
  - drivers/input/misc/uinput.c:uinput_inject_events
  - drivers/input/misc/uinput.c:uinput_inject_events
  - drivers/input/misc/uinput.c:uinput_inject_events
  - drivers/input/misc/uinput.c:uinput_inject_events
```
```
In drivers/firmware/efi/efivars.c (ffffffff819bfa3b)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/socket.c (ffffffff819dfe45)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
```
```
In net/core/sock.c (ffffffff819e6bb1)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/core/filter.c (ffffffff81a2f045)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/core/filter.c:copy_bpf_fprog_from_user
```
```
In net/compat.c (ffffffff81a6b0e3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/compat.c:put_cmsg_compat
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aaaa47)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr
```
```
In net/xfrm/xfrm_state.c (ffffffff81b26409)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b5f767)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr
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
In arch/x86/entry/vdso/vma.c (ffffffff8100464a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_mremap
```
```
In arch/x86/events/intel/lbr.c (ffffffff81014823)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103083e)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/process_64.c (ffffffff81035585)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:KSTK_ESP
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/signal.c (ffffffff8103647c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:copy_siginfo_to_user32
```
```
In arch/x86/kernel/signal_compat.c (ffffffff8103655e)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:sigaction_compat_abi
```
```
In arch/x86/kernel/traps.c (ffffffff81c27b02)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_double_fault
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8103a160)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_opcodes
  - arch/x86/kernel/dumpstack.c:in_task_stack
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff8103cf6f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/kernel/process.c (ffffffff8104291b)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:copy_thread
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff81043dd0)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:convert_from_fxsr
```
```
In arch/x86/kernel/ptrace.c (ffffffff81047805)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:task_user_regset_view
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:set_flags
  - arch/x86/kernel/ptrace.c:set_segment_reg
  - arch/x86/kernel/ptrace.c:set_segment_reg
```
```
In arch/x86/kernel/step.c (ffffffff81048528)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106d68a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810822e4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff81082f8d)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff8108a429)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81091a95)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810966aa)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
```
```
In kernel/fork.c (ffffffff810a1435)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/exit.c (ffffffff810aa174)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810b1acb)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810b45da)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:get_signal
```
```
In kernel/sched/core.c (ffffffff810daf12)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/sched/cpuacct.c (ffffffff81109916)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/power/user.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff8113cfc3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/stacktrace.c (ffffffff8113ea25)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/time/time.c (ffffffff8113f1cf)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/compat.c (ffffffff8116ad4b)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
```
```
In kernel/auditsc.c (ffffffff8118f56a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff811a5214)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/trace_stack.c (ffffffff811cb1a8)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d64df)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/bpf/stackmap.c (ffffffff81237ca0)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/events/callchain.c (ffffffff81253822)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/process_vm_access.c (ffffffff812be2d0)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - mm/process_vm_access.c:process_vm_rw
```
```
In mm/usercopy.c (ffffffff8131bbfe)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - mm/usercopy.c:check_stack_object
```
```
In fs/io_uring.c (ffffffff81399c71)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/binfmt_elf.c (ffffffff813b9acb)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff813babd5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/coredump.c (ffffffff813bfecf)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff813dba4a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/dir.c (ffffffff813f32f7)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_dir_llseek
```
```
In fs/fuse/ioctl.c (ffffffff814a170b)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
```
```
In block/blk-map.c (ffffffff8156e160)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In block/scsi_ioctl.c (ffffffff815896dd)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_cdrom_send_packet
  - block/scsi_ioctl.c:scsi_cdrom_send_packet
  - block/scsi_ioctl.c:get_sg_io_hdr
  - block/scsi_ioctl.c:put_sg_io_hdr
```
```
In lib/iov_iter.c (ffffffff815b3bf9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - lib/iov_iter.c:import_iovec
```
```
In lib/syscall.c (ffffffff815dce4b)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/scsi/sg.c (ffffffff8184403e)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_read
```
```
In drivers/ata/libata-scsi.c (ffffffff8185047b)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
```
```
In drivers/cdrom/cdrom.c (ffffffff818a0303)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
```
In drivers/usb/core/hcd.c (ffffffff818acb29)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/input/input.c (ffffffff81913a02)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff81916bbd)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_ff_effect_from_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff8191aa28)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
```
```
In drivers/input/misc/uinput.c (ffffffff8192063a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ff_upload_from_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/firmware/efi/efivars.c (ffffffff819a413f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/socket.c (ffffffff819c5bab)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
```
```
In net/core/sock.c (ffffffff819cc9b1)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/core/filter.c (ffffffff81a156a5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/core/filter.c:copy_bpf_fprog_from_user
```
```
In net/compat.c (ffffffff81a53813)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/compat.c:put_cmsg_compat
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a96017)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr
```
```
In net/ipv4/tcp.c (ffffffff81aa3296)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81b13fa6)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4cc57)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr
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
In arch/x86/entry/vdso/vma.c (ffffffff81004c7a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_mremap
```
```
In arch/x86/events/intel/lbr.c (ffffffff81015bd3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103570d)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/process_64.c (ffffffff8103a865)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:KSTK_ESP
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/signal.c (ffffffff8103b71c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:copy_siginfo_to_user32
```
```
In arch/x86/kernel/signal_compat.c (ffffffff8103b7fe)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:sigaction_compat_abi
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8103fb10)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_opcodes
  - arch/x86/kernel/dumpstack.c:in_task_stack
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff81042a6f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/kernel/process.c (ffffffff81048c89)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:copy_thread
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff81049cf6)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:__convert_from_fxsr
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104e065)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:task_user_regset_view
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff8104ee68)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/smpboot.c (ffffffff81078ddb)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810912f4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff8109205f)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff81099989)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810a1615)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810a664a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
```
```
In kernel/fork.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/exit.c (ffffffff810bbcb4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810c3bbb)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810c67aa)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:get_signal
  - kernel/signal.c:force_sig_seccomp
```
```
In kernel/sched/core.c (ffffffff810eec03)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/power/user.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff811600e3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/stacktrace.c (ffffffff81161eb5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/time/time.c (ffffffff8116265f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/auditsc.c (ffffffff811b844a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff811ce964)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:populate_seccomp_data
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_stack.c (ffffffff811f74b9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/trace_syscalls.c (ffffffff8120336f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/bpf_trace.c (ffffffff81217df0)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_task_pt_regs
```
```
In kernel/bpf/stackmap.c (ffffffff81272270)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/events/callchain.c (ffffffff8128f162)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/process_vm_access.c (ffffffff81300a70)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - mm/process_vm_access.c:process_vm_rw
```
```
In mm/mempolicy.c (ffffffff81327e2c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:get_bitmap
```
```
In mm/migrate.c (ffffffff8133dea9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
```
```
In mm/usercopy.c (ffffffff81368ebe)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - mm/usercopy.c:check_stack_object
```
```
In fs/io_uring.c (ffffffff813e8d4e)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/binfmt_elf.c (ffffffff814097db)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8140a8d5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/coredump.c (ffffffff8140fcff)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff8142d0e4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/dir.c (ffffffff81445337)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_dir_llseek
```
```
In fs/fuse/ioctl.c (ffffffff814f97d2)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
```
```
In block/blk-map.c (ffffffff815d2620)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In lib/iov_iter.c (ffffffff81619d69)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - lib/iov_iter.c:import_iovec
```
```
In lib/syscall.c (ffffffff816487ab)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff818af6be)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:get_sg_io_hdr
  - drivers/scsi/scsi_ioctl.c:put_sg_io_hdr
```
```
In drivers/scsi/sg.c (ffffffff818d0b07)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_read
```
```
In drivers/ata/libata-scsi.c (ffffffff818ddc7b)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
```
```
In drivers/cdrom/cdrom.c (ffffffff81934c6c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
```
In drivers/usb/core/hcd.c (ffffffff81941b7a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/input/input.c (ffffffff819b5ae2)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff819b8e2d)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_ff_effect_from_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff819bcf3b)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
```
```
In drivers/input/misc/uinput.c (ffffffff819c343a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ff_upload_from_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/firmware/efi/efivars.c (ffffffff81a513df)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/socket.c (ffffffff81a752b3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:put_user_ifreq
  - net/socket.c:get_user_ifreq
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
```
```
In net/core/sock.c (ffffffff81a7c0f1)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/core/filter.c (ffffffff81ac70f5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/core/filter.c:copy_bpf_fprog_from_user
```
```
In net/core/dev_ioctl.c (ffffffff81ad1257)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_ifconf
```
```
In net/compat.c (ffffffff81b0c523)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/compat.c:put_cmsg_compat
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b51477)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:copy_group_source_from_sockptr
```
```
In net/ipv4/tcp.c (ffffffff81b5f46c)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd80a6)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81c13f67)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:copy_group_source_from_sockptr
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
In arch/x86/entry/vdso/vma.c (ffffffff81003d19)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_mremap
```
```
In arch/x86/events/intel/lbr.c (ffffffff81017d30)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:branch_type
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103b53c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/process_64.c (ffffffff81041965)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:KSTK_ESP
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/signal.c (ffffffff81042414)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810472a3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_opcodes
  - arch/x86/kernel/dumpstack.c:in_task_stack
```
```
In arch/x86/kernel/process.c (ffffffff81051f9a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
  - arch/x86/kernel/process.c:copy_thread
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff81053d7f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:__convert_from_fxsr
```
```
In arch/x86/kernel/ptrace.c (ffffffff810590e5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:task_user_regset_view
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff8105a0b8)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/smpboot.c (ffffffff81087bc7)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810a2425)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff810a32c9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810bb8c2)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
```
```
In kernel/ptrace.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/signal.c (ffffffff810de2e5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:get_signal
  - kernel/signal.c:force_sig_seccomp
```
```
In kernel/sched/core.c (ffffffff8110ba73)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff8118a5cb)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/stacktrace.c (ffffffff81194dc3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/auditsc.c (ffffffff811eb31a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff81203375)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:populate_seccomp_data
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_stack.c (ffffffff81231028)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/bpf_trace.c (ffffffff81255c20)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_task_pt_regs
```
```
In kernel/bpf/stackmap.c (ffffffff812c15ae)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/events/callchain.c (ffffffff812e40ef)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/usercopy.c (ffffffff813e6b3e)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - mm/usercopy.c:check_stack_object
```
```
In fs/binfmt_elf.c (ffffffff8147e514)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8147f655)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/coredump.c (ffffffff814856b1)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff814a6aa4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In block/blk-map.c (ffffffff8167e339)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In lib/syscall.c (ffffffff8175ebe3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/spi/spi-mem.c (ffffffff81a4ff1f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_check_op
  - drivers/spi/spi-mem.c:spi_mem_check_op
```
```
In drivers/usb/core/hcd.c (ffffffff81a9b1a9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
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
In arch/x86/entry/vdso/vma.c (ffffffff81004629)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_mremap
```
```
In arch/x86/events/utils.c (ffffffff8100b224)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/events/utils.c:get_branch_type
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043d0c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/process_64.c (ffffffff8104b0f5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:KSTK_ESP
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/signal_64.c (ffffffff8104bad4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81051517)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_opcodes
  - arch/x86/kernel/dumpstack.c:in_task_stack
```
```
In arch/x86/kernel/signal_32.c (ffffffff81055992)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:__do_compat_sys_rt_sigreturn
  - arch/x86/kernel/signal_32.c:__do_compat_sys_sigreturn
```
```
In arch/x86/kernel/process.c (ffffffff8105f7ca)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
  - arch/x86/kernel/process.c:copy_thread
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff810618ff)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:__convert_from_fxsr
```
```
In arch/x86/kernel/ptrace.c (ffffffff810669e5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:task_user_regset_view
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:set_flags
  - arch/x86/kernel/ptrace.c:get_flags
```
```
In arch/x86/kernel/step.c (ffffffff81067ac8)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109b557)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810ba5f5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff810bb689)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
```
```
In kernel/ptrace.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/signal.c (ffffffff810fe775)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:get_signal
  - kernel/signal.c:force_sig_seccomp
```
```
In kernel/sched/core.c (ffffffff81131e53)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff811c6b6b)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/stacktrace.c (ffffffff811d2ad3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/auditsc.c (ffffffff812316ba)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff8124b235)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:populate_seccomp_data
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_stack.c (ffffffff8127d498)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/bpf_trace.c (ffffffff812a5140)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_task_pt_regs
```
```
In kernel/bpf/stackmap.c (ffffffff81324eae)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/events/callchain.c (ffffffff8134c83f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/usercopy.c (ffffffff8146e65e)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - mm/usercopy.c:check_stack_object
```
```
In fs/binfmt_elf.c (ffffffff815112a4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff815127a5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/proc/array.c (ffffffff8153c0e4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In block/blk-map.c (ffffffff8173b019)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In lib/syscall.c (ffffffff8188c503)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/spi/spi-mem.c (ffffffff81bd900f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_check_op
  - drivers/spi/spi-mem.c:spi_mem_check_op
```
```
In drivers/usb/core/hcd.c (ffffffff81c1fff9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
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
In arch/x86/entry/vdso/vma.c (ffffffff81003de9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_mremap
```
```
In arch/x86/events/utils.c (ffffffff8100a9f4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/events/utils.c:get_branch_type
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043a1c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/process_64.c (ffffffff8104b995)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:KSTK_ESP
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/signal_64.c (ffffffff8104c364)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81052277)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_opcodes
  - arch/x86/kernel/dumpstack.c:in_task_stack
```
```
In arch/x86/kernel/signal_32.c (ffffffff810569b2)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:__do_compat_sys_rt_sigreturn
  - arch/x86/kernel/signal_32.c:__do_compat_sys_sigreturn
```
```
In arch/x86/kernel/process.c (ffffffff81060f22)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
  - arch/x86/kernel/process.c:copy_thread
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff810631cf)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:__convert_from_fxsr
```
```
In arch/x86/kernel/ptrace.c (ffffffff81068115)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:task_user_regset_view
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:set_flags
  - arch/x86/kernel/ptrace.c:get_flags
```
```
In arch/x86/kernel/step.c (ffffffff81069378)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109c43c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810bd7c5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff810be7c9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
```
```
In kernel/ptrace.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/signal.c (ffffffff8110a7e5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:get_signal
  - kernel/signal.c:force_sig_seccomp
```
```
In kernel/sched/core.c (ffffffff811400cb)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff811d988b)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/stacktrace.c (ffffffff811e6dc3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/auditsc.c (ffffffff8124834a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff81262553)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:populate_seccomp_data
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_stack.c (ffffffff81299f38)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/bpf_trace.c (ffffffff812c75f0)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_task_pt_regs
```
```
In kernel/bpf/stackmap.c (ffffffff81355106)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/events/callchain.c (ffffffff8137d88f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/usercopy.c (ffffffff814a2e0e)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - mm/usercopy.c:check_stack_object
```
```
In fs/binfmt_elf.c (ffffffff81548bd6)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8154a1e5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/proc/array.c (ffffffff81574407)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In block/blk-map.c (ffffffff81777930)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In lib/syscall.c (ffffffff818ce96b)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/spi/spi-mem.c (ffffffff81c2fa0c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_check_op
  - drivers/spi/spi-mem.c:spi_mem_check_op
```
```
In drivers/usb/core/hcd.c (ffffffff81c86f79)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/hv/hv_common.c (ffffffff81deb1ed)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:hv_die_panic_notify_crash
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
In arch/x86/entry/vdso/vma.c (ffffffff810066f9)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_mremap
```
```
In arch/x86/events/utils.c (ffffffff81010170)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - arch/x86/events/utils.c:get_branch_type
```
```
In arch/x86/xen/smp_pv.c (ffffffff81049f1c)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/process_64.c (ffffffff81052c15)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:KSTK_ESP
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/signal_64.c (ffffffff810535e4)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81059497)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_opcodes
  - arch/x86/kernel/dumpstack.c:in_task_stack
```
```
In arch/x86/kernel/signal_32.c (ffffffff8105dc02)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:__do_compat_sys_rt_sigreturn
  - arch/x86/kernel/signal_32.c:__do_compat_sys_sigreturn
```
```
In arch/x86/kernel/process.c (ffffffff81067fd2)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
  - arch/x86/kernel/process.c:copy_thread
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8106a4bf)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:__convert_from_fxsr
```
```
In arch/x86/kernel/ptrace.c (ffffffff8106f595)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:task_user_regset_view
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:getreg
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:set_flags
  - arch/x86/kernel/ptrace.c:get_flags
```
```
In arch/x86/kernel/step.c (ffffffff810707e8)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a39dc)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810c4945)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff810c5949)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
```
```
In kernel/ptrace.c (0)
Location: include/linux/sched/task_stack.h:20
Inline: True
```
```
In kernel/signal.c (ffffffff81114185)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:get_signal
  - kernel/signal.c:force_sig_seccomp
```
```
In kernel/sched/core.c (ffffffff8114b02b)
Location: include/linux/sched/task_stack.h:20
Inline: True
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff811ef53b)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/stacktrace.c (ffffffff811fcb13)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/auditsc.c (ffffffff812621aa)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff8127c793)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:populate_seccomp_data
  - kernel/seccomp.c:populate_seccomp_data
```
```
In kernel/trace/trace_stack.c (ffffffff812b55b8)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
```
```
In kernel/trace/bpf_trace.c (ffffffff812e3fb0)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_task_pt_regs
```
```
In kernel/bpf/stackmap.c (ffffffff8137dad6)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/events/callchain.c (ffffffff813a6aef)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/usercopy.c (ffffffff814d3c9e)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - mm/usercopy.c:check_stack_object
```
```
In fs/binfmt_elf.c (ffffffff8157df97)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8157f202)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:fill_thread_core_info
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/proc/array.c (ffffffff815ace8b)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In block/blk-map.c (ffffffff817b9b50)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In lib/syscall.c (ffffffff8192074b)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/spi/spi-mem.c (ffffffff81ce28cc)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_check_op
  - drivers/spi/spi-mem.c:spi_mem_check_op
```
```
In drivers/usb/core/hcd.c (ffffffff81d3b9d9)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/hv/hv_common.c (ffffffff81ea148d)
Location: include/linux/sched/task_stack.h:20
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:hv_die_panic_notify_crash
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/debug-monitors.c (ffff800010086b84)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/arm64/kernel/debug-monitors.c:user_fastforward_single_step
  - arch/arm64/kernel/debug-monitors.c:send_user_sigtrap
```
```
In arch/arm64/kernel/process.c (ffff800010089644)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/arm64/kernel/process.c:get_wchan
  - arch/arm64/kernel/process.c:__switch_to
  - arch/arm64/kernel/process.c:copy_thread_tls
  - arch/arm64/kernel/process.c:copy_thread_tls
```
```
In arch/arm64/kernel/ptrace.c (ffff80001008e934)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:compat_arch_ptrace
  - arch/arm64/kernel/ptrace.c:compat_gpr_set
  - arch/arm64/kernel/ptrace.c:compat_gpr_set
  - arch/arm64/kernel/ptrace.c:system_call_set
  - arch/arm64/kernel/ptrace.c:system_call_get
  - arch/arm64/kernel/ptrace.c:gpr_set
  - arch/arm64/kernel/ptrace.c:gpr_set
  - arch/arm64/kernel/ptrace.c:gpr_get
```
```
In arch/arm64/kernel/signal.c (ffff800010093178)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/arm64/kernel/signal.c:__arm64_sys_rt_sigreturn
```
```
In arch/arm64/kernel/stacktrace.c (ffff800010093be4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/arm64/kernel/stacktrace.c:__save_stack_trace
  - arch/arm64/kernel/stacktrace.c:unwind_frame
```
```
In arch/arm64/kernel/traps.c (ffff800010095044)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/arm64/kernel/traps.c:force_signal_inject
  - arch/arm64/kernel/traps.c:arm64_show_signal
  - arch/arm64/kernel/traps.c:dump_backtrace
```
```
In arch/arm64/kernel/smp.c (ffff80001009c01c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:__cpu_up
```
```
In arch/arm64/kernel/signal32.c (ffff80001009fec8)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/arm64/kernel/signal32.c:__arm64_compat_sys_rt_sigreturn
  - arch/arm64/kernel/signal32.c:__arm64_compat_sys_sigreturn
```
```
In arch/arm64/kernel/perf_regs.c (ffff8000100a33f4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/arm64/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/arm64/kernel/ssbd.c (ffff8000100ac014)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set
  - arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set
```
```
In kernel/fork.c (ffff8000100f1048)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/ptrace.c (ffff800010107848)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/signal.c (ffff80001010c158)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__arm64_sys_sigaltstack
  - kernel/signal.c:get_signal
```
```
In kernel/sched/core.c (ffff8000101334d0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/sched/cpuacct.c (ffff8000101648f4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/compat.c (ffff8000101cb7d0)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
```
```
In kernel/auditsc.c (ffff8000101f2e6c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffff80001020a1dc)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:seccomp_init_siginfo
```
```
In kernel/trace/trace_stack.c (ffff8000102324b4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/events/callchain.c (ffff8000102a3968)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/util.c (ffff8000102d8964)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - mm/util.c:vma_is_stack_for_current
```
```
In mm/usercopy.c (ffff800010379e18)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - mm/usercopy.c:check_stack_object
```
```
In fs/binfmt_elf.c (ffff80001041f8c8)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffff800010423250)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/coredump.c (0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In fs/proc/array.c (ffff800010445cb0)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In block/blk-map.c (ffff8000105e9634)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In lib/syscall.c (ffff80001065f53c)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In drivers/usb/core/hcd.c (ffff800010a1c83c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/signal_32.c (c00000000001f00c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal_32.c:compat_sys_sigreturn
  - arch/powerpc/kernel/signal_32.c:compat_sys_rt_sigreturn
  - arch/powerpc/kernel/signal_32.c:__do_compat_sys_swapcontext
```
```
In arch/powerpc/kernel/process.c (c000000000022aec)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/powerpc/kernel/process.c:show_stack
  - arch/powerpc/kernel/process.c:get_wchan
  - arch/powerpc/kernel/process.c:start_thread
  - arch/powerpc/kernel/process.c:copy_thread_tls
  - arch/powerpc/kernel/process.c:copy_thread_tls
```
```
In arch/powerpc/kernel/signal_64.c (c000000000033f40)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal_64.c:sys_rt_sigreturn
```
```
In arch/powerpc/kernel/smp.c (c000000000055b8c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:__cpu_up
```
```
In arch/powerpc/kernel/stacktrace.c (c000000000069758)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/powerpc/kernel/stacktrace.c:save_stack_trace_tsk_reliable
```
```
In kernel/fork.c (c000000000136c80)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/signal.c (c00000000015297c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__se_sys_sigaltstack
```
```
In kernel/sched/core.c (c00000000017e490)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/trace/trace_stack.c (c0000000002bcd78)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In mm/usercopy.c (c00000000046d1fc)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - mm/usercopy.c:check_stack_object
```
```
In fs/binfmt_elf.c (c00000000052e6ac)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (c000000000532348)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/proc/array.c (c00000000055adec)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In block/blk-map.c (c00000000077e650)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In lib/syscall.c (c0000000008120f8)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In drivers/usb/core/hcd.c (c000000000ad7ccc)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/process.c (ffffffe0000b5ad6)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/riscv/kernel/process.c:copy_thread_tls
  - arch/riscv/kernel/process.c:copy_thread_tls
  - arch/riscv/kernel/process.c:arch_dup_task_struct
  - arch/riscv/kernel/process.c:flush_thread
```
```
In arch/riscv/kernel/ptrace.c (ffffffe0000b5fa6)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/riscv/kernel/ptrace.c:riscv_gpr_set
  - arch/riscv/kernel/ptrace.c:riscv_gpr_get
```
```
In arch/riscv/kernel/signal.c (ffffffe0000b686e)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/riscv/kernel/signal.c:sys_rt_sigreturn
```
```
In arch/riscv/kernel/smpboot.c (ffffffe0000b7ae4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/riscv/kernel/smpboot.c:__cpu_up
```
```
In arch/riscv/kernel/perf_regs.c (ffffffe0000b9ada)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/riscv/kernel/perf_regs.c:perf_get_regs_user
```
```
In kernel/fork.c (ffffffe0000be6f2)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/ptrace.c (ffffffe0000cb830)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/signal.c (ffffffe0000d1cfe)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:get_signal
```
```
In kernel/sched/core.c (ffffffe0008c507c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
```
```
In kernel/sched/cpuacct.c (ffffffe000108168)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/auditsc.c (ffffffe00016644a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffe00016c022)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/trace/trace_stack.c (ffffffe000189c0c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/events/callchain.c (ffffffe0001d1f66)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/util.c (ffffffe0001f2f2c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - mm/util.c:vma_is_stack_for_current
```
```
In mm/usercopy.c (ffffffe0002510d4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - mm/usercopy.c:check_stack_object
```
```
In fs/binfmt_elf.c (ffffffe0002c24a8)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/binfmt_flat.c (ffffffe0002c3a4a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/binfmt_flat.c:load_flat_binary
```
```
In fs/coredump.c (ffffffe0002c65f4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffe0002db3b4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In block/blk-map.c (ffffffe000429e6c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In lib/syscall.c (ffffffe00048c57c)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffe000641590)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
</details>
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
In arch/x86/entry/vdso/vma.c (ffffffff81004d7a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_mremap
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102d0fc)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/kernel/process_64.c (ffffffff810308c5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:KSTK_ESP
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/signal.c (ffffffff8103185c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/signal_compat.c (ffffffff810319d8)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:sigaction_compat_abi
```
```
In arch/x86/kernel/traps.c (ffffffff81032649)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_double_fault
```
```
In arch/x86/kernel/ioport.c (ffffffff8103528f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81035775)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:in_task_stack
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff81038520)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/kernel/process.c (ffffffff8103e07a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f3b1)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:convert_from_fxsr
```
```
In arch/x86/kernel/ptrace.c (ffffffff81042bac)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81043b83)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064011)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/perf_regs.c (ffffffff810795e6)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff8107a299)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff81084de9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81088f08)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8109041a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
```
In kernel/fork.c (ffffffff81096565)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/exit.c (ffffffff8109f7f4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810a77bf)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810aa4aa)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:copy_siginfo_from_user_any
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_to_user32
  - kernel/signal.c:get_signal
```
```
In kernel/sched/core.c (ffffffff810cd456)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/sched/cpuacct.c (ffffffff810f95a5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/stacktrace.c (ffffffff8112a8c2)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/time/time.c (ffffffff8112b2df)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/compat.c (ffffffff8115558a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_alloc_user_space
```
```
In kernel/auditsc.c (ffffffff811765fa)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff8118a454)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:seccomp_init_siginfo
```
```
In kernel/trace/trace_stack.c (ffffffff811ac6d3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b6443)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/events/callchain.c (ffffffff812111dc)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/usercopy.c (ffffffff812cc45e)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - mm/usercopy.c:check_stack_object
```
```
In fs/io_uring.c (ffffffff8133d244)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/binfmt_elf.c (ffffffff81352814)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8135604b)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/coredump.c (ffffffff8135a23f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff81371fb4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/dir.c (ffffffff813883a7)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_dir_llseek
```
```
In fs/fuse/file.c (ffffffff81420924)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In block/blk-map.c (ffffffff814e34df)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In lib/syscall.c (ffffffff8154b7f1)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/usb/core/hcd.c (ffffffff817a5ca9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/input/input.c (ffffffff8180c2a0)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff8180e8e7)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff81811c59)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
```
```
In drivers/input/misc/uinput.c (ffffffff81815feb)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/firmware/efi/efivars.c (ffffffff8188d0ce)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/socket.c (ffffffff818aec4d)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
```
```
In net/core/sock.c (ffffffff818b1b58)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/compat.c (ffffffff8192b151)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/compat.c:put_cmsg_compat
```
```
In net/xfrm/xfrm_state.c (ffffffff819c4a33)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In arch/x86/entry/vdso/vma.c (ffffffff8100345a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_mremap
```
```
In arch/x86/kernel/process_64.c (ffffffff81020355)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:KSTK_ESP
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/signal.c (ffffffff8102123c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/signal_compat.c (ffffffff810213b8)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:sigaction_compat_abi
```
```
In arch/x86/kernel/traps.c (ffffffff81021fa9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_double_fault
```
```
In arch/x86/kernel/ioport.c (ffffffff81024bcf)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810250c5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:in_task_stack
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff81027f00)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/kernel/process.c (ffffffff8102d88a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8102ebb1)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:convert_from_fxsr
```
```
In arch/x86/kernel/ptrace.c (ffffffff81032218)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff810331b3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054311)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/perf_regs.c (ffffffff81068d66)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff810699c9)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff81073ab9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81077b68)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107ef2a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
```
In kernel/fork.c (ffffffff81084fe5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/exit.c (ffffffff8108e224)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
```
```
In kernel/ptrace.c (ffffffff8109619f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff81098e5a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:copy_siginfo_from_user_any
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_to_user32
  - kernel/signal.c:get_signal
```
```
In kernel/sched/core.c (ffffffff810bbcb6)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/sched/cpuacct.c (ffffffff810e9785)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/stacktrace.c (ffffffff8111d132)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/time/time.c (ffffffff8111db4f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/compat.c (ffffffff811488aa)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_alloc_user_space
```
```
In kernel/auditsc.c (ffffffff8116979a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff8117d584)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:seccomp_init_siginfo
```
```
In kernel/trace/trace_stack.c (ffffffff8119f423)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_syscalls.c (ffffffff811a9243)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/events/callchain.c (ffffffff81203f6c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/usercopy.c (ffffffff812bd2ce)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - mm/usercopy.c:check_stack_object
```
```
In fs/io_uring.c (ffffffff8132df04)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/binfmt_elf.c (ffffffff813434f4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81346d0b)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/coredump.c (ffffffff8134aeef)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff81362a8d)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/dir.c (ffffffff81378e37)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_dir_llseek
```
```
In fs/fuse/file.c (ffffffff814113a4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In block/blk-map.c (ffffffff814d3e5f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In lib/syscall.c (ffffffff8153bad1)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/usb/core/hcd.c (ffffffff817981d9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/input/input.c (ffffffff817d3a10)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff817d6037)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff817d9399)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
```
```
In drivers/input/misc/uinput.c (ffffffff817dd6eb)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/firmware/efi/efivars.c (ffffffff81844a4e)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In drivers/hv/vmbus_drv.c (ffffffff8184e57f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/hv/vmbus_drv.c:hyperv_panic_event
```
```
In net/socket.c (ffffffff81868b9d)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
```
```
In net/core/sock.c (ffffffff8186baa8)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/compat.c (ffffffff818e4f01)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/compat.c:put_cmsg_compat
```
```
In net/xfrm/xfrm_state.c (ffffffff81981823)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In arch/x86/entry/vdso/vma.c (ffffffff81004d3a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_mremap
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102cf5c)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/kernel/process_64.c (ffffffff81030725)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:KSTK_ESP
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/signal.c (ffffffff810316bc)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/signal_compat.c (ffffffff81031838)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:sigaction_compat_abi
```
```
In arch/x86/kernel/traps.c (ffffffff810324a9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_double_fault
```
```
In arch/x86/kernel/ioport.c (ffffffff810350ef)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810355d5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:in_task_stack
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff81038380)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/kernel/process.c (ffffffff8103deba)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f1f1)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:convert_from_fxsr
```
```
In arch/x86/kernel/ptrace.c (ffffffff810429ec)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff810439c3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/smpboot.c (ffffffff810644c1)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/perf_regs.c (ffffffff81079596)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff8107a249)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff81084d99)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81088eb8)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810903ca)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
```
In kernel/fork.c (ffffffff81096515)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/exit.c (ffffffff8109f7a4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810a6d1f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810a9a0a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:copy_siginfo_from_user_any
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_to_user32
  - kernel/signal.c:get_signal
```
```
In kernel/sched/core.c (ffffffff810cc936)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/sched/cpuacct.c (ffffffff810f67c5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/stacktrace.c (ffffffff811285e2)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/time/time.c (ffffffff81128fff)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/compat.c (ffffffff8115335a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_alloc_user_space
```
```
In kernel/auditsc.c (ffffffff811743ca)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff81188224)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:seccomp_init_siginfo
```
```
In kernel/trace/trace_stack.c (ffffffff811aa4a3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_syscalls.c (ffffffff811b4213)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/events/callchain.c (ffffffff8120ef7c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/usercopy.c (ffffffff812ca26e)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - mm/usercopy.c:check_stack_object
```
```
In fs/io_uring.c (ffffffff8133ad14)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/binfmt_elf.c (ffffffff813502e4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81353b1b)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/coredump.c (ffffffff81357d0f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff8136fa84)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/dir.c (ffffffff81385d07)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_dir_llseek
```
```
In fs/fuse/file.c (ffffffff8141cac4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In block/blk-map.c (ffffffff814df56f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In lib/syscall.c (ffffffff81547531)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/usb/core/hcd.c (ffffffff817e2749)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/input/input.c (ffffffff8184b420)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff8184da67)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff81850dd9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
```
```
In drivers/input/misc/uinput.c (ffffffff818574cb)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/firmware/efi/efivars.c (ffffffff818df1ae)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/socket.c (ffffffff818ffc4d)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
```
```
In net/core/sock.c (ffffffff81902b58)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/compat.c (ffffffff8197c2e1)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/compat.c:put_cmsg_compat
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2f4b3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
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
In arch/x86/entry/vdso/vma.c (ffffffff81004e7a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_mremap
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102dd4c)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/kernel/process_64.c (ffffffff810315b5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:KSTK_ESP
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_ia32
  - arch/x86/kernel/process_64.c:set_personality_64bit
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/process_64.c:copy_thread_tls
```
```
In arch/x86/kernel/signal.c (ffffffff8103256c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
```
In arch/x86/kernel/signal_compat.c (ffffffff810326e8)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:sigaction_compat_abi
```
```
In arch/x86/kernel/traps.c (ffffffff810333f4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_double_fault
```
```
In arch/x86/kernel/ioport.c (ffffffff8103602f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810365b5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:in_task_stack
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff81039380)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
```
```
In arch/x86/kernel/process.c (ffffffff8103f01a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff810404d1)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:convert_from_fxsr
```
```
In arch/x86/kernel/ptrace.c (ffffffff81043dcc)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:getreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:set_flags
```
```
In arch/x86/kernel/step.c (ffffffff81044dc3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:user_disable_single_step
  - arch/x86/kernel/step.c:enable_step
```
```
In arch/x86/kernel/smpboot.c (ffffffff81065a81)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/perf_regs.c (ffffffff8107b696)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff8107c349)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff81086ee9)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:get_mmap_base
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff8108b158)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810927aa)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
```
In kernel/fork.c (ffffffff8109e0f5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In kernel/exit.c (ffffffff810a7704)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
```
```
In kernel/ptrace.c (ffffffff810aefef)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_peek_siginfo
```
```
In kernel/signal.c (ffffffff810b1e5a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:copy_siginfo_from_user_any
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_to_user32
  - kernel/signal.c:get_signal
```
```
In kernel/sched/core.c (ffffffff810d52c8)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In kernel/sched/cpuacct.c (ffffffff811017e5)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/stacktrace.c (ffffffff81134c72)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/time/time.c (ffffffff8113564f)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/time/time.c:get_timespec64
```
```
In kernel/compat.c (ffffffff8116025a)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_alloc_user_space
```
```
In kernel/auditsc.c (ffffffff81181caa)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:audit_seccomp
```
```
In kernel/seccomp.c (ffffffff81195b84)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:seccomp_init_siginfo
```
```
In kernel/trace/trace_stack.c (ffffffff811b82f7)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_syscalls.c (ffffffff811c22b3)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:perf_syscall_exit
  - kernel/trace/trace_syscalls.c:perf_syscall_enter
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/events/callchain.c (ffffffff8121de8c)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
```
In mm/usercopy.c (ffffffff812daf6e)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - mm/usercopy.c:check_stack_object
```
```
In fs/io_uring.c (ffffffff8134dec4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_cqring_wait
```
```
In fs/binfmt_elf.c (ffffffff81363864)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff813672db)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/coredump.c (ffffffff8136b3ef)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff81383414)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/ext4/dir.c (ffffffff813999f7)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_dir_llseek
```
```
In fs/fuse/file.c (ffffffff814338a4)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In block/blk-map.c (ffffffff814f83df)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_kern
```
```
In lib/syscall.c (ffffffff81561381)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/usb/core/hcd.c (ffffffff817fd499)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/input/input.c (ffffffff81866680)
Location: include/linux/sched/task_stack.h:19
Inline: True
```
```
In drivers/input/input-compat.c (ffffffff81868c37)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/evdev.c (ffffffff8186c869)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_read
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
  - drivers/input/evdev.c:evdev_write
```
```
In drivers/input/misc/uinput.c (ffffffff818725eb)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_read
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/firmware/efi/efivars.c (ffffffff818fbc4e)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_delete
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In net/socket.c (ffffffff81920c3d)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
```
```
In net/core/sock.c (ffffffff81923af8)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_get_timeout
  - net/core/sock.c:sock_get_timeout
```
```
In net/compat.c (ffffffff8199e831)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/compat.c:put_cmsg_compat
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3ae03)
Location: include/linux/sched/task_stack.h:19
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
</details>
</li>
</ul>

## Differences
