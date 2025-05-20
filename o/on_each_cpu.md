# Function: <code>on_each_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int on_each_cpu(void (*func)(void *), void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81103eb0)
Location: kernel/smp.c:591
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mcheck/mce.c:set_bank
  - arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce
  - arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce
  - arch/x86/kernel/cpu/mcheck/mce.c:store_int_with_restart
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_bank
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/tlb.c:flush_tlb_all
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/profile.c:create_proc_profile
  - kernel/time/hrtimer.c:clock_was_set_work
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus
  - drivers/idle/intel_idle.c:intel_idle_exit
  - drivers/char/agp/generic.c:global_cache_flush
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff81103eb0-ffffffff81103f07: on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int on_each_cpu(void (*func)(void *), void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8110b2c0)
Location: kernel/smp.c:576
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/cpu/mcheck/mce.c:store_int_with_restart
  - arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce
  - arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce
  - arch/x86/kernel/cpu/mcheck/mce.c:set_bank
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_bank
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover
  - arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_all
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/hrtimer.c:clock_was_set_work
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus
  - drivers/char/agp/generic.c:global_cache_flush
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff8110b2c0-ffffffff8110b317: on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int on_each_cpu(void (*func)(void *), void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81112c20)
Location: kernel/smp.c:583
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/cpu/mcheck/mce.c:store_int_with_restart
  - arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce
  - arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce
  - arch/x86/kernel/cpu/mcheck/mce.c:set_bank
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_bank
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover
  - arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_all
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/hrtimer.c:clock_was_set_work
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus
  - drivers/char/agp/generic.c:global_cache_flush
```
**Symbols:**

```
ffffffff81112c20-ffffffff81112c77: on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int on_each_cpu(void (*func)(void *), void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81114130)
Location: kernel/smp.c:594
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/cpu/mcheck/mce.c:store_int_with_restart
  - arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce
  - arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce
  - arch/x86/kernel/cpu/mcheck/mce.c:set_bank
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_bank
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_read
  - arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_all
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/hrtimer.c:clock_was_set_work
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus
  - drivers/char/agp/generic.c:global_cache_flush
```
**Symbols:**

```
ffffffff81114130-ffffffff81114187: on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int on_each_cpu(void (*func)(void *), void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8111f6a0)
Location: kernel/smp.c:596
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce
  - arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce
  - arch/x86/kernel/cpu/mcheck/mce.c:set_bank
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_bank
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover
  - arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:cpa_flush_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_all
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/hrtimer.c:clock_was_set_work
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus
  - drivers/char/agp/generic.c:global_cache_flush
```
**Symbols:**

```
ffffffff8111f6a0-ffffffff8111f6f9: on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int on_each_cpu(void (*func)(void *), void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8112c9d0)
Location: kernel/smp.c:598
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mcheck/mce.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce
  - arch/x86/kernel/cpu/mcheck/mce.c:set_ignore_ce
  - arch/x86/kernel/cpu/mcheck/mce.c:set_bank
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_disable_bank
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover
  - arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq
  - arch/x86/kernel/ftrace.c:run_sync
  - arch/x86/kernel/ftrace.c:run_sync
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:cpa_flush_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_all
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/hrtimer.c:clock_was_set_work
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus
  - drivers/char/agp/generic.c:global_cache_flush
```
**Symbols:**

```
ffffffff8112c9d0-ffffffff8112ca29: on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int on_each_cpu(void (*func)(void *), void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811382a0)
Location: kernel/smp.c:596
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq
  - arch/x86/kernel/ftrace.c:run_sync
  - arch/x86/kernel/ftrace.c:run_sync
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_all
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/hrtimer.c:clock_was_set_work
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus
  - drivers/char/agp/generic.c:global_cache_flush
