# Function: <code>static_key_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void static_key_disable(struct static_key *key);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a6b0e)
Location: include/linux/jump_label.h:227
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_feat_write
  - kernel/sched/core.c:sysctl_numa_balancing
```
```
In kernel/cgroup.c (ffffffff81113100)
Location: include/linux/jump_label.h:227
Inline: True
Inline callers:
  - kernel/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup.c:cgroup_init
```
**Symbols:**

```
ffffffff81113100-ffffffff81113142: static_key_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void static_key_disable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8119d700)
Location: kernel/jump_label.c:92
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup.c:cgroup_init
  - kernel/cgroup.c:rebind_subsystems
  - kernel/events/core.c:perf_sched_delayed
  - lib/dynamic_debug.c:ddebug_exec_query
```
**Symbols:**

```
ffffffff8119d700-ffffffff8119d74b: static_key_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void static_key_disable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811ad120)
Location: kernel/jump_label.c:92
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup.c:cgroup_init
  - kernel/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_sched_delayed
  - lib/dynamic_debug.c:ddebug_exec_query
  - net/core/dev.c:netstamp_clear
```
**Symbols:**

```
ffffffff811ad120-ffffffff811ad16b: static_key_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void static_key_disable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811b45b0)
Location: kernel/jump_label.c:93
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_sched_delayed
  - lib/dynamic_debug.c:ddebug_exec_query
  - net/core/dev.c:netstamp_clear
```
**Symbols:**

```
ffffffff811b45b0-ffffffff811b45d3: static_key_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void static_key_disable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811c82c0)
Location: kernel/jump_label.c:175
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/paravirt.c:native_pv_lock_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_sched_delayed
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - lib/dynamic_debug.c:ddebug_exec_query
  - net/core/dev.c:netstamp_clear
```
**Symbols:**

```
ffffffff811c82c0-ffffffff811c82e2: static_key_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void static_key_disable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811e86d0)
Location: kernel/jump_label.c:176
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus
  - arch/x86/kernel/paravirt.c:native_pv_lock_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/debug.c:sched_feat_write
  - kernel/time/timer.c:timers_update_migration
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_sched_delayed
  - kernel/memremap.c:dev_pagemap_put_ops
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - lib/dynamic_debug.c:ddebug_exec_query
  - net/core/dev.c:netstamp_clear
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffff811e86d0-ffffffff811e86f2: static_key_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void static_key_disable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811f9390)
Location: kernel/jump_label.c:197
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus
  - arch/x86/kernel/paravirt.c:native_pv_lock_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/time/timer.c:timers_update_migration
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_sched_delayed
  - kernel/memremap.c:dev_pagemap_put_ops
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - lib/dynamic_debug.c:ddebug_exec_query
  - net/core/dev.c:netstamp_clear
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffff811f9390-ffffffff811f93b2: static_key_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void static_key_disable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81211310)
Location: kernel/jump_label.c:212
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus
  - arch/x86/kernel/paravirt.c:native_pv_lock_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/time/timer.c:timers_update_migration
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_sched_delayed
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/shuffle.c:page_alloc_shuffle
  - mm/memremap.c:devmap_managed_enable_put
  - lib/dynamic_debug.c:ddebug_exec_query
  - net/core/dev.c:netstamp_clear
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffff81211310-ffffffff81211334: static_key_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void static_key_disable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8121efc0)
Location: kernel/jump_label.c:212
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus
  - arch/x86/kernel/paravirt.c:native_pv_lock_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/time/timer.c:timers_update_migration
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_sched_delayed
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/shuffle.c:page_alloc_shuffle
  - mm/memremap.c:devmap_managed_enable_put
  - lib/dynamic_debug.c:ddebug_exec_query
  - net/core/dev.c:netstamp_clear
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffff8121efc0-ffffffff8121efe4: static_key_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void static_key_disable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8124ae10)
Location: kernel/jump_label.c:212
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/smpboot.c:disable_freq_invariance_workfn
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus
  - arch/x86/kernel/paravirt.c:native_pv_lock_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_update_keys
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_sched_delayed
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/shuffle.c:page_alloc_shuffle
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - lib/dynamic_debug.c:ddebug_change
  - lib/vsprintf.c:initialize_ptr_random
  - lib/vsprintf.c:enable_ptr_key_workfn
  - net/core/dev.c:netstamp_clear
```
**Symbols:**

```
ffffffff8124ae10-ffffffff8124ae36: static_key_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void static_key_disable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81255200)
Location: kernel/jump_label.c:212
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/smpboot.c:disable_freq_invariance_workfn
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
  - arch/x86/kernel/paravirt.c:native_pv_lock_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_update_keys
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/tracepoint.c:tracepoint_remove_func
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_sched_delayed
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/dynamic_debug.c:ddebug_change
  - lib/vsprintf.c:initialize_ptr_random
  - lib/vsprintf.c:enable_ptr_key_workfn
  - net/core/dev.c:netstamp_clear
