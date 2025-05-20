# Function: <code>static_key_enable</code>

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
In arch/x86/kernel/tsc.c (ffffffff81f6910e)
Location: include/linux/jump_label.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In kernel/sched/core.c (ffffffff810a6ac7)
Location: include/linux/jump_label.h:217
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_feat_write
  - kernel/sched/core.c:sysctl_numa_balancing
```
```
In kernel/cgroup.c (ffffffff81114341)
Location: include/linux/jump_label.h:217
Inline: True
Inline callers:
  - kernel/cgroup.c:rebind_subsystems
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void static_key_enable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8119d5c0)
Location: kernel/jump_label.c:81
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - arch/x86/kernel/tsc.c:tsc_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:force_schedstat_enabled
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup.c:rebind_subsystems
  - kernel/events/core.c:perf_event_alloc
  - lib/dynamic_debug.c:ddebug_exec_query
```
**Symbols:**

```
ffffffff8119d5c0-ffffffff8119d604: static_key_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void static_key_enable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811acfe0)
Location: kernel/jump_label.c:81
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:force_schedstat_enabled
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_event_alloc
  - lib/dynamic_debug.c:ddebug_exec_query
  - net/core/dev.c:netstamp_clear
```
**Symbols:**

```
ffffffff811acfe0-ffffffff811ad024: static_key_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void static_key_enable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811b4490)
Location: kernel/jump_label.c:82
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:force_schedstat_enabled
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/clock.c:sched_clock_init_late
  - kernel/sched/debug.c:sched_feat_write
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - lib/dynamic_debug.c:ddebug_exec_query
  - net/core/dev.c:netstamp_clear
```
**Symbols:**

```
ffffffff811b4490-ffffffff811b44b4: static_key_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void static_key_enable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811c8210)
Location: kernel/jump_label.c:151
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:force_schedstat_enabled
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/clock.c:sched_clock_init_late
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/isolation.c:housekeeping_init
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/hmm.c:hmm_devmem_add
  - lib/dynamic_debug.c:ddebug_exec_query
  - net/core/dev.c:netstamp_clear
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv6/udp.c:udpv6_encap_enable
```
**Symbols:**

```
ffffffff811c8210-ffffffff811c8232: static_key_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void static_key_enable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811e8610)
Location: kernel/jump_label.c:152
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:force_schedstat_enabled
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/clock.c:sched_clock_init_late
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/isolation.c:housekeeping_init
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timers_update_migration
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_event_alloc
  - kernel/memremap.c:dev_pagemap_get_ops
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - lib/dynamic_debug.c:ddebug_exec_query
  - net/core/dev.c:netstamp_clear
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv6/udp.c:udpv6_encap_enable
```
**Symbols:**

```
ffffffff811e8610-ffffffff811e8632: static_key_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void static_key_enable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811f92d0)
Location: kernel/jump_label.c:172
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:force_schedstat_enabled
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/clock.c:sched_clock_init_late
  - kernel/sched/isolation.c:housekeeping_init
  - kernel/sched/psi.c:psi_init
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timers_update_migration
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_event_alloc
  - kernel/memremap.c:dev_pagemap_get_ops
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/usercopy.c:set_hardened_usercopy
  - lib/dynamic_debug.c:ddebug_exec_query
  - net/core/dev.c:netstamp_clear
```
**Symbols:**

```
ffffffff811f92d0-ffffffff811f92f2: static_key_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void static_key_enable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81211250)
Location: kernel/jump_label.c:187
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:force_schedstat_enabled
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/clock.c:sched_clock_init_late
  - kernel/sched/isolation.c:housekeeping_init
  - kernel/sched/psi.c:psi_init
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timers_update_migration
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_event_alloc
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/shuffle.c:page_alloc_shuffle
  - mm/usercopy.c:set_hardened_usercopy
  - mm/memremap.c:devm_memremap_pages
  - lib/dynamic_debug.c:ddebug_exec_query
  - net/core/dev.c:netstamp_clear
