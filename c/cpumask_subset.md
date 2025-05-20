# Function: <code>cpumask_subset</code>

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
In arch/x86/kernel/irq.c (ffffffff81030d99)
Location: include/linux/cpumask.h:445
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105511a)
Location: include/linux/cpumask.h:445
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In kernel/workqueue.c (ffffffff8109bb0e)
Location: include/linux/cpumask.h:445
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffff810a8814)
Location: include/linux/cpumask.h:445
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:build_sched_domain
```
```
In kernel/time/tick-broadcast.c (ffffffff810fcfa5)
Location: include/linux/cpumask.h:445
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cpuset.c (ffffffff8111b776)
Location: include/linux/cpumask.h:445
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/taskstats.c (ffffffff8113e48a)
Location: include/linux/cpumask.h:445
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
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
In arch/x86/kernel/irq.c (ffffffff8102ffc4)
Location: include/linux/cpumask.h:449
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810553d5)
Location: include/linux/cpumask.h:449
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In kernel/workqueue.c (ffffffff8109f133)
Location: include/linux/cpumask.h:449
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffff810b17d3)
Location: include/linux/cpumask.h:449
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domain
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/time/tick-broadcast.c (ffffffff811042eb)
Location: include/linux/cpumask.h:449
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cpuset.c (ffffffff81124721)
Location: include/linux/cpumask.h:449
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/taskstats.c (ffffffff81146ada)
Location: include/linux/cpumask.h:449
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
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
In arch/x86/kernel/irq.c (ffffffff8102ff81)
Location: include/linux/cpumask.h:449
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810581be)
Location: include/linux/cpumask.h:449
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In kernel/workqueue.c (ffffffff810a404c)
Location: include/linux/cpumask.h:449
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffff810b7a7c)
Location: include/linux/cpumask.h:449
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domain
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/time/tick-broadcast.c (ffffffff8110bb15)
Location: include/linux/cpumask.h:449
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cpuset.c (ffffffff8112db90)
Location: include/linux/cpumask.h:449
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/taskstats.c (ffffffff811509da)
Location: include/linux/cpumask.h:449
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
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
In arch/x86/kernel/irq.c (ffffffff8102e2b3)
Location: include/linux/cpumask.h:477
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81057879)
Location: include/linux/cpumask.h:477
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In kernel/workqueue.c (ffffffff810a1013)
Location: include/linux/cpumask.h:477
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffff810b2d2f)
Location: include/linux/cpumask.h:477
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/fair.c (ffffffff810c0d7c)
Location: include/linux/cpumask.h:477
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (ffffffff810cc3b0)
Location: include/linux/cpumask.h:477
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/time/tick-broadcast.c (ffffffff8110db52)
Location: include/linux/cpumask.h:477
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff8112f206)
Location: include/linux/cpumask.h:477
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/taskstats.c (ffffffff81152fda)
Location: include/linux/cpumask.h:477
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
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
In kernel/workqueue.c (ffffffff810a787f)
Location: include/linux/cpumask.h:481
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffff810ba12f)
Location: include/linux/cpumask.h:481
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/fair.c (ffffffff810c811b)
Location: include/linux/cpumask.h:481
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (ffffffff810d367c)
Location: include/linux/cpumask.h:481
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/time/tick-broadcast.c (ffffffff81118dd1)
Location: include/linux/cpumask.h:481
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff8113c0b2)
Location: include/linux/cpumask.h:481
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/taskstats.c (ffffffff8115f7fa)
Location: include/linux/cpumask.h:481
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
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
In kernel/workqueue.c (ffffffff810ae484)
Location: include/linux/cpumask.h:483
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffff810c16cf)
Location: include/linux/cpumask.h:483
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/fair.c (ffffffff810d0341)
Location: include/linux/cpumask.h:483
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
```
```
In kernel/sched/topology.c (ffffffff810db368)
Location: include/linux/cpumask.h:483
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/time/tick-broadcast.c (ffffffff81125951)
Location: include/linux/cpumask.h:483
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff8114a93f)
Location: include/linux/cpumask.h:483
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/taskstats.c (ffffffff8116e745)
Location: include/linux/cpumask.h:483
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105c27d)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In kernel/workqueue.c (ffffffff810b75e4)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffff810ca9ff)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/fair.c (ffffffff810d9b71)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
```
In kernel/sched/topology.c (ffffffff810e4f71)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/time/tick-broadcast.c (ffffffff81131041)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff8115872a)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/taskstats.c (ffffffff8117c215)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105f613)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In kernel/workqueue.c (ffffffff810bc98c)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffff810d26bb)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/fair.c (ffffffff810e10c9)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
```
In kernel/sched/topology.c (ffffffff810ebf23)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/time/tick-broadcast.c (ffffffff8113bb9e)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff81164e08)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/taskstats.c (ffffffff811890a5)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff816d0356)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105fea3)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8106906e)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/workqueue.c (ffffffff810c36dc)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffff810dcb2b)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/fair.c (ffffffff810eb75f)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
```
In kernel/sched/topology.c (ffffffff810f7af6)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/time/tick-broadcast.c (ffffffff811477ae)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff81170ce8)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/taskstats.c (ffffffff81194fe5)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff816f4176)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81065973)
Location: include/linux/cpumask.h:532
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8106f7c2)
Location: include/linux/cpumask.h:532
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:activate_reserved
```
```
In kernel/workqueue.c (ffffffff810caf53)
Location: include/linux/cpumask.h:532
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/sched/core.c (ffffffff810e575c)
Location: include/linux/cpumask.h:532
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/fair.c (ffffffff810f5092)
Location: include/linux/cpumask.h:532
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/topology.c (ffffffff81101f6b)
Location: include/linux/cpumask.h:532
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/cpuhotplug.c (ffffffff8112cbfe)
Location: include/linux/cpumask.h:532
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:hk_should_isolate
```
```
In kernel/time/tick-broadcast.c (ffffffff811574be)
Location: include/linux/cpumask.h:532
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff81182929)
Location: include/linux/cpumask.h:532
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/taskstats.c (ffffffff811aa0a5)
Location: include/linux/cpumask.h:532
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff817ac866)
Location: include/linux/cpumask.h:532
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81063c23)
Location: include/linux/cpumask.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81070ce2)
Location: include/linux/cpumask.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:activate_reserved
```
```
In kernel/workqueue.c (ffffffff810c6083)
Location: include/linux/cpumask.h:538
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/sched/core.c (ffffffff810e3365)
Location: include/linux/cpumask.h:538
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/fair.c (ffffffff810f3124)
Location: include/linux/cpumask.h:538
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/deadline.c (ffffffff810fd183)
Location: include/linux/cpumask.h:538
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/sched/topology.c (ffffffff81100b64)
Location: include/linux/cpumask.h:538
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/cpuhotplug.c (ffffffff8112862e)
Location: include/linux/cpumask.h:538
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:hk_should_isolate
```
```
In kernel/time/tick-broadcast.c (ffffffff8115358e)
Location: include/linux/cpumask.h:538
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff8117f85b)
Location: include/linux/cpumask.h:538
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/taskstats.c (ffffffff811a765b)
Location: include/linux/cpumask.h:538
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff817c1471)
Location: include/linux/cpumask.h:538
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810642c3)
Location: include/linux/cpumask.h:509
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8107157b)
Location: include/linux/cpumask.h:509
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/workqueue.c (ffffffff810c79a5)
Location: include/linux/cpumask.h:509
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/sched/core.c (ffffffff810e5501)
Location: include/linux/cpumask.h:509
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/fair.c (ffffffff810f5471)
Location: include/linux/cpumask.h:509
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/deadline.c (ffffffff810ff532)
Location: include/linux/cpumask.h:509
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/sched/topology.c (ffffffff81102cac)
Location: include/linux/cpumask.h:509
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/cpuhotplug.c (ffffffff81128a3f)
Location: include/linux/cpumask.h:509
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff81154a4e)
Location: include/linux/cpumask.h:509
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff8117fe9b)
Location: include/linux/cpumask.h:509
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/taskstats.c (ffffffff811a803b)
Location: include/linux/cpumask.h:509
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff817a49d1)
Location: include/linux/cpumask.h:509
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106e2b3)
Location: include/linux/cpumask.h:509
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8107d36b)
Location: include/linux/cpumask.h:509
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/workqueue.c (ffffffff810da711)
Location: include/linux/cpumask.h:509
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/sched/core.c (ffffffff810fc40e)
Location: include/linux/cpumask.h:509
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
```
```
In kernel/sched/fair.c (ffffffff8110ee66)
Location: include/linux/cpumask.h:509
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/deadline.c (ffffffff8111b578)
Location: include/linux/cpumask.h:509
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/sched/topology.c (ffffffff8111f852)
Location: include/linux/cpumask.h:509
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/cpuhotplug.c (ffffffff8114901f)
Location: include/linux/cpumask.h:509
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff811796b4)
Location: include/linux/cpumask.h:509
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff811a83e3)
Location: include/linux/cpumask.h:509
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/taskstats.c (ffffffff811d1dfb)
Location: include/linux/cpumask.h:509
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff8182e1e1)
Location: include/linux/cpumask.h:509
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107bb03)
Location: include/linux/cpumask.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8108ca36)
Location: include/linux/cpumask.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/workqueue.c (ffffffff810f3ed3)
Location: include/linux/cpumask.h:544
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/sched/core.c (ffffffff811189a1)
Location: include/linux/cpumask.h:544
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
```
```
In kernel/sched/fair.c (ffffffff8112aebc)
Location: include/linux/cpumask.h:544
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/build_policy.c (ffffffff8113b358)
Location: include/linux/cpumask.h:544
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:task_non_contending
```
```
In kernel/sched/build_utility.c (ffffffff81149851)
Location: include/linux/cpumask.h:544
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/irq/cpuhotplug.c (ffffffff8116dba2)
Location: include/linux/cpumask.h:544
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff811aea77)
Location: include/linux/cpumask.h:544
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff811d951a)
Location: include/linux/cpumask.h:544
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:is_cpuset_subset
```
```
In kernel/taskstats.c (ffffffff81206627)
Location: include/linux/cpumask.h:544
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff8196edb1)
Location: include/linux/cpumask.h:544
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108cf20)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810a1036)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/workqueue.c (ffffffff8111611d)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/sched/core.c (ffffffff811400dd)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
```
```
In kernel/sched/fair.c (ffffffff81154b0d)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/build_policy.c (ffffffff81165d10)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:task_non_contending
```
```
In kernel/sched/build_utility.c (ffffffff811781fe)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/irq/cpuhotplug.c (ffffffff811a2dd2)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff811ef3e0)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff8121e90a)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:is_cpuset_subset
```
```
In kernel/taskstats.c (ffffffff8124ea37)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81ad97e1)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108fd23)
Location: include/linux/cpumask.h:661
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810a4026)
Location: include/linux/cpumask.h:661
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/workqueue.c (ffffffff81122ebd)
Location: include/linux/cpumask.h:661
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/sched/core.c (ffffffff8114f3f5)
Location: include/linux/cpumask.h:661
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
```
```
In kernel/sched/fair.c (ffffffff81164c8a)
Location: include/linux/cpumask.h:661
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/build_policy.c (ffffffff8116d3fd)
Location: include/linux/cpumask.h:661
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:task_non_contending
```
```
In kernel/sched/build_utility.c (ffffffff81188ea5)
Location: include/linux/cpumask.h:661
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/irq/cpuhotplug.c (ffffffff811b4cd2)
Location: include/linux/cpumask.h:661
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff81203940)
Location: include/linux/cpumask.h:661
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff812349fa)
Location: include/linux/cpumask.h:661
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:is_cpuset_subset
```
```
In kernel/taskstats.c (ffffffff81265de7)
Location: include/linux/cpumask.h:661
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/bpf/cpumask.c (ffffffff8135da55)
Location: include/linux/cpumask.h:661
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_subset
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81b27961)
Location: include/linux/cpumask.h:661
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810970b3)
Location: include/linux/cpumask.h:669
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810ab056)
Location: include/linux/cpumask.h:669
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/workqueue.c (ffffffff8112cdc4)
Location: include/linux/cpumask.h:669
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/sched/core.c (ffffffff8115b295)
Location: include/linux/cpumask.h:669
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
```
```
In kernel/sched/fair.c (ffffffff8117181a)
Location: include/linux/cpumask.h:669
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/build_policy.c (ffffffff81179b5e)
Location: include/linux/cpumask.h:669
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:task_non_contending
```
```
In kernel/sched/build_utility.c (ffffffff8119779a)
Location: include/linux/cpumask.h:669
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/irq/cpuhotplug.c (ffffffff811c4b52)
Location: include/linux/cpumask.h:669
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
```
In kernel/rcu/tree.c (ffffffff83903a49)
Location: include/linux/cpumask.h:669
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_nohz
```
```
In kernel/time/tick-broadcast.c (ffffffff81219f00)
Location: include/linux/cpumask.h:669
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff8124e61a)
Location: include/linux/cpumask.h:669
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:compute_partition_effective_cpumask
  - kernel/cgroup/cpuset.c:compute_partition_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:prstate_housekeeping_conflict
  - kernel/cgroup/cpuset.c:remote_cpus_update
  - kernel/cgroup/cpuset.c:remote_cpus_update
  - kernel/cgroup/cpuset.c:remote_partition_disable
  - kernel/cgroup/cpuset.c:tasks_nocpu_error
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:is_cpuset_subset
```
```
In kernel/taskstats.c (ffffffff8127fca7)
Location: include/linux/cpumask.h:669
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/bpf/cpumask.c (ffffffff813867f5)
Location: include/linux/cpumask.h:669
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_subset
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81b7e821)
Location: include/linux/cpumask.h:669
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
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
In kernel/workqueue.c (ffff8000101213a0)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffff80001013c65c)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/fair.c (ffff80001014b910)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
```
In kernel/sched/topology.c (ffff80001015be74)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/time/tick-broadcast.c (ffff8000101b2968)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffff8000101e424c)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/taskstats.c (ffff80001020cf20)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In drivers/base/arch_topology.c (ffff800010920524)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:cpu_coregroup_mask
  - drivers/base/arch_topology.c:cpu_coregroup_mask
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
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:525
Inline: True
```
```
In kernel/sched/core.c (c038ca24)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/fair.c (c0399624)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
```
In kernel/sched/topology.c (c03a88e0)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/time/tick-broadcast.c (c03fd108)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (c04251c0)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/taskstats.c (c044b8d8)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In drivers/base/arch_topology.c (c0a05448)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:cpu_coregroup_mask
  - drivers/base/arch_topology.c:cpu_coregroup_mask
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
In arch/powerpc/mm/numa.c (c0000000000a3540)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
```
```
In arch/powerpc/sysdev/xics/xics-common.c (c0000000000ba7a8)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/xics-common.c:xics_get_irq_server
```
```
In arch/powerpc/platforms/pseries/hotplug-cpu.c (c0000000000f9fcc)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
```
```
In kernel/workqueue.c (c00000000016a9c8)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (c00000000018acd0)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/fair.c (c00000000019dfe4)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
```
In kernel/sched/topology.c (c0000000001b0698)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/time/tick-broadcast.c (c0000000002183bc)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (c000000000254960)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/taskstats.c (c00000000028abec)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
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
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:525
Inline: True
```
```
In kernel/sched/core.c (ffffffe0000ebe6c)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/fair.c (ffffffe0000f512e)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
```
In kernel/sched/topology.c (ffffffe000100fea)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/cgroup/cpuset.c (ffffffe00015a3f0)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/taskstats.c (ffffffe00016e0ee)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In drivers/base/arch_topology.c (ffffffe00059f01a)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:cpu_coregroup_mask
  - drivers/base/arch_topology.c:cpu_coregroup_mask
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105fa23)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81068b5e)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/workqueue.c (ffffffff810bda4c)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffff810d6d3b)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/fair.c (ffffffff810e58bf)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
```
In kernel/sched/topology.c (ffffffff810f0ef6)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/time/tick-broadcast.c (ffffffff8113fdce)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff81169308)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/taskstats.c (ffffffff8118d605)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff816b9966)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8104fd53)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81058ece)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/workqueue.c (ffffffff810ac27c)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffff810c562b)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/fair.c (ffffffff810d4a69)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
```
In kernel/sched/topology.c (ffffffff810e0f66)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/rcu/tree.c (ffffffff828b0eb4)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_nohz
```
```
In kernel/time/tick-broadcast.c (ffffffff81132b4e)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff8115c50c)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/taskstats.c (ffffffff81180725)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff816975a6)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105fe53)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8106900e)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/workqueue.c (ffffffff810bcfac)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffff810d397b)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/fair.c (ffffffff810e1c8f)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
```
In kernel/sched/topology.c (ffffffff810ee026)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/time/tick-broadcast.c (ffffffff8113dc7e)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff811670d8)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/taskstats.c (ffffffff8118b3d5)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff816e7e36)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810613b3)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8106a712)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/workqueue.c (ffffffff810c532c)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffff810de912)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/fair.c (ffffffff810ed84e)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
```
In kernel/sched/topology.c (ffffffff810f9066)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/time/tick-broadcast.c (ffffffff8114a78e)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff811746b9)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/taskstats.c (ffffffff81198d45)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81702536)
Location: include/linux/cpumask.h:525
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
</details>
</li>
</ul>

## Differences
