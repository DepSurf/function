# Function: <code>bitmap_intersects</code>

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
In arch/x86/kernel/apic/vector.c (ffffffff81055084)
Location: include/linux/bitmap.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
```
```
In kernel/sched/core.c (ffffffff810a873e)
Location: include/linux/bitmap.h:264
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:task_can_attach
```
```
In kernel/sched/fair.c (ffffffff810b3273)
Location: include/linux/bitmap.h:264
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/deadline.c (ffffffff810c16f3)
Location: include/linux/bitmap.h:264
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/irq/manage.c (ffffffff810dc052)
Location: include/linux/bitmap.h:264
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_affinity
  - kernel/irq/manage.c:setup_affinity
```
```
In kernel/irq/proc.c (ffffffff810e1be0)
Location: include/linux/bitmap.h:264
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/cpuset.c (ffffffff8111a9f3)
Location: include/linux/bitmap.h:264
Inline: True
Inline callers:
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:guarantee_online_cpus
```
```
In kernel/padata.c (ffffffff8118a146)
Location: include/linux/bitmap.h:264
Inline: True
```
```
In mm/mempolicy.c (ffffffff811e1fa6)
Location: include/linux/bitmap.h:264
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
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
In arch/x86/kernel/apic/vector.c (ffffffff810556e6)
Location: include/linux/bitmap.h:277
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In kernel/sched/core.c (ffffffff810ab2e3)
Location: include/linux/bitmap.h:277
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810b6154)
Location: include/linux/bitmap.h:277
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/deadline.c (ffffffff810c51a3)
Location: include/linux/bitmap.h:277
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/irq/manage.c (ffffffff810e173e)
Location: include/linux/bitmap.h:277
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_affinity
  - kernel/irq/manage.c:setup_affinity
```
```
In kernel/irq/proc.c (ffffffff810e7680)
Location: include/linux/bitmap.h:277
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/cpuset.c (ffffffff81125715)
Location: include/linux/bitmap.h:277
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cpuset.c:cpuset_change_task_nodemask
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
```
```
In kernel/padata.c (ffffffff8119d0e0)
Location: include/linux/bitmap.h:277
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_cpu_callback
  - kernel/padata.c:padata_cpu_callback
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/mempolicy.c (ffffffff81200996)
Location: include/linux/bitmap.h:277
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
```
```
In net/core/ethtool.c (ffffffff81788bf8)
Location: include/linux/bitmap.h:277
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int bitmap_intersects(const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81058436)
Location: include/linux/bitmap.h:277
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In kernel/sched/core.c (ffffffff810b74a9)
Location: include/linux/bitmap.h:277
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
Direct callers:
  - kernel/sched/core.c:cpu_attach_domain
```
```
In kernel/sched/fair.c (ffffffff810c4c2f)
Location: include/linux/bitmap.h:277
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/deadline.c (ffffffff810cb1cf)
Location: include/linux/bitmap.h:277
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/irq/manage.c (ffffffff810e80ac)
Location: include/linux/bitmap.h:277
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_affinity
  - kernel/irq/manage.c:setup_affinity