```
**Symbols:**

```
ffffffff811382a0-ffffffff811382f9: on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void on_each_cpu(void (*func)(void *), void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81143490)
Location: kernel/smp.c:611
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq
  - arch/x86/kernel/ftrace.c:run_sync
  - arch/x86/kernel/ftrace.c:run_sync
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_all
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/hrtimer.c:clock_was_set_work
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus
  - drivers/char/agp/generic.c:global_cache_flush
```
**Symbols:**

```
ffffffff81143490-ffffffff811434e7: on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void on_each_cpu(void (*func)(void *), void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8114efd0)
Location: kernel/smp.c:611
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq
  - arch/x86/kernel/ftrace.c:run_sync
  - arch/x86/kernel/ftrace.c:run_sync
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_all
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/hrtimer.c:clock_was_set_work
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus
  - drivers/char/agp/generic.c:global_cache_flush
```
**Symbols:**

```
ffffffff8114efd0-ffffffff8114f027: on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void on_each_cpu(smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115fa90)
Location: kernel/smp.c:694
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_all
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - kernel/profile.c:profile_discard_flip_buffers
  - kernel/profile.c:profile_flip_buffers
  - kernel/time/hrtimer.c:clock_was_set_work
  - arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus
  - drivers/char/agp/generic.c:global_cache_flush
```
**Symbols:**

```
ffffffff8115fa90-ffffffff8115faea: on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void on_each_cpu(smp_call_func_t func, void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115ba30)
Location: kernel/smp.c:831
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_all
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - kernel/profile.c:profile_discard_flip_buffers
  - kernel/profile.c:profile_flip_buffers
  - kernel/time/hrtimer.c:clock_was_set_work
  - arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus
  - drivers/char/agp/generic.c:global_cache_flush
