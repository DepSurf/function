# Function: <code>__bitmap_intersects</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __bitmap_intersects(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff813f8fb0)
Location: lib/bitmap.c:207
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/irq/manage.c:setup_affinity
  - kernel/irq/manage.c:setup_affinity
  - kernel/irq/proc.c:default_affinity_write
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:guarantee_online_cpus
```
**Symbols:**

```
ffffffff813f8fb0-ffffffff813f901d: __bitmap_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __bitmap_intersects(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8143fe70)
Location: lib/bitmap.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/irq/manage.c:setup_affinity
  - kernel/irq/manage.c:setup_affinity
  - kernel/irq/proc.c:default_affinity_write
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_cpu_callback
  - kernel/padata.c:padata_cpu_callback
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff8143fe70-ffffffff8143fee3: __bitmap_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __bitmap_intersects(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8145cf70)
Location: lib/bitmap.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/irq/manage.c:setup_affinity
  - kernel/irq/manage.c:setup_affinity
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cpuset.c:cpuset_change_task_nodemask
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:guarantee_online_mems
  - mm/mempolicy.c:mempolicy_nodemask_intersects
```
**Symbols:**

```
ffffffff8145cf70-ffffffff8145cfe3: __bitmap_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __bitmap_intersects(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81462200)
Location: lib/bitmap.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_mems
  - mm/mempolicy.c:mempolicy_nodemask_intersects
```
**Symbols:**

```
ffffffff81462200-ffffffff81462272: __bitmap_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __bitmap_intersects(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8148e0e0)
Location: lib/bitmap.c:211
Inline: False
Direct callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_mems
  - mm/mempolicy.c:mempolicy_nodemask_intersects
```
**Symbols:**

```
ffffffff8148e0e0-ffffffff8148e152: __bitmap_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __bitmap_intersects(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814c2e10)
Location: lib/bitmap.c:208
Inline: False
Direct callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/proc.c:default_affinity_write
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:guarantee_online_mems
  - mm/mempolicy.c:mempolicy_nodemask_intersects
```
**Symbols:**

```
ffffffff814c2e10-ffffffff814c2e7c: __bitmap_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __bitmap_intersects(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814d74c0)
Location: lib/bitmap.c:205
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/proc.c:default_affinity_write
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:guarantee_online_mems
  - mm/mempolicy.c:mempolicy_nodemask_intersects
```
**Symbols:**

```
ffffffff814d74c0-ffffffff814d752c: __bitmap_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __bitmap_intersects(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81503320)
Location: lib/bitmap.c:205
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/topology.c:sched_domain_debug_one
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_mems
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
```
**Symbols:**

```
ffffffff81503320-ffffffff81503383: __bitmap_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __bitmap_intersects(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815212c0)
Location: lib/bitmap.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_mems
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
```
**Symbols:**

```
ffffffff815212c0-ffffffff81521323: __bitmap_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __bitmap_intersects(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815844f0)
Location: lib/bitmap.c:304
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/affinity.c:get_nodes_in_cpumask
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
  - kernel/padata.c:padata_validate_cpumask
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32
```
**Symbols:**

```
ffffffff815844f0-ffffffff81584549: __bitmap_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __bitmap_intersects(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a1600)
Location: lib/bitmap.c:304
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/affinity.c:get_nodes_in_cpumask
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
  - kernel/padata.c:padata_validate_cpumask
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32
```
**Symbols:**

```
ffffffff815a1600-ffffffff815a1659: __bitmap_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __bitmap_intersects(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a84b0)
Location: lib/bitmap.c:306
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
  - kernel/padata.c:padata_validate_cpumask
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32
```
**Symbols:**

```
ffffffff815a84b0-ffffffff815a850e: __bitmap_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __bitmap_intersects(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81611470)
Location: lib/bitmap.c:306
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sd_init
  - kernel/sched/topology.c:sd_init
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
  - kernel/padata.c:padata_validate_cpumask
  - mm/mempolicy.c:mempolicy_in_oom_domain
  - mm/mempolicy.c:policy_nodemask
  - net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32
