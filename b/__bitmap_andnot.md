# Function: <code>__bitmap_andnot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __bitmap_andnot(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff813f8f40)
Location: lib/bitmap.c:191
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/sched/core.c:partition_sched_domains
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/cpuset.c:generate_sched_domains
  - drivers/base/cpu.c:print_cpus_offline
```
**Symbols:**

```
ffffffff813f8f40-ffffffff813f8fa9: __bitmap_andnot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __bitmap_andnot(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8143fe00)
Location: lib/bitmap.c:193
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:partition_sched_domains
  - kernel/cpuset.c:generate_sched_domains
  - drivers/base/cpu.c:print_cpus_offline
```
**Symbols:**

```
ffffffff8143fe00-ffffffff8143fe66: __bitmap_andnot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __bitmap_andnot(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8145cf00)
Location: lib/bitmap.c:193
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/sched/core.c:partition_sched_domains
  - kernel/cpuset.c:generate_sched_domains
  - drivers/base/cpu.c:print_cpus_offline
```
**Symbols:**

```
ffffffff8145cf00-ffffffff8145cf66: __bitmap_andnot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __bitmap_andnot(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81462180)
Location: lib/bitmap.c:193
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - drivers/base/cpu.c:print_cpus_offline
```
**Symbols:**

```
ffffffff81462180-ffffffff814621f2: __bitmap_andnot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __bitmap_andnot(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8148e060)
Location: lib/bitmap.c:195
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
```
**Symbols:**

```
ffffffff8148e060-ffffffff8148e0d2: __bitmap_andnot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __bitmap_andnot(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814c2da0)
Location: lib/bitmap.c:192
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
```
**Symbols:**

```
ffffffff814c2da0-ffffffff814c2e0a: __bitmap_andnot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __bitmap_andnot(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814d7450)
Location: lib/bitmap.c:189
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
```
**Symbols:**

```
ffffffff814d7450-ffffffff814d74ba: __bitmap_andnot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __bitmap_andnot(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815032b0)
Location: lib/bitmap.c:189
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/sched/isolation.c:bitmap_andnot
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/net/phy/phy.c:phy_speed_up
```
**Symbols:**

```
ffffffff815032b0-ffffffff81503318: __bitmap_andnot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __bitmap_andnot(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81521250)
Location: lib/bitmap.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - kernel/sched/isolation.c:bitmap_andnot
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
```
**Symbols:**

```
ffffffff81521250-ffffffff815212b8: __bitmap_andnot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __bitmap_andnot(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81584440)
Location: lib/bitmap.c:276
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:select_idle_core
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
```
**Symbols:**

```
ffffffff81584440-ffffffff815844a7: __bitmap_andnot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __bitmap_andnot(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a1550)
Location: lib/bitmap.c:276
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/sched/fair.c:select_idle_core
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
```
**Symbols:**

```
ffffffff815a1550-ffffffff815a15b7: __bitmap_andnot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __bitmap_andnot(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a8400)
Location: lib/bitmap.c:278
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/sched/fair.c:select_idle_core
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
```
**Symbols:**

```
ffffffff815a8400-ffffffff815a8467: __bitmap_andnot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __bitmap_andnot(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816113c0)
Location: lib/bitmap.c:278
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/fair.c:select_idle_core
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
```
**Symbols:**

```
ffffffff816113c0-ffffffff81611427: __bitmap_andnot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __bitmap_andnot(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816dd470)
Location: lib/bitmap.c:278
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
  - net/core/dev.c:netif_get_num_default_rss_queues
```
**Symbols:**

```
ffffffff816dd470-ffffffff816dd4f3: __bitmap_andnot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __bitmap_andnot(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff817cd340)
Location: lib/bitmap.c:278
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
  - net/core/dev.c:netif_get_num_default_rss_queues
```
**Symbols:**

```
ffffffff817cd340-ffffffff817cd3c1: __bitmap_andnot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __bitmap_andnot(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8180b750)
Location: lib/bitmap.c:278
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/cpu.c:cpuhp_bringup_cpus_parallel
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
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
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
  - lib/group_cpus.c:group_cpus_evenly
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/net/phy/phy-c45.c:genphy_c45_ethtool_set_eee
  - net/core/dev.c:netif_get_num_default_rss_queues
```
**Symbols:**

```
ffffffff8180b750-ffffffff8180b7d1: __bitmap_andnot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __bitmap_andnot(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81851f30)
Location: lib/bitmap.c:267
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/cpu.c:cpuhp_bringup_cpus_parallel
  - kernel/workqueue.c:workqueue_unbound_exclude_cpumask
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/fair.c:should_we_balance
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:init_sched_groups_capacity
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
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
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
  - lib/group_cpus.c:group_cpus_evenly
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/net/phy/phy-c45.c:genphy_c45_ethtool_set_eee
  - net/core/dev.c:netif_get_num_default_rss_queues
```
**Symbols:**

```
ffffffff81851f30-ffffffff81851fb1: __bitmap_andnot (STB_GLOBAL)
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
int __bitmap_andnot(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffff80001062a910)
Location: lib/bitmap.c:209
Inline: False
Direct callers:
  - arch/arm64/kernel/fpsimd.c:sve_verify_vq_map
  - arch/arm64/kernel/fpsimd.c:sve_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
```
**Symbols:**

```
ffff80001062a910-ffff80001062a988: __bitmap_andnot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __bitmap_andnot(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c07d1afc)
Location: lib/bitmap.c:209
Inline: False
```
**Symbols:**

```
c07d1afc-c07d1b80: __bitmap_andnot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __bitmap_andnot(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c0000000007cc9d0)
Location: lib/bitmap.c:209
Inline: False
Direct callers:
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
  - arch/powerpc/kernel/rtas.c:rtas_ibm_suspend_me
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
  - arch/powerpc/mm/slice.c:slice_get_unmapped_area
  - arch/powerpc/mm/slice.c:slice_get_unmapped_area
  - arch/powerpc/platforms/powernv/subcore.c:cpu_update_split_mode
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_work_fn
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_work_fn
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_work_fn
```
**Symbols:**

```
c0000000007cc9d0-c0000000007cca68: __bitmap_andnot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __bitmap_andnot(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffe00045b24c)
Location: lib/bitmap.c:209
Inline: False
```
**Symbols:**

```
ffffffe00045b24c-ffffffe00045b2d4: __bitmap_andnot (STB_GLOBAL)
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
int __bitmap_andnot(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81519830)
Location: lib/bitmap.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/sched/isolation.c:bitmap_andnot
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
```
**Symbols:**

```
ffffffff81519830-ffffffff81519898: __bitmap_andnot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __bitmap_andnot(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81509b20)
Location: lib/bitmap.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/sched/isolation.c:bitmap_andnot
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
```
**Symbols:**

```
ffffffff81509b20-ffffffff81509b88: __bitmap_andnot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __bitmap_andnot(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815158c0)
Location: lib/bitmap.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/sched/isolation.c:bitmap_andnot
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
```
**Symbols:**

```
ffffffff815158c0-ffffffff81515928: __bitmap_andnot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __bitmap_andnot(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8152f050)
Location: lib/bitmap.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - kernel/sched/isolation.c:bitmap_andnot
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - drivers/base/cpu.c:print_cpus_isolated
  - drivers/base/cpu.c:print_cpus_offline
```
**Symbols:**

```
ffffffff8152f050-ffffffff8152f0b8: __bitmap_andnot (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
