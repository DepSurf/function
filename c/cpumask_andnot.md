# Function: <code>cpumask_andnot</code>

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
In arch/x86/kernel/apic/vector.c (ffffffff81055398)
Location: include/linux/cpumask.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059d58)
Location: include/linux/cpumask.h:394
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In kernel/smpboot.c (ffffffff810a3948)
Location: include/linux/cpumask.h:394
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
```
```
In kernel/sched/core.c (ffffffff810affe4)
Location: include/linux/cpumask.h:394
Inline: True
Inline callers:
  - kernel/sched/core.c:partition_sched_domains
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
```
```
In kernel/cpuset.c (ffffffff8111a7e6)
Location: include/linux/cpumask.h:394
Inline: True
Inline callers:
  - kernel/cpuset.c:generate_sched_domains
```
```
In drivers/base/cpu.c (ffffffff8154ead6)
Location: include/linux/cpumask.h:394
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_offline
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
In arch/x86/kernel/apic/vector.c (ffffffff81055601)
Location: include/linux/cpumask.h:398
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105a003)
Location: include/linux/cpumask.h:398
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In kernel/smpboot.c (ffffffff810a7068)
Location: include/linux/cpumask.h:398
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
```
```
In kernel/sched/core.c (ffffffff81fa6e05)
Location: include/linux/cpumask.h:398
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:partition_sched_domains
```
```
In kernel/cpuset.c (ffffffff81122696)
Location: include/linux/cpumask.h:398
Inline: True
Inline callers:
  - kernel/cpuset.c:generate_sched_domains
```
```
In drivers/base/cpu.c (ffffffff815a08c6)
Location: include/linux/cpumask.h:398
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_offline
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81044492)
Location: include/linux/cpumask.h:398
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81058173)
Location: include/linux/cpumask.h:398
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105cdc0)
Location: include/linux/cpumask.h:398
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In kernel/smpboot.c (ffffffff810ad066)
Location: include/linux/cpumask.h:398
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
```
```
In kernel/sched/core.c (ffffffff81fe299b)
Location: include/linux/cpumask.h:398
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:partition_sched_domains
```
```
In kernel/cpuset.c (ffffffff8112c793)
Location: include/linux/cpumask.h:398
Inline: True
Inline callers:
  - kernel/cpuset.c:generate_sched_domains