```
```
In kernel/irq/proc.c (ffffffff810ee3f2)
Location: include/linux/bitmap.h:277
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff810ef9cd)
Location: include/linux/bitmap.h:277
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/cpuset.c (ffffffff8112f104)
Location: include/linux/bitmap.h:277
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cpuset.c:cpuset_change_task_nodemask
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:guarantee_online_mems
```
```
In kernel/padata.c (ffffffff811abe16)
Location: include/linux/bitmap.h:277
Inline: True
```
```
In mm/mempolicy.c (ffffffff812123aa)
Location: include/linux/bitmap.h:277
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
```
```
In net/core/ethtool.c (ffffffff817b64a8)
Location: include/linux/bitmap.h:277
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
```
**Symbols:**

```
ffffffff810afe70-ffffffff810afe7b: bitmap_intersects (STB_LOCAL)
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
In arch/x86/kernel/apic/vector.c (ffffffff81057b16)
Location: include/linux/bitmap.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In kernel/sched/core.c (ffffffff810b375f)
Location: include/linux/bitmap.h:274
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810b7acc)
Location: include/linux/bitmap.h:274
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/deadline.c (ffffffff810c5b82)
Location: include/linux/bitmap.h:274
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff810cb7cb)
Location: include/linux/bitmap.h:274
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/manage.c (ffffffff810e77c2)
Location: include/linux/bitmap.h:274
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (ffffffff810edc3b)
Location: include/linux/bitmap.h:274
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff810ef997)
Location: include/linux/bitmap.h:274
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff81130784)
Location: include/linux/bitmap.h:274
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/padata.c (ffffffff811b3276)
Location: include/linux/bitmap.h:274
Inline: True
```
```
In mm/mempolicy.c (ffffffff8121d73a)
Location: include/linux/bitmap.h:274
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
```
```
In net/core/ethtool.c (ffffffff817d510a)
Location: include/linux/bitmap.h:274
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
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
In kernel/sched/core.c (ffffffff810ba9cf)
Location: include/linux/bitmap.h:292
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810bee95)
Location: include/linux/bitmap.h:292
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/deadline.c (ffffffff810cd292)
Location: include/linux/bitmap.h:292
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff810d2f75)
Location: include/linux/bitmap.h:292
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/manage.c (ffffffff810efb42)
Location: include/linux/bitmap.h:292
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (ffffffff810f667b)
Location: include/linux/bitmap.h:292
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff810f857e)
Location: include/linux/bitmap.h:292
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff8113d6b4)
Location: include/linux/bitmap.h:292
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/padata.c (ffffffff811c6ec6)
Location: include/linux/bitmap.h:292
Inline: True
```
```
In mm/mempolicy.c (ffffffff8123892a)
Location: include/linux/bitmap.h:292
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
```
```
In net/core/ethtool.c (ffffffff8184f5c5)
Location: include/linux/bitmap.h:292
Inline: True
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
In kernel/sched/core.c (ffffffff810c1e2c)
Location: include/linux/bitmap.h:323
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810c72a6)
Location: include/linux/bitmap.h:323
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/deadline.c (ffffffff810d5154)
Location: include/linux/bitmap.h:323
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff810dcdeb)
Location: include/linux/bitmap.h:323
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/manage.c (ffffffff810f7f9e)
Location: include/linux/bitmap.h:323
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (ffffffff810fe99b)
Location: include/linux/bitmap.h:323
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff811007ad)
Location: include/linux/bitmap.h:323
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff8114bfd5)
Location: include/linux/bitmap.h:323
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/padata.c (ffffffff811e7115)
Location: include/linux/bitmap.h:323
Inline: True
```
```
In mm/mempolicy.c (ffffffff8125be49)
Location: include/linux/bitmap.h:323
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
```
```
In net/core/ethtool.c (ffffffff81899cbc)
Location: include/linux/bitmap.h:323
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_settings
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810579a6)
Location: include/linux/bitmap.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105d41d)
Location: include/linux/bitmap.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
```
```
In kernel/sched/core.c (ffffffff810cb15c)
Location: include/linux/bitmap.h:324
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810cf9a3)
Location: include/linux/bitmap.h:324
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/deadline.c (ffffffff810deb84)
Location: include/linux/bitmap.h:324
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff810e6a4b)
Location: include/linux/bitmap.h:324
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/manage.c (ffffffff81103710)
Location: include/linux/bitmap.h:324
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (ffffffff8110a16b)
Location: include/linux/bitmap.h:324
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff8110bf66)
Location: include/linux/bitmap.h:324
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff81158c25)
Location: include/linux/bitmap.h:324
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/padata.c (ffffffff811f7e65)
Location: include/linux/bitmap.h:324
Inline: True
```
```
In mm/mempolicy.c (ffffffff81270709)
Location: include/linux/bitmap.h:324
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
```
```
In net/core/ethtool.c (ffffffff818bc705)
Location: include/linux/bitmap.h:324
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ac09)
Location: include/linux/bitmap.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106079d)
Location: include/linux/bitmap.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
```
```
In kernel/sched/core.c (ffffffff810d2e07)
Location: include/linux/bitmap.h:324
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810d6eec)
Location: include/linux/bitmap.h:324
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (ffffffff810e5bd0)
Location: include/linux/bitmap.h:324
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff810ed53c)
Location: include/linux/bitmap.h:324
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/manage.c (ffffffff8110c13a)
Location: include/linux/bitmap.h:324
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (ffffffff8111385a)
Location: include/linux/bitmap.h:324
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff811156fb)
Location: include/linux/bitmap.h:324
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff81165305)
Location: include/linux/bitmap.h:324
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/padata.c (ffffffff8120fce5)
Location: include/linux/bitmap.h:324
Inline: True
```
```
In mm/mempolicy.c (ffffffff8128c007)
Location: include/linux/bitmap.h:324
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
```
```
In mm/sparse.c (ffffffff81a97377)
Location: include/linux/bitmap.h:324
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
```
```
In net/core/ethtool.c (ffffffff81909036)
Location: include/linux/bitmap.h:324
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b4f9)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106104d)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
```
```
In kernel/sched/core.c (ffffffff810dd297)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810e14cc)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (ffffffff810f1000)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff810f77a8)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/manage.c (ffffffff8111856a)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (ffffffff8111f9ca)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff811218fb)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff811711f5)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/padata.c (ffffffff8121d305)
Location: include/linux/bitmap.h:348
Inline: True
```
```
In mm/mempolicy.c (ffffffff8129bbd7)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
```
```
In mm/sparse.c (ffffffff81acec59)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
```
```
In net/core/ethtool.c (ffffffff8193b776)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int bitmap_intersects(const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060879)
Location: include/linux/bitmap.h:364
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81066ced)
Location: include/linux/bitmap.h:364
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
```
```
In kernel/sched/core.c (ffffffff810e5e55)
Location: include/linux/bitmap.h:364
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810eb3bc)
Location: include/linux/bitmap.h:364
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (ffffffff810fb380)
Location: include/linux/bitmap.h:364
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff81101ea8)
Location: include/linux/bitmap.h:364
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
Direct callers:
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/manage.c (ffffffff81123e5a)
Location: include/linux/bitmap.h:364
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff8112bf0a)
Location: include/linux/bitmap.h:364
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff8112e082)
Location: include/linux/bitmap.h:364
Inline: True
Inline callers:
  - kernel/irq/affinity.c:get_nodes_in_cpumask