```
**Symbols:**

```
ffffffff81211250-ffffffff81211274: static_key_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void static_key_enable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8121ef00)
Location: kernel/jump_label.c:187
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:force_schedstat_enabled
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/clock.c:sched_clock_init_late
  - kernel/sched/isolation.c:housekeeping_init
  - kernel/sched/psi.c:psi_init
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timers_update_migration
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_event_alloc
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/shuffle.c:page_alloc_shuffle
  - mm/usercopy.c:set_hardened_usercopy
  - mm/memremap.c:memremap_pages
  - lib/dynamic_debug.c:ddebug_exec_query
  - net/core/dev.c:netstamp_clear
```
**Symbols:**

```
ffffffff8121ef00-ffffffff8121ef24: static_key_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void static_key_enable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8124ad50)
Location: kernel/jump_label.c:187
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:force_schedstat_enabled
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/clock.c:sched_clock_init_late
  - kernel/sched/isolation.c:housekeeping_init
  - kernel/sched/psi.c:psi_init
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timer_update_keys
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:account_event
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/shuffle.c:page_alloc_shuffle
  - mm/usercopy.c:set_hardened_usercopy
  - mm/memremap.c:memremap_pages
  - mm/page_reporting.c:page_reporting_register
  - lib/dynamic_debug.c:ddebug_change
  - net/core/dev.c:netstamp_clear
```
**Symbols:**

```
ffffffff8124ad50-ffffffff8124ad76: static_key_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void static_key_enable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81255140)
Location: kernel/jump_label.c:187
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/sev-es.c:sev_es_init_vc_handling
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:force_schedstat_enabled
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/clock.c:sched_clock_init_late
  - kernel/sched/isolation.c:housekeeping_init
  - kernel/sched/psi.c:psi_init
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timer_update_keys
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:account_event
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:init_mem_debugging_and_hardening
  - mm/page_alloc.c:init_mem_debugging_and_hardening
  - mm/page_alloc.c:init_mem_debugging_and_hardening
  - mm/shuffle.c:shuffle_store
  - mm/slub.c:setup_slub_debug
  - mm/memcontrol.c:memcg_online_kmem
  - mm/usercopy.c:set_hardened_usercopy
  - mm/page_reporting.c:page_reporting_register
  - lib/dynamic_debug.c:ddebug_change
  - net/core/dev.c:netstamp_clear
```
**Symbols:**

```
ffffffff81255140-ffffffff81255166: static_key_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void static_key_enable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81259640)
Location: kernel/jump_label.c:187
Inline: False
Direct callers:
  - init/main.c:early_randomize_kstack_offset
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:force_schedstat_enabled
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/clock.c:sched_clock_init_late
  - kernel/sched/isolation.c:housekeeping_init
  - kernel/sched/psi.c:psi_init
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timer_update_keys
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:account_event
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/page_alloc.c:init_mem_debugging_and_hardening
  - mm/page_alloc.c:init_mem_debugging_and_hardening
  - mm/page_alloc.c:init_mem_debugging_and_hardening
  - mm/shuffle.c:shuffle_store
  - mm/slub.c:setup_slub_debug
  - mm/memcontrol.c:memcg_online_kmem
  - mm/usercopy.c:set_hardened_usercopy
  - mm/page_reporting.c:page_reporting_register
  - lib/dynamic_debug.c:ddebug_change
  - drivers/iommu/dma-iommu.c:iommu_dma_init
  - net/core/dev.c:netstamp_clear
```
**Symbols:**

```
ffffffff81259640-ffffffff81259666: static_key_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void static_key_enable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81295300)
Location: kernel/jump_label.c:187
Inline: False
Direct callers:
  - init/main.c:early_randomize_kstack_offset
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:setup_schedstats
  - kernel/sched/core.c:force_schedstat_enabled
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sched_core_get
  - kernel/sched/clock.c:sched_clock_init_late
  - kernel/sched/isolation.c:housekeeping_init
  - kernel/sched/psi.c:psi_init
  - kernel/irq/manage.c:setup_forced_irqthreads
  - kernel/time/timer.c:timer_migration_handler
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timer_update_keys
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/delayacct.c:sysctl_delayacct
  - kernel/delayacct.c:delayacct_init
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:account_event
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/page_alloc.c:init_mem_debugging_and_hardening
  - mm/page_alloc.c:init_mem_debugging_and_hardening
  - mm/page_alloc.c:init_mem_debugging_and_hardening
  - mm/shuffle.c:shuffle_store
  - mm/slub.c:setup_slub_debug
  - mm/kfence/core.c:kfence_init
  - mm/memcontrol.c:memcg_online_kmem
  - mm/usercopy.c:set_hardened_usercopy
  - mm/page_reporting.c:page_reporting_register
  - lib/dynamic_debug.c:ddebug_change
  - drivers/iommu/dma-iommu.c:iommu_dma_init
  - net/core/dev.c:netstamp_clear
  - net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler
```
**Symbols:**

```
ffffffff81295300-ffffffff81295326: static_key_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void static_key_enable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812eb0c0)
Location: kernel/jump_label.c:187
Inline: False
Direct callers:
  - init/main.c:early_randomize_kstack_offset
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/fpu/xstate.c:xfd_update_static_branch
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/aperfmperf.c:freq_invariance_enable
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/crypto/blake2s-glue.c:blake2s_mod_init
  - arch/x86/crypto/blake2s-glue.c:blake2s_mod_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:setup_schedstats
  - kernel/sched/core.c:force_schedstat_enabled
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:set_numabalancing_state
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sched_core_get
  - kernel/sched/build_utility.c:psi_init
  - kernel/sched/build_utility.c:__set_sched_clock_stable
  - kernel/sched/build_utility.c:housekeeping_init
  - kernel/irq/manage.c:setup_forced_irqthreads
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timer_migration_handler
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/delayacct.c:sysctl_delayacct
  - kernel/delayacct.c:delayacct_init
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/fgraph.c:ftrace_return_to_handler
  - kernel/trace/fgraph.c:ftrace_return_to_handler
  - kernel/events/core.c:account_event
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/page_alloc.c:init_mem_debugging_and_hardening
  - mm/page_alloc.c:init_mem_debugging_and_hardening
  - mm/page_alloc.c:init_mem_debugging_and_hardening
  - mm/shuffle.c:shuffle_store
  - mm/slub.c:setup_slub_debug
  - mm/kfence/core.c:kfence_init_enable
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/usercopy.c:set_hardened_usercopy
  - mm/page_reporting.c:page_reporting_register
  - crypto/algapi.c:crypto_algapi_init
  - lib/dynamic_debug.c:ddebug_change
  - lib/vsprintf.c:enable_ptr_key_workfn
  - drivers/char/random.c:random_init
  - drivers/iommu/dma-iommu.c:iommu_dma_init
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_add_target
  - net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler
```
**Symbols:**

```
ffffffff812eb0c0-ffffffff812eb0eb: static_key_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void static_key_enable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81355110)
Location: kernel/jump_label.c:215
Inline: False
Direct callers:
  - init/main.c:early_randomize_kstack_offset
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/fpu/xstate.c:xfd_update_static_branch
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/aperfmperf.c:freq_invariance_enable
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/crypto/blake2s-glue.c:blake2s_mod_init
  - arch/x86/crypto/blake2s-glue.c:blake2s_mod_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:setup_schedstats
  - kernel/sched/core.c:force_schedstat_enabled
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:set_numabalancing_state
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sched_core_get
  - kernel/sched/build_utility.c:psi_init
  - kernel/sched/build_utility.c:__set_sched_clock_stable
  - kernel/sched/build_utility.c:housekeeping_init
  - kernel/irq/manage.c:setup_forced_irqthreads
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timer_migration_handler
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/delayacct.c:sysctl_delayacct
  - kernel/delayacct.c:delayacct_init
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/fgraph.c:ftrace_return_to_handler
  - kernel/trace/fgraph.c:ftrace_return_to_handler
  - kernel/events/core.c:account_event
  - mm/vmscan.c:store_enabled
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/page_alloc.c:init_mem_debugging_and_hardening
  - mm/page_alloc.c:init_mem_debugging_and_hardening
  - mm/page_alloc.c:init_mem_debugging_and_hardening
  - mm/shuffle.c:shuffle_param_set
  - mm/slub.c:setup_slub_debug
  - mm/kfence/core.c:kfence_init_enable
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/usercopy.c:set_hardened_usercopy
  - mm/page_reporting.c:page_reporting_register
  - lib/dynamic_debug.c:ddebug_change
  - drivers/char/random.c:random_init
  - drivers/iommu/dma-iommu.c:iommu_dma_init
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_add_target
  - net/sched/sch_api.c:pktsched_init
  - net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
