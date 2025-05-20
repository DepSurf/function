# Function: <code>bitmap_or</code>

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
In arch/x86/kernel/apic/vector.c (ffffffff8105537d)
Location: include/linux/bitmap.h:220
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In kernel/sysctl.c (ffffffff810892c4)
Location: include/linux/bitmap.h:220
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/core.c (ffffffff810a875a)
Location: include/linux/bitmap.h:220
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:build_sched_domain
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:sched_init_smp
```
```
In kernel/time/tick-broadcast.c (ffffffff810fcf8a)
Location: include/linux/bitmap.h:220
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
```
```
In kernel/cpuset.c (ffffffff8111ab1f)
Location: include/linux/bitmap.h:220
Inline: True
Inline callers:
  - kernel/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff811cb450)
Location: include/linux/bitmap.h:220
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/mempolicy.c (ffffffff811e0b67)
Location: include/linux/bitmap.h:220
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In lib/cpu_rmap.c (ffffffff81415e49)
Location: include/linux/bitmap.h:220
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff816b3c13)
Location: include/linux/bitmap.h:220
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
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
In arch/x86/kernel/apic/vector.c (ffffffff810555e6)
Location: include/linux/bitmap.h:230
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In kernel/sysctl.c (ffffffff8108c1f1)
Location: include/linux/bitmap.h:230
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/core.c (ffffffff81fa6b64)
Location: include/linux/bitmap.h:230
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domain
  - kernel/sched/core.c:cpu_attach_domain
```
```
In kernel/time/tick-broadcast.c (ffffffff81104b97)
Location: include/linux/bitmap.h:230
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cpuset.c (ffffffff8112357b)
Location: include/linux/bitmap.h:230
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_change_task_nodemask
  - kernel/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff811e85da)
Location: include/linux/bitmap.h:230
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/mempolicy.c (ffffffff811ff51f)
Location: include/linux/bitmap.h:230
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In lib/cpu_rmap.c (ffffffff8145dc89)
Location: include/linux/bitmap.h:230
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81715c3e)
Location: include/linux/bitmap.h:230
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810446d5)
Location: include/linux/bitmap.h:230
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81058164)
Location: include/linux/bitmap.h:230
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In kernel/sysctl.c (ffffffff81091151)
Location: include/linux/bitmap.h:230
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/core.c (ffffffff81fe26e5)
Location: include/linux/bitmap.h:230
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domain
  - kernel/sched/core.c:cpu_attach_domain
```
```
In kernel/time/tick-broadcast.c (ffffffff8110c2d5)
Location: include/linux/bitmap.h:230
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cpuset.c (ffffffff8112b268)
Location: include/linux/bitmap.h:230
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_change_task_nodemask
  - kernel/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff811f98eb)
