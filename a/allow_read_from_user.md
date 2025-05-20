# Function: <code>allow_read_from_user</code>

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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/powerpc/kernel/ptrace.c (c0000000000160bc)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:pmu_set
  - arch/powerpc/kernel/ptrace.c:pmu_set
  - arch/powerpc/kernel/ptrace.c:ebb_set
  - arch/powerpc/kernel/ptrace.c:ebb_set
  - arch/powerpc/kernel/ptrace.c:ebb_set
  - arch/powerpc/kernel/ptrace.c:ebb_set
  - arch/powerpc/kernel/ptrace.c:ebb_set
  - arch/powerpc/kernel/ptrace.c:ebb_set
  - arch/powerpc/kernel/ptrace.c:tar_set
  - arch/powerpc/kernel/ptrace.c:tar_set
  - arch/powerpc/kernel/ptrace.c:dscr_set
  - arch/powerpc/kernel/ptrace.c:dscr_set
  - arch/powerpc/kernel/ptrace.c:ppr_set
  - arch/powerpc/kernel/ptrace.c:ppr_set
  - arch/powerpc/kernel/ptrace.c:tm_dscr_set
  - arch/powerpc/kernel/ptrace.c:tm_dscr_set
  - arch/powerpc/kernel/ptrace.c:tm_ppr_set
  - arch/powerpc/kernel/ptrace.c:tm_ppr_set
  - arch/powerpc/kernel/ptrace.c:tm_tar_set
  - arch/powerpc/kernel/ptrace.c:tm_tar_set
  - arch/powerpc/kernel/ptrace.c:tm_spr_set
  - arch/powerpc/kernel/ptrace.c:tm_spr_set
  - arch/powerpc/kernel/ptrace.c:tm_cvmx_set
  - arch/powerpc/kernel/ptrace.c:tm_cvmx_set
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_set
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_set
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_set
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_set
  - arch/powerpc/kernel/ptrace.c:vr_set
  - arch/powerpc/kernel/ptrace.c:vr_set
  - arch/powerpc/kernel/ptrace.c:gpr_set
  - arch/powerpc/kernel/ptrace.c:gpr_set
  - arch/powerpc/kernel/ptrace.c:gpr_set
  - arch/powerpc/kernel/ptrace.c:gpr_set
```
```
In arch/powerpc/kernel/align.c (c00000000001c3bc)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - arch/powerpc/kernel/align.c:fix_alignment
```
```
In arch/powerpc/kernel/signal_32.c (c00000000001f0b8)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal_32.c:compat_sys_sigreturn
  - arch/powerpc/kernel/signal_32.c:compat_sys_sigreturn
  - arch/powerpc/kernel/signal_32.c:compat_sys_rt_sigreturn
  - arch/powerpc/kernel/signal_32.c:compat_sys_rt_sigreturn
  - arch/powerpc/kernel/signal_32.c:compat_sys_rt_sigreturn
  - arch/powerpc/kernel/signal_32.c:compat_sys_rt_sigreturn
  - arch/powerpc/kernel/signal_32.c:compat_sys_rt_sigreturn
  - arch/powerpc/kernel/signal_32.c:compat_sys_rt_sigreturn
  - arch/powerpc/kernel/signal_32.c:compat_sys_rt_sigreturn
  - arch/powerpc/kernel/signal_32.c:compat_sys_rt_sigreturn
  - arch/powerpc/kernel/signal_32.c:compat_sys_rt_sigreturn
  - arch/powerpc/kernel/signal_32.c:compat_sys_rt_sigreturn
  - arch/powerpc/kernel/signal_32.c:__do_compat_sys_swapcontext
  - arch/powerpc/kernel/signal_32.c:__do_compat_sys_swapcontext
  - arch/powerpc/kernel/signal_32.c:__do_compat_sys_swapcontext
  - arch/powerpc/kernel/signal_32.c:__do_compat_sys_swapcontext
  - arch/powerpc/kernel/signal_32.c:__do_compat_sys_swapcontext
  - arch/powerpc/kernel/signal_32.c:__do_compat_sys_swapcontext
  - arch/powerpc/kernel/signal_32.c:__do_compat_sys_swapcontext
  - arch/powerpc/kernel/signal_32.c:__do_compat_sys_swapcontext
  - arch/powerpc/kernel/signal_32.c:do_setcontext
  - arch/powerpc/kernel/signal_32.c:do_setcontext
  - arch/powerpc/kernel/signal_32.c:restore_user_regs
  - arch/powerpc/kernel/signal_32.c:restore_user_regs
  - arch/powerpc/kernel/signal_32.c:restore_user_regs
  - arch/powerpc/kernel/signal_32.c:restore_user_regs
  - arch/powerpc/kernel/signal_32.c:restore_user_regs
  - arch/powerpc/kernel/signal_32.c:restore_user_regs
  - arch/powerpc/kernel/signal_32.c:restore_user_regs
  - arch/powerpc/kernel/signal_32.c:restore_user_regs
  - arch/powerpc/kernel/signal_32.c:copy_ckvsx_from_user
  - arch/powerpc/kernel/signal_32.c:copy_ckvsx_from_user
  - arch/powerpc/kernel/signal_32.c:copy_ckfpr_from_user
  - arch/powerpc/kernel/signal_32.c:copy_ckfpr_from_user
  - arch/powerpc/kernel/signal_32.c:copy_vsx_from_user
  - arch/powerpc/kernel/signal_32.c:copy_vsx_from_user
  - arch/powerpc/kernel/signal_32.c:copy_fpr_from_user
  - arch/powerpc/kernel/signal_32.c:copy_fpr_from_user