**Symbols:**

```
ffffffff81355110-ffffffff8135513b: static_key_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void static_key_enable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81386600)
Location: kernel/jump_label.c:215
Inline: False
Direct callers:
  - init/main.c:early_randomize_kstack_offset
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/fpu/xstate.c:xfd_update_static_branch
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/crypto/blake2s-glue.c:blake2s_mod_init
  - arch/x86/crypto/blake2s-glue.c:blake2s_mod_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:setup_schedstats
  - kernel/sched/core.c:force_schedstat_enabled
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:set_numabalancing_state
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sched_core_get
  - kernel/sched/build_utility.c:psi_init
  - kernel/sched/build_utility.c:__set_sched_clock_stable
  - kernel/sched/build_utility.c:housekeeping_init
  - kernel/irq/manage.c:setup_forced_irqthreads
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timer_migration_handler
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/delayacct.c:sysctl_delayacct
  - kernel/delayacct.c:delayacct_init
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/fgraph.c:ftrace_return_to_handler
  - kernel/trace/fgraph.c:ftrace_return_to_handler
  - kernel/events/core.c:account_event
  - mm/vmscan.c:enabled_store
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:mm_core_init
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/shuffle.c:shuffle_param_set
  - mm/slub.c:setup_slub_debug
  - mm/kfence/core.c:kfence_init_enable
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/usercopy.c:set_hardened_usercopy
  - mm/page_reporting.c:page_reporting_register
  - lib/dynamic_debug.c:ddebug_change
  - drivers/char/random.c:random_init
  - drivers/iommu/dma-iommu.c:iommu_dma_init
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_add_target
  - net/sched/sch_api.c:pktsched_init
  - net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
**Symbols:**

```
ffffffff81386600-ffffffff8138662b: static_key_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void static_key_enable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff813afac0)
Location: kernel/jump_label.c:215
Inline: False
Direct callers:
  - init/main.c:early_randomize_kstack_offset
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/fpu/xstate.c:xfd_update_static_branch
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/crypto/blake2s-glue.c:blake2s_mod_init
  - arch/x86/crypto/blake2s-glue.c:blake2s_mod_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:setup_schedstats
  - kernel/sched/core.c:force_schedstat_enabled
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:set_numabalancing_state
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sched_core_get
  - kernel/sched/build_utility.c:psi_init
  - kernel/sched/build_utility.c:__set_sched_clock_stable
  - kernel/sched/build_utility.c:housekeeping_init
  - kernel/irq/manage.c:setup_forced_irqthreads
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timer_migration_handler
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/delayacct.c:sysctl_delayacct
  - kernel/delayacct.c:delayacct_init
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/fgraph.c:ftrace_return_to_handler
  - kernel/trace/fgraph.c:ftrace_return_to_handler
  - kernel/events/core.c:account_event
  - mm/vmscan.c:enabled_store
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:mm_core_init
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/shuffle.c:shuffle_param_set
  - mm/slub.c:setup_slub_debug
  - mm/kfence/core.c:kfence_init_enable
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/usercopy.c:set_hardened_usercopy
  - mm/page_reporting.c:page_reporting_register
  - lib/dynamic_debug.c:ddebug_change
  - drivers/char/random.c:random_init
  - drivers/iommu/dma-iommu.c:iommu_dma_init
  - drivers/gpu/drm/drm_cache.c:drm_memcpy_init_early
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_add_target
  - net/sched/sch_api.c:pktsched_init
  - net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
**Symbols:**

```
ffffffff813afac0-ffffffff813afaeb: static_key_enable (STB_GLOBAL)
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
void static_key_enable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffff8000102ab0d0)
Location: kernel/jump_label.c:187
Inline: False
Direct callers:
  - arch/arm64/kernel/cpufeature.c:enable_cpu_capabilities
  - arch/arm64/kernel/cpufeature.c:setup_cpu_features
  - virt/kvm/arm/vgic/vgic-init.c:kvm_vgic_hyp_init
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_probe
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_probe
  - virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:force_schedstat_enabled
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/isolation.c:housekeeping_init
  - kernel/sched/psi.c:psi_init
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timers_update_migration
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_event_alloc
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/shuffle.c:page_alloc_shuffle
  - mm/usercopy.c:set_hardened_usercopy
  - lib/dynamic_debug.c:ddebug_exec_query
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_probe
  - net/core/dev.c:netstamp_clear
```
**Symbols:**