```
```
In drivers/base/cpu.c (ffffffff815cef6b)
Location: include/linux/cpumask.h:398
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_offline
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff8104343d)
Location: include/linux/cpumask.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105782f)
Location: include/linux/cpumask.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c72f)
Location: include/linux/cpumask.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In kernel/smpboot.c (ffffffff810a9ae1)
Location: include/linux/cpumask.h:426
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
```
```
In kernel/sched/core.c (ffffffff820c32a2)
Location: include/linux/cpumask.h:426
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
```
```
In kernel/sched/topology.c (ffffffff810cd73a)
Location: include/linux/cpumask.h:426
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
```
```
In kernel/cgroup/cpuset.c (ffffffff8112da03)
Location: include/linux/cpumask.h:426
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In drivers/base/cpu.c (ffffffff815e39d8)
Location: include/linux/cpumask.h:426
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_offline
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81046aa8)
Location: include/linux/cpumask.h:430
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106044c)
Location: include/linux/cpumask.h:430
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In kernel/smpboot.c (ffffffff810b0698)
Location: include/linux/cpumask.h:430
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
```
```
In kernel/sched/isolation.c (ffffffff826cbc8c)
Location: include/linux/cpumask.h:430
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In drivers/base/cpu.c (ffffffff8164ae9c)
Location: include/linux/cpumask.h:430
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81048ff9)
Location: include/linux/cpumask.h:432
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106353c)
Location: include/linux/cpumask.h:432
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In kernel/smpboot.c (ffffffff810b74da)
Location: include/linux/cpumask.h:432
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
```
```
In kernel/sched/isolation.c (ffffffff826f5df5)
Location: include/linux/cpumask.h:432
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/affinity.c (ffffffff81100d6d)
Location: include/linux/cpumask.h:432
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In drivers/base/cpu.c (ffffffff816864ac)
Location: include/linux/cpumask.h:432
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81058fdb)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106923c)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In kernel/sched/isolation.c (ffffffff828acc3f)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/affinity.c (ffffffff8110c525)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff811582fa)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In drivers/base/cpu.c (ffffffff816a614c)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c58e)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106ca80)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In kernel/sched/isolation.c (ffffffff828c5537)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/affinity.c (ffffffff81115cda)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff81164e8d)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In drivers/base/cpu.c (ffffffff816df192)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ce88)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106e220)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81097789)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
```
```
In kernel/sched/isolation.c (ffffffff828cdba0)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/affinity.c (ffffffff811220d1)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff81170d6d)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In drivers/base/cpu.c (ffffffff817033e2)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81062c97)
Location: include/linux/cpumask.h:467
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810758a0)
Location: include/linux/cpumask.h:467
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109c8c4)
Location: include/linux/cpumask.h:467
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
```
```
In kernel/sched/fair.c (ffffffff810ea36d)
Location: include/linux/cpumask.h:467
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_core
```
```
In kernel/sched/isolation.c (ffffffff82ceef64)
Location: include/linux/cpumask.h:467
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/affinity.c (ffffffff8112e5c4)
Location: include/linux/cpumask.h:467
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff81182975)
Location: include/linux/cpumask.h:467
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In drivers/base/cpu.c (ffffffff817bd712)
Location: include/linux/cpumask.h:467
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81061127)
Location: include/linux/cpumask.h:473
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075ede)
Location: include/linux/cpumask.h:473
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In kernel/sched/fair.c (ffffffff810e7f25)
Location: include/linux/cpumask.h:473
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_core
```
```
In kernel/sched/isolation.c (ffffffff82fdb67b)
Location: include/linux/cpumask.h:473
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/affinity.c (ffffffff8112a1b4)
Location: include/linux/cpumask.h:473
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff8117f8a7)
Location: include/linux/cpumask.h:473
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In drivers/base/cpu.c (ffffffff817d2482)
Location: include/linux/cpumask.h:473
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81061657)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81076960)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In kernel/sched/fair.c (ffffffff810ebc9f)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_core
```
```
In kernel/sched/isolation.c (ffffffff831e63d5)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/affinity.c (ffffffff8112a434)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff8117fee7)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In drivers/base/cpu.c (ffffffff817b5ea2)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106b337)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810840f9)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In kernel/sched/core.c (ffffffff810f1bbc)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:__sched_core_flip
```
```
In kernel/sched/fair.c (ffffffff81103860)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_core
```
```
In kernel/sched/isolation.c (ffffffff832ca4d1)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/affinity.c (ffffffff8114ada6)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff811a8127)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In drivers/base/cpu.c (ffffffff8183f3c2)
Location: include/linux/cpumask.h:444
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810785d6)
Location: include/linux/cpumask.h:479
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810941e1)
Location: include/linux/cpumask.h:479
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In kernel/sched/core.c (ffffffff8110d4fa)
Location: include/linux/cpumask.h:479
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:__sched_core_flip
```
```
In kernel/sched/fair.c (ffffffff8111f731)
Location: include/linux/cpumask.h:479
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_core
```
```
In kernel/sched/build_utility.c (ffffffff8347d6a4)
Location: include/linux/cpumask.h:479
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
```
```
In kernel/irq/affinity.c (ffffffff81170417)
Location: include/linux/cpumask.h:479
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff811d9231)
Location: include/linux/cpumask.h:479
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In drivers/base/cpu.c (ffffffff81982488)
Location: include/linux/cpumask.h:479
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
```
```
In net/core/dev.c (ffffffff81c0fa47)
Location: include/linux/cpumask.h:479
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81089275)
Location: include/linux/cpumask.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a9819)
Location: include/linux/cpumask.h:544
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In kernel/sched/core.c (ffffffff811343cb)
Location: include/linux/cpumask.h:544
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_core_flip
```
```
In kernel/sched/fair.c (ffffffff811448fa)
Location: include/linux/cpumask.h:544
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_core
```
```
In kernel/sched/build_utility.c (ffffffff83ea8f89)
Location: include/linux/cpumask.h:544
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
```
```
In kernel/irq/affinity.c (ffffffff811a688d)
Location: include/linux/cpumask.h:544
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff8121e7eb)
Location: include/linux/cpumask.h:544
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In drivers/base/cpu.c (ffffffff81af02dd)
Location: include/linux/cpumask.h:544
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
```
```
In net/core/dev.c (ffffffff81dc2247)
Location: include/linux/cpumask.h:544
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108c185)
Location: include/linux/cpumask.h:608
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810aca34)
Location: include/linux/cpumask.h:608
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In kernel/cpu.c (ffffffff836c9d57)
Location: include/linux/cpumask.h:608
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_bringup_cpus_parallel
```
```
In kernel/sched/core.c (ffffffff8114330b)
Location: include/linux/cpumask.h:608
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_core_flip
```
```
In kernel/sched/fair.c (ffffffff81154e1a)
Location: include/linux/cpumask.h:608
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_core
```
```
In kernel/sched/build_utility.c (ffffffff836cda49)
Location: include/linux/cpumask.h:608
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
```
```
In kernel/cgroup/cpuset.c (ffffffff812348db)
Location: include/linux/cpumask.h:608
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_attach_task
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
```
```
In lib/group_cpus.c (ffffffff818e72b8)
Location: include/linux/cpumask.h:608
Inline: True
Inline callers:
  - lib/group_cpus.c:group_cpus_evenly