```
```
In arch/powerpc/kernel/process.c (c000000000021014)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - arch/powerpc/kernel/process.c:start_thread
  - arch/powerpc/kernel/process.c:start_thread
  - arch/powerpc/kernel/process.c:start_thread
  - arch/powerpc/kernel/process.c:start_thread
```
```
In arch/powerpc/kernel/traps.c (c00000000002edb0)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - arch/powerpc/kernel/traps.c:facility_unavailable_exception
  - arch/powerpc/kernel/traps.c:facility_unavailable_exception
  - arch/powerpc/kernel/traps.c:emulate_instruction
  - arch/powerpc/kernel/traps.c:emulate_instruction
  - arch/powerpc/kernel/traps.c:emulate_instruction
  - arch/powerpc/kernel/traps.c:emulate_instruction
  - arch/powerpc/kernel/traps.c:p9_hmi_special_emu
  - arch/powerpc/kernel/traps.c:p9_hmi_special_emu
  - arch/powerpc/kernel/traps.c:p9_hmi_special_emu
  - arch/powerpc/kernel/traps.c:p9_hmi_special_emu
```
```
In arch/powerpc/kernel/signal_64.c (c000000000034b98)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
  - arch/powerpc/kernel/signal_64.c:sys_rt_sigreturn
  - arch/powerpc/kernel/signal_64.c:sys_rt_sigreturn
  - arch/powerpc/kernel/signal_64.c:sys_rt_sigreturn
  - arch/powerpc/kernel/signal_64.c:sys_rt_sigreturn
  - arch/powerpc/kernel/signal_64.c:sys_rt_sigreturn
  - arch/powerpc/kernel/signal_64.c:sys_rt_sigreturn
  - arch/powerpc/kernel/signal_64.c:sys_rt_sigreturn
  - arch/powerpc/kernel/signal_64.c:sys_rt_sigreturn
  - arch/powerpc/kernel/signal_64.c:__se_sys_swapcontext
  - arch/powerpc/kernel/signal_64.c:__se_sys_swapcontext
  - arch/powerpc/kernel/signal_64.c:__se_sys_swapcontext
  - arch/powerpc/kernel/signal_64.c:__se_sys_swapcontext
  - arch/powerpc/kernel/signal_64.c:__se_sys_swapcontext
  - arch/powerpc/kernel/signal_64.c:__se_sys_swapcontext
  - arch/powerpc/kernel/signal_64.c:__se_sys_swapcontext
  - arch/powerpc/kernel/signal_64.c:__se_sys_swapcontext
  - arch/powerpc/kernel/signal_64.c:__se_sys_swapcontext
  - arch/powerpc/kernel/signal_64.c:__se_sys_swapcontext
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
  - arch/powerpc/kernel/signal_64.c:restore_tm_sigcontexts
