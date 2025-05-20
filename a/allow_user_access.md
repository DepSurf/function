# Function: <code>allow_user_access</code>

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
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/ptrace.c (c000000000018e44)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:arch_ptrace
  - arch/powerpc/kernel/ptrace.c:arch_ptrace
  - arch/powerpc/kernel/ptrace.c:arch_ptrace
  - arch/powerpc/kernel/ptrace.c:arch_ptrace
  - arch/powerpc/kernel/ptrace.c:pmu_set
  - arch/powerpc/kernel/ptrace.c:pmu_set
  - arch/powerpc/kernel/ptrace.c:pmu_get
  - arch/powerpc/kernel/ptrace.c:pmu_get
  - arch/powerpc/kernel/ptrace.c:ebb_set
  - arch/powerpc/kernel/ptrace.c:ebb_set
  - arch/powerpc/kernel/ptrace.c:ebb_set
  - arch/powerpc/kernel/ptrace.c:ebb_set
  - arch/powerpc/kernel/ptrace.c:ebb_set
  - arch/powerpc/kernel/ptrace.c:ebb_set
  - arch/powerpc/kernel/ptrace.c:ebb_get
  - arch/powerpc/kernel/ptrace.c:ebb_get
  - arch/powerpc/kernel/ptrace.c:tar_set
  - arch/powerpc/kernel/ptrace.c:tar_set
  - arch/powerpc/kernel/ptrace.c:tar_get
  - arch/powerpc/kernel/ptrace.c:tar_get
  - arch/powerpc/kernel/ptrace.c:dscr_set
  - arch/powerpc/kernel/ptrace.c:dscr_set
  - arch/powerpc/kernel/ptrace.c:dscr_get
  - arch/powerpc/kernel/ptrace.c:dscr_get
  - arch/powerpc/kernel/ptrace.c:ppr_set
  - arch/powerpc/kernel/ptrace.c:ppr_set
  - arch/powerpc/kernel/ptrace.c:ppr_get
  - arch/powerpc/kernel/ptrace.c:ppr_get
  - arch/powerpc/kernel/ptrace.c:tm_dscr_set
  - arch/powerpc/kernel/ptrace.c:tm_dscr_set
  - arch/powerpc/kernel/ptrace.c:tm_dscr_get
  - arch/powerpc/kernel/ptrace.c:tm_dscr_get
  - arch/powerpc/kernel/ptrace.c:tm_ppr_set
  - arch/powerpc/kernel/ptrace.c:tm_ppr_set
  - arch/powerpc/kernel/ptrace.c:tm_ppr_get
  - arch/powerpc/kernel/ptrace.c:tm_ppr_get
  - arch/powerpc/kernel/ptrace.c:tm_tar_set
  - arch/powerpc/kernel/ptrace.c:tm_tar_set
  - arch/powerpc/kernel/ptrace.c:tm_tar_get
  - arch/powerpc/kernel/ptrace.c:tm_tar_get
  - arch/powerpc/kernel/ptrace.c:tm_spr_set
  - arch/powerpc/kernel/ptrace.c:tm_spr_set
  - arch/powerpc/kernel/ptrace.c:tm_spr_get
  - arch/powerpc/kernel/ptrace.c:tm_spr_get
  - arch/powerpc/kernel/ptrace.c:tm_spr_get
  - arch/powerpc/kernel/ptrace.c:tm_spr_get
  - arch/powerpc/kernel/ptrace.c:tm_spr_get
  - arch/powerpc/kernel/ptrace.c:tm_spr_get
  - arch/powerpc/kernel/ptrace.c:tm_cvsx_get
  - arch/powerpc/kernel/ptrace.c:tm_cvsx_get
  - arch/powerpc/kernel/ptrace.c:tm_cvmx_set
  - arch/powerpc/kernel/ptrace.c:tm_cvmx_set
  - arch/powerpc/kernel/ptrace.c:tm_cvmx_get
  - arch/powerpc/kernel/ptrace.c:tm_cvmx_get
  - arch/powerpc/kernel/ptrace.c:tm_cvmx_get
  - arch/powerpc/kernel/ptrace.c:tm_cvmx_get
  - arch/powerpc/kernel/ptrace.c:tm_cfpr_get
  - arch/powerpc/kernel/ptrace.c:tm_cfpr_get
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_set
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_set
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_set
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_set
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_get
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_get
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_get
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_get
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_get
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_get
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_get
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_get
  - arch/powerpc/kernel/ptrace.c:vsr_get
  - arch/powerpc/kernel/ptrace.c:vsr_get
  - arch/powerpc/kernel/ptrace.c:vr_set
  - arch/powerpc/kernel/ptrace.c:vr_set
  - arch/powerpc/kernel/ptrace.c:vr_get
  - arch/powerpc/kernel/ptrace.c:vr_get
  - arch/powerpc/kernel/ptrace.c:vr_get
  - arch/powerpc/kernel/ptrace.c:vr_get
  - arch/powerpc/kernel/ptrace.c:fpr_get
  - arch/powerpc/kernel/ptrace.c:fpr_get
  - arch/powerpc/kernel/ptrace.c:gpr_set
  - arch/powerpc/kernel/ptrace.c:gpr_set
  - arch/powerpc/kernel/ptrace.c:gpr_set
  - arch/powerpc/kernel/ptrace.c:gpr_set
  - arch/powerpc/kernel/ptrace.c:gpr_get
  - arch/powerpc/kernel/ptrace.c:gpr_get
  - arch/powerpc/kernel/ptrace.c:gpr_get
  - arch/powerpc/kernel/ptrace.c:gpr_get
  - arch/powerpc/kernel/ptrace.c:gpr_get
  - arch/powerpc/kernel/ptrace.c:gpr_get
  - arch/powerpc/kernel/ptrace.c:gpr_get
  - arch/powerpc/kernel/ptrace.c:gpr_get
