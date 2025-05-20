# Function: <code>proc_dointvec_minmax</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81088ca0)
Location: kernel/sysctl.c:2288
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
Direct callers:
  - kernel/fork.c:sysctl_max_threads
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/events/core.c:perf_proc_update_handler
  - mm/page_alloc.c:min_free_kbytes_sysctl_handler
  - mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler
  - mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page-writeback.c:dirty_background_ratio_handler
  - mm/page-writeback.c:dirty_ratio_handler
  - mm/compaction.c:sysctl_extfrag_handler
  - fs/pipe.c:pipe_proc_fn
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - ipc/ipc_sysctl.c:proc_ipc_auto_msgmni
  - ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax
  - ipc/mq_sysctl.c:proc_mq_dointvec_minmax
  - security/yama/yama_lsm.c:yama_dointvec_minmax
  - net/core/neighbour.c:neigh_proc_dointvec_unres_qlen
  - net/core/neighbour.c:neigh_proc_dointvec_zero_intmax
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv6/addrconf.c:addrconf_sysctl_mtu
```
**Symbols:**

```
ffffffff81088ca0-ffffffff81088d0d: proc_dointvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8108b869)
Location: kernel/sysctl.c:2434
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
Direct callers:
  - kernel/fork.c:sysctl_max_threads
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/callchain.c:perf_event_max_stack_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler
  - mm/page_alloc.c:watermark_scale_factor_sysctl_handler
  - mm/page_alloc.c:min_free_kbytes_sysctl_handler
  - mm/page-writeback.c:dirty_ratio_handler
  - mm/page-writeback.c:dirty_background_ratio_handler
  - mm/compaction.c:sysctl_extfrag_handler
  - fs/pipe.c:pipe_proc_fn
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - ipc/ipc_sysctl.c:proc_ipc_auto_msgmni
  - ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax
  - ipc/mq_sysctl.c:proc_mq_dointvec_minmax
  - security/yama/yama_lsm.c:yama_dointvec_minmax
  - net/core/neighbour.c:neigh_proc_dointvec_unres_qlen
  - net/core/neighbour.c:neigh_proc_dointvec_zero_intmax
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/ipv6/addrconf.c:addrconf_sysctl_mtu
  - net/ipv6/addrconf.c:addrconf_sysctl_hop_limit