```
```
In arch/powerpc/kernel/ptrace32.c (c0000000000352f0)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace32.c:compat_arch_ptrace
  - arch/powerpc/kernel/ptrace32.c:compat_arch_ptrace
  - arch/powerpc/kernel/ptrace32.c:compat_arch_ptrace
  - arch/powerpc/kernel/ptrace32.c:compat_arch_ptrace
```
```
In arch/powerpc/kernel/hw_breakpoint.c (c0000000000381a4)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - arch/powerpc/kernel/hw_breakpoint.c:hw_breakpoint_handler
```
```
In arch/powerpc/kernel/vecemu.c (c00000000003bca0)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - arch/powerpc/kernel/vecemu.c:emulate_altivec
```
```
In arch/powerpc/kernel/kvm.c (c000000001353e1c)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - arch/powerpc/kernel/kvm.c:kvm_guest_init
  - arch/powerpc/kernel/kvm.c:kvm_guest_init
```
```
In arch/powerpc/mm/fault.c (c000000000086bb8)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/fault.c:__do_page_fault
```
```
In arch/powerpc/mm/mem.c (c000000000087474)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - arch/powerpc/mm/mem.c:__flush_dcache_icache
```
```
In arch/powerpc/mm/book3s64/subpage_prot.c (c00000000009fdc4)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/subpage_prot.c:__se_sys_subpage_prot
  - arch/powerpc/mm/book3s64/subpage_prot.c:__se_sys_subpage_prot
```
```
In arch/powerpc/lib/pmem.c (c0000000000a7f8c)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - arch/powerpc/lib/pmem.c:__copy_from_user_flushcache
  - arch/powerpc/lib/pmem.c:__copy_from_user_flushcache
```
```
In arch/powerpc/lib/checksum_wrappers.c (c0000000000aa0a8)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - arch/powerpc/lib/checksum_wrappers.c:csum_and_copy_from_user
  - arch/powerpc/lib/checksum_wrappers.c:csum_and_copy_from_user
  - arch/powerpc/lib/checksum_wrappers.c:csum_and_copy_from_user
  - arch/powerpc/lib/checksum_wrappers.c:csum_and_copy_from_user
```
```
In arch/powerpc/lib/sstep.c (c0000000000b1474)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - arch/powerpc/lib/sstep.c:emulate_loadstore
  - arch/powerpc/lib/sstep.c:emulate_loadstore
  - arch/powerpc/lib/sstep.c:emulate_loadstore
  - arch/powerpc/lib/sstep.c:emulate_loadstore
  - arch/powerpc/lib/sstep.c:emulate_loadstore
  - arch/powerpc/lib/sstep.c:emulate_loadstore
  - arch/powerpc/lib/sstep.c:emulate_loadstore
  - arch/powerpc/lib/sstep.c:emulate_loadstore
  - arch/powerpc/lib/sstep.c:emulate_loadstore
  - arch/powerpc/lib/sstep.c:emulate_loadstore
  - arch/powerpc/lib/sstep.c:emulate_loadstore
  - arch/powerpc/lib/sstep.c:emulate_loadstore
  - arch/powerpc/lib/sstep.c:emulate_loadstore
  - arch/powerpc/lib/sstep.c:emulate_loadstore
  - arch/powerpc/lib/sstep.c:emulate_loadstore
  - arch/powerpc/lib/sstep.c:emulate_loadstore
  - arch/powerpc/lib/sstep.c:emulate_loadstore
  - arch/powerpc/lib/sstep.c:emulate_loadstore
  - arch/powerpc/lib/sstep.c:emulate_loadstore
  - arch/powerpc/lib/sstep.c:emulate_loadstore
  - arch/powerpc/lib/sstep.c:emulate_loadstore
  - arch/powerpc/lib/sstep.c:emulate_loadstore
  - arch/powerpc/lib/sstep.c:emulate_loadstore
  - arch/powerpc/lib/sstep.c:emulate_loadstore
  - arch/powerpc/lib/sstep.c:do_fp_load
  - arch/powerpc/lib/sstep.c:do_fp_load
  - arch/powerpc/lib/sstep.c:do_fp_load
  - arch/powerpc/lib/sstep.c:do_fp_load
  - arch/powerpc/lib/sstep.c:do_fp_load
  - arch/powerpc/lib/sstep.c:do_fp_load
  - arch/powerpc/lib/sstep.c:do_fp_load
  - arch/powerpc/lib/sstep.c:do_fp_load