```
```
In kernel/cgroup/cpuset.c (ffffffff81182f05)
Location: include/linux/bitmap.h:364
Inline: True
Inline callers:
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
```
```
In kernel/padata.c (ffffffff812494c5)
Location: include/linux/bitmap.h:364
Inline: True
Inline callers:
  - kernel/padata.c:padata_validate_cpumask
```
```
In mm/mempolicy.c (ffffffff812cf7d7)
Location: include/linux/bitmap.h:364
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
```
```
In mm/sparse.c (ffffffff81bc758a)
Location: include/linux/bitmap.h:364
Inline: True
Inline callers:
  - mm/sparse.c:section_activate
```
```
In net/ethtool/ioctl.c (ffffffff81a816d6)
Location: include/linux/bitmap.h:364
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32
```
**Symbols:**

```
ffffffff811006d0-ffffffff811006db: bitmap_intersects (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int bitmap_intersects(const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105eab9)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81064f32)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
```
```
In kernel/sched/core.c (ffffffff810e3ba5)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
```
```
In kernel/sched/fair.c (ffffffff810e91ab)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (ffffffff810f9d53)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff81100a9d)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
Direct callers:
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/manage.c (ffffffff8111fcba)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff8112792a)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff81129c72)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
  - kernel/irq/affinity.c:get_nodes_in_cpumask