```
**Symbols:**

```
ffffffff81255200-ffffffff81255226: static_key_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void static_key_disable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81259700)
Location: kernel/jump_label.c:212
Inline: False
Direct callers:
  - init/main.c:early_randomize_kstack_offset
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/smpboot.c:disable_freq_invariance_workfn
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
  - arch/x86/kernel/paravirt.c:native_pv_lock_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_update_keys
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_sched_delayed
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:init_mem_debugging_and_hardening
  - mm/page_alloc.c:init_mem_debugging_and_hardening
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/dynamic_debug.c:ddebug_change
  - lib/vsprintf.c:initialize_ptr_random
  - lib/vsprintf.c:enable_ptr_key_workfn
  - net/core/dev.c:netstamp_clear
```
**Symbols:**

```
ffffffff81259700-ffffffff81259726: static_key_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void static_key_disable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812953d0)
Location: kernel/jump_label.c:212
Inline: False
Direct callers:
  - init/main.c:early_randomize_kstack_offset
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/smpboot.c:disable_freq_invariance_workfn
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
  - arch/x86/kernel/paravirt.c:native_pv_lock_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:setup_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/sched/psi.c:psi_init
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_update_keys
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/delayacct.c:sysctl_delayacct
  - kernel/delayacct.c:delayacct_init
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/trace/trace.c:late_trace_init
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_sched_delayed
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:init_mem_debugging_and_hardening
  - mm/page_alloc.c:init_mem_debugging_and_hardening
  - mm/slub.c:setup_slub_debug
  - lib/once.c:once_deferred
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/dynamic_debug.c:ddebug_change
  - lib/vsprintf.c:initialize_ptr_random
  - lib/vsprintf.c:enable_ptr_key_workfn
  - net/core/dev.c:netstamp_clear
```
**Symbols:**

```
ffffffff812953d0-ffffffff812953f6: static_key_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void static_key_disable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812eb1a0)
Location: kernel/jump_label.c:212
Inline: False
Direct callers:
  - init/main.c:early_randomize_kstack_offset
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/aperfmperf.c:disable_freq_invariance_workfn
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
  - arch/x86/kernel/paravirt.c:native_pv_lock_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:setup_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:set_numabalancing_state
  - kernel/sched/build_utility.c:psi_init
  - kernel/sched/build_utility.c:__sched_clock_work
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timer_migration_handler
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/delayacct.c:sysctl_delayacct
  - kernel/delayacct.c:delayacct_init
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/trace/trace.c:late_trace_init
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_sched_delayed
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:init_mem_debugging_and_hardening
  - mm/page_alloc.c:init_mem_debugging_and_hardening
  - mm/slub.c:setup_slub_debug
  - lib/once.c:once_deferred
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/crc64-rocksoft.c:crc64_rocksoft_rehash
  - lib/dynamic_debug.c:ddebug_change
```
**Symbols:**

```
ffffffff812eb1a0-ffffffff812eb1cb: static_key_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void static_key_disable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81355210)
Location: kernel/jump_label.c:240
Inline: False
Direct callers:
  - init/main.c:early_randomize_kstack_offset
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/aperfmperf.c:disable_freq_invariance_workfn
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
  - arch/x86/kernel/paravirt.c:native_pv_lock_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:setup_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:set_numabalancing_state
  - kernel/sched/build_utility.c:psi_init
  - kernel/sched/build_utility.c:psi_init
  - kernel/sched/build_utility.c:__sched_clock_work
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timer_migration_handler
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/delayacct.c:sysctl_delayacct
  - kernel/delayacct.c:delayacct_init
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/trace/trace.c:late_trace_init
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_sched_delayed
  - mm/vmscan.c:store_enabled
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:init_mem_debugging_and_hardening
  - mm/page_alloc.c:init_mem_debugging_and_hardening
  - mm/slub.c:setup_slub_debug
  - lib/once.c:once_deferred
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/crc64-rocksoft.c:crc64_rocksoft_rehash
  - lib/dynamic_debug.c:ddebug_change