```
```
In arch/powerpc/platforms/powernv/opal-lpc.c (c0000000000c9c94)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-lpc.c:lpc_debug_write
  - arch/powerpc/platforms/powernv/opal-lpc.c:lpc_debug_write
  - arch/powerpc/platforms/powernv/opal-lpc.c:lpc_debug_write
  - arch/powerpc/platforms/powernv/opal-lpc.c:lpc_debug_write
  - arch/powerpc/platforms/powernv/opal-lpc.c:lpc_debug_write
  - arch/powerpc/platforms/powernv/opal-lpc.c:lpc_debug_write
```
```
In arch/powerpc/platforms/powernv/opal-xscom.c (c0000000000e7108)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-xscom.c:scom_debug_write
```
```
In arch/powerpc/perf/callchain.c (c000000000125178)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - arch/powerpc/perf/callchain.c:read_user_stack_32
  - arch/powerpc/perf/callchain.c:read_user_stack_32
  - arch/powerpc/perf/callchain.c:read_user_stack_64
  - arch/powerpc/perf/callchain.c:read_user_stack_64
```
```
In arch/powerpc/perf/core-book3s.c (c000000000128eb4)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - arch/powerpc/perf/core-book3s.c:record_and_restart
```
```
In kernel/sysctl.c (c00000000014a4ec)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - kernel/sysctl.c:_proc_do_string
```
```
In kernel/sysctl_binary.c (c00000000014cce8)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__se_compat_sys_sysctl
  - kernel/sysctl_binary.c:__se_compat_sys_sysctl
  - kernel/sysctl_binary.c:__se_sys_sysctl
  - kernel/sysctl_binary.c:__se_sys_sysctl
```
```
In kernel/capability.c (c00000000014d808)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - kernel/capability.c:__se_sys_capset
  - kernel/capability.c:__se_sys_capset
  - kernel/capability.c:__se_sys_capget
  - kernel/capability.c:__se_sys_capget
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
```
```
In kernel/ptrace.c (c000000000150e20)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (c00000000015ae04)
Location: arch/powerpc/include/asm/kup.h:59
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
  - kernel/signal.c:__se_compat_sys_rt_sigaction
  - kernel/signal.c:__se_compat_sys_rt_sigaction
  - kernel/signal.c:__se_compat_sys_rt_sigaction
  - kernel/signal.c:__se_compat_sys_rt_sigaction
  - kernel/signal.c:__se_compat_sys_rt_sigaction
  - kernel/signal.c:__se_compat_sys_rt_sigaction
```
```
In kernel/groups.c (c00000000017a848)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - kernel/groups.c:__se_sys_setgroups
```
```
In kernel/sched/core.c (c000000000182dd0)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_setattr
```
```
In kernel/time/time.c (c0000000001fa9dc)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - kernel/time/time.c:__se_sys_stime32
  - kernel/time/time.c:__se_sys_stime32
  - kernel/time/time.c:__se_sys_stime
  - kernel/time/time.c:__se_sys_stime
```
```
In kernel/futex.c (c00000000021f43c)
Location: arch/powerpc/include/asm/kup.h:59
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
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:handle_futex_death
  - kernel/futex.c:handle_futex_death
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:get_futex_value_locked
```
```
In kernel/compat.c (c000000000237198)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:__se_compat_sys_sigprocmask
  - kernel/compat.c:__se_compat_sys_sigprocmask
  - kernel/compat.c:compat_get_timespec
  - kernel/compat.c:compat_get_timespec
  - kernel/compat.c:compat_get_timespec
  - kernel/compat.c:compat_get_timespec
  - kernel/compat.c:compat_get_timeval
  - kernel/compat.c:compat_get_timeval
  - kernel/compat.c:compat_get_timeval
  - kernel/compat.c:compat_get_timeval
```
```
In kernel/trace/trace.c (c0000000002a72f0)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_get_user
```
```
In kernel/bpf/syscall.c (c000000000305df8)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
```
```
In kernel/bpf/cgroup.c (c000000000339e48)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
```
```
In kernel/events/core.c (c000000000343fc0)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:perf_output_sample_ustack
  - kernel/events/core.c:perf_output_sample_ustack
