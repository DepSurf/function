# Function: <code>cpumask_intersects</code>

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
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
```
```
In kernel/sched/core.c (ffffffff810a873e)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:task_can_attach
```
```
In kernel/sched/fair.c (ffffffff810b326f)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/deadline.c (ffffffff810c16f3)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/irq/manage.c (ffffffff810dbfdc)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_affinity
  - kernel/irq/manage.c:setup_affinity
```
```
In kernel/irq/proc.c (ffffffff810e1be0)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/cpuset.c (ffffffff8111a9d6)
Location: include/linux/cpumask.h:431
Inline: True
Inline callers:
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:guarantee_online_cpus
```
```
In kernel/padata.c (ffffffff8118a146)
Location: include/linux/cpumask.h:431
Inline: True
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
Location: include/linux/cpumask.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In kernel/sched/core.c (ffffffff810ab2e3)
Location: include/linux/cpumask.h:435
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810b6150)
Location: include/linux/cpumask.h:435
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/deadline.c (ffffffff810c51a3)
Location: include/linux/cpumask.h:435
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/irq/manage.c (ffffffff810e173e)
Location: include/linux/cpumask.h:435
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_affinity
  - kernel/irq/manage.c:setup_affinity
```
```
In kernel/irq/proc.c (ffffffff810e7680)
Location: include/linux/cpumask.h:435
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/cpuset.c (ffffffff811228f4)
Location: include/linux/cpumask.h:435
Inline: True
Inline callers:
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
```
```
In kernel/padata.c (ffffffff8119d0e0)
Location: include/linux/cpumask.h:435
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_cpu_callback
  - kernel/padata.c:padata_cpu_callback
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
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
In arch/x86/kernel/apic/vector.c (ffffffff81058436)
Location: include/linux/cpumask.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In kernel/sched/core.c (ffffffff810b1558)
Location: include/linux/cpumask.h:435
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810c4c2b)
Location: include/linux/cpumask.h:435
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/deadline.c (ffffffff810cb1cf)
Location: include/linux/cpumask.h:435
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/irq/manage.c (ffffffff810e80a4)
Location: include/linux/cpumask.h:435
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_affinity
  - kernel/irq/manage.c:setup_affinity
