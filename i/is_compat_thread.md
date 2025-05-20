# Function: <code>is_compat_thread</code>

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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/process.c (ffff800010089490)
Location: arch/arm64/include/asm/compat.h:204
Inline: True
Inline callers:
  - arch/arm64/kernel/process.c:__switch_to
  - arch/arm64/kernel/process.c:__switch_to
  - arch/arm64/kernel/process.c:__switch_to
  - arch/arm64/kernel/process.c:copy_thread_tls
  - arch/arm64/kernel/process.c:copy_thread_tls
```
```
In arch/arm64/kernel/ptrace.c (ffff80001008ebe8)
Location: arch/arm64/include/asm/compat.h:204
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:task_user_regset_view
```
```
In arch/arm64/kernel/perf_regs.c (ffff8000100a3408)
Location: arch/arm64/include/asm/compat.h:204
Inline: True
Inline callers:
  - arch/arm64/kernel/perf_regs.c:perf_get_regs_user
```
```
In arch/arm64/kernel/hw_breakpoint.c (ffff8000100a6574)
Location: arch/arm64/include/asm/compat.h:204
Inline: True
Inline callers:
  - arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
  - arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
```
```
In arch/arm64/kernel/ssbd.c (ffff8000100abff4)
Location: arch/arm64/include/asm/compat.h:204
Inline: True
Inline callers:
  - arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set
  - arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set
```
```
In kernel/ptrace.c (ffff800010107898)
Location: arch/arm64/include/asm/compat.h:204
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/auditsc.c (ffff8000101f2e58)
Location: arch/arm64/include/asm/compat.h:204
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/seccomp.c (ffff800010209474)
Location: arch/arm64/include/asm/compat.h:204
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:seccomp_init_siginfo
```
</details>
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
