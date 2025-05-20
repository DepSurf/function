# Function: <code>cpumask_or</code>

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
Location: include/linux/cpumask.h:365
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In kernel/sched/core.c (ffffffff810a875a)
Location: include/linux/cpumask.h:365
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:build_sched_domain
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:sched_init_smp
```
```
In kernel/time/tick-broadcast.c (ffffffff810fcf8a)
Location: include/linux/cpumask.h:365
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
```
```
In kernel/cpuset.c (ffffffff8111ab17)
Location: include/linux/cpumask.h:365
Inline: True
Inline callers:
  - kernel/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff811cb450)
Location: include/linux/cpumask.h:365
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In lib/cpu_rmap.c (ffffffff81415e49)
Location: include/linux/cpumask.h:365
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff816b3c13)
Location: include/linux/cpumask.h:365
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
Location: include/linux/cpumask.h:369
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In kernel/sched/core.c (ffffffff81fa6b64)
Location: include/linux/cpumask.h:369
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domain
  - kernel/sched/core.c:cpu_attach_domain
```
```
In kernel/time/tick-broadcast.c (ffffffff81104b97)
Location: include/linux/cpumask.h:369
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cpuset.c (ffffffff81122a60)
Location: include/linux/cpumask.h:369
Inline: True
Inline callers:
  - kernel/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff811e85da)
Location: include/linux/cpumask.h:369
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In lib/cpu_rmap.c (ffffffff8145dc89)
Location: include/linux/cpumask.h:369
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81715c3e)
Location: include/linux/cpumask.h:369
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810446cc)
Location: include/linux/cpumask.h:369
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105815d)
Location: include/linux/cpumask.h:369
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In kernel/sched/core.c (ffffffff81fe26e5)
Location: include/linux/cpumask.h:369
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domain
  - kernel/sched/core.c:cpu_attach_domain
```
```
In kernel/time/tick-broadcast.c (ffffffff8110c2ce)
Location: include/linux/cpumask.h:369
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cpuset.c (ffffffff8112cb39)
Location: include/linux/cpumask.h:369
Inline: True
Inline callers:
  - kernel/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff811f98eb)
