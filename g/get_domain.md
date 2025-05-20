# Function: <code>get_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct protection_domain *get_domain(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8152ed10)
Location: drivers/iommu/amd_iommu.c:2237
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_v2_domain
  - drivers/iommu/amd_iommu.c:unmap_sg
  - drivers/iommu/amd_iommu.c:unmap_page
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_page
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
**Symbols:**

```
ffffffff8152ed10-ffffffff8152ed83: get_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct protection_domain *get_domain(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81584850)
Location: drivers/iommu/amd_iommu.c:2224
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_v2_domain
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:unmap_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:unmap_page
  - drivers/iommu/amd_iommu.c:map_page
```
**Symbols:**

```
ffffffff81584850-ffffffff81584890: get_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct protection_domain *get_domain(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815b1930)
Location: drivers/iommu/amd_iommu.c:2317
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_v2_domain
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:unmap_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:unmap_page
  - drivers/iommu/amd_iommu.c:map_page
```
**Symbols:**

```
ffffffff815b1930-ffffffff815b1970: get_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct protection_domain *get_domain(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c75a0)
Location: drivers/iommu/amd_iommu.c:2478
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_v2_domain
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:unmap_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:unmap_page
  - drivers/iommu/amd_iommu.c:map_page
```
**Symbols:**

```
ffffffff815c75a0-ffffffff815c75f7: get_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct protection_domain *get_domain(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162e240)
Location: drivers/iommu/amd_iommu.c:2249
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_v2_domain
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:unmap_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:unmap_page
  - drivers/iommu/amd_iommu.c:map_page
```
**Symbols:**

```
ffffffff8162e240-ffffffff8162e2c8: get_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct protection_domain *get_domain(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81668fb0)
Location: drivers/iommu/amd_iommu.c:2257
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_v2_domain
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:unmap_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:unmap_page
  - drivers/iommu/amd_iommu.c:map_page
```
**Symbols:**

```
ffffffff81668fb0-ffffffff81669038: get_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct protection_domain *get_domain(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81687810)
Location: drivers/iommu/amd_iommu.c:2333
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_v2_domain
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:unmap_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:unmap_page
  - drivers/iommu/amd_iommu.c:map_page
```
**Symbols:**

```
ffffffff81687810-ffffffff81687898: get_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct protection_domain *get_domain(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816befa0)
Location: drivers/iommu/amd_iommu.c:2314
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_v2_domain
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:unmap_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:unmap_page
  - drivers/iommu/amd_iommu.c:map_page
```
**Symbols:**

```
ffffffff816befa0-ffffffff816bf02b: get_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct protection_domain *get_domain(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e2340)
Location: drivers/iommu/amd_iommu.c:2348
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_v2_domain
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:unmap_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:unmap_page
  - drivers/iommu/amd_iommu.c:map_page
```
**Symbols:**

```
ffffffff816e2340-ffffffff816e23cb: get_domain (STB_LOCAL)
```
</details>
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
In arch/arm/kernel/ptrace.c (c030cb94)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
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
```
```
In arch/arm/kernel/signal.c (c030ea44)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
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
  - arch/arm/kernel/signal.c:setup_sigframe
  - arch/arm/kernel/signal.c:setup_sigframe
  - arch/arm/kernel/signal.c:setup_sigframe
  - arch/arm/kernel/signal.c:restore_sigframe
  - arch/arm/kernel/signal.c:restore_sigframe
  - arch/arm/kernel/signal.c:restore_vfp_context
  - arch/arm/kernel/signal.c:preserve_vfp_context
  - arch/arm/kernel/signal.c:restore_iwmmxt_context
  - arch/arm/kernel/signal.c:preserve_iwmmxt_context
```
```
In arch/arm/kernel/traps.c (c030f724)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - arch/arm/kernel/traps.c:do_undefinstr
  - arch/arm/kernel/traps.c:do_undefinstr
  - arch/arm/kernel/traps.c:do_undefinstr
  - arch/arm/kernel/traps.c:dump_mem
```
```
In arch/arm/kernel/smp_tlb.c (c0313ce4)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - arch/arm/kernel/smp_tlb.c:ipi_flush_tlb_range
  - arch/arm/kernel/smp_tlb.c:ipi_flush_tlb_page