```
ffff8000102ab0d0-ffff8000102ab104: static_key_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void static_key_enable(struct static_key *key);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (c035fc14)
Location: include/linux/jump_label.h:304
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_static_key
```
```
In kernel/sched/core.c (c038aae8)
Location: include/linux/jump_label.h:304
Inline: True
Inline callers:
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:force_schedstat_enabled
```
```
In kernel/sched/isolation.c (c151f838)
Location: include/linux/jump_label.h:304
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_init
```
```
In kernel/sched/psi.c (c151f9e4)
Location: include/linux/jump_label.h:304
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_init
```
```
In kernel/time/timer.c (c03e7cf4)
Location: include/linux/jump_label.h:304
Inline: True
Inline callers:
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timers_update_migration
  - kernel/time/timer.c:timers_update_migration
```
```
In kernel/cgroup/cgroup.c (c04189e8)
Location: include/linux/jump_label.h:304
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/trace/trace.c (c0460080)
Location: include/linux/jump_label.h:304
Inline: True
Inline callers:
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
Direct callers:
  - kernel/trace/trace.c:early_trace_init
```
```
In kernel/events/core.c (c04c707c)
Location: include/linux/jump_label.h:304
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
```
```
In mm/page_alloc.c (c0535110)
Location: include/linux/jump_label.h:304
Inline: True
Direct callers:
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
```
```
In mm/shuffle.c (c15be118)
Location: include/linux/jump_label.h:304
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/usercopy.c (c1535588)
Location: include/linux/jump_label.h:304
Inline: True
Inline callers:
  - mm/usercopy.c:set_hardened_usercopy
```
```
In drivers/irqchip/irq-gic-v3.c (0)
Location: include/linux/jump_label.h:304
Inline: False
```
```
In net/ipv4/tcp.c (c0d8100c)
Location: include/linux/jump_label.h:304
Inline: True
```
**Symbols:**

```
c0382efc-c0382fb8: static_key_enable.constprop.0 (STB_LOCAL)
c045de7c-c045df30: static_key_enable (STB_LOCAL)
c0535110-c05351bc: static_key_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void static_key_enable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (c00000000035ecf0)
Location: kernel/jump_label.c:187
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/setup.c:pSeries_setup_arch
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:force_schedstat_enabled
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/isolation.c:housekeeping_init
  - kernel/sched/psi.c:psi_init
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timers_update_migration
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/shuffle.c:page_alloc_shuffle
  - mm/usercopy.c:set_hardened_usercopy
  - mm/memremap.c:memremap_pages
  - lib/dynamic_debug.c:ddebug_exec_query
  - net/core/dev.c:netstamp_clear
```
**Symbols:**

```
c00000000035ecf0-c00000000035ed38: static_key_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void static_key_enable(struct static_key *key);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (ffffffe0000ca7d2)
Location: include/linux/jump_label.h:304
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_static_key
```
```
In kernel/sched/core.c (ffffffe0000ea7ca)
Location: include/linux/jump_label.h:304
Inline: True
Inline callers:
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:force_schedstat_enabled
```
```
In kernel/sched/isolation.c (ffffffe000007456)
Location: include/linux/jump_label.h:304
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_init
```
```
In kernel/sched/psi.c (ffffffe00000758e)
Location: include/linux/jump_label.h:304
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_init
```
```
In kernel/time/timer.c (ffffffe00012c3b4)
Location: include/linux/jump_label.h:304
Inline: True
Inline callers:
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timers_update_migration
  - kernel/time/timer.c:timers_update_migration
```
```
In kernel/cgroup/cgroup.c (ffffffe00014f0e8)
Location: include/linux/jump_label.h:304
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/trace/trace.c (ffffffe00017e7f4)
Location: include/linux/jump_label.h:304
Inline: True
Inline callers:
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/trace/trace.c:tracepoint_printk_sysctl
Direct callers:
  - kernel/trace/trace.c:early_trace_init
```
```
In kernel/events/core.c (ffffffe0001ca5e6)
Location: include/linux/jump_label.h:304
Inline: True
```
```
In mm/page_alloc.c (ffffffe00022025e)
Location: include/linux/jump_label.h:304
Inline: True
Direct callers:
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
```
```
In mm/shuffle.c (ffffffe00004756a)
Location: include/linux/jump_label.h:304
Inline: True
Inline callers:
  - mm/shuffle.c:page_alloc_shuffle
```
```
In mm/usercopy.c (ffffffe00001a0e4)
Location: include/linux/jump_label.h:304
Inline: True
Inline callers:
  - mm/usercopy.c:set_hardened_usercopy
```
```
In net/ipv4/tcp.c (ffffffe0007d73bc)
Location: include/linux/jump_label.h:304
Inline: True
```
**Symbols:**

