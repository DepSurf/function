# Function: <code>__bitmap_subset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __bitmap_subset(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff813f9020)
Location: lib/bitmap.c:222
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:build_sched_domain
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/taskstats.c:add_del_listener
  - drivers/input/input.c:input_attach_handler
  - drivers/input/input.c:input_attach_handler
```
**Symbols:**

```
ffffffff813f9020-ffffffff813f9094: __bitmap_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __bitmap_subset(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8143fef0)
Location: lib/bitmap.c:224
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:build_sched_domain
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/taskstats.c:add_del_listener
  - drivers/input/input.c:input_attach_handler
  - drivers/input/input.c:input_attach_handler
```
**Symbols:**

```
ffffffff8143fef0-ffffffff8143ff6a: __bitmap_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __bitmap_subset(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8145cff0)
Location: lib/bitmap.c:224
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:build_sched_domain
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/taskstats.c:add_del_listener
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/mempolicy.c:SYSC_migrate_pages
  - drivers/input/input.c:input_attach_handler
  - drivers/input/input.c:input_attach_handler
```
**Symbols:**

```
ffffffff8145cff0-ffffffff8145d06a: __bitmap_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __bitmap_subset(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81462280)
Location: lib/bitmap.c:224
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/fair.c:load_balance
  - kernel/sched/topology.c:build_sched_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/taskstats.c:add_del_listener
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/mempolicy.c:SYSC_migrate_pages
  - drivers/input/input.c:input_attach_handler
  - drivers/input/input.c:input_attach_handler
```
**Symbols:**

```
ffffffff81462280-ffffffff814622f8: __bitmap_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __bitmap_subset(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8148e160)
Location: lib/bitmap.c:226
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/fair.c:load_balance
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/taskstats.c:add_del_listener
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/mempolicy.c:SYSC_migrate_pages
```
**Symbols:**

```
ffffffff8148e160-ffffffff8148e1d8: __bitmap_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __bitmap_subset(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814c2e80)
Location: lib/bitmap.c:223
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/taskstats.c:add_del_listener
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
```
**Symbols:**

```
ffffffff814c2e80-ffffffff814c2ef2: __bitmap_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __bitmap_subset(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814d7530)
Location: lib/bitmap.c:220
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/taskstats.c:add_del_listener
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
```
**Symbols:**

```
ffffffff814d7530-ffffffff814d75a2: __bitmap_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __bitmap_subset(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81503390)
Location: lib/bitmap.c:220
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domain_debug_one
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/taskstats.c:add_del_listener
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff81503390-ffffffff815033f6: __bitmap_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __bitmap_subset(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81521330)
Location: lib/bitmap.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/taskstats.c:add_del_listener
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff81521330-ffffffff81521396: __bitmap_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __bitmap_subset(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81584550)
Location: lib/bitmap.c:319
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - arch/x86/kernel/apic/vector.c:activate_reserved
  - kernel/workqueue.c:get_unbound_pool
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/fair.c:load_balance
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/cpuhotplug.c:hk_should_isolate
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/taskstats.c:add_del_listener
  - mm/oom_kill.c:constrained_alloc
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
  - drivers/input/input.c:input_match_device_id
  - drivers/input/input.c:input_match_device_id
```
**Symbols:**

```
ffffffff81584550-ffffffff815845b7: __bitmap_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __bitmap_subset(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a1660)
Location: lib/bitmap.c:319
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - arch/x86/kernel/apic/vector.c:activate_reserved
  - kernel/workqueue.c:get_unbound_pool
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/fair.c:load_balance
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/cpuhotplug.c:hk_should_isolate
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/taskstats.c:add_del_listener
  - mm/oom_kill.c:constrained_alloc
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
  - drivers/input/input.c:input_match_device_id
  - drivers/input/input.c:input_match_device_id
```
**Symbols:**

```
ffffffff815a1660-ffffffff815a16c7: __bitmap_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __bitmap_subset(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a8510)
Location: lib/bitmap.c:321
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - kernel/workqueue.c:get_unbound_pool
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/fair.c:load_balance
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/taskstats.c:add_del_listener
  - mm/oom_kill.c:constrained_alloc
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
  - drivers/input/input.c:input_match_device_id
  - drivers/input/input.c:input_match_device_id
```
**Symbols:**

```
ffffffff815a8510-ffffffff815a857d: __bitmap_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __bitmap_subset(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816114d0)
Location: lib/bitmap.c:321
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - kernel/workqueue.c:get_unbound_pool
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/fair.c:load_balance
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/taskstats.c:add_del_listener
  - mm/oom_kill.c:constrained_alloc
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
  - drivers/input/input.c:input_match_device_id
  - drivers/input/input.c:input_match_device_id