```
**Symbols:**

```
ffffffff8108b720-ffffffff8108b78d: proc_dointvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810907b9)
Location: kernel/sysctl.c:2419
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
Direct callers:
  - arch/x86/kernel/itmt.c:sched_itmt_update_handler
  - kernel/fork.c:sysctl_max_threads
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/callchain.c:perf_event_max_stack_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler
  - mm/page_alloc.c:watermark_scale_factor_sysctl_handler
  - mm/page_alloc.c:min_free_kbytes_sysctl_handler
  - mm/page-writeback.c:dirty_ratio_handler
  - mm/page-writeback.c:dirty_background_ratio_handler
  - mm/compaction.c:sysctl_extfrag_handler
  - fs/pipe.c:pipe_proc_fn
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - ipc/ipc_sysctl.c:proc_ipc_auto_msgmni
  - ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax
  - ipc/mq_sysctl.c:proc_mq_dointvec_minmax
  - security/yama/yama_lsm.c:yama_dointvec_minmax
  - net/core/neighbour.c:neigh_proc_dointvec_unres_qlen
  - net/core/neighbour.c:neigh_proc_dointvec_zero_intmax
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/ipv6/addrconf.c:addrconf_sysctl_mtu
```
**Symbols:**

```
ffffffff81090670-ffffffff810906dd: proc_dointvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8108df09)
Location: kernel/sysctl.c:2576
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
Direct callers:
  - arch/x86/kernel/itmt.c:sched_itmt_update_handler
  - kernel/fork.c:sysctl_max_threads
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/time/timer.c:timer_migration_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/callchain.c:perf_event_max_stack_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler
  - mm/page_alloc.c:watermark_scale_factor_sysctl_handler
  - mm/page_alloc.c:min_free_kbytes_sysctl_handler
  - mm/page-writeback.c:dirty_ratio_handler
  - mm/page-writeback.c:dirty_background_ratio_handler
  - mm/compaction.c:sysctl_extfrag_handler
  - fs/pipe.c:pipe_proc_fn
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - ipc/ipc_sysctl.c:proc_ipc_auto_msgmni
  - ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax
  - ipc/mq_sysctl.c:proc_mq_dointvec_minmax
  - security/yama/yama_lsm.c:yama_dointvec_minmax
  - net/core/neighbour.c:neigh_proc_dointvec_unres_qlen
  - net/core/neighbour.c:neigh_proc_dointvec_zero_intmax
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/ipv6/addrconf.c:addrconf_sysctl_mtu
```
**Symbols:**

```
ffffffff8108ddc0-ffffffff8108de27: proc_dointvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81094889)
Location: kernel/sysctl.c:2566
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
Direct callers:
  - arch/x86/kernel/itmt.c:sched_itmt_update_handler
  - kernel/fork.c:sysctl_max_threads
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/time/timer.c:timer_migration_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/callchain.c:perf_event_max_stack_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler
  - mm/page_alloc.c:watermark_scale_factor_sysctl_handler
  - mm/page_alloc.c:min_free_kbytes_sysctl_handler
  - mm/page-writeback.c:dirty_ratio_handler
  - mm/page-writeback.c:dirty_background_ratio_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/compaction.c:sysctl_extfrag_handler
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - ipc/ipc_sysctl.c:proc_ipc_auto_msgmni
  - ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax
  - ipc/mq_sysctl.c:proc_mq_dointvec_minmax
  - security/yama/yama_lsm.c:yama_dointvec_minmax
  - net/core/neighbour.c:neigh_proc_dointvec_unres_qlen
  - net/core/neighbour.c:neigh_proc_dointvec_zero_intmax
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/ipv6/addrconf.c:addrconf_sysctl_mtu
```
**Symbols:**

```
ffffffff81094740-ffffffff810947a7: proc_dointvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810981d6)
Location: kernel/sysctl.c:2580
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
Direct callers:
  - arch/x86/kernel/itmt.c:sched_itmt_update_handler
  - kernel/fork.c:sysctl_max_threads
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/time/timer.c:timer_migration_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/callchain.c:perf_event_max_stack_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler
  - mm/page_alloc.c:watermark_scale_factor_sysctl_handler
  - mm/page_alloc.c:min_free_kbytes_sysctl_handler
  - mm/page-writeback.c:dirty_ratio_handler
  - mm/page-writeback.c:dirty_background_ratio_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/compaction.c:sysctl_extfrag_handler
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - ipc/ipc_sysctl.c:proc_ipc_auto_msgmni
  - ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax
  - ipc/mq_sysctl.c:proc_mq_dointvec_minmax
  - security/yama/yama_lsm.c:yama_dointvec_minmax
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/neighbour.c:neigh_proc_dointvec_unres_qlen
  - net/core/neighbour.c:neigh_proc_dointvec_zero_intmax
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/ipv6/addrconf.c:addrconf_sysctl_mtu
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffff81098010-ffffffff81098077: proc_dointvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a04f6)
Location: kernel/sysctl.c:2637
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
Direct callers:
  - arch/x86/kernel/itmt.c:sched_itmt_update_handler
  - kernel/fork.c:sysctl_max_threads
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/time/timer.c:timer_migration_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/callchain.c:perf_event_max_stack_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler
  - mm/page_alloc.c:watermark_scale_factor_sysctl_handler
  - mm/page_alloc.c:watermark_boost_factor_sysctl_handler
  - mm/page_alloc.c:min_free_kbytes_sysctl_handler
  - mm/page-writeback.c:dirty_ratio_handler
  - mm/page-writeback.c:dirty_background_ratio_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/compaction.c:sysctl_extfrag_handler
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - ipc/ipc_sysctl.c:proc_ipc_auto_msgmni
  - ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax
  - ipc/mq_sysctl.c:proc_mq_dointvec_minmax
  - security/yama/yama_lsm.c:yama_dointvec_minmax
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/neighbour.c:neigh_proc_dointvec_unres_qlen
  - net/core/neighbour.c:neigh_proc_dointvec_zero_intmax
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/ipv6/addrconf.c:addrconf_sysctl_mtu
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffff810a0320-ffffffff810a0387: proc_dointvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a4ea3)
Location: kernel/sysctl.c:2716
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
Direct callers:
  - arch/x86/kernel/itmt.c:sched_itmt_update_handler
  - kernel/fork.c:sysctl_max_threads
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/time/timer.c:timer_migration_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/callchain.c:perf_event_max_stack_handler
  - mm/page-writeback.c:dirty_ratio_handler
  - mm/page-writeback.c:dirty_background_ratio_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler
  - mm/page_alloc.c:watermark_scale_factor_sysctl_handler
  - mm/page_alloc.c:watermark_boost_factor_sysctl_handler
  - mm/page_alloc.c:min_free_kbytes_sysctl_handler
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - ipc/ipc_sysctl.c:proc_ipc_auto_msgmni
  - ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax
  - ipc/mq_sysctl.c:proc_mq_dointvec_minmax
  - security/yama/yama_lsm.c:yama_dointvec_minmax
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/neighbour.c:neigh_proc_dointvec_unres_qlen
  - net/core/neighbour.c:neigh_proc_dointvec_zero_intmax
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/ipv6/addrconf.c:addrconf_sysctl_mtu
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffff810a4a60-ffffffff810a4acc: proc_dointvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810ab483)
Location: kernel/sysctl.c:2718
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
Direct callers:
  - arch/x86/kernel/itmt.c:sched_itmt_update_handler
  - kernel/fork.c:sysctl_max_threads
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/time/timer.c:timer_migration_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/callchain.c:perf_event_max_stack_handler
  - mm/page-writeback.c:dirty_ratio_handler
  - mm/page-writeback.c:dirty_background_ratio_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler
  - mm/page_alloc.c:watermark_scale_factor_sysctl_handler
  - mm/page_alloc.c:watermark_boost_factor_sysctl_handler
  - mm/page_alloc.c:min_free_kbytes_sysctl_handler
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - ipc/ipc_sysctl.c:proc_ipc_auto_msgmni
  - ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax
  - ipc/mq_sysctl.c:proc_mq_dointvec_minmax
  - security/yama/yama_lsm.c:yama_dointvec_minmax
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/neighbour.c:neigh_proc_dointvec_unres_qlen
  - net/core/neighbour.c:neigh_proc_dointvec_zero_intmax
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/ipv6/addrconf.c:addrconf_sysctl_mtu
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffff810ab040-ffffffff810ab0ac: proc_dointvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810b3b73)
Location: kernel/sysctl.c:959
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
  - kernel/sysctl.c:proc_dointvec_minmax_warn_RT_change
  - kernel/sysctl.c:bpf_stats_handler