```
```
In arch/powerpc/kernel/align.c (c00000000001c3bc)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - arch/powerpc/kernel/align.c:fix_alignment
```
```
In arch/powerpc/kernel/signal_32.c (c00000000001f0b8)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal_32.c:compat_sys_sigreturn
  - arch/powerpc/kernel/signal_32.c:compat_sys_sigreturn
  - arch/powerpc/kernel/signal_32.c:handle_signal32
  - arch/powerpc/kernel/signal_32.c:handle_signal32
  - arch/powerpc/kernel/signal_32.c:handle_signal32
  - arch/powerpc/kernel/signal_32.c:handle_signal32
  - arch/powerpc/kernel/signal_32.c:handle_signal32
  - arch/powerpc/kernel/signal_32.c:handle_signal32
  - arch/powerpc/kernel/signal_32.c:handle_signal32
  - arch/powerpc/kernel/signal_32.c:handle_signal32
  - arch/powerpc/kernel/signal_32.c:handle_signal32
  - arch/powerpc/kernel/signal_32.c:handle_signal32
  - arch/powerpc/kernel/signal_32.c:handle_signal32
  - arch/powerpc/kernel/signal_32.c:handle_signal32
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
  - arch/powerpc/kernel/signal_32.c:__do_compat_sys_swapcontext
  - arch/powerpc/kernel/signal_32.c:__do_compat_sys_swapcontext
  - arch/powerpc/kernel/signal_32.c:do_setcontext
  - arch/powerpc/kernel/signal_32.c:do_setcontext
  - arch/powerpc/kernel/signal_32.c:handle_rt_signal32
  - arch/powerpc/kernel/signal_32.c:handle_rt_signal32
  - arch/powerpc/kernel/signal_32.c:handle_rt_signal32
  - arch/powerpc/kernel/signal_32.c:handle_rt_signal32
  - arch/powerpc/kernel/signal_32.c:handle_rt_signal32
  - arch/powerpc/kernel/signal_32.c:handle_rt_signal32
  - arch/powerpc/kernel/signal_32.c:handle_rt_signal32
  - arch/powerpc/kernel/signal_32.c:handle_rt_signal32
  - arch/powerpc/kernel/signal_32.c:handle_rt_signal32
  - arch/powerpc/kernel/signal_32.c:handle_rt_signal32
  - arch/powerpc/kernel/signal_32.c:handle_rt_signal32
  - arch/powerpc/kernel/signal_32.c:handle_rt_signal32
  - arch/powerpc/kernel/signal_32.c:restore_user_regs
  - arch/powerpc/kernel/signal_32.c:restore_user_regs
  - arch/powerpc/kernel/signal_32.c:restore_user_regs
  - arch/powerpc/kernel/signal_32.c:restore_user_regs
  - arch/powerpc/kernel/signal_32.c:restore_user_regs
  - arch/powerpc/kernel/signal_32.c:restore_user_regs
  - arch/powerpc/kernel/signal_32.c:restore_user_regs
  - arch/powerpc/kernel/signal_32.c:restore_user_regs
  - arch/powerpc/kernel/signal_32.c:save_user_regs
  - arch/powerpc/kernel/signal_32.c:save_user_regs
  - arch/powerpc/kernel/signal_32.c:save_user_regs
  - arch/powerpc/kernel/signal_32.c:save_user_regs
  - arch/powerpc/kernel/signal_32.c:save_user_regs
  - arch/powerpc/kernel/signal_32.c:save_user_regs
  - arch/powerpc/kernel/signal_32.c:save_user_regs
  - arch/powerpc/kernel/signal_32.c:save_user_regs
  - arch/powerpc/kernel/signal_32.c:save_user_regs
  - arch/powerpc/kernel/signal_32.c:save_user_regs
  - arch/powerpc/kernel/signal_32.c:save_user_regs
  - arch/powerpc/kernel/signal_32.c:save_user_regs
  - arch/powerpc/kernel/signal_32.c:save_user_regs
  - arch/powerpc/kernel/signal_32.c:save_user_regs
  - arch/powerpc/kernel/signal_32.c:save_user_regs
  - arch/powerpc/kernel/signal_32.c:save_user_regs
  - arch/powerpc/kernel/signal_32.c:copy_ckvsx_from_user
  - arch/powerpc/kernel/signal_32.c:copy_ckvsx_from_user
  - arch/powerpc/kernel/signal_32.c:copy_ckvsx_to_user
  - arch/powerpc/kernel/signal_32.c:copy_ckvsx_to_user
  - arch/powerpc/kernel/signal_32.c:copy_ckfpr_from_user
  - arch/powerpc/kernel/signal_32.c:copy_ckfpr_from_user
  - arch/powerpc/kernel/signal_32.c:copy_ckfpr_to_user
  - arch/powerpc/kernel/signal_32.c:copy_ckfpr_to_user
  - arch/powerpc/kernel/signal_32.c:copy_vsx_from_user
  - arch/powerpc/kernel/signal_32.c:copy_vsx_from_user
  - arch/powerpc/kernel/signal_32.c:copy_vsx_to_user
  - arch/powerpc/kernel/signal_32.c:copy_vsx_to_user
  - arch/powerpc/kernel/signal_32.c:copy_fpr_from_user
  - arch/powerpc/kernel/signal_32.c:copy_fpr_from_user
  - arch/powerpc/kernel/signal_32.c:copy_fpr_to_user
  - arch/powerpc/kernel/signal_32.c:copy_fpr_to_user