```
```
In kernel/cgroup/cpuset.c (ffffffff8117fe75)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
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
```
```
In kernel/padata.c (ffffffff81253a56)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
  - kernel/padata.c:padata_validate_cpumask
```
```
In mm/mempolicy.c (ffffffff812db2a7)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
```
```
In mm/sparse.c (ffffffff81c402b6)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
  - mm/sparse.c:section_activate
```
```
In net/ethtool/ioctl.c (ffffffff81a8b2c6)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32
```
**Symbols:**

```
ffffffff810ff220-ffffffff810ff22b: bitmap_intersects (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int bitmap_intersects(const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105f2d9)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81065552)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
```
```
In kernel/sched/core.c (ffffffff810e5b75)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
```
```
In kernel/sched/fair.c (ffffffff810eadcb)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (ffffffff810fbc53)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff81102beb)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
Direct callers:
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/manage.c (ffffffff8111ff6a)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff81127aca)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff81129fa0)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff81180955)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
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
```
```
In kernel/padata.c (ffffffff81258076)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
  - kernel/padata.c:padata_validate_cpumask
```
```
In mm/mempolicy.c (ffffffff812e2b17)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
```
```
In mm/sparse.c (ffffffff81c32429)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
```
```
In net/ethtool/ioctl.c (ffffffff81a74766)
Location: include/linux/bitmap.h:362
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32
```
**Symbols:**

```
ffffffff81101410-ffffffff8110141b: bitmap_intersects (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int bitmap_intersects(const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81068c60)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106f646)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
```
```
In kernel/sched/core.c (ffffffff810fcc62)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
```
```
In kernel/sched/fair.c (ffffffff81102adc)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/deadline.c (ffffffff81117028)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff8111f794)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sd_init
  - kernel/sched/topology.c:sd_init
Direct callers:
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/manage.c (ffffffff81140483)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff8114803a)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff8114a8fe)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff811a8745)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
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
```
```
In kernel/padata.c (ffffffff81293be6)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - kernel/padata.c:padata_validate_cpumask
```
```
In mm/mempolicy.c (ffffffff81329eb9)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_in_oom_domain
  - mm/mempolicy.c:policy_nodemask
```
```
In mm/sparse.c (ffffffff81d50e25)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
```
```
In net/ethtool/ioctl.c (ffffffff81b2e9b6)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32
```
**Symbols:**

```
ffffffff8111d630-ffffffff8111d63b: bitmap_intersects (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool bitmap_intersects(const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81075dc8)
Location: include/linux/bitmap.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107cebd)
Location: include/linux/bitmap.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
```
```
In kernel/workqueue.c (ffffffff810f0496)
Location: include/linux/bitmap.h:387
Inline: True
Inline callers:
  - kernel/workqueue.c:unbind_workers
```
```
In kernel/sched/core.c (ffffffff811195c0)
Location: include/linux/bitmap.h:387
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
```
```
In kernel/sched/fair.c (ffffffff8111e0a8)
Location: include/linux/bitmap.h:387
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/build_policy.c (ffffffff81130a7c)
Location: include/linux/bitmap.h:387
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
```
```
In kernel/sched/build_utility.c (ffffffff811497dd)
Location: include/linux/bitmap.h:387
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:sd_init
Direct callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/irq/manage.c (ffffffff81163dad)
Location: include/linux/bitmap.h:387
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff8116cbcf)
Location: include/linux/bitmap.h:387
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/msi.c (ffffffff8116f6f6)
Location: include/linux/bitmap.h:387
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
```
```
In kernel/irq/affinity.c (ffffffff8116fedc)
Location: include/linux/bitmap.h:387
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff811d98d5)
Location: include/linux/bitmap.h:387
Inline: True
Inline callers:
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
```
```
In kernel/padata.c (ffffffff812e9b96)
Location: include/linux/bitmap.h:387
Inline: True
Inline callers:
  - kernel/padata.c:padata_validate_cpumask