Direct callers:
  - arch/x86/kernel/itmt.c:sched_itmt_update_handler
  - kernel/fork.c:sysctl_max_threads
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/sched/topology.c:sched_energy_aware_handler
  - kernel/sched/topology.c:sched_energy_aware_handler
  - kernel/time/timer.c:timer_migration_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/callchain.c:perf_event_max_stack_handler
  - mm/page-writeback.c:dirty_ratio_handler
  - mm/page-writeback.c:dirty_background_ratio_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler
  - mm/page_alloc.c:watermark_scale_factor_sysctl_handler
  - mm/page_alloc.c:min_free_kbytes_sysctl_handler
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - ipc/ipc_sysctl.c:proc_ipc_auto_msgmni
  - ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax
  - ipc/mq_sysctl.c:proc_mq_dointvec_minmax
  - security/yama/yama_lsm.c:yama_dointvec_minmax
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/neighbour.c:neigh_proc_dointvec_unres_qlen
  - net/core/neighbour.c:neigh_proc_dointvec_zero_intmax
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/ipv6/addrconf.c:addrconf_sysctl_mtu
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffff810b34d0-ffffffff810b353a: proc_dointvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810af3a3)
Location: kernel/sysctl.c:958
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
  - kernel/sysctl.c:proc_dointvec_minmax_warn_RT_change
  - kernel/sysctl.c:bpf_stats_handler
Direct callers:
  - arch/x86/kernel/itmt.c:sched_itmt_update_handler
  - kernel/fork.c:sysctl_max_threads
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/sched/topology.c:sched_energy_aware_handler
  - kernel/sched/topology.c:sched_energy_aware_handler
  - kernel/time/timer.c:timer_migration_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/callchain.c:perf_event_max_stack_handler
  - mm/page-writeback.c:dirty_ratio_handler
  - mm/page-writeback.c:dirty_background_ratio_handler
  - mm/util.c:overcommit_policy_handler
  - mm/util.c:overcommit_policy_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler
  - mm/page_alloc.c:watermark_scale_factor_sysctl_handler
  - mm/page_alloc.c:min_free_kbytes_sysctl_handler
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - ipc/ipc_sysctl.c:proc_ipc_auto_msgmni
  - ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax
  - ipc/mq_sysctl.c:proc_mq_dointvec_minmax
  - security/yama/yama_lsm.c:yama_dointvec_minmax
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/neighbour.c:neigh_proc_dointvec_unres_qlen
  - net/core/neighbour.c:neigh_proc_dointvec_zero_intmax
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/ipv6/addrconf.c:addrconf_sysctl_mtu
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffff810aed00-ffffffff810aed6a: proc_dointvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810b094a)
Location: kernel/sysctl.c:970
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
  - kernel/sysctl.c:proc_dointvec_minmax_warn_RT_change
  - kernel/sysctl.c:bpf_unpriv_handler
  - kernel/sysctl.c:bpf_stats_handler