```
**Symbols:**

```
ffffffff816114d0-ffffffff8161153d: __bitmap_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __bitmap_subset(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816dd5e0)
Location: lib/bitmap.c:321
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - kernel/workqueue.c:get_unbound_pool
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/fair.c:load_balance
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:is_cpuset_subset
  - kernel/cgroup/cpuset.c:is_cpuset_subset
  - kernel/taskstats.c:add_del_listener
  - mm/oom_kill.c:constrained_alloc
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
  - drivers/input/input.c:input_match_device_id
  - drivers/input/input.c:input_match_device_id
```
**Symbols:**

```
ffffffff816dd5e0-ffffffff816dd666: __bitmap_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __bitmap_subset(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff817cd4e0)
Location: lib/bitmap.c:321
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - kernel/workqueue.c:get_unbound_pool
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/fair.c:load_balance
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:is_cpuset_subset
  - kernel/cgroup/cpuset.c:is_cpuset_subset
  - kernel/taskstats.c:add_del_listener
  - mm/oom_kill.c:constrained_alloc
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
  - drivers/input/input.c:input_match_device_id
  - drivers/input/input.c:input_match_device_id
```
**Symbols:**

```
ffffffff817cd4e0-ffffffff817cd566: __bitmap_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __bitmap_subset(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8180b8f0)
Location: lib/bitmap.c:321
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - kernel/workqueue.c:get_unbound_pool
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/fair.c:load_balance
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:is_cpuset_subset
  - kernel/cgroup/cpuset.c:is_cpuset_subset
  - kernel/taskstats.c:add_del_listener
  - kernel/bpf/cpumask.c:bpf_cpumask_subset
  - mm/oom_kill.c:constrained_alloc
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
  - drivers/input/input.c:input_match_device_id
  - drivers/input/input.c:input_match_device_id
```
**Symbols:**

```
ffffffff8180b8f0-ffffffff8180b976: __bitmap_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __bitmap_subset(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff818520d0)
Location: lib/bitmap.c:310
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - kernel/workqueue.c:get_unbound_pool
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/fair.c:load_balance
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/rcu/tree.c:rcu_init_nohz
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed_fallback
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
  - kernel/cgroup/cpuset.c:is_cpuset_subset
  - kernel/taskstats.c:add_del_listener
  - kernel/bpf/cpumask.c:bpf_cpumask_subset
  - mm/oom_kill.c:constrained_alloc
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
  - drivers/input/input.c:input_match_device_id
  - drivers/input/input.c:input_match_device_id
```
**Symbols:**

```
ffffffff818520d0-ffffffff81852156: __bitmap_subset (STB_GLOBAL)
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
int __bitmap_subset(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffff80001062aa00)
Location: lib/bitmap.c:240
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/taskstats.c:add_del_listener
  - drivers/base/arch_topology.c:cpu_coregroup_mask
  - drivers/base/arch_topology.c:cpu_coregroup_mask
```
**Symbols:**

```
ffff80001062aa00-ffff80001062aa78: __bitmap_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __bitmap_subset(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c07d1c00)
Location: lib/bitmap.c:240
Inline: False
```
**Symbols:**

```
c07d1c00-c07d1c80: __bitmap_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __bitmap_subset(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c0000000007ccb00)
Location: lib/bitmap.c:240
Inline: False
Direct callers:
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
  - arch/powerpc/sysdev/xics/xics-common.c:xics_get_irq_server
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/taskstats.c:add_del_listener
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
```
**Symbols:**

```
c0000000007ccb00-c0000000007ccb8c: __bitmap_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __bitmap_subset(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffe00045b33e)
Location: lib/bitmap.c:240
Inline: False
```
**Symbols:**

```
ffffffe00045b33e-ffffffe00045b3b2: __bitmap_subset (STB_GLOBAL)
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
int __bitmap_subset(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81519910)
Location: lib/bitmap.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/taskstats.c:add_del_listener
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff81519910-ffffffff81519976: __bitmap_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __bitmap_subset(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81509c00)
Location: lib/bitmap.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/rcu/tree.c:rcu_init_nohz
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/taskstats.c:add_del_listener
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff81509c00-ffffffff81509c66: __bitmap_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __bitmap_subset(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815159a0)
Location: lib/bitmap.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/taskstats.c:add_del_listener
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff815159a0-ffffffff81515a06: __bitmap_subset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __bitmap_subset(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8152f130)
Location: lib/bitmap.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_mmap
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/taskstats.c:add_del_listener
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:kernel_migrate_pages
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff8152f130-ffffffff8152f196: __bitmap_subset (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