```
**Symbols:**

```
ffffffff8115ba30-ffffffff8115ba8a: on_each_cpu (STB_GLOBAL)
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
In arch/x86/events/core.c (ffffffff81005b35)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/events/core.c:set_attr_rdpmc
```
```
In arch/x86/events/intel/core.c (ffffffff8100ce10)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/xen/suspend.c (ffffffff81023c35)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
```
```
In arch/x86/kernel/alternative.c (ffffffff8103ed18)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81bc74cf)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff8104de75)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810523f9)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_bank
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810552e9)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff81069ffe)
Location: include/linux/smp.h:69
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106f755)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq
```
```
In arch/x86/kernel/amd_nb.c (ffffffff831daad8)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f53e)
Location: include/linux/smp.h:69
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff8108c47e)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_all
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108de8f)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
```
In kernel/profile.c (ffffffff8113dd67)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
```
```
In kernel/time/hrtimer.c (ffffffff81143aa5)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set_work
```
```
In kernel/trace/ftrace.c (ffffffff811b2838)
Location: include/linux/smp.h:69
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff811d2d42)
Location: include/linux/smp.h:69
Inline: True
```
```
In arch/x86/lib/cache-smp.c (ffffffff815ef1f5)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus
```
```
In drivers/char/agp/generic.c (ffffffff817783e5)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:global_cache_flush
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
In arch/x86/events/core.c (ffffffff81006105)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/events/core.c:set_attr_rdpmc
```
```
In arch/x86/events/intel/core.c (ffffffff8100d916)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/xen/suspend.c (ffffffff81027ed5)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
```
```
In arch/x86/kernel/alternative.c (ffffffff81044a88)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81c9acd6)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff81055675)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105a91a)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_bank
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105dc89)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff8107468e)
Location: include/linux/smp.h:69
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8107b185)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq
```
```
In arch/x86/kernel/amd_nb.c (ffffffff832bdd12)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
```
```
In arch/x86/kernel/kvm.c (ffffffff8108e2be)
Location: include/linux/smp.h:69
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff8109bcbe)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_all
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109d79b)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:cpa_flush_all
```
```
In kernel/profile.c (ffffffff81160f48)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
```
```
In kernel/time/hrtimer.c (ffffffff81167eb4)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set
```
```
In kernel/trace/ftrace.c (ffffffff811dc768)
Location: include/linux/smp.h:69
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff811ffb22)
Location: include/linux/smp.h:69
Inline: True
```
```
In arch/x86/lib/cache-smp.c (ffffffff8165c305)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus
```
```
In drivers/char/agp/generic.c (ffffffff817fde85)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:global_cache_flush
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
In arch/x86/events/core.c (ffffffff810054fd)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/events/core.c:set_attr_rdpmc
```
```
In arch/x86/events/intel/core.c (ffffffff8100ecb1)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/xen/suspend.c (ffffffff8102c410)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
```
```
In arch/x86/kernel/alternative.c (ffffffff8104d0bf)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81e4a1f6)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff81061623)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810675e2)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_bank
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8106a3a9)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff81082f6d)
Location: include/linux/smp.h:69
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8108a295)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq
```
```
In arch/x86/kernel/amd_nb.c (ffffffff8346f71f)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
```
```
In arch/x86/kernel/kvm.c (ffffffff8109ed9d)
Location: include/linux/smp.h:69
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff810af19b)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_all
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b1071)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:cpa_flush_all
```
```
In kernel/profile.c (ffffffff81193cfc)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
```
```
In kernel/time/hrtimer.c (ffffffff8119b895)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set
```
```
In kernel/trace/ftrace.c (ffffffff81212c97)
Location: include/linux/smp.h:69
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff8123a5d3)
Location: include/linux/smp.h:69
Inline: True
```
```
In arch/x86/lib/cache-smp.c (ffffffff81775355)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus
```
```
In drivers/char/agp/generic.c (ffffffff8193d3d5)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:global_cache_flush
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
In arch/x86/events/core.c (ffffffff8100610d)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/events/core.c:set_attr_rdpmc
```
```
In arch/x86/events/intel/core.c (ffffffff810123e1)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/xen/suspend.c (ffffffff810333d8)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
```
```
In arch/x86/kernel/alternative.c (ffffffff810594df)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106ee6e)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff81070023)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81076bc2)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_bank
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107a199)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff81095aad)
Location: include/linux/smp.h:69
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8109e285)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq
```
```
In arch/x86/kernel/amd_nb.c (ffffffff83e95de4)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
```
```
In arch/x86/kernel/kvm.c (ffffffff810b648d)
Location: include/linux/smp.h:69
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff810c957b)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_all
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cb790)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:cpa_flush_all
```
```
In kernel/profile.c (ffffffff811d21d0)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - kernel/profile.c:profile_discard_flip_buffers
  - kernel/profile.c:profile_flip_buffers
```
```
In kernel/time/hrtimer.c (ffffffff811da143)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set
```
```
In kernel/trace/ftrace.c (ffffffff8125c3a7)
Location: include/linux/smp.h:69
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff81287783)
Location: include/linux/smp.h:69
Inline: True
```
```
In arch/x86/lib/cache-smp.c (ffffffff818a5f35)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus
```
```
In drivers/char/agp/generic.c (ffffffff81a9e255)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:global_cache_flush
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
In arch/x86/events/core.c (ffffffff810058ad)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/events/core.c:set_attr_rdpmc
```
```
In arch/x86/events/intel/core.c (ffffffff810118ee)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/xen/suspend.c (ffffffff81033378)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
```
```
In arch/x86/kernel/alternative.c (ffffffff8105aa86)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8107065e)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff81071c33)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81076b35)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:amd_check_microcode
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81078e42)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_bank
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107c449)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff81098aed)
Location: include/linux/smp.h:69
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a1265)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq
```
```
In arch/x86/kernel/amd_nb.c (ffffffff836b9964)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
```
```
In arch/x86/kernel/kvm.c (ffffffff810b958d)
Location: include/linux/smp.h:69
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff810ccc06)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_all
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cedb0)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:cpa_flush_all
```
```
In kernel/profile.c (ffffffff811e64be)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - kernel/profile.c:profile_discard_flip_buffers
  - kernel/profile.c:profile_flip_buffers
```
```
In kernel/time/hrtimer.c (ffffffff811ee659)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set
```
```
In kernel/trace/ftrace.c (ffffffff812732d4)
Location: include/linux/smp.h:69
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff812a4473)
Location: include/linux/smp.h:69
Inline: True
```
```
In arch/x86/lib/cache-smp.c (ffffffff818e8d45)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus
```
```
In drivers/char/agp/generic.c (ffffffff81ae9bf5)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:global_cache_flush
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
In arch/x86/events/core.c (ffffffff8100afad)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/events/core.c:set_attr_rdpmc
```
```
In arch/x86/events/intel/core.c (ffffffff8101708e)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
```
```
In arch/x86/xen/suspend.c (ffffffff81039688)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
```
```
In arch/x86/kernel/alternative.c (ffffffff81061d46)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81077f3e)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff81079453)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8107e18e)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:amd_check_microcode
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810803f2)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_bank
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810838f1)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff810a008d)
Location: include/linux/smp.h:69
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a8635)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq
```
```
In arch/x86/kernel/amd_nb.c (ffffffff838ea294)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
```
```
In arch/x86/kernel/kvm.c (ffffffff810c09ad)
Location: include/linux/smp.h:69
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff810d52c6)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_all
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d7490)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:cpa_flush_all
```
```
In kernel/profile.c (ffffffff811fc20e)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - kernel/profile.c:profile_discard_flip_buffers
  - kernel/profile.c:profile_flip_buffers
```
```
In kernel/time/hrtimer.c (ffffffff812047d9)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set
```
```
In kernel/trace/ftrace.c (ffffffff8128d864)
Location: include/linux/smp.h:69
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffff812bfdd5)
Location: include/linux/smp.h:69
Inline: True
```
```
In arch/x86/lib/cache-smp.c (ffffffff819301e5)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus
```
```
In drivers/char/agp/generic.c (ffffffff81b3d085)
Location: include/linux/smp.h:69
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:global_cache_flush
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void on_each_cpu(void (*func)(void *), void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffff8000101bd600)
Location: kernel/smp.c:611
Inline: False
Direct callers:
  - arch/arm64/kernel/armv8_deprecated.c:register_insn_emulation
  - arch/arm64/kernel/armv8_deprecated.c:update_insn_emulation_mode
  - arch/arm64/kernel/armv8_deprecated.c:update_insn_emulation_mode
  - virt/kvm/kvm_main.c:kvm_exit
  - virt/kvm/kvm_main.c:kvm_reboot
  - virt/kvm/kvm_main.c:kvm_create_vm
  - virt/kvm/arm/arm.c:kvm_arch_init
  - virt/kvm/arm/arm.c:kvm_arch_init
  - virt/kvm/arm/arm.c:kvm_arch_init
  - virt/kvm/arm/arm.c:kvm_arch_init
  - virt/kvm/arm/arm.c:kvm_arch_init
  - virt/kvm/arm/arm.c:kvm_arch_init
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/hrtimer.c:clock_was_set_work
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_remove
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_probe
  - drivers/firmware/arm_sdei.c:sdei_device_thaw
  - drivers/firmware/arm_sdei.c:sdei_device_resume
  - drivers/firmware/arm_sdei.c:sdei_device_suspend
  - drivers/firmware/arm_sdei.c:sdei_event_disable
  - drivers/firmware/arm_sdei.c:sdei_event_enable
  - drivers/firmware/arm_sdei.c:sdei_platform_reset
  - drivers/firmware/arm_sdei.c:sdei_mark_interface_broken
```
**Symbols:**