```
```
In kernel/irq/proc.c (ffffffff810ee3f2)
Location: include/linux/cpumask.h:435
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff810ef9cd)
Location: include/linux/cpumask.h:435
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/cpuset.c (ffffffff8112c9e4)
Location: include/linux/cpumask.h:435
Inline: True
Inline callers:
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
```
```
In kernel/padata.c (ffffffff811abe16)
Location: include/linux/cpumask.h:435
Inline: True
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
Location: include/linux/cpumask.h:463
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In kernel/sched/core.c (ffffffff810b375f)
Location: include/linux/cpumask.h:463
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810b7ac8)
Location: include/linux/cpumask.h:463
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/deadline.c (ffffffff810c5b82)
Location: include/linux/cpumask.h:463
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff810cb7cb)
Location: include/linux/cpumask.h:463
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/manage.c (ffffffff810e77ba)
Location: include/linux/cpumask.h:463
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (ffffffff810edc3b)
Location: include/linux/cpumask.h:463
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff810ef997)
Location: include/linux/cpumask.h:463
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff8112dc76)
Location: include/linux/cpumask.h:463
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/padata.c (ffffffff811b3276)
Location: include/linux/cpumask.h:463
Inline: True
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
Location: include/linux/cpumask.h:467
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810bee91)
Location: include/linux/cpumask.h:467
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/deadline.c (ffffffff810cd292)
Location: include/linux/cpumask.h:467
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff810d2f75)
Location: include/linux/cpumask.h:467
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/manage.c (ffffffff810efb3a)
Location: include/linux/cpumask.h:467
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (ffffffff810f667b)
Location: include/linux/cpumask.h:467
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff810f857e)
Location: include/linux/cpumask.h:467
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff8113a772)
Location: include/linux/cpumask.h:467
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/padata.c (ffffffff811c6ec6)
Location: include/linux/cpumask.h:467
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
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810c728d)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/deadline.c (ffffffff810d5154)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff810dcdeb)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/manage.c (ffffffff810f7f96)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (ffffffff810fe99b)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff811007ad)
Location: include/linux/cpumask.h:469
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff81149c08)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/padata.c (ffffffff811e7115)
Location: include/linux/cpumask.h:469
Inline: True
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105d41d)
Location: include/linux/cpumask.h:481
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/sched/core.c (ffffffff810cb15c)
Location: include/linux/cpumask.h:481
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810cf98a)
Location: include/linux/cpumask.h:481
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/deadline.c (ffffffff810deb84)
Location: include/linux/cpumask.h:481
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff810e6a4b)
Location: include/linux/cpumask.h:481
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/manage.c (ffffffff81103708)
Location: include/linux/cpumask.h:481
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (ffffffff8110a16b)
Location: include/linux/cpumask.h:481
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff8110bf66)
Location: include/linux/cpumask.h:481
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff81157cbd)
Location: include/linux/cpumask.h:481
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/padata.c (ffffffff811f7e65)
Location: include/linux/cpumask.h:481
Inline: True
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106079d)
Location: include/linux/cpumask.h:481
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/sched/core.c (ffffffff810d2e07)
Location: include/linux/cpumask.h:481
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810d6ee8)
Location: include/linux/cpumask.h:481
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (ffffffff810e5bd0)
Location: include/linux/cpumask.h:481
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff810ed53c)
Location: include/linux/cpumask.h:481
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/manage.c (ffffffff8110c132)
Location: include/linux/cpumask.h:481
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (ffffffff8111385a)
Location: include/linux/cpumask.h:481
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff811156fb)
Location: include/linux/cpumask.h:481
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff8116224e)
Location: include/linux/cpumask.h:481
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
```
```
In kernel/padata.c (ffffffff8120fce5)
Location: include/linux/cpumask.h:481
Inline: True
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106104d)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/sched/core.c (ffffffff810dd297)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810e14c8)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (ffffffff810f1000)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff810f77a8)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/manage.c (ffffffff81118562)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (ffffffff8111f9ca)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff811218fb)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff8116df2e)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
```
```
In kernel/padata.c (ffffffff8121d305)
Location: include/linux/cpumask.h:511
Inline: True
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81066ced)
Location: include/linux/cpumask.h:518
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/sched/core.c (ffffffff810e5e55)
Location: include/linux/cpumask.h:518
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810eb3aa)
Location: include/linux/cpumask.h:518
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (ffffffff810fb380)
Location: include/linux/cpumask.h:518
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff81101ea8)
Location: include/linux/cpumask.h:518
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/manage.c (ffffffff81123e52)
Location: include/linux/cpumask.h:518
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff8112bf0a)
Location: include/linux/cpumask.h:518
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff8112e082)
Location: include/linux/cpumask.h:518
Inline: True
Inline callers:
  - kernel/irq/affinity.c:get_nodes_in_cpumask
```
```
In kernel/cgroup/cpuset.c (ffffffff811820d1)
Location: include/linux/cpumask.h:518
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
```
```
In kernel/padata.c (ffffffff812494c5)
Location: include/linux/cpumask.h:518
Inline: True
Inline callers:
  - kernel/padata.c:padata_validate_cpumask
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81064f32)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/sched/core.c (ffffffff810e3ba5)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
```
```
In kernel/sched/fair.c (ffffffff810e9199)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (ffffffff810f9d53)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff81100a9d)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/manage.c (ffffffff8111fcb2)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff8112792a)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff81129c72)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/irq/affinity.c:get_nodes_in_cpumask
```
```
In kernel/cgroup/cpuset.c (ffffffff8117eff1)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
```
```
In kernel/padata.c (ffffffff81253a56)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/padata.c:padata_validate_cpumask
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81065552)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/sched/core.c (ffffffff810e5b75)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
```
```
In kernel/sched/fair.c (ffffffff810eadb9)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (ffffffff810fbc53)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff81102beb)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/manage.c (ffffffff8111ff62)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff81127aca)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff81129fa0)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff8117eff6)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
```
```
In kernel/padata.c (ffffffff81258076)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/padata.c:padata_validate_cpumask
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106f646)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/sched/core.c (ffffffff810fcc62)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
```
```
In kernel/sched/fair.c (ffffffff81102abd)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/deadline.c (ffffffff81117028)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff8111f794)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sd_init
  - kernel/sched/topology.c:sd_init
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/manage.c (ffffffff8114047b)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff8114803a)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff8114a8fe)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff811a71b6)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
```
```
In kernel/padata.c (ffffffff81293be6)
Location: include/linux/cpumask.h:495
Inline: True
Inline callers:
  - kernel/padata.c:padata_validate_cpumask
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107cebd)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/workqueue.c (ffffffff810f0496)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - kernel/workqueue.c:unbind_workers
```
```
In kernel/sched/core.c (ffffffff811195c0)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
```
```
In kernel/sched/fair.c (ffffffff8111e08d)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/build_policy.c (ffffffff81130a7c)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
```
```
In kernel/sched/build_utility.c (ffffffff8347d6be)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/irq/manage.c (ffffffff81163da5)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff8116cbcf)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/msi.c (ffffffff8116f6f6)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
```
```
In kernel/irq/affinity.c (ffffffff8116fedc)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff811d8288)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
```
```
In kernel/padata.c (ffffffff812e9b96)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - kernel/padata.c:padata_validate_cpumask
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108e242)
Location: include/linux/cpumask.h:595
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/workqueue.c (ffffffff81111d56)
Location: include/linux/cpumask.h:595
Inline: True
Inline callers:
  - kernel/workqueue.c:unbind_workers