```
ffffffe0000e6134-ffffffe0000e6196: static_key_enable.constprop.0 (STB_LOCAL)
ffffffe00017cba6-ffffffe00017cbfc: static_key_enable (STB_LOCAL)
ffffffe00022025e-ffffffe0002202b2: static_key_enable (STB_LOCAL)
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
void static_key_enable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81217550)
Location: kernel/jump_label.c:187
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:force_schedstat_enabled
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/clock.c:sched_clock_init_late
  - kernel/sched/isolation.c:housekeeping_init
  - kernel/sched/psi.c:psi_init
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timers_update_migration
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_event_alloc
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/shuffle.c:page_alloc_shuffle
  - mm/usercopy.c:set_hardened_usercopy
  - mm/memremap.c:memremap_pages
  - lib/dynamic_debug.c:ddebug_exec_query
  - net/core/dev.c:netstamp_clear
```
**Symbols:**

```
ffffffff81217550-ffffffff81217574: static_key_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void static_key_enable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8120a2b0)
Location: kernel/jump_label.c:187
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:force_schedstat_enabled
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/clock.c:sched_clock_init_late
  - kernel/sched/isolation.c:housekeeping_init
  - kernel/sched/psi.c:psi_init
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timers_update_migration
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_event_alloc
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/shuffle.c:page_alloc_shuffle
  - mm/usercopy.c:set_hardened_usercopy
  - mm/memremap.c:memremap_pages
  - lib/dynamic_debug.c:ddebug_exec_query
  - net/core/dev.c:netstamp_clear
```
**Symbols:**

```
ffffffff8120a2b0-ffffffff8120a2d4: static_key_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void static_key_enable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812152f0)
Location: kernel/jump_label.c:187
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:force_schedstat_enabled
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/clock.c:sched_clock_init_late
  - kernel/sched/isolation.c:housekeeping_init
  - kernel/sched/psi.c:psi_init
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timers_update_migration
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_event_alloc
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/shuffle.c:page_alloc_shuffle
  - mm/usercopy.c:set_hardened_usercopy
  - mm/memremap.c:memremap_pages
  - lib/dynamic_debug.c:ddebug_exec_query
  - net/core/dev.c:netstamp_clear
```
**Symbols:**

```
ffffffff812152f0-ffffffff81215314: static_key_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void static_key_enable(struct static_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812242e0)
Location: kernel/jump_label.c:187
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:force_schedstat_enabled
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/clock.c:sched_clock_init_late
  - kernel/sched/isolation.c:housekeeping_init
  - kernel/sched/psi.c:psi_init
  - kernel/time/timer.c:timer_update_keys
  - kernel/time/timer.c:timers_update_migration
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:register_ftrace_export
  - kernel/trace/trace.c:tracepoint_printk_sysctl
  - kernel/events/core.c:perf_event_alloc
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/shuffle.c:page_alloc_shuffle
  - mm/usercopy.c:set_hardened_usercopy
  - mm/memremap.c:memremap_pages
  - lib/dynamic_debug.c:ddebug_exec_query
  - net/core/dev.c:netstamp_clear
```
**Symbols:**

```
ffffffff812242e0-ffffffff81224304: static_key_enable (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