Location: include/linux/bitmap.h:230
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/mempolicy.c (ffffffff8120fce2)
Location: include/linux/bitmap.h:230
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In lib/cpu_rmap.c (ffffffff8147c793)
Location: include/linux/bitmap.h:230
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff817479d3)
Location: include/linux/bitmap.h:230
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81043986)
Location: include/linux/bitmap.h:229
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81057820)
Location: include/linux/bitmap.h:229
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In kernel/sysctl.c (ffffffff8108e2fa)
Location: include/linux/bitmap.h:229
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/topology.c (ffffffff810ccbdb)
Location: include/linux/bitmap.h:229
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domain
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/time/tick-broadcast.c (ffffffff8110d7f1)
Location: include/linux/bitmap.h:229
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff8112c588)
Location: include/linux/bitmap.h:229
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff812044cb)
Location: include/linux/bitmap.h:229
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In lib/cpu_rmap.c (ffffffff81485ac3)
Location: include/linux/bitmap.h:229
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8176602d)
Location: include/linux/bitmap.h:229
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81047096)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/sysctl.c (ffffffff8109514c)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/topology.c (ffffffff810d4258)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/matrix.c (ffffffff810f8f6a)
Location: include/linux/bitmap.h:239
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff81118a81)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff811393b8)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff8121d2e9)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In lib/cpu_rmap.c (ffffffff814c1bdf)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff817dbff9)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81049646)
Location: include/linux/bitmap.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/sysctl.c (ffffffff810989bd)
Location: include/linux/bitmap.h:270
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/topology.c (ffffffff810dcf33)
Location: include/linux/bitmap.h:270
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/matrix.c (ffffffff811014d1)
Location: include/linux/bitmap.h:270
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff81125601)
Location: include/linux/bitmap.h:270
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff81148488)
Location: include/linux/bitmap.h:270
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In mm/rmap.c (ffffffff8123f18a)
Location: include/linux/bitmap.h:270
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In lib/cpu_rmap.c (ffffffff814f2b22)
Location: include/linux/bitmap.h:270
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8173ac33)
Location: include/linux/bitmap.h:270
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81824ca9)
Location: include/linux/bitmap.h:270
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810596a9)
Location: include/linux/bitmap.h:271
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105d3f3)
Location: include/linux/bitmap.h:271
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/sysctl.c (ffffffff810a0d70)
Location: include/linux/bitmap.h:271
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/topology.c (ffffffff810e6b93)
Location: include/linux/bitmap.h:271
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/affinity.c (ffffffff8110c239)
Location: include/linux/bitmap.h:271
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff8110cdeb)
Location: include/linux/bitmap.h:271
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff81130cf1)
Location: include/linux/bitmap.h:271
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff81153fa8)
Location: include/linux/bitmap.h:271
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In mm/rmap.c (ffffffff812537fd)
Location: include/linux/bitmap.h:271
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In lib/cpu_rmap.c (ffffffff81506e52)
Location: include/linux/bitmap.h:271
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/net/phy/phy.c (ffffffff8175872b)
Location: include/linux/bitmap.h:271
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_speed_up
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8175e37d)
Location: include/linux/bitmap.h:271
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81850c39)
Location: include/linux/bitmap.h:271
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105cc5d)
Location: include/linux/bitmap.h:271
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060773)
Location: include/linux/bitmap.h:271
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/sysctl.c (ffffffff810a57f8)
Location: include/linux/bitmap.h:271
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/topology.c (ffffffff810ed849)
Location: include/linux/bitmap.h:271
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/affinity.c (ffffffff811159be)
Location: include/linux/bitmap.h:271
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff811164cc)
Location: include/linux/bitmap.h:271
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff8113b850)
Location: include/linux/bitmap.h:271
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff811604f8)
Location: include/linux/bitmap.h:271
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff81265a39)
Location: include/linux/bitmap.h:271
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/sparse.c (ffffffff81a9737f)
Location: include/linux/bitmap.h:271
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
```
```
In lib/cpu_rmap.c (ffffffff81535066)
Location: include/linux/bitmap.h:271
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/net/phy/phy.c (ffffffff817954d8)
Location: include/linux/bitmap.h:271
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_speed_up
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8179ba0a)
Location: include/linux/bitmap.h:271
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81894179)
Location: include/linux/bitmap.h:271
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d53d)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81061023)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/sysctl.c (ffffffff810abdd8)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/topology.c (ffffffff810f93ea)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/affinity.c (ffffffff81121dce)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff8112289c)
Location: include/linux/bitmap.h:275
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff81147460)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff8116c1c8)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff81274358)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/sparse.c (ffffffff81acec61)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
```
```
In lib/cpu_rmap.c (ffffffff81555e76)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/net/phy/sfp-bus.c (ffffffff817bf4ba)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818c6199)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void bitmap_or(long unsigned int *dst, const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060c02)
Location: include/linux/bitmap.h:291
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81066cc3)
Location: include/linux/bitmap.h:291
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/sysctl.c (ffffffff810b2830)
Location: include/linux/bitmap.h:291
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/topology.c (ffffffff8110258c)
Location: include/linux/bitmap.h:291
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/affinity.c (ffffffff8112e399)
Location: include/linux/bitmap.h:291
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff8112eeec)
Location: include/linux/bitmap.h:291
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff811575d0)
Location: include/linux/bitmap.h:291
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff8117e0f8)
Location: include/linux/bitmap.h:291
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff812a55f6)
Location: include/linux/bitmap.h:291
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/sparse.c (ffffffff81bc7592)
Location: include/linux/bitmap.h:291
Inline: True
Inline callers:
  - mm/sparse.c:section_activate