```
```
In arch/powerpc/kernel/process.c (c000000000022840)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - arch/powerpc/kernel/process.c:get_unalign_ctl
  - arch/powerpc/kernel/process.c:get_unalign_ctl
  - arch/powerpc/kernel/process.c:get_endian
  - arch/powerpc/kernel/process.c:get_endian
  - arch/powerpc/kernel/process.c:get_fpexc_mode
  - arch/powerpc/kernel/process.c:get_fpexc_mode
  - arch/powerpc/kernel/process.c:start_thread
  - arch/powerpc/kernel/process.c:start_thread
  - arch/powerpc/kernel/process.c:start_thread
  - arch/powerpc/kernel/process.c:start_thread
```
```
In arch/powerpc/kernel/traps.c (c00000000002edb0)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - arch/powerpc/kernel/traps.c:facility_unavailable_exception
  - arch/powerpc/kernel/traps.c:facility_unavailable_exception
  - arch/powerpc/kernel/traps.c:emulate_instruction
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
In arch/powerpc/kernel/signal_64.c (c000000000034380)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
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
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace32.c:compat_arch_ptrace
  - arch/powerpc/kernel/ptrace32.c:compat_arch_ptrace
  - arch/powerpc/kernel/ptrace32.c:compat_arch_ptrace
  - arch/powerpc/kernel/ptrace32.c:compat_arch_ptrace
  - arch/powerpc/kernel/ptrace32.c:compat_arch_ptrace
  - arch/powerpc/kernel/ptrace32.c:compat_arch_ptrace
  - arch/powerpc/kernel/ptrace32.c:compat_arch_ptrace
  - arch/powerpc/kernel/ptrace32.c:compat_arch_ptrace
  - arch/powerpc/kernel/ptrace32.c:compat_arch_ptrace
  - arch/powerpc/kernel/ptrace32.c:compat_arch_ptrace
  - arch/powerpc/kernel/ptrace32.c:compat_arch_ptrace
  - arch/powerpc/kernel/ptrace32.c:compat_arch_ptrace
```
```
In arch/powerpc/kernel/hw_breakpoint.c (c0000000000381a4)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - arch/powerpc/kernel/hw_breakpoint.c:hw_breakpoint_handler
```
```
In arch/powerpc/kernel/vecemu.c (c00000000003bca0)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - arch/powerpc/kernel/vecemu.c:emulate_altivec
```
```
In arch/powerpc/kernel/kvm.c (c000000001353e1c)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - arch/powerpc/kernel/kvm.c:kvm_guest_init
  - arch/powerpc/kernel/kvm.c:kvm_guest_init