```
```
In mm/mempolicy.c (ffffffff81399321)
Location: include/linux/bitmap.h:387
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_in_oom_domain
  - mm/mempolicy.c:policy_nodemask
```
```
In mm/sparse.c (ffffffff81f2103b)
Location: include/linux/bitmap.h:387
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
```
```
In net/ethtool/ioctl.c (ffffffff81cb97b6)
Location: include/linux/bitmap.h:387
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32
```
**Symbols:**

```
ffffffff81e56b53-ffffffff81e56b68: bitmap_intersects (STB_LOCAL)
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81085e28)
Location: include/linux/bitmap.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108e242)
Location: include/linux/bitmap.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
```
```
In kernel/workqueue.c (ffffffff81111d56)
Location: include/linux/bitmap.h:401
Inline: True
Inline callers:
  - kernel/workqueue.c:unbind_workers
```
```
In kernel/sched/core.c (ffffffff81140ea0)
Location: include/linux/bitmap.h:401
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
```
```
In kernel/sched/fair.c (ffffffff81147382)
Location: include/linux/bitmap.h:401
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/build_policy.c (ffffffff8115be55)
Location: include/linux/bitmap.h:401
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
```
```
In kernel/sched/build_utility.c (ffffffff83ea8fa3)
Location: include/linux/bitmap.h:401
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/irq/manage.c (ffffffff81197acd)
Location: include/linux/bitmap.h:401
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff811a1cc4)
Location: include/linux/bitmap.h:401
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/msi.c (ffffffff811a4bcb)
Location: include/linux/bitmap.h:401
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
```
```
In kernel/irq/affinity.c (ffffffff811a633c)
Location: include/linux/bitmap.h:401
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff8121ed75)
Location: include/linux/bitmap.h:401
Inline: True
Inline callers:
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
```
```
In kernel/padata.c (ffffffff813539e6)
Location: include/linux/bitmap.h:401
Inline: True
Inline callers:
  - kernel/padata.c:padata_validate_cpumask
```
```
In mm/mempolicy.c (ffffffff81419191)
Location: include/linux/bitmap.h:401
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_in_oom_domain
  - mm/mempolicy.c:policy_nodemask
```
```
In mm/sparse.c (ffffffff820cac55)
Location: include/linux/bitmap.h:401
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81088ac8)
Location: include/linux/bitmap.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810910f2)
Location: include/linux/bitmap.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
```
```
In kernel/workqueue.c (ffffffff8111d8cb)
Location: include/linux/bitmap.h:399
Inline: True
Inline callers:
  - kernel/workqueue.c:unbind_worker
```
```
In kernel/sched/fair.c (ffffffff81157212)
Location: include/linux/bitmap.h:399
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/build_policy.c (ffffffff8116c295)
Location: include/linux/bitmap.h:399
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
```
```
In kernel/sched/build_utility.c (ffffffff836cda63)
Location: include/linux/bitmap.h:399
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/irq/manage.c (ffffffff811a978d)
Location: include/linux/bitmap.h:399
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff811b3964)
Location: include/linux/bitmap.h:399
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/msi.c (ffffffff811b6afa)
Location: include/linux/bitmap.h:399
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
```
```
In kernel/cgroup/cpuset.c (ffffffff81234ea5)
Location: include/linux/bitmap.h:399
Inline: True
Inline callers:
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
```
```
In kernel/bpf/cpumask.c (ffffffff8135da25)
Location: include/linux/bitmap.h:399
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_intersects
```
```
In kernel/padata.c (ffffffff81384be6)
Location: include/linux/bitmap.h:399
Inline: True
Inline callers:
  - kernel/padata.c:padata_validate_cpumask
```
```
In mm/mempolicy.c (ffffffff8144c671)
Location: include/linux/bitmap.h:399
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_in_oom_domain
  - mm/mempolicy.c:policy_nodemask