```
```
In arch/arm/kernel/machine_kexec.c (c031522c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - arch/arm/kernel/machine_kexec.c:machine_kexec_prepare
```
```
In arch/arm/kernel/crash_dump.c (c0315b68)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - arch/arm/kernel/crash_dump.c:copy_oldmem_page
```
```
In arch/arm/kernel/swp_emulate.c (c0315e54)
Location: arch/arm/include/asm/domain.h:85
Inline: True
```
```
In arch/arm/kernel/perf_callchain.c (c0317ce4)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - arch/arm/kernel/perf_callchain.c:perf_callchain_user
```
```
In arch/arm/mm/alignment.c (c0321228)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - arch/arm/mm/alignment.c:do_alignment
  - arch/arm/mm/alignment.c:alignment_get_thumb
  - arch/arm/mm/alignment.c:do_alignment_ldmstm
  - arch/arm/mm/alignment.c:do_alignment_ldrstr
  - arch/arm/mm/alignment.c:do_alignment_ldrstr
  - arch/arm/mm/alignment.c:do_alignment_ldrdstrd
  - arch/arm/mm/alignment.c:do_alignment_ldrdstrd
  - arch/arm/mm/alignment.c:do_alignment_ldrhstrh
  - arch/arm/mm/alignment.c:do_alignment_ldrhstrh
  - arch/arm/mm/alignment.c:alignment_proc_write
```
```
In kernel/fork.c (c03508c4)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/fork.c:copy_clone_args_from_user
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_release
```
```
In kernel/exit.c (c035b268)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/exit.c:__se_sys_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/sysctl.c (c035ee24)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_put_long
  - kernel/sysctl.c:_proc_do_string
  - kernel/sysctl.c:_proc_do_string
  - kernel/sysctl.c:_proc_do_string
```
```
In kernel/sysctl_binary.c (c0360974)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__se_sys_sysctl
  - kernel/sysctl_binary.c:__se_sys_sysctl
  - kernel/sysctl_binary.c:__se_sys_sysctl
  - kernel/sysctl_binary.c:__se_sys_sysctl
```
```
In kernel/capability.c (c036123c)
Location: arch/arm/include/asm/domain.h:85
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
In kernel/ptrace.c (c03629c4)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/ptrace.c:generic_ptrace_peekdata
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_writedata
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/signal.c (c036a924)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigsuspend
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
  - kernel/signal.c:__se_sys_sigpending
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__se_sys_sigaltstack
  - kernel/signal.c:__se_sys_sigaltstack
  - kernel/signal.c:__se_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__se_sys_rt_sigtimedwait
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:__se_sys_rt_sigpending
  - kernel/signal.c:__se_sys_rt_sigprocmask
  - kernel/signal.c:__se_sys_rt_sigprocmask
  - kernel/signal.c:set_user_sigmask
```
```
In kernel/sys.c (c036ebb0)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_sysinfo
  - kernel/sys.c:__se_sys_getcpu
  - kernel/sys.c:__se_sys_getcpu
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:__se_sys_getrusage
  - kernel/sys.c:__se_sys_setrlimit
  - kernel/sys.c:__se_sys_prlimit64
  - kernel/sys.c:__se_sys_prlimit64
  - kernel/sys.c:__se_sys_getrlimit
  - kernel/sys.c:__se_sys_setdomainname
  - kernel/sys.c:__se_sys_gethostname
  - kernel/sys.c:__se_sys_sethostname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__se_sys_times
  - kernel/sys.c:__se_sys_getresgid
  - kernel/sys.c:__se_sys_getresgid
  - kernel/sys.c:__se_sys_getresgid
  - kernel/sys.c:__se_sys_getresuid
  - kernel/sys.c:__se_sys_getresuid
  - kernel/sys.c:__se_sys_getresuid
```
```
In kernel/groups.c (c038075c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/groups.c:__se_sys_setgroups
  - kernel/groups.c:__se_sys_getgroups
```
```
In kernel/sched/core.c (c038cd70)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_getaffinity
  - kernel/sched/core.c:__se_sys_sched_setaffinity
  - kernel/sched/core.c:__se_sys_sched_getattr
  - kernel/sched/core.c:__se_sys_sched_getparam
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:schedule_tail
```
```
In kernel/sched/debug.c (c03ac394)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/sched/psi.c (c03b4ad0)
Location: arch/arm/include/asm/domain.h:85
Inline: True
```
```
In kernel/power/qos.c (c03b8834)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_write
```
```
In kernel/power/user.c (c03c3a68)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
```
```
In kernel/printk/printk.c (c03c6e64)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:devkmsg_read
```
```
In kernel/kcmp.c (c03e2d6c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
```
```
In kernel/profile.c (c03e3dd4)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/profile.c:read_profile
```
```
In kernel/time/time.c (c03e4e98)
Location: arch/arm/include/asm/domain.h:85
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
```
```
In kernel/time/posix-timers.c (c03f74b0)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__se_sys_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/itimer.c (c03fad50)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/time/itimer.c:__se_sys_setitimer
  - kernel/time/itimer.c:__se_sys_setitimer
  - kernel/time/itimer.c:__se_sys_getitimer
```
```
In kernel/futex.c (c0403008)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:__se_sys_get_robust_list
  - kernel/futex.c:__se_sys_get_robust_list
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/uid16.c (c04064b8)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/uid16.c:__se_sys_setgroups16
  - kernel/uid16.c:__se_sys_getgroups16
  - kernel/uid16.c:__se_sys_getresgid16
  - kernel/uid16.c:__se_sys_getresgid16
  - kernel/uid16.c:__se_sys_getresgid16
  - kernel/uid16.c:__se_sys_getresuid16
  - kernel/uid16.c:__se_sys_getresuid16
  - kernel/uid16.c:__se_sys_getresuid16
```
```
In kernel/module.c (c040cbe4)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/module.c:__se_sys_init_module
```
```
In kernel/kexec_core.c (c041060c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
```
```
In kernel/kexec.c (c0410f44)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
```
```
In kernel/user_namespace.c (c04273b4)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_setgroups_write
```
```
In kernel/kprobes.c (c0438950)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
```
```
In kernel/seccomp.c (c04492dc)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_ioctl
```
```
In kernel/relay.c (c044a0e4)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/trace/trace.c (c0467cdc)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:tracing_trace_options_write
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_get_user
```
```
In kernel/trace/blktrace.c (c0471d5c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
```
```
In kernel/trace/bpf_trace.c (c0481990)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/trace/trace_uprobe.c (c048d238)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
```
```
In kernel/bpf/core.c (c049266c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
```
```
In kernel/bpf/syscall.c (c0497070)
Location: arch/arm/include/asm/domain.h:85
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
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/verifier.c (c049b908)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:bpf_verifier_vlog
```
```
In kernel/bpf/btf.c (c04b635c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/offload.c (c04ba7a4)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
```
In kernel/bpf/cgroup.c (c04bd3e4)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
```
In kernel/events/core.c (c04c53e4)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
```
```
In kernel/events/uprobes.c (c04d6fe8)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
```
```
In kernel/rseq.c (c04d9bac)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - kernel/rseq.c:__se_sys_rseq
  - kernel/rseq.c:__se_sys_rseq
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
```
```
In mm/maccess.c (c04e5f4c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/shmem.c (c04fb410)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/util.c (c04ffb3c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - mm/util.c:memdup_user_nul
  - mm/util.c:vmemdup_user
  - mm/util.c:memdup_user
```
```
In mm/memory.c (c05172f4)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/mincore.c (c051c8b8)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - mm/mincore.c:__se_sys_mincore
```
```
In mm/mmap.c (c051fb64)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - mm/mmap.c:__se_sys_old_mmap
```
```
In mm/userfaultfd.c (c0563d34)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/memfd.c (c056700c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - mm/memfd.c:__se_sys_memfd_create
```
```
In fs/read_write.c (c056ddb8)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:__se_sys_sendfile64
  - fs/read_write.c:__se_sys_sendfile64
  - fs/read_write.c:__se_sys_sendfile
  - fs/read_write.c:__se_sys_sendfile
  - fs/read_write.c:rw_copy_check_uvector
  - fs/read_write.c:__se_sys_llseek
```
```
In fs/stat.c (c0573348)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat64
  - fs/stat.c:cp_new_stat
```
```
In fs/exec.c (c05749f0)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/exec.c:copy_strings
  - fs/exec.c:get_user_arg_ptr
```
```
In fs/pipe.c (c0577f14)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:pipe_ioctl
```
```
In fs/namei.c (c0581284)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/namei.c:readlink_copy
```
```
In fs/fcntl.c (c05823b4)
Location: arch/arm/include/asm/domain.h:85
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
```
```
In fs/ioctl.c (c0583ee0)
Location: arch/arm/include/asm/domain.h:85
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
  - fs/ioctl.c:file_ioctl
  - fs/ioctl.c:file_ioctl
  - fs/ioctl.c:file_ioctl
  - fs/ioctl.c:ioctl_preallocate
  - fs/ioctl.c:fiemap_fill_next_extent
```
```
In fs/readdir.c (c0584988)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:__se_sys_getdents
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
```
```
In fs/select.c (c05858b0)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:__se_sys_old_select
  - fs/select.c:__se_sys_pselect6_time32
  - fs/select.c:__se_sys_pselect6_time32
  - fs/select.c:__se_sys_pselect6
  - fs/select.c:__se_sys_pselect6
  - fs/select.c:kern_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:poll_select_finish
```
```
In fs/filesystems.c (c05923fc)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/filesystems.c:__se_sys_sysfs
```
```
In fs/namespace.c (c0597160)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
```
```
In fs/seq_file.c (c059a090)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
```
```
In fs/xattr.c (c059b65c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/xattr.c:setxattr
```
```
In fs/libfs.c (c059e634)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/libfs.c:simple_attr_write
  - fs/libfs.c:simple_write_to_buffer
  - fs/libfs.c:simple_read_from_buffer
```
```
In fs/splice.c (c05aa168)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
```
In fs/utimes.c (c05abe74)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:__se_sys_utime32
  - fs/utimes.c:__se_sys_utime32
```
```
In fs/d_path.c (c05ad028)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/d_path.c:__se_sys_getcwd
```
```
In fs/statfs.c (c05ada18)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
```
```
In fs/nsfs.c (c05ae844)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/nsfs.c:ns_ioctl
```
```
In fs/fsopen.c (c05b0794)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/fsopen.c:fscontext_read
```
```
In fs/notify/inotify/inotify_user.c (c05c2c8c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (c05c4680)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_ioctl
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (c05c79c0)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/signalfd.c (c05c90b0)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/signalfd.c:__se_sys_signalfd
  - fs/signalfd.c:__se_sys_signalfd4
  - fs/signalfd.c:signalfd_copyinfo
```
```
In fs/timerfd.c (c05c988c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (c05cadb8)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (c05cc8ac)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
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
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/aio.c (c05d1a90)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_pgetevents_time32
  - fs/aio.c:__se_sys_io_pgetevents
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:aio_read_events
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (c05d7848)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_uring_setup
  - fs/io_uring.c:io_uring_setup
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In fs/crypto/keyring.c (c05dae18)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
```
In fs/crypto/policy.c (c05dcfd8)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
```
```
In fs/verity/enable.c (c05de010)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
```
```
In fs/verity/measure.c (c05dea18)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
```
```
In fs/binfmt_elf.c (c05e8fcc)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:fill_psinfo
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
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
In fs/binfmt_elf_fdpic.c (c05e95bc)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/binfmt_elf_fdpic.c:fill_psinfo
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
```
```
In fs/binfmt_flat.c (c05ed838)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
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
  - fs/binfmt_flat.c:create_flat_tables
  - fs/binfmt_flat.c:create_flat_tables
  - fs/binfmt_flat.c:create_flat_tables
  - fs/binfmt_flat.c:create_flat_tables
  - fs/binfmt_flat.c:create_flat_tables
  - fs/binfmt_flat.c:create_flat_tables
  - fs/binfmt_flat.c:create_flat_tables
```
```
In fs/fhandle.c (c05f2184)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_open_by_handle_at
  - fs/fhandle.c:__se_sys_open_by_handle_at
  - fs/fhandle.c:do_sys_name_to_handle
  - fs/fhandle.c:do_sys_name_to_handle
  - fs/fhandle.c:do_sys_name_to_handle
```
```
In fs/quota/quota.c (c05febbc)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
```
```
In fs/proc/task_mmu.c (c06006fc)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (c0604810)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:mem_rw
  - fs/proc/base.c:mem_rw
```
```
In fs/proc/vmcore.c (c0611ef4)
Location: arch/arm/include/asm/domain.h:85
Inline: True
```
```
In fs/proc/page.c (c0612f90)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In fs/kernfs/file.c (c0617b10)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
```
```
In fs/configfs/file.c (c061ad8c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_write_file
```
```
In fs/dcookies.c (c061fe00)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/dcookies.c:__se_sys_lookup_dcookie
```
```
In fs/ext4/ioctl.c (c064d460)
Location: arch/arm/include/asm/domain.h:85
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
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
```
```
In fs/fat/dir.c (c06a5ea4)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
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
```
```
In fs/fat/file.c (c06a90bc)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/miscdev.c (c06bb488)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/fuse/dev.c (c06be590)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_ioctl
```
```
In fs/pstore/ram_core.c (c06d74dc)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/pstore/ram_core.c:persistent_ram_update_user
```
```
In fs/efivarfs/file.c (c06d85f4)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In ipc/msgutil.c (c06da640)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:load_msg
```
```
In ipc/msg.c (c06dacc4)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - ipc/msg.c:do_msg_fill
  - ipc/msg.c:ksys_msgsnd
  - ipc/msg.c:ksys_msgctl
  - ipc/msg.c:copy_msqid_from_user
  - ipc/msg.c:copy_msqid_from_user
  - ipc/msg.c:copy_msqid_to_user
  - ipc/msg.c:copy_msqid_to_user
```
```
In ipc/sem.c (c06dee94)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:copy_semid_from_user
  - ipc/sem.c:copy_semid_from_user
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:copy_semid_to_user
  - ipc/sem.c:copy_semid_to_user
```
```
In ipc/shm.c (c06e0fdc)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
```
```
In ipc/mqueue.c (c06e4e68)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_getsetattr
  - ipc/mqueue.c:__se_sys_mq_getsetattr
  - ipc/mqueue.c:__se_sys_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_open
```
```
In security/keys/keyring.c (c06e79a0)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_read_iterator
```
```
In security/keys/keyctl.c (c06eb200)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__se_sys_add_key
```
```
In security/keys/request_key_auth.c (c06ed87c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_read
```
```
In security/keys/user_defined.c (c06ee028)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_read
```
```
In security/keys/dh.c (c06ef618)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - security/keys/dh.c:keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute_kdf
```
```
In security/keys/keyctl_pkey.c (c06efc98)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
```
```
In security/keys/big_key.c (c06f0600)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_read
```
```
In security/keys/trusted.c (c06f2598)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (c06f3554)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
```
In security/selinux/hooks.c (c0701154)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
```
```
In security/selinux/selinuxfs.c (c070b96c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
```
In security/smack/smack_lsm.c (c0721374)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
```
```
In security/smack/smackfs.c (c072961c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
```
```
In security/tomoyo/common.c (c072f87c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
```
```
In security/tomoyo/securityfs_if.c (c0737e7c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
```
```
In security/apparmor/apparmorfs.c (c073dd04)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lsm.c (c074f520)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
```
```
In block/ioctl.c (c07a4344)
Location: arch/arm/include/asm/domain.h:85
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
  - block/ioctl.c:blkdev_pr_preempt
  - block/ioctl.c:put_uint
  - block/ioctl.c:put_int
  - block/ioctl.c:put_ushort
  - block/ioctl.c:blk_ioctl_discard
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
```
In block/scsi_ioctl.c (c07b4874)
Location: arch/arm/include/asm/domain.h:85
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
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_scsi_complete_rq
  - block/bsg.c:bsg_scsi_fill_hdr
```
```
In block/bsg-lib.c (c07b5bfc)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_transport_complete_rq
```
```
In block/blk-zoned.c (c07c7f34)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In block/blk-mq-debugfs.c (c07cad4c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In block/sed-opal.c (c07cea44)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - block/sed-opal.c:write_shadow_mbr
```
```
In lib/bitmap.c (c07d2250)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (c07d89e0)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:iov_iter_fault_in_readable
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
```
```
In lib/kfifo.c (c07da864)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_from_user
  - lib/kfifo.c:kfifo_copy_from_user
```
```
In lib/usercopy.c (c07dd9cc)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/kstrtox.c (c07e064c)
Location: arch/arm/include/asm/domain.h:85
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
In lib/strncpy_from_user.c (c080f6a4)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (c080f844)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/gpio/gpiolib.c (c0861644)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
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
In drivers/pci/proc.c (c0890a1c)
Location: arch/arm/include/asm/domain.h:85
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
In drivers/pci/syscall.c (c08a3278)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/pci/syscall.c:__se_sys_pciconfig_write
  - drivers/pci/syscall.c:__se_sys_pciconfig_write
  - drivers/pci/syscall.c:__se_sys_pciconfig_write
  - drivers/pci/syscall.c:__se_sys_pciconfig_read
  - drivers/pci/syscall.c:__se_sys_pciconfig_read
  - drivers/pci/syscall.c:__se_sys_pciconfig_read
  - drivers/pci/syscall.c:__se_sys_pciconfig_read
  - drivers/pci/syscall.c:__se_sys_pciconfig_read
  - drivers/pci/syscall.c:__se_sys_pciconfig_read
```
```
In drivers/video/fbdev/core/fbmem.c (c08c8fb0)
Location: arch/arm/include/asm/domain.h:85
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
In drivers/video/fbdev/core/fbcmap.c (c08cbd2c)
Location: arch/arm/include/asm/domain.h:85
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
In drivers/video/fbdev/core/fbcon.c (c08d5908)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
```
```
In drivers/video/fbdev/imsttfb.c (c08dd66c)
Location: arch/arm/include/asm/domain.h:85
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
In drivers/tty/tty_io.c (c095cdcc)
Location: arch/arm/include/asm/domain.h:85
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
  - drivers/tty/tty_io.c:tty_write
```
```
In drivers/tty/n_tty.c (c095f044)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
```
In drivers/tty/tty_ioctl.c (c0963c78)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:set_termiox
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
```
```
In drivers/tty/tty_jobctrl.c (c09679a4)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
```
In drivers/tty/pty.c (c0967f78)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_get_pktmode
  - drivers/tty/pty.c:pty_set_pktmode
  - drivers/tty/pty.c:pty_get_lock
  - drivers/tty/pty.c:pty_set_lock
```
```
In drivers/tty/sysrq.c (c096a524)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:write_sysrq_trigger
```
```
In drivers/tty/vt/vt_ioctl.c (c096ba18)
Location: arch/arm/include/asm/domain.h:85
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
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
```
```
In drivers/tty/vt/vc_screen.c (c096cedc)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
```
```
In drivers/tty/vt/selection.c (c096e7f8)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:set_selection_user
  - drivers/tty/vt/selection.c:sel_loadlut
```
```
In drivers/tty/vt/keyboard.c (c0972854)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
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
```
```
In drivers/tty/vt/consolemap.c (c09734ac)
Location: arch/arm/include/asm/domain.h:85
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
In drivers/tty/vt/vt.c (c097bb00)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
```
```
In drivers/tty/serial/serial_core.c (c0982314)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/char/mem.c (c09a7208)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (c09ab33c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/virtio_console.c (c09adfa4)
Location: arch/arm/include/asm/domain.h:85
Inline: True
```
```
In drivers/char/hw_random/core.c (c09b0a44)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/char/tpm/tpm-dev-common.c (c09b2370)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
```
```
In drivers/lightnvm/core.c (c09d0124)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
```
```
In drivers/base/regmap/regmap-debugfs.c (c0a00c08)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
```
```
In drivers/block/loop.c (c0a07e08)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
  - drivers/block/loop.c:loop_set_status64
  - drivers/block/loop.c:loop_set_status_old
```
```
In drivers/mfd/ab3100-core.c (c0a32e74)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
```
```
In drivers/mfd/aat2870-core.c (c0a3671c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/dma-buf/dma-buf.c (c0a3c044)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
```
In drivers/dma-buf/sync_file.c (c0a409f4)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
```
```
In drivers/dma-buf/sw_sync.c (c0a412d0)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/dma-buf/udmabuf.c (c0a42544)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
```
```
In drivers/scsi/scsi_ioctl.c (c0a45410)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/scsi_error.c (c0a495e0)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
```
```
In drivers/scsi/scsi_devinfo.c (c0a533a8)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
```
```
In drivers/scsi/scsi_proc.c (c0a53f3c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
```
```
In drivers/scsi/sg.c (c0a652e0)
Location: arch/arm/include/asm/domain.h:85
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
  - drivers/scsi/sg.c:sg_new_write
  - drivers/scsi/sg.c:sg_new_write
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
```
```
In drivers/ata/libata-scsi.c (c0a7563c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
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
In drivers/gpu/vga/vgaarb.c (c0a8d908)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
```
```
In drivers/mtd/mtdchar.c (c0a95efc)
Location: arch/arm/include/asm/domain.h:85
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
  - drivers/mtd/mtdchar.c:mtdchar_readoob
  - drivers/mtd/mtdchar.c:mtdchar_readoob
  - drivers/mtd/mtdchar.c:mtdchar_writeoob
  - drivers/mtd/mtdchar.c:mtdchar_write
  - drivers/mtd/mtdchar.c:mtdchar_read
```
```
In drivers/net/tun.c (c0ac62d8)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_set_ebpf
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (c0aceeec)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_get
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_set
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_set
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad4208)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_ioctl
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_ioctl
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (c0add108)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
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
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/cdrom/cdrom.c (c0ae7214)
Location: arch/arm/include/asm/domain.h:85
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
```
```
In drivers/usb/core/devio.c (c0b05690)
Location: arch/arm/include/asm/domain.h:85
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
  - drivers/usb/core/devio.c:proc_disconnect_claim
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
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (c0b082e4)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/host/xhci-debugfs.c (c0b61f20)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
```
```
In drivers/usb/musb/musb_debugfs.c (c0b71514)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/usb/musb/musb_debugfs.c:musb_softconnect_write
  - drivers/usb/musb/musb_debugfs.c:musb_test_mode_write
```
```
In drivers/input/input-compat.c (c0b7b410)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_ff_effect_from_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_from_user
```
```
In drivers/input/mousedev.c (c0b7d40c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/mousedev.c:mousedev_write
```
```
In drivers/input/evdev.c (c0b7f6e8)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_handle_set_keycode_v2
  - drivers/input/evdev.c:evdev_handle_set_keycode
  - drivers/input/evdev.c:evdev_handle_set_keycode
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:evdev_handle_get_keycode
  - drivers/input/evdev.c:evdev_handle_get_keycode
  - drivers/input/evdev.c:str_to_user
```
```
In drivers/input/misc/uinput.c (c0b84a1c)
Location: arch/arm/include/asm/domain.h:85
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
  - drivers/input/misc/uinput.c:uinput_ff_upload_from_user
  - drivers/input/misc/uinput.c:uinput_dev_setup
```
```
In drivers/rtc/dev.c (c0b89784)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_read
```
```
In drivers/rtc/rtc-pcf8523.c (c0b8d45c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_ioctl
```
```
In drivers/i2c/i2c-dev.c (c0b97d4c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
```
In drivers/media/cec/cec-api.c (c0ba4af4)
Location: arch/arm/include/asm/domain.h:85
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
In drivers/pps/pps.c (c0ba5bac)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
```
```
In drivers/ptp/ptp_chardev.c (c0ba81c0)
Location: arch/arm/include/asm/domain.h:85
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
In drivers/watchdog/watchdog_dev.c (c0bc1ce4)
Location: arch/arm/include/asm/domain.h:85
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
  - drivers/watchdog/watchdog_dev.c:watchdog_write
```
```
In drivers/md/md.c (c0bd568c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:get_array_info
```
```
In drivers/md/dm-ioctl.c (c0be79cc)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
```
In drivers/mmc/core/block.c (c0c1b7a0)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_ioctl_multi_cmd
  - drivers/mmc/core/block.c:mmc_blk_ioctl_copy_from_user
```
```
In drivers/firmware/tegra/bpmp-debugfs.c (c0c42a2c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_store
```
```
In drivers/remoteproc/remoteproc_debugfs.c (c0c65b80)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
```
```
In sound/core/memory.c (c0c84c10)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - sound/core/memory.c:copy_from_user_toio
  - sound/core/memory.c:copy_to_user_fromio
```
```
In sound/core/control.c (c0c877a4)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
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
In sound/core/info.c (c0c89768)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - sound/core/info.c:snd_info_text_entry_write
```
```
In sound/core/timer.c (c0c8e63c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
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
```
```
In sound/core/pcm.c (c0c904a8)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - sound/core/pcm.c:snd_pcm_control_ioctl
  - sound/core/pcm.c:snd_pcm_control_ioctl
  - sound/core/pcm.c:snd_pcm_control_ioctl
  - sound/core/pcm.c:snd_pcm_control_ioctl
  - sound/core/pcm.c:snd_pcm_control_ioctl
  - sound/core/pcm.c:snd_pcm_control_ioctl
```
```
In sound/core/pcm_native.c (c0c95dcc)
Location: arch/arm/include/asm/domain.h:85
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
  - sound/core/pcm_native.c:snd_pcm_rewind_ioctl
  - sound/core/pcm_native.c:snd_pcm_rewind_ioctl
  - sound/core/pcm_native.c:snd_pcm_rewind_ioctl
  - sound/core/pcm_native.c:snd_pcm_sync_ptr
  - sound/core/pcm_native.c:snd_pcm_sync_ptr
  - sound/core/pcm_native.c:snd_pcm_sync_ptr
  - sound/core/pcm_native.c:snd_pcm_status_user
  - sound/core/pcm_native.c:snd_pcm_status_user
  - sound/core/pcm_native.c:snd_pcm_sw_params_user
  - sound/core/pcm_native.c:snd_pcm_sw_params_user
  - sound/core/pcm_native.c:snd_pcm_info_user
```
```
In sound/core/pcm_lib.c (c0c988d8)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - sound/core/pcm_lib.c:pcm_chmap_ctl_tlv
  - sound/core/pcm_lib.c:pcm_chmap_ctl_tlv
  - sound/core/pcm_lib.c:pcm_chmap_ctl_tlv
  - sound/core/pcm_lib.c:pcm_chmap_ctl_tlv
  - sound/core/pcm_lib.c:pcm_chmap_ctl_tlv
  - sound/core/pcm_lib.c:default_read_copy
  - sound/core/pcm_lib.c:default_write_copy
```
```
In sound/core/compress_offload.c (c0c9e708)
Location: arch/arm/include/asm/domain.h:85
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
  - sound/core/compress_offload.c:snd_compr_get_caps
  - sound/core/compress_offload.c:snd_compr_write
  - sound/core/compress_offload.c:snd_compr_write
  - sound/core/compress_offload.c:snd_compr_write
```
```
In sound/soc/soc-generic-dmaengine-pcm.c (c0cbb654)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - sound/soc/soc-generic-dmaengine-pcm.c:dmaengine_copy_user
  - sound/soc/soc-generic-dmaengine-pcm.c:dmaengine_copy_user
```
```
In net/socket.c (c0cc5b14)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:__se_sys_getsockopt
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:move_addr_to_user
  - net/socket.c:move_addr_to_user
  - net/socket.c:move_addr_to_user
  - net/socket.c:move_addr_to_kernel
```
```
In net/core/sock.c (c0cccb90)
Location: arch/arm/include/asm/domain.h:85
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
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_set_timeout
```
```
In net/core/scm.c (c0cda0a4)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
```
```
In net/core/flow_dissector.c (c0cde60c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
```
In net/core/sysctl_net_core.c (c0ce0f68)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (c0cf6e80)
Location: arch/arm/include/asm/domain.h:85
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
In net/core/filter.c (c0d1c6c4)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
```
```
In net/core/dev_ioctl.c (c0d1d360)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/netlink/af_netlink.c (c0d5cab8)
Location: arch/arm/include/asm/domain.h:85
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
In net/bpf/test_run.c (c0d63730)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_ctx_finish
  - net/bpf/test_run.c:bpf_ctx_finish
  - net/bpf/test_run.c:bpf_test_init
  - net/bpf/test_run.c:bpf_test_finish
  - net/bpf/test_run.c:bpf_test_finish
  - net/bpf/test_run.c:bpf_test_finish
  - net/bpf/test_run.c:bpf_test_finish
```
```
In net/ipv4/ip_options.c (c0d7118c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_get_from_user
```
```
In net/ipv4/ip_sockglue.c (c0d75d30)
Location: arch/arm/include/asm/domain.h:85
Inline: True
```
```
In net/ipv4/tcp.c (c0d7f398)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (c0d9bb8c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
```
```
In net/ipv4/raw.c (c0da4d24)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/raw.c:raw_ioctl
```
```
In net/ipv4/udp.c (c0da7b34)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_ioctl
  - net/ipv4/udp.c:udp_ioctl
```
```
In net/ipv4/arp.c (c0dafe68)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
```
```
In net/ipv4/devinet.c (c0db2c18)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_gifconf
```
```
In net/ipv4/af_inet.c (c0db8bb4)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
```
In net/ipv4/igmp.c (c0dbe4bc)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
```
```
In net/ipv4/fib_frontend.c (c0dbf634)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
```
```
In net/ipv4/bpfilter/sockopt.c (c0dd1b20)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
```
```
In net/ipv4/ipmr.c (c0dd9d78)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
```
In net/unix/af_unix.c (c0df753c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/addrconf.c (c0e0fec8)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
```
```
In net/ipv6/route.c (c0e1c77c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
```
```
In net/ipv6/ipv6_sockglue.c (c0e215d8)
Location: arch/arm/include/asm/domain.h:85
Inline: True
```
```
In net/ipv6/raw.c (c0e2cc90)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/mcast.c (c0e34e5c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
```
```
In net/ipv6/tcp_ipv6.c (c0e39bec)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
```
In net/ipv6/ip6_flowlabel.c (c0e4285c)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/ip6mr.c (c0e49444)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
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
```
```
In net/packet/af_packet.c (c0e56d94)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_ioctl
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
```
```
In net/wireless/wext-core.c (c0e60eb0)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
```
```
In net/wireless/wext-priv.c (c0e61884)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:ioctl_private_iw_point
  - net/wireless/wext-priv.c:ioctl_private_iw_point
```
```
In net/rfkill/core.c (c0e6a430)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_read
```
```
In net/xdp/xsk.c (c0e7a004)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
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
```
```
In lib/seq_buf.c (c0e8a8d0)
Location: arch/arm/include/asm/domain.h:85
Inline: True
Inline callers:
  - lib/seq_buf.c:seq_buf_to_user
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct protection_domain *get_domain(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a7d90)
Location: drivers/iommu/amd_iommu.c:2348
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_v2_domain
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:unmap_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:unmap_page
  - drivers/iommu/amd_iommu.c:map_page
```
**Symbols:**

```
ffffffff816a7d90-ffffffff816a7e1b: get_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct protection_domain *get_domain(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81685780)
Location: drivers/iommu/amd_iommu.c:2348
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_v2_domain
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:unmap_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:unmap_page
  - drivers/iommu/amd_iommu.c:map_page
```
**Symbols:**

```
ffffffff81685780-ffffffff8168580b: get_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct protection_domain *get_domain(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d6000)
Location: drivers/iommu/amd_iommu.c:2348
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_v2_domain
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:unmap_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:unmap_page
  - drivers/iommu/amd_iommu.c:map_page
```
**Symbols:**

```
ffffffff816d6000-ffffffff816d608b: get_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct protection_domain *get_domain(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816f05b0)
Location: drivers/iommu/amd_iommu.c:2348
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_v2_domain
  - drivers/iommu/amd_iommu.c:free_coherent
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:unmap_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:unmap_page
  - drivers/iommu/amd_iommu.c:map_page
```
**Symbols:**

```
ffffffff816f05b0-ffffffff816f063b: get_domain (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