```
```
In arch/powerpc/mm/fault.c (c000000000086bb8)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - arch/powerpc/mm/mem.c:__flush_dcache_icache
```
```
In arch/powerpc/mm/book3s64/subpage_prot.c (c00000000009fdc4)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/subpage_prot.c:__se_sys_subpage_prot
  - arch/powerpc/mm/book3s64/subpage_prot.c:__se_sys_subpage_prot
```
```
In arch/powerpc/lib/pmem.c (c0000000000a7f8c)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - arch/powerpc/lib/pmem.c:__copy_from_user_flushcache
  - arch/powerpc/lib/pmem.c:__copy_from_user_flushcache
```
```
In arch/powerpc/lib/checksum_wrappers.c (c0000000000a9df4)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - arch/powerpc/lib/checksum_wrappers.c:csum_and_copy_to_user
  - arch/powerpc/lib/checksum_wrappers.c:csum_and_copy_from_user
  - arch/powerpc/lib/checksum_wrappers.c:csum_and_copy_from_user
  - arch/powerpc/lib/checksum_wrappers.c:csum_and_copy_from_user
  - arch/powerpc/lib/checksum_wrappers.c:csum_and_copy_from_user
```
```
In arch/powerpc/lib/sstep.c (c0000000000b1474)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
  - arch/powerpc/lib/sstep.c:emulate_dcbz
  - arch/powerpc/lib/sstep.c:emulate_dcbz
  - arch/powerpc/lib/sstep.c:do_fp_store
  - arch/powerpc/lib/sstep.c:do_fp_store
  - arch/powerpc/lib/sstep.c:do_fp_store
  - arch/powerpc/lib/sstep.c:do_fp_store
  - arch/powerpc/lib/sstep.c:do_fp_store
  - arch/powerpc/lib/sstep.c:do_fp_store
  - arch/powerpc/lib/sstep.c:do_fp_store
  - arch/powerpc/lib/sstep.c:do_fp_store
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
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-lpc.c:lpc_debug_write
  - arch/powerpc/platforms/powernv/opal-lpc.c:lpc_debug_write
  - arch/powerpc/platforms/powernv/opal-lpc.c:lpc_debug_write
  - arch/powerpc/platforms/powernv/opal-lpc.c:lpc_debug_write
  - arch/powerpc/platforms/powernv/opal-lpc.c:lpc_debug_write
  - arch/powerpc/platforms/powernv/opal-lpc.c:lpc_debug_write
  - arch/powerpc/platforms/powernv/opal-lpc.c:lpc_debug_read
  - arch/powerpc/platforms/powernv/opal-lpc.c:lpc_debug_read
  - arch/powerpc/platforms/powernv/opal-lpc.c:lpc_debug_read
  - arch/powerpc/platforms/powernv/opal-lpc.c:lpc_debug_read
  - arch/powerpc/platforms/powernv/opal-lpc.c:lpc_debug_read
  - arch/powerpc/platforms/powernv/opal-lpc.c:lpc_debug_read
```
```
In arch/powerpc/platforms/powernv/opal-xscom.c (c0000000000e7108)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-xscom.c:scom_debug_write
  - arch/powerpc/platforms/powernv/opal-xscom.c:scom_debug_read
```
```
In arch/powerpc/perf/callchain.c (c000000000125178)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - arch/powerpc/perf/callchain.c:read_user_stack_32
  - arch/powerpc/perf/callchain.c:read_user_stack_32
  - arch/powerpc/perf/callchain.c:read_user_stack_64
  - arch/powerpc/perf/callchain.c:read_user_stack_64
```
```
In arch/powerpc/perf/core-book3s.c (c000000000128eb4)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - arch/powerpc/perf/core-book3s.c:record_and_restart
```
```
In kernel/fork.c (c00000000013ad5c)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_release
  - kernel/fork.c:mm_release
```
```
In kernel/exit.c (c0000000001438fc)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
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
```
```
In kernel/sysctl.c (c00000000014a4ec)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - kernel/sysctl.c:_proc_do_string
  - kernel/sysctl.c:_proc_do_string
  - kernel/sysctl.c:_proc_do_string