```
```
In mm/sparse.c (ffffffff8214eee5)
Location: include/linux/bitmap.h:399
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
```
```
In lib/group_cpus.c (ffffffff818e6d6e)
Location: include/linux/bitmap.h:399
Inline: True
Inline callers:
  - lib/group_cpus.c:__group_cpus_evenly
```
```
In drivers/net/phy/phy-c45.c (ffffffff81c36162)
Location: include/linux/bitmap.h:399
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108fba8)
Location: include/linux/bitmap.h:376
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810984b2)
Location: include/linux/bitmap.h:376
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
```
```
In kernel/workqueue.c (ffffffff838fbacf)
Location: include/linux/bitmap.h:376
Inline: True
Inline callers:
  - kernel/workqueue.c:restrict_unbound_cpumask
  - kernel/workqueue.c:unbind_worker
```
```
In kernel/sched/fair.c (ffffffff81162665)
Location: include/linux/bitmap.h:376
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/build_policy.c (ffffffff81179635)
Location: include/linux/bitmap.h:376
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
```
```
In kernel/sched/build_utility.c (ffffffff838feea1)
Location: include/linux/bitmap.h:376
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/irq/manage.c (ffffffff811b92ed)
Location: include/linux/bitmap.h:376
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff811c37e4)
Location: include/linux/bitmap.h:376
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/msi.c (ffffffff811c69cc)
Location: include/linux/bitmap.h:376
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
```
```
In kernel/cgroup/cpuset.c (ffffffff8124eac5)
Location: include/linux/bitmap.h:376
Inline: True
Inline callers:
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
```
```
In kernel/trace/trace_events_filter.c (ffffffff812c7322)
Location: include/linux/bitmap.h:376
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:filter_pred_fn_call
```
```
In kernel/bpf/cpumask.c (ffffffff813867c5)
Location: include/linux/bitmap.h:376
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_intersects
```
```
In kernel/padata.c (ffffffff813adff6)
Location: include/linux/bitmap.h:376
Inline: True
Inline callers:
  - kernel/padata.c:padata_validate_cpumask
```
```
In mm/mempolicy.c (ffffffff814858f1)
Location: include/linux/bitmap.h:376
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_in_oom_domain
  - mm/mempolicy.c:policy_nodemask
```
```
In mm/sparse.c (ffffffff82231d55)
Location: include/linux/bitmap.h:376
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
```
```
In lib/group_cpus.c (ffffffff8192dd8e)
Location: include/linux/bitmap.h:376
Inline: True
Inline callers:
  - lib/group_cpus.c:__group_cpus_evenly
```
```
In drivers/net/phy/phy-c45.c (ffffffff81ceb0e2)
Location: include/linux/bitmap.h:376
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_adv
  - drivers/net/phy/phy-c45.c:genphy_c45_write_eee_adv
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
In arch/arm64/kernel/fpsimd.c (ffff800010087ad4)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - arch/arm64/kernel/fpsimd.c:sve_verify_vq_map
```
```
In kernel/sched/core.c (ffff80001013cd9c)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffff800010141a78)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (ffff800010152f80)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffff80001015bae8)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/manage.c (ffff80001017adcc)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (ffff8000101855b8)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffff800010187ba4)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffff8000101e4864)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/padata.c (ffff8000102a987c)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/mempolicy.c (ffff80001033ab54)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
```
```
In mm/sparse.c (ffff800010da082c)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff80001067323c)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_set_affinity
```
```
In net/core/ethtool.c (ffff800010bd97a0)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
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
In arch/arm/kernel/hw_breakpoint.c (c03167fc)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - arch/arm/kernel/hw_breakpoint.c:reset_ctrl_regs
  - arch/arm/kernel/hw_breakpoint.c:reset_ctrl_regs