```
```
In lib/cpu_rmap.c (ffffffff815df7e5)
Location: include/linux/bitmap.h:291
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/net/phy/sfp-bus.c (ffffffff818885d6)
Location: include/linux/bitmap.h:291
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189f6a7)
Location: include/linux/bitmap.h:291
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81998219)
Location: include/linux/bitmap.h:291
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In net/ethtool/features.c (ffffffff81a8a143)
Location: include/linux/bitmap.h:291
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff81100510-ffffffff8110051b: bitmap_or (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void bitmap_or(long unsigned int *dst, const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105f28a)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81064f04)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068082)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
```
```
In kernel/sysctl.c (ffffffff810ae060)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/topology.c (ffffffff811011ac)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/affinity.c (ffffffff81129f89)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff8112aecc)
Location: include/linux/bitmap.h:289
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff811536a0)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff8117af68)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff812b0a4d)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/sparse.c (ffffffff81c402be)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - mm/sparse.c:section_activate
```
```
In lib/cpu_rmap.c (ffffffff815fcf85)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81896876)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ae708)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8199b339)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In net/ethtool/features.c (ffffffff81a939cd)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff810ff060-ffffffff810ff06b: bitmap_or (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void bitmap_or(long unsigned int *dst, const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810619a4)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81065524)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810685f2)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
```
```
In kernel/sysctl.c (ffffffff810af351)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/topology.c (ffffffff81102eaf)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/affinity.c (ffffffff8112a1fb)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff8112b160)
Location: include/linux/bitmap.h:289
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff81154824)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff8117c7e8)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff812b613a)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/sparse.c (ffffffff81c32431)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
```
```
In lib/cpu_rmap.c (ffffffff815dfd0e)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81879460)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81892a20)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8198001f)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In net/ethtool/features.c (ffffffff81a7d3ed)
Location: include/linux/bitmap.h:289
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff81101400-ffffffff8110140b: bitmap_or (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void bitmap_or(long unsigned int *dst, const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106b695)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106f61c)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81072d88)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
```
In kernel/sysctl.c (ffffffff810c1aea)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/topology.c (ffffffff8111fa8d)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/affinity.c (ffffffff8114ab59)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff8114bb40)
Location: include/linux/bitmap.h:295
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff81179274)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff811a4378)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff812f7cb4)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/sparse.c (ffffffff81d50e2d)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
```
```
In mm/migrate.c (ffffffff8133e29b)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - mm/migrate.c:__set_migration_target_nodes
```
```
In lib/cpu_rmap.c (ffffffff8164b96c)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8190a2c0)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff819238ca)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81a291bf)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In net/ethtool/features.c (ffffffff81b375dd)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff8111d600-ffffffff8111d60b: bitmap_or (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void bitmap_or(long unsigned int *dst, const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810789ad)
Location: include/linux/bitmap.h:314
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107ce93)
Location: include/linux/bitmap.h:314
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81080fb6)
Location: include/linux/bitmap.h:314
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
```
```
In kernel/sysctl.c (ffffffff810d92b9)
Location: include/linux/bitmap.h:314
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/build_utility.c (ffffffff81149acb)
Location: include/linux/bitmap.h:314
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:build_overlap_sched_groups
Direct callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/irq/affinity.c (ffffffff8117019c)
Location: include/linux/bitmap.h:314
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff811714e0)
Location: include/linux/bitmap.h:314
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff811aebcf)
Location: include/linux/bitmap.h:314
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff811d3e27)
Location: include/linux/bitmap.h:314
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff8135daee)
Location: include/linux/bitmap.h:314
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/sparse.c (ffffffff81f21043)
Location: include/linux/bitmap.h:314
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
```
```
In mm/migrate.c (ffffffff813b10be)
Location: include/linux/bitmap.h:314
Inline: True
Inline callers:
  - mm/migrate.c:__set_migration_target_nodes
```
```
In lib/cpu_rmap.c (ffffffff8176246c)
Location: include/linux/bitmap.h:314
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81a5d9e2)
Location: include/linux/bitmap.h:314
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a79292)
Location: include/linux/bitmap.h:314
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81b9321c)
Location: include/linux/bitmap.h:314
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In net/ethtool/features.c (ffffffff81cc3014)
Location: include/linux/bitmap.h:314
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff81e56b3c-ffffffff81e56b53: bitmap_or (STB_LOCAL)
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81086a1d)
Location: include/linux/bitmap.h:328
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108e218)
Location: include/linux/bitmap.h:328
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108fd36)
Location: include/linux/bitmap.h:328
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In kernel/sysctl.c (ffffffff810f8115)
Location: include/linux/bitmap.h:328
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/build_utility.c (ffffffff811782ea)
Location: include/linux/bitmap.h:328
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/irq/affinity.c (ffffffff811a65f4)
Location: include/linux/bitmap.h:328
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff811a7b00)
Location: include/linux/bitmap.h:328
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff811eed81)
Location: include/linux/bitmap.h:328
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff81217be7)
Location: include/linux/bitmap.h:328
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff813d8972)
Location: include/linux/bitmap.h:328
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/sparse.c (ffffffff820cac61)
Location: include/linux/bitmap.h:328
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
```
```
In mm/memory-tiers.c (ffffffff81436c18)
Location: include/linux/bitmap.h:328
Inline: True
Inline callers:
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:nodelist_show
```
```
In lib/cpu_rmap.c (ffffffff81891362)
Location: include/linux/bitmap.h:328
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81be85d4)
Location: include/linux/bitmap.h:328
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d3388f)
Location: include/linux/bitmap.h:328
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In net/ethtool/features.c (ffffffff81e82314)
Location: include/linux/bitmap.h:328
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108c590)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810910c8)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81092c4c)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In kernel/sysctl.c (ffffffff81104511)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/build_utility.c (ffffffff81188f92)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/irq/matrix.c (ffffffff811b97e0)
Location: include/linux/bitmap.h:326
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff81203adc)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff8122d407)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/bpf/cpumask.c (ffffffff8135d975)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_or
```
```
In mm/rmap.c (ffffffff8140ad73)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - mm/rmap.c:set_tlb_ubc_flush_pending
```
```
In mm/sparse.c (ffffffff8214eef1)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
```
```
In mm/memory-tiers.c (ffffffff8146c8d8)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:nodelist_show
```
```
In lib/cpu_rmap.c (ffffffff818d3672)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In lib/group_cpus.c (ffffffff818e7022)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - lib/group_cpus.c:__group_cpus_evenly
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81c40975)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d9cc1f)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In net/ethtool/features.c (ffffffff81ede974)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81092870)
Location: include/linux/bitmap.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81098488)
Location: include/linux/bitmap.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a08c)
Location: include/linux/bitmap.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In kernel/sysctl.c (ffffffff8110de61)
Location: include/linux/bitmap.h:303
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/build_utility.c (ffffffff81197885)
Location: include/linux/bitmap.h:303
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/irq/matrix.c (ffffffff811c96a0)
Location: include/linux/bitmap.h:303
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff83903a00)
Location: include/linux/bitmap.h:303
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_nohz
```
```
In kernel/time/tick-broadcast.c (ffffffff8121a09c)
Location: include/linux/bitmap.h:303
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff812456d7)
Location: include/linux/bitmap.h:303
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
  - kernel/cgroup/cpuset.c:partition_xcpus_del
  - kernel/cgroup/cpuset.c:partition_xcpus_add
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/bpf/cpumask.c (ffffffff81386715)
Location: include/linux/bitmap.h:303
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_or
```
```
In mm/rmap.c (ffffffff814374a3)
Location: include/linux/bitmap.h:303
Inline: True
```
```
In mm/sparse.c (ffffffff82231d62)
Location: include/linux/bitmap.h:303
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
```
```
In mm/memory-tiers.c (ffffffff8149ba28)
Location: include/linux/bitmap.h:303
Inline: True
Inline callers:
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:nodelist_show
```
```
In lib/cpu_rmap.c (ffffffff81925752)
Location: include/linux/bitmap.h:303
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In lib/group_cpus.c (ffffffff8192e042)
Location: include/linux/bitmap.h:303
Inline: True
Inline callers:
  - lib/group_cpus.c:__group_cpus_evenly
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81cf5fe7)
Location: include/linux/bitmap.h:303
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81e548df)
Location: include/linux/bitmap.h:303
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In net/ethtool/features.c (ffffffff81fa27b7)
Location: include/linux/bitmap.h:303
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
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
In arch/arm64/kernel/fpsimd.c (ffff800010087a50)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - arch/arm64/kernel/fpsimd.c:sve_update_vq_map
```
```
In arch/arm64/kernel/alternative.c (ffff80001009b5a8)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - arch/arm64/kernel/alternative.c:__apply_alternatives
```
```
In kernel/sysctl.c (ffff8000101044bc)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/topology.c (ffff80001015c6b8)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/irq/affinity.c (ffff800010188000)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffff8000101b2600)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffff8000101e10a4)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/sparse.c (ffff800010da0840)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
```
```
In lib/cpu_rmap.c (ffff800010662918)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/net/phy/sfp-bus.c (ffff8000109d98f0)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffff800010b241f0)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/hw_breakpoint.c (c031678c)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - arch/arm/kernel/hw_breakpoint.c:reset_ctrl_regs
  - arch/arm/kernel/hw_breakpoint.c:reset_ctrl_regs
```
```
In kernel/sysctl.c (c0360678)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/topology.c (c03a912c)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/irq/affinity.c (c03d6780)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (c03fcd54)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (c0424a8c)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In lib/cpu_rmap.c (c080b54c)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/net/phy/sfp-bus.c (c0ac0538)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/cpufreq/cpufreq_ondemand.c (c0bfe280)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/watchdog.c (c000000000036b78)
Location: include/linux/bitmap.h:275
Inline: True
```
```
In arch/powerpc/mm/numa.c (c0000000000a3918)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
```
```
In arch/powerpc/mm/slice.c (c0000000000a53c0)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - arch/powerpc/mm/slice.c:slice_is_hugepage_only_range
  - arch/powerpc/mm/slice.c:slice_get_unmapped_area
  - arch/powerpc/mm/slice.c:slice_get_unmapped_area
  - arch/powerpc/mm/slice.c:slice_get_unmapped_area
```
```
In kernel/sysctl.c (c00000000014c7e8)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/topology.c (c0000000001b0f10)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/irq/affinity.c (c0000000001e1e04)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (c000000000217d34)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (c00000000024f044)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/sparse.c (c000000000eed494)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - mm/sparse.c:section_activate
```
```
In lib/cpu_rmap.c (c000000000816aa4)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/net/phy/sfp-bus.c (c000000000a9b470)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/cpufreq/cpufreq_ondemand.c (c000000000c18a80)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
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
In kernel/sysctl.c (ffffffe0000c9ab2)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/topology.c (ffffffe0001018ea)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/affinity.c (ffffffe00011d6b8)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffe0001592a4)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In lib/cpu_rmap.c (ffffffe00048edbc)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/net/phy/sfp-bus.c (ffffffe000624824)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d0bd)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060ba3)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/sysctl.c (ffffffff810a56f8)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/topology.c (ffffffff810f27ea)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/affinity.c (ffffffff8111a3ae)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff8111ae7c)
Location: include/linux/bitmap.h:275
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff8113fa80)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff811647e8)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff8126c9a8)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/sparse.c (ffffffff81a6dad1)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
```
```
In lib/cpu_rmap.c (ffffffff8154e456)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81783f8a)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8186a8b9)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104d28d)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81051003)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/sysctl.c (ffffffff810940d8)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/topology.c (ffffffff810e285a)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/affinity.c (ffffffff8110b41e)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff8110beec)
Location: include/linux/bitmap.h:275
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff828b0e9f)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_nohz
```
```
In kernel/time/tick-broadcast.c (ffffffff81132800)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff81157a32)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff8125e9fe)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/sparse.c (ffffffff81a2a018)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
```
```
In lib/cpu_rmap.c (ffffffff8153e736)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/net/phy/sfp-bus.c (ffffffff817638da)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81833569)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d4ed)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060fd3)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/sysctl.c (ffffffff810a56a8)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/topology.c (ffffffff810ef91a)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/affinity.c (ffffffff8111829e)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff81118d6c)
Location: include/linux/bitmap.h:275
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff8113d930)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff811625b8)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff8126a748)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/sparse.c (ffffffff81ad9ee1)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
```
```
In lib/cpu_rmap.c (ffffffff8154a196)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/net/phy/sfp-bus.c (ffffffff817b433a)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818bb649)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ea0d)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81062593)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/sysctl.c (ffffffff810ad768)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_large_bitmap
```
```
In kernel/sched/topology.c (ffffffff810fa96a)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/affinity.c (ffffffff8112392e)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff811243fc)
Location: include/linux/bitmap.h:275
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff8114a440)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff8116fb38)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff81279eed)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/sparse.c (ffffffff81ae6397)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
```
```
In lib/cpu_rmap.c (ffffffff81563fe6)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/net/phy/sfp-bus.c (ffffffff817ce30a)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_parse_support
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818d7939)
Location: include/linux/bitmap.h:275
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