```
```
In kernel/sysctl_binary.c (c00000000014cce8)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__se_compat_sys_sysctl
  - kernel/sysctl_binary.c:__se_compat_sys_sysctl
  - kernel/sysctl_binary.c:__se_compat_sys_sysctl
  - kernel/sysctl_binary.c:__se_compat_sys_sysctl
  - kernel/sysctl_binary.c:__se_sys_sysctl
  - kernel/sysctl_binary.c:__se_sys_sysctl
  - kernel/sysctl_binary.c:__se_sys_sysctl
  - kernel/sysctl_binary.c:__se_sys_sysctl
```
```
In kernel/capability.c (c00000000014d808)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - kernel/capability.c:__se_sys_capset
  - kernel/capability.c:__se_sys_capset
  - kernel/capability.c:__se_sys_capget
  - kernel/capability.c:__se_sys_capget
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
```
```
In kernel/ptrace.c (c000000000150d1c)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:generic_ptrace_peekdata
  - kernel/ptrace.c:generic_ptrace_peekdata
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (c00000000015ae04)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
  - kernel/signal.c:__se_compat_sys_rt_sigaction
  - kernel/signal.c:__se_compat_sys_rt_sigaction
  - kernel/signal.c:__se_compat_sys_rt_sigaction
  - kernel/signal.c:__se_compat_sys_rt_sigaction
  - kernel/signal.c:__se_compat_sys_rt_sigaction
  - kernel/signal.c:__se_compat_sys_rt_sigaction
  - kernel/signal.c:__se_compat_sys_sigpending
  - kernel/signal.c:__se_compat_sys_sigpending
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/sys.c (c00000000015e7dc)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
  - kernel/sys.c:__se_sys_getcpu
  - kernel/sys.c:__se_sys_getcpu
  - kernel/sys.c:__se_sys_getcpu
  - kernel/sys.c:__se_sys_getcpu
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:__se_compat_sys_old_getrlimit
  - kernel/sys.c:__se_compat_sys_old_getrlimit
  - kernel/sys.c:__se_compat_sys_old_getrlimit
  - kernel/sys.c:__se_compat_sys_old_getrlimit
  - kernel/sys.c:__se_sys_getresgid
  - kernel/sys.c:__se_sys_getresgid
  - kernel/sys.c:__se_sys_getresgid
  - kernel/sys.c:__se_sys_getresgid
  - kernel/sys.c:__se_sys_getresgid
  - kernel/sys.c:__se_sys_getresgid
  - kernel/sys.c:__se_sys_getresuid
  - kernel/sys.c:__se_sys_getresuid
  - kernel/sys.c:__se_sys_getresuid
  - kernel/sys.c:__se_sys_getresuid
  - kernel/sys.c:__se_sys_getresuid
  - kernel/sys.c:__se_sys_getresuid
```
```
In kernel/groups.c (c00000000017a848)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - kernel/groups.c:__se_sys_setgroups
  - kernel/groups.c:__se_sys_getgroups
```
```
In kernel/sched/core.c (c000000000182dd0)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/profile.c (c0000000001f8d18)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/time/time.c (c0000000001fb140)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - kernel/time/time.c:__se_compat_sys_gettimeofday
  - kernel/time/time.c:__se_compat_sys_gettimeofday
  - kernel/time/time.c:__se_compat_sys_gettimeofday
  - kernel/time/time.c:__se_compat_sys_gettimeofday
  - kernel/time/time.c:__se_sys_gettimeofday
  - kernel/time/time.c:__se_sys_gettimeofday
  - kernel/time/time.c:__se_sys_gettimeofday
  - kernel/time/time.c:__se_sys_gettimeofday
  - kernel/time/time.c:__se_sys_stime32
  - kernel/time/time.c:__se_sys_stime32
  - kernel/time/time.c:__se_sys_time32
  - kernel/time/time.c:__se_sys_time32
  - kernel/time/time.c:__se_sys_stime
  - kernel/time/time.c:__se_sys_stime
  - kernel/time/time.c:__se_sys_time
  - kernel/time/time.c:__se_sys_time