```
```
In kernel/sched/core.c (c038d204)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (c03908ac)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (c03a058c)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (c03a8580)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/manage.c (c03cbf64)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (c03d4758)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (c03d66b8)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (c042569c)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/padata.c (c04d8b4c)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
```
In drivers/irqchip/irq-gic-v3-its.c (c081b264)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_set_affinity
```
```
In net/core/ethtool.c (c0cf4188)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
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
In arch/powerpc/platforms/powernv/idle.c (c0000000000c791c)
Location: include/linux/bitmap.h:348
Inline: True
```
```
In arch/powerpc/platforms/powernv/opal-imc.c (c0000000000dfd7c)
Location: include/linux/bitmap.h:348
Inline: True
```
```
In kernel/sched/core.c (c00000000018b510)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (c000000000190008)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (c0000000001a72b8)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (c0000000001b020c)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/manage.c (c0000000001d53a8)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (c0000000001dfab0)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (c0000000001e1840)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (c000000000254ffc)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/padata.c (c00000000035e070)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/mempolicy.c (c000000000415564)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
```
```
In mm/sparse.c (c000000000eed480)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - mm/sparse.c:section_activate
```
```
In net/core/ethtool.c (c000000000cb9e2c)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
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
In kernel/sched/core.c (ffffffe0000ec582)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffe0000ee8ec)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (ffffffe0000fad4a)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffe000100ce8)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/manage.c (ffffffe000114a4e)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (ffffffe00011c0fc)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffe00011d606)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffe00015aa62)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/padata.c (ffffffe0001d2c6c)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
```
In net/core/ethtool.c (ffffffe0007617b8)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b079)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060bcd)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
```
```
In kernel/sched/core.c (ffffffff810d7487)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810db67c)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (ffffffff810ea400)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff810f0ba8)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/manage.c (ffffffff81110b4a)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (ffffffff81117faa)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff81119edb)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff81169815)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/padata.c (ffffffff81215955)
Location: include/linux/bitmap.h:348
Inline: True
```
```
In mm/mempolicy.c (ffffffff812941b7)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
```
```
In mm/sparse.c (ffffffff81a6dac9)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
```
```
In net/core/ethtool.c (ffffffff818db746)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104b209)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105102d)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
```
```
In kernel/sched/core.c (ffffffff810c5da7)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810ca68c)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (ffffffff810da430)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff810e0c18)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/manage.c (ffffffff8110187a)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (ffffffff8110901a)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff8110af4b)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff8115ca15)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/padata.c (ffffffff812086b5)
Location: include/linux/bitmap.h:348
Inline: True
```
```
In mm/mempolicy.c (ffffffff81285dc7)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
```
```
In mm/sparse.c (ffffffff81a2a010)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
```
```
In net/core/ethtool.c (ffffffff81895586)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b4a9)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060ffd)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
```
```
In kernel/sched/core.c (ffffffff810d40e7)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810d79fc)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (ffffffff810e7530)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff810edcd8)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/manage.c (ffffffff8110ea3a)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (ffffffff81115e9a)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff81117dcb)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff811675e5)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/padata.c (ffffffff812136f5)
Location: include/linux/bitmap.h:348
Inline: True
```
```
In mm/mempolicy.c (ffffffff81291fc7)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
```
```
In mm/sparse.c (ffffffff81ad9ed9)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
```
```
In net/core/ethtool.c (ffffffff8192c776)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c969)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810625bd)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_cbm_overlaps_pseudo_locked
```
```
In kernel/sched/core.c (ffffffff810df067)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810e349c)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (ffffffff810f2650)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff810f8d18)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/manage.c (ffffffff81119f68)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (ffffffff811214ca)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff8112345b)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff81174c65)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed_intersects
  - kernel/cgroup/cpuset.c:cpuset_nodemask_valid_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/padata.c (ffffffff81222cd5)
Location: include/linux/bitmap.h:348
Inline: True
```
```
In mm/mempolicy.c (ffffffff812a1dd7)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_nodemask_intersects
```
```
In mm/sparse.c (ffffffff81ae638f)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
```
```
In net/core/ethtool.c (ffffffff8194de46)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
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
</ul>