```
```
In kernel/events/uprobes.c (c00000000035b4a4)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In kernel/rseq.c (c000000000360904)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In mm/maccess.c (c000000000371d84)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (c0000000003bc148)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mempolicy.c (c00000000041286c)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - mm/mempolicy.c:get_nodes
```
```
In mm/migrate.c (c00000000043930c)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - mm/migrate.c:__se_compat_sys_move_pages
  - mm/migrate.c:__se_compat_sys_move_pages
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
```
```
In fs/read_write.c (c000000000479728)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - fs/read_write.c:__se_compat_sys_sendfile
  - fs/read_write.c:__se_compat_sys_sendfile
  - fs/read_write.c:__se_sys_sendfile
  - fs/read_write.c:__se_sys_sendfile
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/exec.c (c0000000004842ac)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
```
```
In fs/ioctl.c (c000000000498cac)
Location: arch/powerpc/include/asm/kup.h:59
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
In fs/select.c (c00000000049dd08)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - fs/select.c:__se_compat_sys_pselect6_time32
  - fs/select.c:__se_compat_sys_pselect6_time32
  - fs/select.c:__se_compat_sys_pselect6_time32
  - fs/select.c:__se_compat_sys_pselect6_time32
  - fs/select.c:__se_compat_sys_pselect6_time64
  - fs/select.c:__se_compat_sys_pselect6_time64
  - fs/select.c:__se_compat_sys_pselect6_time64
  - fs/select.c:__se_compat_sys_pselect6_time64
  - fs/select.c:__se_sys_pselect6
  - fs/select.c:__se_sys_pselect6
  - fs/select.c:__se_sys_pselect6
  - fs/select.c:__se_sys_pselect6
```
```
In fs/namespace.c (c0000000004b6a48)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/utimes.c (c0000000004d3c0c)
Location: arch/powerpc/include/asm/kup.h:59
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
  - fs/utimes.c:__se_sys_utime
  - fs/utimes.c:__se_sys_utime
  - fs/utimes.c:__se_sys_utime
  - fs/utimes.c:__se_sys_utime
```
```
In fs/aio.c (c000000000504a90)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:__se_compat_sys_io_submit
  - fs/aio.c:__se_compat_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_compat_sys_io_setup
  - fs/aio.c:__se_compat_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:lookup_ioctx
```
```
In fs/crypto/policy.c (c00000000051de78)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/measure.c (c0000000005201ac)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - fs/verity/measure.c:fsverity_ioctl_measure
```
```
In fs/compat_ioctl.c (c00000000052b528)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
Direct callers:
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
```
```
In fs/binfmt_elf.c (c00000000052ffec)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (c000000000533c04)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/ext4/ioctl.c (c0000000005b4110)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
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
In fs/fat/file.c (c000000000629004)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/fuse/dev.c (c000000000646394)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_ioctl
```
```
In ipc/msg.c (c00000000066a5d4)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - ipc/msg.c:compat_ksys_msgsnd
  - ipc/msg.c:compat_ksys_msgsnd
  - ipc/msg.c:ksys_msgsnd
  - ipc/msg.c:ksys_msgsnd
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:compat_ksys_msgctl
```
```
In ipc/syscall.c (c000000000673f84)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:ksys_ipc
  - ipc/syscall.c:ksys_ipc
```
```
In security/tomoyo/common.c (c0000000006e8908)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
```
In block/ioctl.c (c0000000007915ac)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
```
In block/scsi_ioctl.c (c0000000007a559c)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
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
```
```
In block/bsg.c (c0000000007a66ac)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
```
```
In block/compat_ioctl.c (c0000000007ba744)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
Direct callers:
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
```
```
In lib/bitmap.c (c0000000007cdd18)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (c0000000007d8358)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyin
```
```
In lib/usercopy.c (c0000000007de038)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:_copy_from_user
  - lib/usercopy.c:_copy_from_user