```
**Symbols:**

```
ffffffff81355210-ffffffff8135523b: static_key_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void static_key_disable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81386700)
Location: kernel/jump_label.c:240
Inline: False
Direct callers:
  - init/main.c:early_randomize_kstack_offset
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/aperfmperf.c:disable_freq_invariance_workfn
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
  - arch/x86/kernel/paravirt.c:native_pv_lock_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:setup_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:set_numabalancing_state
  - kernel/sched/build_utility.c:psi_init
  - kernel/sched/build_utility.c:psi_init
  - kernel/sched/build_utility.c:__sched_clock_work
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timer_migration_handler
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/delayacct.c:sysctl_delayacct
  - kernel/delayacct.c:delayacct_init
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/trace/trace.c:late_trace_init
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_sched_delayed
  - mm/vmscan.c:enabled_store
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:mm_core_init
  - mm/slub.c:setup_slub_debug
  - lib/once.c:once_deferred
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/crc64-rocksoft.c:crc64_rocksoft_rehash
  - lib/dynamic_debug.c:ddebug_change
```
**Symbols:**

```
ffffffff81386700-ffffffff8138672b: static_key_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void static_key_disable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff813afbc0)
Location: kernel/jump_label.c:240
Inline: False
Direct callers:
  - init/main.c:early_randomize_kstack_offset
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/aperfmperf.c:disable_freq_invariance_workfn
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
  - arch/x86/kernel/paravirt.c:native_pv_lock_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:setup_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:set_numabalancing_state
  - kernel/sched/build_utility.c:psi_init
  - kernel/sched/build_utility.c:psi_init
  - kernel/sched/build_utility.c:__sched_clock_work
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timer_migration_handler
  - kernel/cgroup/cgroup.c:cgroup_disable
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/delayacct.c:sysctl_delayacct
  - kernel/delayacct.c:delayacct_init
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/trace/trace.c:late_trace_init
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_sched_delayed
  - mm/vmscan.c:enabled_store
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:mm_core_init
  - mm/slub.c:setup_slub_debug
  - lib/once.c:once_deferred
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/crc64-rocksoft.c:crc64_rocksoft_rehash
  - lib/dynamic_debug.c:ddebug_change
```
**Symbols:**

```
ffffffff813afbc0-ffffffff813afbeb: static_key_disable (STB_GLOBAL)
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
void static_key_disable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffff8000102ab310)
Location: kernel/jump_label.c:212
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/time/timer.c:timers_update_migration
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_sched_delayed
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/shuffle.c:page_alloc_shuffle
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/irqchip/irq-gic.c:gic_v2_acpi_init
  - drivers/irqchip/irq-gic.c:gic_of_init
  - drivers/irqchip/irq-gic.c:gic_init
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - net/core/dev.c:netstamp_clear
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffff8000102ab310-ffff8000102ab344: static_key_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void static_key_disable(struct static_key *key);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (c035fcb4)
Location: include/linux/jump_label.h:315
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_static_key
```
```
In kernel/sched/core.c (c038ab7c)
Location: include/linux/jump_label.h:315
Inline: True
Inline callers:
  - kernel/sched/core.c:sysctl_schedstats
Direct callers:
  - kernel/sched/core.c:sched_init
```
```
In kernel/time/timer.c (c03e7b94)
Location: include/linux/jump_label.h:315
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_update_migration
```
```
In kernel/cgroup/cgroup.c (c0418920)
Location: include/linux/jump_label.h:315
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/trace/trace.c (c045e864)
Location: include/linux/jump_label.h:315
Inline: True
Inline callers:
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
```
```
In kernel/events/core.c (c04c4914)
Location: include/linux/jump_label.h:315
Inline: True
Inline callers:
  - kernel/events/core.c:perf_sched_delayed
```
```
In mm/page_alloc.c (c05351bc)
Location: include/linux/jump_label.h:315
Inline: True
Direct callers:
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
```
```
In mm/shuffle.c (c15be064)
Location: include/linux/jump_label.h:315
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In lib/once.c (c07dd370)
Location: include/linux/jump_label.h:315
Inline: True
```
```
In drivers/irqchip/irq-gic.c (c0815f14)
Location: include/linux/jump_label.h:315
Inline: True
Direct callers:
  - drivers/irqchip/irq-gic.c:gic_of_init
  - drivers/irqchip/irq-gic.c:gic_init