```
```
In kernel/sched/core.c (ffffffff81140ea0)
Location: include/linux/cpumask.h:595
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
```
```
In kernel/sched/fair.c (ffffffff8114737e)
Location: include/linux/cpumask.h:595
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/build_policy.c (ffffffff8115be55)
Location: include/linux/cpumask.h:595
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
```
```
In kernel/sched/build_utility.c (ffffffff83ea8fa3)
Location: include/linux/cpumask.h:595
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/irq/manage.c (ffffffff81197ac5)
Location: include/linux/cpumask.h:595
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff811a1cc4)
Location: include/linux/cpumask.h:595
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/msi.c (ffffffff811a4bcb)
Location: include/linux/cpumask.h:595
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
```
```
In kernel/irq/affinity.c (ffffffff811a633c)
Location: include/linux/cpumask.h:595
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff8121e807)
Location: include/linux/cpumask.h:595
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
```
```
In kernel/padata.c (ffffffff813539e6)
Location: include/linux/cpumask.h:595
Inline: True
Inline callers:
  - kernel/padata.c:padata_validate_cpumask
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810910f2)
Location: include/linux/cpumask.h:647
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/workqueue.c (ffffffff8111d8cb)
Location: include/linux/cpumask.h:647
Inline: True
Inline callers:
  - kernel/workqueue.c:unbind_worker
```
```
In kernel/sched/fair.c (ffffffff8115720e)
Location: include/linux/cpumask.h:647
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/build_policy.c (ffffffff8116c295)
Location: include/linux/cpumask.h:647
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
```
```
In kernel/sched/build_utility.c (ffffffff836cda63)
Location: include/linux/cpumask.h:647
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/irq/manage.c (ffffffff811a9785)
Location: include/linux/cpumask.h:647
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff811b3964)
Location: include/linux/cpumask.h:647
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/msi.c (ffffffff811b6afa)
Location: include/linux/cpumask.h:647
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
```
```
In kernel/cgroup/cpuset.c (ffffffff812348f7)
Location: include/linux/cpumask.h:647
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
```
```
In kernel/bpf/cpumask.c (ffffffff8135da25)
Location: include/linux/cpumask.h:647
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_intersects
```
```
In kernel/padata.c (ffffffff81384be6)
Location: include/linux/cpumask.h:647
Inline: True
Inline callers:
  - kernel/padata.c:padata_validate_cpumask
```
```
In lib/group_cpus.c (ffffffff818e6d6e)
Location: include/linux/cpumask.h:647
Inline: True
Inline callers:
  - lib/group_cpus.c:__group_cpus_evenly
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810984b2)
Location: include/linux/cpumask.h:655
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/workqueue.c (ffffffff838fbac4)
Location: include/linux/cpumask.h:655
Inline: True
Inline callers:
  - kernel/workqueue.c:restrict_unbound_cpumask
  - kernel/workqueue.c:unbind_worker