```
```
In kernel/futex.c (c00000000021c624)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - kernel/futex.c:__se_compat_sys_get_robust_list
  - kernel/futex.c:__se_compat_sys_get_robust_list
  - kernel/futex.c:__se_compat_sys_get_robust_list
  - kernel/futex.c:__se_compat_sys_get_robust_list
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
  - kernel/futex.c:__se_sys_get_robust_list
  - kernel/futex.c:__se_sys_get_robust_list
  - kernel/futex.c:__se_sys_get_robust_list
  - kernel/futex.c:__se_sys_get_robust_list
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/compat.c (c000000000237450)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
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
  - kernel/compat.c:__se_compat_sys_sigprocmask
  - kernel/compat.c:__se_compat_sys_sigprocmask
  - kernel/compat.c:compat_put_timespec
  - kernel/compat.c:compat_put_timespec
  - kernel/compat.c:compat_put_timespec
  - kernel/compat.c:compat_put_timespec
  - kernel/compat.c:compat_get_timespec
  - kernel/compat.c:compat_get_timespec
  - kernel/compat.c:compat_get_timespec
  - kernel/compat.c:compat_get_timespec
  - kernel/compat.c:compat_put_timeval
  - kernel/compat.c:compat_put_timeval
  - kernel/compat.c:compat_put_timeval
  - kernel/compat.c:compat_put_timeval
  - kernel/compat.c:compat_get_timeval
  - kernel/compat.c:compat_get_timeval
  - kernel/compat.c:compat_get_timeval
  - kernel/compat.c:compat_get_timeval
```
```
In kernel/trace/trace.c (c0000000002a72f0)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
In kernel/bpf/syscall.c (c000000000307168)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
```
```
In kernel/bpf/verifier.c (c00000000030f644)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
```
```
In kernel/bpf/btf.c (c000000000330c80)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_info_by_fd
```
```
In kernel/bpf/cgroup.c (c000000000339e48)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
```
```
In kernel/events/core.c (c000000000343fc0)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:perf_output_sample_ustack
  - kernel/events/core.c:perf_output_sample_ustack
```
```
In kernel/events/uprobes.c (c00000000035b4a4)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In kernel/rseq.c (c0000000003604b4)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
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
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In mm/maccess.c (c000000000371d84)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/memory.c (c0000000003bc148)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mempolicy.c (c0000000004145dc)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - mm/mempolicy.c:__se_compat_sys_get_mempolicy
  - mm/mempolicy.c:__se_compat_sys_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:get_nodes
```
```
In mm/migrate.c (c00000000043930c)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - mm/migrate.c:__se_compat_sys_move_pages
  - mm/migrate.c:__se_compat_sys_move_pages
  - mm/migrate.c:__se_compat_sys_move_pages
  - mm/migrate.c:__se_compat_sys_move_pages
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:store_status
  - mm/migrate.c:store_status
```
```
In fs/read_write.c (c000000000479958)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - fs/read_write.c:__se_compat_sys_sendfile64
  - fs/read_write.c:__se_compat_sys_sendfile64
  - fs/read_write.c:__se_compat_sys_sendfile
  - fs/read_write.c:__se_compat_sys_sendfile
  - fs/read_write.c:__se_compat_sys_sendfile
  - fs/read_write.c:__se_compat_sys_sendfile
  - fs/read_write.c:__se_sys_sendfile64
  - fs/read_write.c:__se_sys_sendfile64
  - fs/read_write.c:__se_sys_sendfile
  - fs/read_write.c:__se_sys_sendfile
  - fs/read_write.c:__se_sys_sendfile
  - fs/read_write.c:__se_sys_sendfile
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
```
```
In fs/exec.c (c0000000004842ac)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
```
```
In fs/pipe.c (c000000000487218)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - fs/pipe.c:pipe_ioctl
```
```
In fs/fcntl.c (c000000000496cb8)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (c000000000498bf8)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
```
```
In fs/readdir.c (c000000000499eb8)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - fs/readdir.c:__se_compat_sys_getdents
  - fs/readdir.c:__se_compat_sys_getdents
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
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
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
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
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (c00000000049dd08)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:__se_sys_pselect6
  - fs/select.c:__se_sys_pselect6
  - fs/select.c:__se_sys_pselect6
  - fs/select.c:__se_sys_pselect6
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/namespace.c (c0000000004b6a48)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/utimes.c (c0000000004d3c0c)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
In fs/nsfs.c (c0000000004d76c4)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - fs/nsfs.c:ns_ioctl
```
```
In fs/notify/inotify/inotify_user.c (c0000000004f3bbc)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (c0000000004f5ed4)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_ioctl
  - fs/notify/fanotify/fanotify_user.c:fanotify_ioctl
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
```
```
In fs/eventpoll.c (c0000000004f972c)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/timerfd.c (c0000000004fc9e0)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (c0000000004fe350)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (c0000000004ffdc8)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
```
```
In fs/aio.c (c000000000504a90)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:__se_compat_sys_io_submit
  - fs/aio.c:__se_compat_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:__se_compat_sys_io_setup
  - fs/aio.c:__se_compat_sys_io_setup
  - fs/aio.c:__se_compat_sys_io_setup
  - fs/aio.c:__se_compat_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:lookup_ioctx