```
```
In drivers/irqchip/irq-gic-v3.c (c154b7a8)
Location: include/linux/jump_label.h:315
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
```
```
In lib/vsprintf.c (c0e95208)
Location: include/linux/jump_label.h:315
Inline: True
Direct callers:
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
c0815f14-c0815fc4: static_key_disable.constprop.0 (STB_LOCAL)
c0382e40-c0382efc: static_key_disable.constprop.0 (STB_LOCAL)
c04131f0-c04132a4: static_key_disable (STB_LOCAL)
c05351bc-c0535268: static_key_disable (STB_LOCAL)
c0e95208-c0e952c8: static_key_disable.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void static_key_disable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (c00000000035ef40)
Location: kernel/jump_label.c:212
Inline: False
Direct callers:
  - arch/powerpc/kernel/cputable.c:mmu_feature_keys_init
  - arch/powerpc/kernel/cputable.c:cpu_feature_keys_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/time/timer.c:timers_update_migration
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_sched_delayed
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/shuffle.c:page_alloc_shuffle
  - mm/memremap.c:devmap_managed_enable_put
  - lib/once.c:once_deferred
  - lib/dynamic_debug.c:ddebug_exec_query
  - net/core/dev.c:netstamp_clear
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
c00000000035ef40-c00000000035ef88: static_key_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void static_key_disable(struct static_key *key);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (ffffffe0000ca86e)
Location: include/linux/jump_label.h:315
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_static_key
```
```
In kernel/sched/core.c (ffffffe0000ea846)
Location: include/linux/jump_label.h:315
Inline: True
Inline callers:
  - kernel/sched/core.c:sysctl_schedstats
Direct callers:
  - kernel/sched/core.c:sched_init
```
```
In kernel/time/timer.c (ffffffe00012c2e6)
Location: include/linux/jump_label.h:315
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_update_migration
```
```
In kernel/cgroup/cgroup.c (ffffffe00014f03a)
Location: include/linux/jump_label.h:315
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:rebind_subsystems
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/trace/trace.c (ffffffe00017d55e)
Location: include/linux/jump_label.h:315
Inline: True
Inline callers:
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
```
```
In kernel/events/core.c (ffffffe0001c6556)
Location: include/linux/jump_label.h:315
Inline: True
Inline callers:
  - kernel/events/core.c:perf_sched_delayed
```
```
In mm/page_alloc.c (ffffffe0002202b2)
Location: include/linux/jump_label.h:315
Inline: True
Direct callers:
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
```
```
In mm/shuffle.c (ffffffe00004750c)
Location: include/linux/jump_label.h:315
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In lib/once.c (ffffffe000464974)
Location: include/linux/jump_label.h:315
Inline: True
```
```
In lib/vsprintf.c (ffffffe0008c16d8)
Location: include/linux/jump_label.h:315
Inline: True
Direct callers:
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffe0000e60ca-ffffffe0000e6134: static_key_disable.constprop.0 (STB_LOCAL)
ffffffe00014a068-ffffffe00014a0c8: static_key_disable (STB_LOCAL)
ffffffe0002202b2-ffffffe000220306: static_key_disable (STB_LOCAL)
ffffffe0008c16d8-ffffffe0008c1742: static_key_disable.constprop.0 (STB_LOCAL)
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
void static_key_disable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81217610)
Location: kernel/jump_label.c:212
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus
  - arch/x86/kernel/paravirt.c:native_pv_lock_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/time/timer.c:timers_update_migration
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_sched_delayed
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/shuffle.c:page_alloc_shuffle
  - mm/memremap.c:devmap_managed_enable_put
  - lib/dynamic_debug.c:ddebug_exec_query
  - net/core/dev.c:netstamp_clear
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffff81217610-ffffffff81217634: static_key_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void static_key_disable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8120a370)
Location: kernel/jump_label.c:212
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus
  - arch/x86/kernel/paravirt.c:native_pv_lock_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/time/timer.c:timers_update_migration
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_sched_delayed
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/shuffle.c:page_alloc_shuffle
  - mm/memremap.c:devmap_managed_enable_put
  - lib/dynamic_debug.c:ddebug_exec_query
  - net/core/dev.c:netstamp_clear
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffff8120a370-ffffffff8120a394: static_key_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void static_key_disable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812153b0)
Location: kernel/jump_label.c:212
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus
  - arch/x86/kernel/paravirt.c:native_pv_lock_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/time/timer.c:timers_update_migration
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_sched_delayed
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/shuffle.c:page_alloc_shuffle
  - mm/memremap.c:devmap_managed_enable_put
  - lib/dynamic_debug.c:ddebug_exec_query
  - net/core/dev.c:netstamp_clear
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffff812153b0-ffffffff812153d4: static_key_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void static_key_disable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812243a0)
Location: kernel/jump_label.c:212
Inline: False
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus
  - arch/x86/kernel/paravirt.c:native_pv_lock_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/clock.c:__sched_clock_work
  - kernel/time/timer.c:timers_update_migration
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:unregister_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_sched_delayed
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/shuffle.c:page_alloc_shuffle
  - mm/memremap.c:devmap_managed_enable_put
  - lib/dynamic_debug.c:ddebug_exec_query
  - net/core/dev.c:netstamp_clear
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffff812243a0-ffffffff812243c4: static_key_disable (STB_GLOBAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