```
```
In kernel/sched/fair.c (ffffffff81162661)
Location: include/linux/cpumask.h:655
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/build_policy.c (ffffffff81179635)
Location: include/linux/cpumask.h:655
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
```
```
In kernel/sched/build_utility.c (ffffffff838feea1)
Location: include/linux/cpumask.h:655
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/irq/manage.c (ffffffff811b92e5)
Location: include/linux/cpumask.h:655
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff811c37e4)
Location: include/linux/cpumask.h:655
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/msi.c (ffffffff811c69cc)
Location: include/linux/cpumask.h:655
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
```
```
In kernel/cgroup/cpuset.c (ffffffff8124e517)
Location: include/linux/cpumask.h:655
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:remote_cpus_update
  - kernel/cgroup/cpuset.c:tasks_nocpu_error
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
```
```
In kernel/trace/trace_events_filter.c (ffffffff812c7322)
Location: include/linux/cpumask.h:655
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:filter_pred_fn_call
```
```
In kernel/bpf/cpumask.c (ffffffff813867c5)
Location: include/linux/cpumask.h:655
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_intersects
```
```
In kernel/padata.c (ffffffff813adff6)
Location: include/linux/cpumask.h:655
Inline: True
Inline callers:
  - kernel/padata.c:padata_validate_cpumask
```
```
In lib/group_cpus.c (ffffffff8192dd8e)
Location: include/linux/cpumask.h:655
Inline: True
Inline callers:
  - lib/group_cpus.c:__group_cpus_evenly
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
In kernel/sched/core.c (ffff80001013cd9c)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffff800010141a70)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (ffff800010152f80)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffff80001015bae8)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/manage.c (ffff80001017adcc)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (ffff8000101855b8)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffff800010187ba4)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffff8000101e2744)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
```
```
In kernel/padata.c (ffff8000102a987c)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff80001067323c)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_set_affinity
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
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - arch/arm/kernel/hw_breakpoint.c:reset_ctrl_regs
  - arch/arm/kernel/hw_breakpoint.c:reset_ctrl_regs
```
```
In kernel/sched/core.c (c038d204)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (c03908ac)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (c03a058c)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (c03a8580)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/manage.c (c03cbf64)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (c03d4758)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (c03d66b8)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (c0424c60)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
```
```
In kernel/padata.c (c04d8b4c)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
```
In drivers/irqchip/irq-gic-v3-its.c (c081b264)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_set_affinity
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
Location: include/linux/cpumask.h:511
Inline: True
```
```
In arch/powerpc/platforms/powernv/opal-imc.c (c0000000000dfd7c)
Location: include/linux/cpumask.h:511
Inline: True
```
```
In kernel/sched/core.c (c00000000018b510)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (c000000000190000)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (c0000000001a72b8)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (c0000000001b020c)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/manage.c (c0000000001d53a8)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (c0000000001dfab0)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (c0000000001e1840)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (c000000000250e84)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
```
```
In kernel/padata.c (c00000000035e070)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
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
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffe0000ee8ec)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (ffffffe0000fad4a)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffe000100ce8)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/manage.c (ffffffe000114a4e)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (ffffffe00011c0fc)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffe00011d606)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffe00015947a)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
```
```
In kernel/padata.c (ffffffe0001d2c6c)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060bcd)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/sched/core.c (ffffffff810d7487)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810db678)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (ffffffff810ea400)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff810f0ba8)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/manage.c (ffffffff81110b42)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (ffffffff81117faa)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff81119edb)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff8116654e)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
```
```
In kernel/padata.c (ffffffff81215955)
Location: include/linux/cpumask.h:511
Inline: True
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105102d)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/sched/core.c (ffffffff810c5da7)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810ca688)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (ffffffff810da430)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff810e0c18)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/manage.c (ffffffff81101872)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (ffffffff8110901a)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff8110af4b)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff8115978e)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
```
```
In kernel/padata.c (ffffffff812086b5)
Location: include/linux/cpumask.h:511
Inline: True
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060ffd)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/sched/core.c (ffffffff810d40e7)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810d79f8)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (ffffffff810e7530)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff810edcd8)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/manage.c (ffffffff8110ea32)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (ffffffff81115e9a)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff81117dcb)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff8116431e)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
```
```
In kernel/padata.c (ffffffff812136f5)
Location: include/linux/cpumask.h:511
Inline: True
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
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810625bd)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In kernel/sched/core.c (ffffffff810df067)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/fair.c (ffffffff810e3498)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (ffffffff810f2650)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
```
In kernel/sched/topology.c (ffffffff810f8d18)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/manage.c (ffffffff81119f60)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/proc.c (ffffffff811214ca)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/irq/affinity.c (ffffffff8112345b)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff811717c9)
Location: include/linux/cpumask.h:511
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:validate_change
```
```
In kernel/padata.c (ffffffff81222cd5)
Location: include/linux/cpumask.h:511
Inline: True
```
</details>
</li>
</ul>

## Differences