Direct callers:
  - arch/x86/kernel/itmt.c:sched_itmt_update_handler
  - kernel/fork.c:sysctl_max_threads
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/topology.c:sched_energy_aware_handler
  - kernel/sched/topology.c:sched_energy_aware_handler
  - kernel/time/timer.c:timer_migration_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/callchain.c:perf_event_max_stack_handler
  - mm/page-writeback.c:dirty_ratio_handler
  - mm/page-writeback.c:dirty_background_ratio_handler
  - mm/util.c:overcommit_policy_handler
  - mm/util.c:overcommit_policy_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler
  - mm/page_alloc.c:watermark_scale_factor_sysctl_handler
  - mm/page_alloc.c:min_free_kbytes_sysctl_handler
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - ipc/ipc_sysctl.c:proc_ipc_auto_msgmni
  - ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax
  - ipc/mq_sysctl.c:proc_mq_dointvec_minmax
  - security/yama/yama_lsm.c:yama_dointvec_minmax
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/neighbour.c:neigh_proc_dointvec_unres_qlen
  - net/core/neighbour.c:neigh_proc_dointvec_zero_intmax
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/ipv6/addrconf.c:addrconf_sysctl_mtu
```
**Symbols:**

```
ffffffff810afcf0-ffffffff810afd5a: proc_dointvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810c267a)
Location: kernel/sysctl.c:1014
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
  - kernel/sysctl.c:proc_dointvec_minmax_warn_RT_change
  - kernel/sysctl.c:bpf_unpriv_handler
  - kernel/sysctl.c:bpf_stats_handler
Direct callers:
  - arch/x86/kernel/itmt.c:sched_itmt_update_handler
  - kernel/fork.c:sysctl_max_threads
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/topology.c:sched_energy_aware_handler
  - kernel/sched/topology.c:sched_energy_aware_handler
  - kernel/time/timer.c:timer_migration_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/delayacct.c:sysctl_delayacct
  - kernel/delayacct.c:sysctl_delayacct
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/callchain.c:perf_event_max_stack_handler
  - mm/page-writeback.c:dirty_ratio_handler
  - mm/page-writeback.c:dirty_background_ratio_handler
  - mm/util.c:overcommit_policy_handler
  - mm/util.c:overcommit_policy_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/compaction.c:compaction_proactiveness_sysctl_handler
  - mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler
  - mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler
  - mm/page_alloc.c:watermark_scale_factor_sysctl_handler
  - mm/page_alloc.c:min_free_kbytes_sysctl_handler
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - ipc/ipc_sysctl.c:proc_ipc_auto_msgmni
  - ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax
  - ipc/mq_sysctl.c:proc_mq_dointvec_minmax
  - security/yama/yama_lsm.c:yama_dointvec_minmax
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/neighbour.c:neigh_proc_dointvec_unres_qlen
  - net/core/neighbour.c:neigh_proc_dointvec_zero_intmax
  - net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler
  - net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/ipv6/addrconf.c:addrconf_sysctl_mtu