```
```
In lib/strncpy_from_user.c (c00000000081c694)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
  - lib/strncpy_from_user.c:strncpy_from_user
  - lib/strncpy_from_user.c:strncpy_from_user
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (c00000000081c8b0)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
  - lib/strnlen_user.c:strnlen_user
  - lib/strnlen_user.c:strnlen_user
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (c000000000875674)
Location: arch/powerpc/include/asm/kup.h:59
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
```
```
In drivers/pci/syscall.c (c000000000888f30)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - drivers/pci/syscall.c:__se_sys_pciconfig_write
  - drivers/pci/syscall.c:__se_sys_pciconfig_write
  - drivers/pci/syscall.c:__se_sys_pciconfig_write
  - drivers/pci/syscall.c:__se_sys_pciconfig_write
  - drivers/pci/syscall.c:__se_sys_pciconfig_write
  - drivers/pci/syscall.c:__se_sys_pciconfig_write
```
```
In drivers/video/fbdev/core/fbmem.c (c0000000008a66a0)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
```
```
In drivers/tty/tty_io.c (c0000000008f1058)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/tty/tty_ioctl.c (c0000000008f9f38)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
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
In drivers/tty/tty_jobctrl.c (c0000000008ffeac)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
```
In drivers/tty/pty.c (c00000000090172c)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_set_pktmode
  - drivers/tty/pty.c:pty_set_pktmode
  - drivers/tty/pty.c:pty_set_lock
  - drivers/tty/pty.c:pty_set_lock
```
```
In drivers/tty/sysrq.c (c000000000903e2c)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:write_sysrq_trigger
```
```
In drivers/tty/vt/vt_ioctl.c (c000000000905b6c)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/keyboard.c (c00000000090d474)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
```
```
In drivers/tty/vt/vt.c (c000000000917934)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
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
In drivers/char/mem.c (c000000000942a68)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
```
```
In drivers/char/random.c (c000000000948a88)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
```
```
In drivers/scsi/scsi_ioctl.c (c000000000a29b50)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/scsi_error.c (c000000000a2ecb0)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
```
```
In drivers/scsi/sg.c (c000000000a56a34)
Location: arch/powerpc/include/asm/kup.h:59
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
```
```
In drivers/net/tun.c (c000000000aa4bbc)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aaba14)
Location: arch/powerpc/include/asm/kup.h:59
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
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/vfio/vfio.c (c000000000aaf3a0)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/usb/core/devio.c (c000000000aefa08)
Location: arch/powerpc/include/asm/kup.h:59
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
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
```
```
In drivers/input/mousedev.c (c000000000b7d044)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_write
```
```
In drivers/input/evdev.c (c000000000b7fe78)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_set_keycode
  - drivers/input/evdev.c:evdev_handle_set_keycode
```
```
In drivers/watchdog/watchdog_dev.c (c000000000bc8304)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
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
In drivers/md/md.c (c000000000be158c)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
```
In net/socket.c (c000000000c7b090)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_getsockopt
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:move_addr_to_user
  - net/socket.c:move_addr_to_user
```
```
In net/core/sock.c (c000000000c84da0)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/ethtool.c (c000000000cbe004)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/compat.c (c000000000d2cf68)
Location: arch/powerpc/include/asm/kup.h:59
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
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
```
```
In net/netlink/af_netlink.c (c000000000d4b398)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/ipv4/ip_sockglue.c (c000000000d6b7f0)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp.c (c000000000d787d0)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
```
```
In net/ipv4/raw.c (c000000000da990c)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_geticmpfilter
```
```
In net/ipv4/udp.c (c000000000dacb74)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
```
```
In net/ipv4/bpfilter/sockopt.c (c000000000de2e9c)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
```
```
In net/ipv4/ipmr.c (c000000000ded3c4)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
```
In net/ipv6/ipv6_sockglue.c (c000000000e4ab7c)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
```
```
In net/ipv6/raw.c (c000000000e59b80)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
```
```
In net/ipv6/ip6mr.c (c000000000e7c8d4)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
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
```
```
In net/packet/af_packet.c (c000000000e9608c)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/xdp/xsk.c (c000000000ebf530)
Location: arch/powerpc/include/asm/kup.h:59
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_getsockopt
```
**Symbols:**

```
c000000000529c50-c000000000529c68: allow_read_from_user.isra.0.part.0 (STB_LOCAL)
c0000000007b9470-c0000000007b9488: allow_read_from_user.isra.0.part.0 (STB_LOCAL)
c000000000de7250-c000000000de7268: allow_read_from_user.isra.0.part.0 (STB_LOCAL)
```
</details>
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