```
```
In fs/crypto/keyring.c (c00000000051b0fc)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
```
```
In fs/crypto/policy.c (c00000000051de78)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/measure.c (c0000000005201ac)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - fs/verity/measure.c:fsverity_ioctl_measure
```
```
In fs/compat_ioctl.c (c00000000052b528)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
```
```
In fs/binfmt_elf.c (c00000000052ffec)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
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
```
```
In fs/compat_binfmt_elf.c (c000000000533c04)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/fhandle.c (c0000000005397c8)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_name_to_handle_at
```
```
In fs/proc/kcore.c (c000000000566050)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/page.c (c000000000567db4)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
In fs/ext4/ioctl.c (c0000000005b4110)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/fat/dir.c (c000000000624860)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
  - fs/fat/dir.c:fat_compat_dir_ioctl
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
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
In fs/fat/file.c (c00000000062956c)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/miscdev.c (c000000000641624)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/fuse/dev.c (c000000000646394)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_ioctl
```
```
In ipc/msg.c (c0000000006684d8)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - ipc/msg.c:compat_do_msg_fill
  - ipc/msg.c:compat_do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/msg.c:do_msg_fill
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
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:compat_ksys_ipc
  - ipc/syscall.c:ksys_ipc
  - ipc/syscall.c:ksys_ipc
  - ipc/syscall.c:ksys_ipc
  - ipc/syscall.c:ksys_ipc
```
```
In ipc/mqueue.c (c000000000676a04)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
```
```
In security/keys/keyring.c (c00000000067c464)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_read_iterator
```
```
In security/keys/keyctl.c (c00000000067f810)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
```
```
In security/keys/keyctl_pkey.c (c000000000687f84)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
```
```
In security/selinux/hooks.c (c0000000006a33ac)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
```
```
In security/smack/smack_lsm.c (c0000000006d32b8)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
```
```
In security/tomoyo/common.c (c0000000006e8908)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
```
```
In security/apparmor/lsm.c (c000000000715434)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
```
```
In block/ioctl.c (c000000000790d7c)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
  - block/ioctl.c:put_uint
  - block/ioctl.c:put_uint
  - block/ioctl.c:put_int
  - block/ioctl.c:put_int
  - block/ioctl.c:put_ushort
  - block/ioctl.c:put_ushort
```
```
In block/scsi_ioctl.c (c0000000007a5424)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
```
```
In block/bsg.c (c0000000007a6624)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_ioctl
```
```
In block/compat_ioctl.c (c0000000007baaf0)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
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
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_put_uint
  - block/compat_ioctl.c:compat_put_uint
  - block/compat_ioctl.c:compat_put_int
  - block/compat_ioctl.c:compat_put_int
  - block/compat_ioctl.c:compat_put_ushort
  - block/compat_ioctl.c:compat_put_ushort
```
```
In lib/bitmap.c (c0000000007cdd18)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (c0000000007d4580)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:copyout_mcsafe
  - lib/iov_iter.c:copyout_mcsafe
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
  - lib/iov_iter.c:copyout
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (c0000000007de038)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
  - lib/usercopy.c:_copy_from_user