```
**Symbols:**

```
ffffffff810c0e50-ffffffff810c0eba: proc_dointvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810d9afb)
Location: kernel/sysctl.c:883
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_dointvec_minmax_warn_RT_change
Direct callers:
  - arch/x86/kernel/itmt.c:sched_itmt_update_handler
  - kernel/fork.c:sysctl_max_threads
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/build_utility.c:sched_energy_aware_handler
  - kernel/sched/build_utility.c:sched_energy_aware_handler
  - kernel/printk/sysctl.c:proc_dointvec_minmax_sysadmin
  - kernel/time/timer.c:timer_migration_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/delayacct.c:sysctl_delayacct
  - kernel/delayacct.c:sysctl_delayacct
  - kernel/bpf/syscall.c:bpf_unpriv_handler
  - kernel/bpf/syscall.c:bpf_unpriv_handler
  - kernel/bpf/syscall.c:bpf_stats_handler
  - kernel/bpf/syscall.c:bpf_stats_handler
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/callchain.c:perf_event_max_stack_handler
  - mm/page-writeback.c:dirty_ratio_handler
  - mm/page-writeback.c:dirty_background_ratio_handler
  - mm/util.c:overcommit_policy_handler
  - mm/util.c:overcommit_policy_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/compaction.c:compaction_proactiveness_sysctl_handler
  - mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler
  - mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler
  - mm/page_alloc.c:watermark_scale_factor_sysctl_handler
  - mm/page_alloc.c:min_free_kbytes_sysctl_handler
  - mm/hugetlb_vmemmap.c:hugetlb_optimize_vmemmap_handler
  - mm/hugetlb_vmemmap.c:hugetlb_optimize_vmemmap_handler
  - fs/exec.c:proc_dointvec_minmax_coredump
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - ipc/ipc_sysctl.c:proc_ipc_auto_msgmni
  - ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax_orphans
  - security/yama/yama_lsm.c:yama_dointvec_minmax
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/neighbour.c:neigh_proc_dointvec_unres_qlen
  - net/core/neighbour.c:neigh_proc_dointvec_zero_intmax
  - net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler
  - net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/ipv6/addrconf.c:addrconf_sysctl_mtu
```
**Symbols:**

```
ffffffff810d8520-ffffffff810d8597: proc_dointvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810f9a7b)
Location: kernel/sysctl.c:890
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_dointvec_minmax_warn_RT_change
Direct callers:
  - arch/x86/kernel/itmt.c:sched_itmt_update_handler
  - kernel/fork.c:sysctl_max_threads
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/build_utility.c:sched_energy_aware_handler
  - kernel/sched/build_utility.c:sched_energy_aware_handler
  - kernel/printk/sysctl.c:proc_dointvec_minmax_sysadmin
  - kernel/time/timer.c:timer_migration_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/delayacct.c:sysctl_delayacct
  - kernel/delayacct.c:sysctl_delayacct
  - kernel/bpf/syscall.c:bpf_unpriv_handler
  - kernel/bpf/syscall.c:bpf_unpriv_handler
  - kernel/bpf/syscall.c:bpf_stats_handler
  - kernel/bpf/syscall.c:bpf_stats_handler
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/callchain.c:perf_event_max_stack_handler
  - mm/page-writeback.c:dirty_ratio_handler
  - mm/page-writeback.c:dirty_background_ratio_handler
  - mm/util.c:overcommit_policy_handler
  - mm/util.c:overcommit_policy_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/compaction.c:compaction_proactiveness_sysctl_handler
  - mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler
  - mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler
  - mm/page_alloc.c:watermark_scale_factor_sysctl_handler
  - mm/page_alloc.c:min_free_kbytes_sysctl_handler
  - fs/exec.c:proc_dointvec_minmax_coredump
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - ipc/ipc_sysctl.c:proc_ipc_auto_msgmni
  - ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax_orphans
  - security/yama/yama_lsm.c:yama_dointvec_minmax
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/neighbour.c:neigh_proc_dointvec_unres_qlen
  - net/core/neighbour.c:neigh_proc_dointvec_zero_intmax
  - net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler
  - net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler
  - net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/ipv6/addrconf.c:addrconf_sysctl_mtu
```
**Symbols:**

```
ffffffff810f93f0-ffffffff810f9467: proc_dointvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81105d8b)
Location: kernel/sysctl.c:868
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_static_key
Direct callers:
  - arch/x86/kernel/itmt.c:sched_itmt_update_handler
  - kernel/fork.c:sysctl_max_threads
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/build_utility.c:sched_energy_aware_handler
  - kernel/sched/build_utility.c:sched_energy_aware_handler
  - kernel/printk/sysctl.c:proc_dointvec_minmax_sysadmin
  - kernel/time/timer.c:timer_migration_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_mfd_noexec_dointvec_minmax
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/delayacct.c:sysctl_delayacct
  - kernel/delayacct.c:sysctl_delayacct
  - kernel/bpf/syscall.c:bpf_unpriv_handler
  - kernel/bpf/syscall.c:bpf_unpriv_handler
  - kernel/bpf/syscall.c:bpf_stats_handler
  - kernel/bpf/syscall.c:bpf_stats_handler
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/callchain.c:perf_event_max_stack_handler
  - mm/page-writeback.c:dirty_ratio_handler
  - mm/page-writeback.c:dirty_background_ratio_handler
  - mm/util.c:overcommit_policy_handler
  - mm/util.c:overcommit_policy_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/compaction.c:proc_dointvec_minmax_warn_RT_change
  - mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler
  - mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler
  - mm/page_alloc.c:watermark_scale_factor_sysctl_handler
  - fs/exec.c:proc_dointvec_minmax_coredump
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - ipc/ipc_sysctl.c:proc_ipc_auto_msgmni
  - ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax_orphans
  - security/yama/yama_lsm.c:yama_dointvec_minmax
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/neighbour.c:neigh_proc_dointvec_unres_qlen
  - net/core/neighbour.c:neigh_proc_dointvec_zero_intmax
  - net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler
  - net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/ipv6/addrconf.c:addrconf_sysctl_mtu