```
ffff8000101bd600-ffff8000101bd678: on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void on_each_cpu(void (*func)(void *), void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (c0405794)
Location: kernel/smp.c:611
Inline: False
Direct callers:
  - arch/arm/vfp/vfpmodule.c:vfp_init
  - arch/arm/kernel/smp_tlb.c:flush_bp_all
  - arch/arm/kernel/smp_tlb.c:flush_tlb_kernel_range
  - arch/arm/kernel/smp_tlb.c:flush_tlb_kernel_page
  - arch/arm/kernel/smp_tlb.c:flush_tlb_all
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/hrtimer.c:clock_was_set_work
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/trace_events.c:ftrace_event_pid_write
```
**Symbols:**

```
c0405794-c04057e4: on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void on_each_cpu(void (*func)(void *), void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (c000000000223a20)
Location: kernel/smp.c:611
Inline: False
Direct callers:
  - arch/powerpc/kernel/sysfs.c:store_dscr_default
  - arch/powerpc/kernel/setup_64.c:rfi_flush_enable
  - arch/powerpc/kernel/rtas.c:rtas_ibm_suspend_me
  - arch/powerpc/kernel/kvm.c:kvm_guest_init
  - arch/powerpc/mm/slice.c:slice_get_unmapped_area
  - arch/powerpc/mm/slice.c:slice_get_unmapped_area
  - arch/powerpc/perf/imc-pmu.c:thread_imc_disable
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/hrtimer.c:clock_was_set_work
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - drivers/char/agp/generic.c:global_cache_flush
```
**Symbols:**