```
**Symbols:**

```
ffffffff81611470-ffffffff816114ce: __bitmap_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __bitmap_intersects(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816dd550)
Location: lib/bitmap.c:306
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
  - kernel/workqueue.c:unbind_workers
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:sd_init
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
  - kernel/padata.c:padata_validate_cpumask
  - mm/mempolicy.c:mempolicy_in_oom_domain
  - mm/mempolicy.c:policy_nodemask
  - net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32
```
**Symbols:**

```
ffffffff816dd550-ffffffff816dd5d4: __bitmap_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __bitmap_intersects(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff817cd440)
Location: lib/bitmap.c:306
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
  - kernel/workqueue.c:unbind_workers
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
  - kernel/padata.c:padata_validate_cpumask
  - mm/mempolicy.c:mempolicy_in_oom_domain
  - mm/mempolicy.c:policy_nodemask
```
**Symbols:**

```
ffffffff817cd440-ffffffff817cd4c4: __bitmap_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __bitmap_intersects(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8180b850)
Location: lib/bitmap.c:306
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
  - kernel/workqueue.c:unbind_worker
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_fork
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
  - kernel/bpf/cpumask.c:bpf_cpumask_intersects
  - kernel/padata.c:padata_validate_cpumask
  - mm/mempolicy.c:mempolicy_in_oom_domain
  - mm/mempolicy.c:policy_nodemask
  - lib/group_cpus.c:__group_cpus_evenly
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv
```
**Symbols:**

```
ffffffff8180b850-ffffffff8180b8d4: __bitmap_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __bitmap_intersects(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81852030)
Location: lib/bitmap.c:295
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
  - kernel/workqueue.c:restrict_unbound_cpumask
  - kernel/workqueue.c:unbind_worker
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_fork
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:remote_cpus_update
  - kernel/cgroup/cpuset.c:tasks_nocpu_error
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
  - kernel/trace/trace_events_filter.c:filter_pred_fn_call
  - kernel/bpf/cpumask.c:bpf_cpumask_intersects
  - kernel/padata.c:padata_validate_cpumask
  - mm/mempolicy.c:mempolicy_in_oom_domain
  - mm/mempolicy.c:policy_nodemask
  - lib/group_cpus.c:__group_cpus_evenly
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv
```
**Symbols:**

```
ffffffff81852030-ffffffff818520b4: __bitmap_intersects (STB_GLOBAL)
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
int __bitmap_intersects(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffff80001062a988)
Location: lib/bitmap.c:225
Inline: False
Direct callers:
  - arch/arm64/kernel/fpsimd.c:sve_verify_vq_map
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - mm/sparse.c:sparse_add_section
  - drivers/irqchip/irq-gic-v3-its.c:its_set_affinity
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
```
**Symbols:**

```
ffff80001062a988-ffff80001062aa00: __bitmap_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __bitmap_intersects(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c07d1b80)
Location: lib/bitmap.c:225
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
```
**Symbols:**

```
c07d1b80-c07d1c00: __bitmap_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __bitmap_intersects(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c0000000007cca70)
Location: lib/bitmap.c:225
Inline: False
Direct callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_mems
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
```
**Symbols:**

```
c0000000007cca70-c0000000007ccafc: __bitmap_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __bitmap_intersects(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffe00045b2d4)
Location: lib/bitmap.c:225
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
```
**Symbols:**

```
ffffffe00045b2d4-ffffffe00045b33e: __bitmap_intersects (STB_GLOBAL)
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
int __bitmap_intersects(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815198a0)
Location: lib/bitmap.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_mems
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
```
**Symbols:**

```
ffffffff815198a0-ffffffff81519903: __bitmap_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __bitmap_intersects(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81509b90)
Location: lib/bitmap.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_mems
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
```
**Symbols:**

```
ffffffff81509b90-ffffffff81509bf3: __bitmap_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __bitmap_intersects(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81515930)
Location: lib/bitmap.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_mems
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
```
**Symbols:**

```
ffffffff81515930-ffffffff81515993: __bitmap_intersects (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __bitmap_intersects(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8152f0c0)
Location: lib/bitmap.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_mems
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
```
**Symbols:**

```
ffffffff8152f0c0-ffffffff8152f123: __bitmap_intersects (STB_GLOBAL)
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