```
**Symbols:**

```
ffffffff81105790-ffffffff81105807: proc_dointvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8110f6db)
Location: kernel/sysctl.c:868
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_static_key
Direct callers:
  - arch/x86/kernel/itmt.c:sched_itmt_update_handler
  - kernel/fork.c:sysctl_max_threads
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/build_policy.c:sched_rt_handler
  - kernel/printk/sysctl.c:proc_dointvec_minmax_sysadmin
  - kernel/time/timer.c:timer_migration_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_mfd_noexec_dointvec_minmax
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/delayacct.c:sysctl_delayacct
  - kernel/delayacct.c:sysctl_delayacct
  - kernel/bpf/syscall.c:bpf_unpriv_handler
  - kernel/bpf/syscall.c:bpf_unpriv_handler
  - kernel/bpf/syscall.c:bpf_stats_handler
  - kernel/bpf/syscall.c:bpf_stats_handler
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_event_max_sample_rate_handler
  - kernel/events/core.c:perf_event_max_sample_rate_handler
  - kernel/events/callchain.c:perf_event_max_stack_handler
  - mm/page-writeback.c:dirty_ratio_handler
  - mm/page-writeback.c:dirty_background_ratio_handler
  - mm/util.c:overcommit_policy_handler
  - mm/util.c:overcommit_policy_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/compaction.c:proc_dointvec_minmax_warn_RT_change
  - mm/page_alloc.c:percpu_pagelist_high_fraction_sysctl_handler
  - mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler
  - mm/page_alloc.c:watermark_scale_factor_sysctl_handler
  - fs/exec.c:proc_dointvec_minmax_coredump
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - ipc/ipc_sysctl.c:proc_ipc_auto_msgmni
  - ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax_orphans
  - security/yama/yama_lsm.c:yama_dointvec_minmax
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/neighbour.c:neigh_proc_dointvec_unres_qlen
  - net/core/neighbour.c:neigh_proc_dointvec_zero_intmax
  - net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler
  - net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/ipv6/addrconf.c:addrconf_sysctl_mtu