Location: include/linux/cpumask.h:369
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In lib/cpu_rmap.c (ffffffff8147c77e)
Location: include/linux/cpumask.h:369
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff817479d3)
Location: include/linux/cpumask.h:369
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff8104396f)
Location: include/linux/cpumask.h:397
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
In arch/x86/kernel/apic/vector.c (ffffffff81057819)
Location: include/linux/cpumask.h:397
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In kernel/sched/topology.c (ffffffff810ccbdb)
Location: include/linux/cpumask.h:397
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domain
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/time/tick-broadcast.c (ffffffff8110d7ea)
Location: include/linux/cpumask.h:397
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff8112ddce)
Location: include/linux/cpumask.h:397
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff812044cb)
Location: include/linux/cpumask.h:397
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In lib/cpu_rmap.c (ffffffff81485aae)
Location: include/linux/cpumask.h:397
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8176602d)
Location: include/linux/cpumask.h:397
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff8104707f)
Location: include/linux/cpumask.h:401
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
In kernel/sched/topology.c (ffffffff810d4258)
Location: include/linux/cpumask.h:401
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/time/tick-broadcast.c (ffffffff81118a7a)
Location: include/linux/cpumask.h:401
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff8113a8b4)
Location: include/linux/cpumask.h:401
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff8121d2e9)
Location: include/linux/cpumask.h:401
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In lib/cpu_rmap.c (ffffffff814c1bc0)
Location: include/linux/cpumask.h:401
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff817dbff9)
Location: include/linux/cpumask.h:401
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
Location: include/linux/cpumask.h:403
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
In kernel/sched/topology.c (ffffffff810dcf33)
Location: include/linux/cpumask.h:403
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/time/tick-broadcast.c (ffffffff811255fa)
Location: include/linux/cpumask.h:403
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff81149e23)
Location: include/linux/cpumask.h:403
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In mm/rmap.c (ffffffff8123f18a)
Location: include/linux/cpumask.h:403
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In lib/cpu_rmap.c (ffffffff814f2b22)
Location: include/linux/cpumask.h:403
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81824ca9)
Location: include/linux/cpumask.h:403
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
Location: include/linux/cpumask.h:415
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
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/sched/topology.c (ffffffff810e6b93)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/affinity.c (ffffffff8110c21e)
Location: include/linux/cpumask.h:415
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff81130cea)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff81155aa6)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In mm/rmap.c (ffffffff812537e2)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In lib/cpu_rmap.c (ffffffff81506e52)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81850c39)
Location: include/linux/cpumask.h:415
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
Location: include/linux/cpumask.h:415
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
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/sched/topology.c (ffffffff810ed849)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/affinity.c (ffffffff811159a3)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff8113b849)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff81162da2)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff81265a24)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In lib/cpu_rmap.c (ffffffff81535066)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81894179)
Location: include/linux/cpumask.h:415
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
Location: include/linux/cpumask.h:431
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
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/sched/topology.c (ffffffff810f93ea)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/affinity.c (ffffffff81121dad)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff81147459)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff8116ea6c)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff81274343)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In lib/cpu_rmap.c (ffffffff81555e76)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818c6199)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060c02)
Location: include/linux/cpumask.h:438
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
Location: include/linux/cpumask.h:438
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/sched/topology.c (ffffffff811034a1)
Location: include/linux/cpumask.h:438
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/affinity.c (ffffffff8112e378)
Location: include/linux/cpumask.h:438
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff811575c9)
Location: include/linux/cpumask.h:438
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff81180da1)
Location: include/linux/cpumask.h:438
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff812a55db)
Location: include/linux/cpumask.h:438
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In lib/cpu_rmap.c (ffffffff815df7e5)
Location: include/linux/cpumask.h:438
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81998219)
Location: include/linux/cpumask.h:438
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105f28a)
Location: include/linux/cpumask.h:444
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
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068082)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
```
```
In kernel/sched/topology.c (ffffffff81bdce18)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/affinity.c (ffffffff81129f68)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff81153699)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff8117dc71)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff812b0a32)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In lib/cpu_rmap.c (ffffffff815fcf85)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8199b339)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810619a4)
Location: include/linux/cpumask.h:415
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
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810685f2)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
```
```
In kernel/sched/topology.c (ffffffff81bcefb3)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/affinity.c (ffffffff8112a1e0)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff8115481d)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff8117dbfe)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff812b611f)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In lib/cpu_rmap.c (ffffffff815dfd0e)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8198001f)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106b695)
Location: include/linux/cpumask.h:415
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106f618)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81072d88)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
```
In kernel/sched/topology.c (ffffffff81ca768e)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/affinity.c (ffffffff8114ab3e)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff8117926d)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff811a592d)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff812f7ca3)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In lib/cpu_rmap.c (ffffffff8164b96c)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81a291bf)
Location: include/linux/cpumask.h:415
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810789ad)
Location: include/linux/cpumask.h:450
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107ce8f)
Location: include/linux/cpumask.h:450
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81080fb6)
Location: include/linux/cpumask.h:450
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
```
```
In kernel/sched/build_utility.c (ffffffff81e5942d)
Location: include/linux/cpumask.h:450
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/irq/affinity.c (ffffffff8117017d)
Location: include/linux/cpumask.h:450
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff811aebc8)
Location: include/linux/cpumask.h:450
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff811d6bbe)
Location: include/linux/cpumask.h:450
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff8135dad7)
Location: include/linux/cpumask.h:450
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In lib/cpu_rmap.c (ffffffff8176246c)
Location: include/linux/cpumask.h:450
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81b9321c)
Location: include/linux/cpumask.h:450
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
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
Location: include/linux/cpumask.h:515
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108e214)
Location: include/linux/cpumask.h:515
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108fd36)
Location: include/linux/cpumask.h:515
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In kernel/sched/build_utility.c (ffffffff811782ea)
Location: include/linux/cpumask.h:515
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/irq/affinity.c (ffffffff811a65d5)
Location: include/linux/cpumask.h:515
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff811eed7a)
Location: include/linux/cpumask.h:515
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff8121bed9)
Location: include/linux/cpumask.h:515
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff813d895b)
Location: include/linux/cpumask.h:515
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In lib/cpu_rmap.c (ffffffff8189135e)
Location: include/linux/cpumask.h:515
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d3388b)
Location: include/linux/cpumask.h:515
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
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
Location: include/linux/cpumask.h:579
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810910c4)
Location: include/linux/cpumask.h:579
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81092c4c)
Location: include/linux/cpumask.h:579
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In kernel/sched/build_utility.c (ffffffff81188f92)
Location: include/linux/cpumask.h:579
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/time/tick-broadcast.c (ffffffff81203ad5)
Location: include/linux/cpumask.h:579
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff81232217)
Location: include/linux/cpumask.h:579
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/bpf/cpumask.c (ffffffff8135d975)
Location: include/linux/cpumask.h:579
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_or
```
```
In mm/rmap.c (ffffffff8140ad66)
Location: include/linux/cpumask.h:579
Inline: True
Inline callers:
  - mm/rmap.c:set_tlb_ubc_flush_pending
```
```
In lib/cpu_rmap.c (ffffffff818d366e)
Location: include/linux/cpumask.h:579
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In lib/group_cpus.c (ffffffff818e7006)
Location: include/linux/cpumask.h:579
Inline: True
Inline callers:
  - lib/group_cpus.c:__group_cpus_evenly
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d9cc1b)
Location: include/linux/cpumask.h:579
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
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
Location: include/linux/cpumask.h:579
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81098484)
Location: include/linux/cpumask.h:579
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a08c)
Location: include/linux/cpumask.h:579
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In kernel/sched/build_utility.c (ffffffff81197885)
Location: include/linux/cpumask.h:579
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/rcu/tree.c (ffffffff83903a00)
Location: include/linux/cpumask.h:579
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_nohz
```
```
In kernel/time/tick-broadcast.c (ffffffff8121a095)
Location: include/linux/cpumask.h:579
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff81246371)
Location: include/linux/cpumask.h:579
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:partition_xcpus_del
  - kernel/cgroup/cpuset.c:partition_xcpus_add
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/bpf/cpumask.c (ffffffff81386715)
Location: include/linux/cpumask.h:579
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_or
```
```
In mm/rmap.c (ffffffff81437496)
Location: include/linux/cpumask.h:579
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff8192574e)
Location: include/linux/cpumask.h:579
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In lib/group_cpus.c (ffffffff8192e026)
Location: include/linux/cpumask.h:579
Inline: True
Inline callers:
  - lib/group_cpus.c:__group_cpus_evenly
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81e548db)
Location: include/linux/cpumask.h:579
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
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
In kernel/sched/topology.c (ffff80001015c6b8)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/irq/affinity.c (ffff800010187ff0)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffff8000101b2600)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffff8000101e23c8)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In lib/cpu_rmap.c (ffff800010662918)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffff800010b241f0)
Location: include/linux/cpumask.h:431
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
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - arch/arm/kernel/hw_breakpoint.c:reset_ctrl_regs
  - arch/arm/kernel/hw_breakpoint.c:reset_ctrl_regs
```
```
In kernel/sched/topology.c (c03a912c)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/irq/affinity.c (c03d6780)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (c03fcd54)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (c0424a8c)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In lib/cpu_rmap.c (c080b54c)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/cpufreq/cpufreq_ondemand.c (c0bfe280)
Location: include/linux/cpumask.h:431
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
Location: include/linux/cpumask.h:431
Inline: True
```
```
In arch/powerpc/mm/numa.c (c0000000000a3918)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
```
```
In kernel/sched/topology.c (c0000000001b0f10)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/irq/affinity.c (c0000000001e1dec)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (c000000000217d34)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (c000000000250934)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In lib/cpu_rmap.c (c000000000816aa4)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/cpufreq/cpufreq_ondemand.c (c000000000c18a80)
Location: include/linux/cpumask.h:431
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
In kernel/sched/topology.c (ffffffe0001018ea)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/affinity.c (ffffffe00011d6b8)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffe0001592a4)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In lib/cpu_rmap.c (ffffffe00048edbc)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
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
Location: include/linux/cpumask.h:431
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
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/sched/topology.c (ffffffff810f27ea)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/affinity.c (ffffffff8111a38d)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff8113fa79)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff8116708c)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff8126c993)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In lib/cpu_rmap.c (ffffffff8154e456)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8186a8b9)
Location: include/linux/cpumask.h:431
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
Location: include/linux/cpumask.h:431
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
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/sched/topology.c (ffffffff810e285a)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/affinity.c (ffffffff8110b3fd)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff828b0e9f)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_nohz
```
```
In kernel/time/tick-broadcast.c (ffffffff811327f9)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff8115a2bc)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff8125e9e3)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In lib/cpu_rmap.c (ffffffff8153e736)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81833569)
Location: include/linux/cpumask.h:431
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
Location: include/linux/cpumask.h:431
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
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/sched/topology.c (ffffffff810ef91a)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/affinity.c (ffffffff8111827d)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff8113d929)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff81164e5c)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff8126a733)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In lib/cpu_rmap.c (ffffffff8154a196)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818bb649)
Location: include/linux/cpumask.h:431
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
Location: include/linux/cpumask.h:431
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
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/sched/topology.c (ffffffff810fa96a)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/affinity.c (ffffffff8112390d)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff8114a439)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff811722f9)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In mm/rmap.c (ffffffff81279ed9)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In lib/cpu_rmap.c (ffffffff81563fe6)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818d7939)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
</details>
</li>
</ul>

## Differences