```
```
In lib/strncpy_from_user.c (c00000000081c694)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
  - lib/strncpy_from_user.c:strncpy_from_user
  - lib/strncpy_from_user.c:strncpy_from_user
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (c00000000081c8b0)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
  - lib/strnlen_user.c:strnlen_user
  - lib/strnlen_user.c:strnlen_user
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/pci/proc.c (c000000000875674)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
In drivers/pci/syscall.c (c000000000888f30)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
In drivers/video/fbdev/core/fbmem.c (c0000000008a6508)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
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
In drivers/tty/tty_io.c (c0000000008f0cec)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
```
```
In drivers/tty/n_tty.c (c0000000008f4a84)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
```
```
In drivers/tty/tty_ioctl.c (c0000000008fa140)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/tty_ioctl.c:get_termio
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
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
```
In drivers/tty/pty.c (c000000000901680)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
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
In drivers/tty/sysrq.c (c000000000903e2c)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:write_sysrq_trigger
```
```
In drivers/tty/vt/vt_ioctl.c (c000000000905658)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
In drivers/tty/vt/keyboard.c (c00000000090ef04)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
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
```
```
In drivers/tty/vt/consolemap.c (c000000000910118)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
```
```
In drivers/tty/vt/vt.c (c000000000917934)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
```
```
In drivers/tty/serial/serial_core.c (c0000000009295e4)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/char/mem.c (c000000000942a68)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:read_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (c0000000009489e4)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
```
```
In drivers/scsi/scsi_ioctl.c (c000000000a29a40)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/scsi_error.c (c000000000a2ecb0)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
```
```
In drivers/scsi/sg.c (c000000000a56a34)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/ata/libata-scsi.c (c000000000a6b374)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
```
```
In drivers/net/tun.c (c000000000aa4784)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aaba14)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/vfio/vfio.c (c000000000aaf3a0)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
```
In drivers/usb/core/devio.c (c000000000aef980)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
  - drivers/usb/core/devio.c:processcompl_compat
  - drivers/usb/core/devio.c:processcompl_compat
  - drivers/usb/core/devio.c:processcompl_compat
  - drivers/usb/core/devio.c:processcompl_compat
  - drivers/usb/core/devio.c:processcompl_compat
  - drivers/usb/core/devio.c:processcompl_compat
  - drivers/usb/core/devio.c:processcompl_compat
  - drivers/usb/core/devio.c:processcompl_compat
  - drivers/usb/core/devio.c:processcompl_compat
  - drivers/usb/core/devio.c:processcompl_compat
  - drivers/usb/core/devio.c:processcompl_compat
  - drivers/usb/core/devio.c:processcompl_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
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
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
```
```
In drivers/input/mousedev.c (c000000000b7d044)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_write
```
```
In drivers/input/evdev.c (c000000000b7fcf4)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_set_keycode
  - drivers/input/evdev.c:evdev_handle_set_keycode
  - drivers/input/evdev.c:evdev_handle_get_keycode
  - drivers/input/evdev.c:evdev_handle_get_keycode
```
```
In drivers/input/misc/uinput.c (c000000000b85e30)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
```
```
In drivers/rtc/dev.c (c000000000b8cb18)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/i2c/i2c-dev.c (c000000000b9b7f0)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
```
In drivers/pps/pps.c (c000000000ba7044)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_ioctl
```
```
In drivers/watchdog/watchdog_dev.c (c000000000bc8894)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_write
  - drivers/watchdog/watchdog_dev.c:watchdog_write
```
```
In drivers/md/md.c (c000000000be158c)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-ioctl.c (c000000000bfb074)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
```
In net/socket.c (c000000000c7b090)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:do_recvmmsg
  - net/socket.c:do_recvmmsg
  - net/socket.c:do_recvmmsg
  - net/socket.c:do_recvmmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:move_addr_to_user
  - net/socket.c:move_addr_to_user
  - net/socket.c:move_addr_to_user
  - net/socket.c:move_addr_to_user
```
```
In net/core/sock.c (c000000000c84da0)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
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
```
```
In net/core/scm.c (c000000000c97938)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
```
```
In net/core/ethtool.c (c000000000cbe004)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/compat.c (c000000000d2cf68)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:scm_detach_fds_compat
  - net/compat.c:scm_detach_fds_compat
  - net/compat.c:scm_detach_fds_compat
  - net/compat.c:scm_detach_fds_compat
  - net/compat.c:scm_detach_fds_compat
  - net/compat.c:scm_detach_fds_compat
  - net/compat.c:scm_detach_fds_compat
  - net/compat.c:scm_detach_fds_compat
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
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
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
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/ipv4/ip_sockglue.c (c000000000d6b7f0)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp.c (c000000000d771bc)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/raw.c (c000000000da8810)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/raw.c:raw_geticmpfilter
  - net/ipv4/raw.c:raw_geticmpfilter
  - net/ipv4/raw.c:raw_geticmpfilter
```
```
In net/ipv4/udp.c (c000000000dacb74)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_ioctl
  - net/ipv4/udp.c:udp_ioctl
  - net/ipv4/udp.c:udp_ioctl
  - net/ipv4/udp.c:udp_ioctl
```
```
In net/ipv4/igmp.c (c000000000dc9b04)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
```
```
In net/ipv4/bpfilter/sockopt.c (c000000000de2e9c)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
```
```
In net/ipv4/ipmr.c (c000000000ded3c4)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
```
In net/unix/af_unix.c (c000000000e15df0)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/ipv6_sockglue.c (c000000000e4ab7c)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
```
```
In net/ipv6/raw.c (c000000000e5a440)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
  - net/ipv6/raw.c:rawv6_ioctl
  - net/ipv6/raw.c:rawv6_ioctl
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/mcast.c (c000000000e64298)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
```
```
In net/ipv6/ip6mr.c (c000000000e7c8d4)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
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
```
```
In net/packet/af_packet.c (c000000000e910b4)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/xdp/xsk.c (c000000000ebf530)
Location: arch/powerpc/include/asm/book3s/64/kup-radix.h:80
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
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