```
**Symbols:**

```
ffffffff8110f0e0-ffffffff8110f157: proc_dointvec_minmax (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffff800010103bd0)
Location: kernel/sysctl.c:2718
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
Direct callers:
  - arch/arm64/kernel/armv8_deprecated.c:emulation_proc_handler
  - kernel/fork.c:sysctl_max_threads
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/time/timer.c:timer_migration_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/callchain.c:perf_event_max_stack_handler
  - mm/page-writeback.c:dirty_ratio_handler
  - mm/page-writeback.c:dirty_background_ratio_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler
  - mm/page_alloc.c:watermark_scale_factor_sysctl_handler
  - mm/page_alloc.c:watermark_boost_factor_sysctl_handler
  - mm/page_alloc.c:min_free_kbytes_sysctl_handler
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - ipc/ipc_sysctl.c:proc_ipc_auto_msgmni
  - ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax
  - ipc/mq_sysctl.c:proc_mq_dointvec_minmax
  - security/yama/yama_lsm.c:yama_dointvec_minmax
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/neighbour.c:neigh_proc_dointvec_unres_qlen
  - net/core/neighbour.c:neigh_proc_dointvec_zero_intmax
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/ipv6/addrconf.c:addrconf_sysctl_mtu
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffff8000101035f8-ffff800010103690: proc_dointvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (c035fbe8)
Location: kernel/sysctl.c:2718
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
Direct callers:
  - kernel/fork.c:sysctl_max_threads
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/time/timer.c:timer_migration_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/callchain.c:perf_event_max_stack_handler
  - mm/page-writeback.c:dirty_ratio_handler
  - mm/page-writeback.c:dirty_background_ratio_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler
  - mm/page_alloc.c:watermark_scale_factor_sysctl_handler
  - mm/page_alloc.c:watermark_boost_factor_sysctl_handler
  - mm/page_alloc.c:min_free_kbytes_sysctl_handler
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - ipc/ipc_sysctl.c:proc_ipc_auto_msgmni
  - ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax
  - ipc/mq_sysctl.c:proc_mq_dointvec_minmax
  - security/yama/yama_lsm.c:yama_dointvec_minmax
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/neighbour.c:neigh_proc_dointvec_unres_qlen
  - net/core/neighbour.c:neigh_proc_dointvec_zero_intmax
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/ipv6/addrconf.c:addrconf_sysctl_mtu
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
c035f678-c035f70c: proc_dointvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (c00000000014ba64)
Location: kernel/sysctl.c:2718
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
Direct callers:
  - kernel/fork.c:sysctl_max_threads
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/time/timer.c:timer_migration_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/callchain.c:perf_event_max_stack_handler
  - mm/page-writeback.c:dirty_ratio_handler
  - mm/page-writeback.c:dirty_background_ratio_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler
  - mm/page_alloc.c:watermark_scale_factor_sysctl_handler
  - mm/page_alloc.c:watermark_boost_factor_sysctl_handler
  - mm/page_alloc.c:min_free_kbytes_sysctl_handler
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - ipc/ipc_sysctl.c:proc_ipc_auto_msgmni
  - ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax
  - ipc/mq_sysctl.c:proc_mq_dointvec_minmax
  - security/yama/yama_lsm.c:yama_dointvec_minmax
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/neighbour.c:neigh_proc_dointvec_unres_qlen
  - net/core/neighbour.c:neigh_proc_dointvec_zero_intmax
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/ipv6/addrconf.c:addrconf_sysctl_mtu
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
c00000000014b420-c00000000014b4b8: proc_dointvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffe0000ca782)
Location: kernel/sysctl.c:2718
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
Direct callers:
  - kernel/fork.c:sysctl_max_threads
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/time/timer.c:timer_migration_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/callchain.c:perf_event_max_stack_handler
  - mm/page-writeback.c:dirty_ratio_handler
  - mm/page-writeback.c:dirty_background_ratio_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler
  - mm/page_alloc.c:watermark_scale_factor_sysctl_handler
  - mm/page_alloc.c:watermark_boost_factor_sysctl_handler
  - mm/page_alloc.c:min_free_kbytes_sysctl_handler
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - ipc/ipc_sysctl.c:proc_ipc_auto_msgmni
  - ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax
  - ipc/mq_sysctl.c:proc_mq_dointvec_minmax
  - security/yama/yama_lsm.c:yama_dointvec_minmax
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/neighbour.c:neigh_proc_dointvec_unres_qlen
  - net/core/neighbour.c:neigh_proc_dointvec_zero_intmax
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/ipv6/addrconf.c:addrconf_sysctl_mtu
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffe0000ca378-ffffffe0000ca3e0: proc_dointvec_minmax (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a4da3)
Location: kernel/sysctl.c:2718
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
Direct callers:
  - arch/x86/kernel/itmt.c:sched_itmt_update_handler
  - kernel/fork.c:sysctl_max_threads
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/time/timer.c:timer_migration_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/callchain.c:perf_event_max_stack_handler
  - mm/page-writeback.c:dirty_ratio_handler
  - mm/page-writeback.c:dirty_background_ratio_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler
  - mm/page_alloc.c:watermark_scale_factor_sysctl_handler
  - mm/page_alloc.c:watermark_boost_factor_sysctl_handler
  - mm/page_alloc.c:min_free_kbytes_sysctl_handler
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - ipc/ipc_sysctl.c:proc_ipc_auto_msgmni
  - ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax
  - ipc/mq_sysctl.c:proc_mq_dointvec_minmax
  - security/yama/yama_lsm.c:yama_dointvec_minmax
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/neighbour.c:neigh_proc_dointvec_unres_qlen
  - net/core/neighbour.c:neigh_proc_dointvec_zero_intmax
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/ipv6/addrconf.c:addrconf_sysctl_mtu
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffff810a4960-ffffffff810a49cc: proc_dointvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81093783)
Location: kernel/sysctl.c:2718
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
Direct callers:
  - arch/x86/kernel/itmt.c:sched_itmt_update_handler
  - kernel/fork.c:sysctl_max_threads
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/time/timer.c:timer_migration_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/callchain.c:perf_event_max_stack_handler
  - mm/page-writeback.c:dirty_ratio_handler
  - mm/page-writeback.c:dirty_background_ratio_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler
  - mm/page_alloc.c:watermark_scale_factor_sysctl_handler
  - mm/page_alloc.c:watermark_boost_factor_sysctl_handler
  - mm/page_alloc.c:min_free_kbytes_sysctl_handler
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - ipc/ipc_sysctl.c:proc_ipc_auto_msgmni
  - ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax
  - ipc/mq_sysctl.c:proc_mq_dointvec_minmax
  - security/yama/yama_lsm.c:yama_dointvec_minmax
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/neighbour.c:neigh_proc_dointvec_unres_qlen
  - net/core/neighbour.c:neigh_proc_dointvec_zero_intmax
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/ipv6/addrconf.c:addrconf_sysctl_mtu
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffff81093340-ffffffff810933ac: proc_dointvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a4d53)
Location: kernel/sysctl.c:2718
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
Direct callers:
  - arch/x86/kernel/itmt.c:sched_itmt_update_handler
  - kernel/fork.c:sysctl_max_threads
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/time/timer.c:timer_migration_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/callchain.c:perf_event_max_stack_handler
  - mm/page-writeback.c:dirty_ratio_handler
  - mm/page-writeback.c:dirty_background_ratio_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler
  - mm/page_alloc.c:watermark_scale_factor_sysctl_handler
  - mm/page_alloc.c:watermark_boost_factor_sysctl_handler
  - mm/page_alloc.c:min_free_kbytes_sysctl_handler
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - ipc/ipc_sysctl.c:proc_ipc_auto_msgmni
  - ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax
  - ipc/mq_sysctl.c:proc_mq_dointvec_minmax
  - security/yama/yama_lsm.c:yama_dointvec_minmax
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/neighbour.c:neigh_proc_dointvec_unres_qlen
  - net/core/neighbour.c:neigh_proc_dointvec_zero_intmax
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/ipv6/addrconf.c:addrconf_sysctl_mtu
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffff810a4910-ffffffff810a497c: proc_dointvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int proc_dointvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810ace13)
Location: kernel/sysctl.c:2718
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_static_key
  - kernel/sysctl.c:proc_dointvec_minmax_sysadmin