```
```
In drivers/base/cpu.c (ffffffff81b3e43d)
Location: include/linux/cpumask.h:608
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
```
```
In net/core/dev.c (ffffffff81e317a7)
Location: include/linux/cpumask.h:608
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81093ef5)
Location: include/linux/cpumask.h:608
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b36b4)
Location: include/linux/cpumask.h:608
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In kernel/cpu.c (ffffffff838fa9c7)
Location: include/linux/cpumask.h:608
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_bringup_cpus_parallel
```
```
In kernel/workqueue.c (ffffffff8112f6a2)
Location: include/linux/cpumask.h:608
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_unbound_exclude_cpumask
```
```
In kernel/sched/core.c (ffffffff8114e7db)
Location: include/linux/cpumask.h:608
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_core_flip
```
```
In kernel/sched/fair.c (ffffffff81163192)
Location: include/linux/cpumask.h:608
Inline: True
Inline callers:
  - kernel/sched/fair.c:should_we_balance
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
```
```
In kernel/sched/build_utility.c (ffffffff838fee87)
Location: include/linux/cpumask.h:608
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:init_sched_groups_capacity
```
```
In kernel/cgroup/cpuset.c (ffffffff8124e4fb)
Location: include/linux/cpumask.h:608
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_attach_task
  - kernel/cgroup/cpuset.c:compute_partition_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:remote_cpus_update
  - kernel/cgroup/cpuset.c:remote_cpus_update
  - kernel/cgroup/cpuset.c:partition_xcpus_del
  - kernel/cgroup/cpuset.c:partition_xcpus_add
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
```
```
In lib/group_cpus.c (ffffffff8192e2f4)
Location: include/linux/cpumask.h:608
Inline: True
Inline callers:
  - lib/group_cpus.c:group_cpus_evenly
```
```
In drivers/base/cpu.c (ffffffff81b960cd)
Location: include/linux/cpumask.h:608
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
```
```
In net/core/dev.c (ffffffff81eeff27)
Location: include/linux/cpumask.h:608
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
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
In kernel/sched/isolation.c (ffff80001144547c)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/affinity.c (ffff8000101882c8)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffff8000101e4280)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In drivers/base/cpu.c (ffff8000108eebc8)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
```
```
In drivers/base/arch_topology.c (ffff800010920348)
Location: include/linux/cpumask.h:460
Inline: True
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
In kernel/sched/isolation.c (c151f5c8)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/affinity.c (c03d6c7c)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/cgroup/cpuset.c (c04251d4)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In drivers/base/cpu.c (c09dc5c4)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
```
```
In drivers/base/arch_topology.c (c0a05304)
Location: include/linux/cpumask.h:460
Inline: True
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
In arch/powerpc/kernel/watchdog.c (c000000000037274)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
```
```
In arch/powerpc/kernel/rtas.c (c00000000003ee00)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - arch/powerpc/kernel/rtas.c:rtas_ibm_suspend_me
```
```
In arch/powerpc/mm/numa.c (c0000000000a37f0)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
```
```
In arch/powerpc/platforms/powernv/subcore.c (c0000000000cf210)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/subcore.c:cpu_update_split_mode
```
```
In arch/powerpc/platforms/pseries/suspend.c (c000000000104770)
Location: include/linux/cpumask.h:460
Inline: True
```
```
In kernel/sched/isolation.c (c000000001369f00)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/affinity.c (c0000000001e2084)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (c0000000002549c0)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In drivers/base/cpu.c (c0000000009878fc)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
```
```
In drivers/cpufreq/powernv-cpufreq.c (c000000000c1ca38)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_work_fn
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
In arch/riscv/mm/cacheflush.c (ffffffe0000ba082)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - arch/riscv/mm/cacheflush.c:flush_icache_mm
```
```
In kernel/sched/isolation.c (ffffffe000007268)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/affinity.c (ffffffe00011da18)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffe00015a664)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In drivers/base/cpu.c (ffffffe000581698)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ca08)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d1c0)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In kernel/sched/isolation.c (ffffffff828b6930)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/affinity.c (ffffffff8111a6b1)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff8116938d)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In drivers/base/cpu.c (ffffffff816c8b32)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104cbd8)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d5b3)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In kernel/sched/isolation.c (ffffffff828aeb26)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/affinity.c (ffffffff8110b721)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff8115c591)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In drivers/base/cpu.c (ffffffff816a3e62)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ce38)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d670)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In kernel/sched/isolation.c (ffffffff828c97d4)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/affinity.c (ffffffff811185a1)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff8116715d)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In drivers/base/cpu.c (ffffffff816f70a2)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105e358)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106f8f0)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81098c59)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
```
```
In kernel/sched/isolation.c (ffffffff828ceb86)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/affinity.c (ffffffff81123c31)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffff8117473e)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In drivers/base/cpu.c (ffffffff81711942)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
```
</details>
</li>
</ul>

## Differences