```
c000000000223a20-c000000000223ab8: on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void on_each_cpu(void (*func)(void *), void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffe000140b96)
Location: kernel/smp.c:611
Inline: False
Direct callers:
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/hrtimer.c:clock_was_set_work
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/trace_events.c:ftrace_event_pid_write
```
**Symbols:**

```
ffffffe000140b96-ffffffe000140bea: on_each_cpu (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void on_each_cpu(void (*func)(void *), void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811475f0)
Location: kernel/smp.c:611
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq
  - arch/x86/kernel/ftrace.c:run_sync
  - arch/x86/kernel/ftrace.c:run_sync
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_all
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/hrtimer.c:clock_was_set_work
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus
  - drivers/char/agp/generic.c:global_cache_flush
```
**Symbols:**

```
ffffffff811475f0-ffffffff81147647: on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void on_each_cpu(void (*func)(void *), void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8113a8a0)
Location: kernel/smp.c:611
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq
  - arch/x86/kernel/ftrace.c:run_sync
  - arch/x86/kernel/ftrace.c:run_sync
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_all
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/hrtimer.c:clock_was_set_work
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus
  - drivers/char/agp/generic.c:global_cache_flush
```
**Symbols:**

```
ffffffff8113a8a0-ffffffff8113a8e3: on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void on_each_cpu(void (*func)(void *), void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811454a0)
Location: kernel/smp.c:611
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq
  - arch/x86/kernel/ftrace.c:run_sync
  - arch/x86/kernel/ftrace.c:run_sync
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_all
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/hrtimer.c:clock_was_set_work
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus
  - drivers/char/agp/generic.c:global_cache_flush
```
**Symbols:**

```
ffffffff811454a0-ffffffff811454f7: on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void on_each_cpu(void (*func)(void *), void *info, int wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81152090)
Location: kernel/smp.c:611
Inline: False
Direct callers:
  - arch/x86/events/core.c:set_attr_rdpmc
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:freeze_on_smi_store
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/umwait.c:max_time_store
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_cmci_disabled
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_ignore_ce
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:mce_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/apic/apic.c:lapic_update_tsc_freq
  - arch/x86/kernel/ftrace.c:run_sync
  - arch/x86/kernel/ftrace.c:run_sync
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_all
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/time/hrtimer.c:clock_was_set_work
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - arch/x86/lib/cache-smp.c:wbinvd_on_all_cpus
  - drivers/char/agp/generic.c:global_cache_flush
```
**Symbols:**

```
ffffffff81152090-ffffffff811520ef: on_each_cpu (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void (*func)(void *)</code> ➡️ <code>smp_call_func_t func</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