Direct callers:
  - arch/x86/kernel/itmt.c:sched_itmt_update_handler
  - kernel/fork.c:sysctl_max_threads
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_schedstats
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/time/timer.c:timer_migration_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/watchdog.c:proc_watchdog_common
  - kernel/events/core.c:perf_cpu_time_max_percent_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/core.c:perf_proc_update_handler
  - kernel/events/callchain.c:perf_event_max_stack_handler
  - mm/page-writeback.c:dirty_ratio_handler
  - mm/page-writeback.c:dirty_background_ratio_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/page_alloc.c:percpu_pagelist_fraction_sysctl_handler
  - mm/page_alloc.c:lowmem_reserve_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_slab_ratio_sysctl_handler
  - mm/page_alloc.c:sysctl_min_unmapped_ratio_sysctl_handler
  - mm/page_alloc.c:watermark_scale_factor_sysctl_handler
  - mm/page_alloc.c:watermark_boost_factor_sysctl_handler
  - mm/page_alloc.c:min_free_kbytes_sysctl_handler
  - fs/fs-writeback.c:dirtytime_interval_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - ipc/ipc_sysctl.c:proc_ipc_auto_msgmni
  - ipc/ipc_sysctl.c:proc_ipc_dointvec_minmax
  - ipc/mq_sysctl.c:proc_mq_dointvec_minmax
  - security/yama/yama_lsm.c:yama_dointvec_minmax
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_restricted
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/sysctl_net_core.c:proc_dointvec_minmax_bpf_enable
  - net/core/neighbour.c:neigh_proc_dointvec_unres_qlen
  - net/core/neighbour.c:neigh_proc_dointvec_zero_intmax
  - net/ipv4/sysctl_net_ipv4.c:proc_fib_multipath_hash_policy
  - net/ipv4/sysctl_net_ipv4.c:proc_tfo_blackhole_detect_timeout
  - net/ipv4/sysctl_net_ipv4.c:ipv4_fwd_update_priority
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_privileged_ports
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
  - net/ipv6/addrconf.c:addrconf_sysctl_mtu
  - net/ipv6/sysctl_net_ipv6.c:proc_rt6_multipath_hash_policy
```
**Symbols:**

```
ffffffff810ac9d0-ffffffff810aca3c: proc_dointvec_minmax (STB_GLOBAL)
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
