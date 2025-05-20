# Function: <code>zalloc_cpumask_var</code>

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
In arch/x86/xen/smp.c (ffffffff81f64fa3)
Location: include/linux/cpumask.h:680
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81f69630)
Location: include/linux/cpumask.h:680
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:init_amd_e400_c1e_mask
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81f6af01)
Location: include/linux/cpumask.h:680
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
```
```
In arch/x86/kernel/smpboot.c (ffffffff81f6f7c0)
Location: include/linux/cpumask.h:680
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059e38)
Location: include/linux/cpumask.h:680
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
  - arch/x86/kernel/apic/x2apic_cluster.c:update_clusterinfo
  - arch/x86/kernel/apic/x2apic_cluster.c:update_clusterinfo
```
```
In kernel/workqueue.c (ffffffff8109d176)
Location: include/linux/cpumask.h:680
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:wq_unbound_cpumask_store
```
```
In kernel/sched/core.c (ffffffff810a5d72)
Location: include/linux/cpumask.h:680
Inline: True
Inline callers:
  - kernel/sched/core.c:init_rootdomain
  - kernel/sched/core.c:init_rootdomain
  - kernel/sched/core.c:init_rootdomain
  - kernel/sched/core.c:init_rootdomain
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff81f7e4a7)
Location: include/linux/cpumask.h:680
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_sched_fair_class
```
```
In kernel/sched/cpupri.c (ffffffff810c428d)
Location: include/linux/cpumask.h:680
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffff810c48af)
Location: include/linux/cpumask.h:680
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/irq/proc.c (ffffffff810e1ae9)
Location: include/linux/cpumask.h:680
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/time/tick-broadcast.c (ffffffff81f809ab)
Location: include/linux/cpumask.h:680
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
```
```
In kernel/smp.c (ffffffff81103faf)
Location: include/linux/cpumask.h:680
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond
```
```
In kernel/trace/trace.c (ffffffff811501de)
Location: include/linux/cpumask.h:680
Inline: True
Inline callers:
  - kernel/trace/trace.c:__tracing_open
```
```
In block/blk-mq-tag.c (ffffffff813c7845)
Location: include/linux/cpumask.h:680
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In lib/cpu_rmap.c (ffffffff81415dc6)
Location: include/linux/cpumask.h:680
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/acpi_processor.c (ffffffff81482192)
Location: include/linux/cpumask.h:680
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
```
In drivers/acpi/processor_throttling.c (ffffffff814ada1b)
Location: include/linux/cpumask.h:680
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff814af34a)
Location: include/linux/cpumask.h:680
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/cpufreq/cpufreq.c (ffffffff816b1cdc)
Location: include/linux/cpumask.h:680
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff816b66ef)
Location: include/linux/cpumask.h:680
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff816b87ba)
Location: include/linux/cpumask.h:680
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff816b978d)
Location: include/linux/cpumask.h:680
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In net/core/net-sysfs.c (ffffffff817363be)
Location: include/linux/cpumask.h:680
Inline: True
Inline callers:
  - net/core/net-sysfs.c:show_xps_map
  - net/core/net-sysfs.c:show_rps_map
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
In arch/x86/xen/smp.c (ffffffff81f8cb64)
Location: include/linux/cpumask.h:682
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81f9151f)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:init_amd_e400_c1e_mask
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81f931fe)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
```
```
In arch/x86/kernel/smpboot.c (ffffffff81f97eac)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105a0da)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In kernel/workqueue.c (ffffffff810a0a1e)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
```
```
In kernel/sched/core.c (ffffffff81fa72d6)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff81fa7378)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_sched_fair_class
```
```
In kernel/sched/cpupri.c (ffffffff810c7f7d)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffff810c855d)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/irq/irqdesc.c (ffffffff81fa7f25)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/proc.c (ffffffff810e7589)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/time/tick-broadcast.c (ffffffff81fa9a15)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
```
```
In kernel/smp.c (ffffffff8110b3bf)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond
```
```
In kernel/trace/trace.c (ffffffff811591aa)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - kernel/trace/trace.c:__tracing_open
```
```
In block/blk-mq-tag.c (ffffffff8140ba80)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In lib/cpu_rmap.c (ffffffff8145dc06)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/acpi_processor.c (ffffffff814d0c9b)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
```
In drivers/acpi/processor_throttling.c (ffffffff814fd41e)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff814fecb6)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81713e76)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff817181ad)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8171a516)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff8171b18d)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In net/core/net-sysfs.c (ffffffff817a2564)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - net/core/net-sysfs.c:show_xps_map
  - net/core/net-sysfs.c:show_rps_map
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool zalloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8144b620)
Location: lib/cpumask.c:99
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_prepare_cpus
  - arch/x86/xen/smp.c:xen_smp_prepare_cpus
  - arch/x86/xen/smp.c:xen_smp_prepare_cpus
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:init_rootdomain
  - kernel/sched/core.c:init_rootdomain
  - kernel/sched/core.c:init_rootdomain
  - kernel/sched/core.c:init_rootdomain
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/smp.c:on_each_cpu_cond
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:__tracing_open
  - lib/cpu_rmap.c:cpu_rmap_update
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - net/core/net-sysfs.c:show_xps_map
  - net/core/net-sysfs.c:show_rps_map
```
**Symbols:**

```
ffffffff8144b620-ffffffff8144b636: zalloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool zalloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff818ebce0)
Location: lib/cpumask.c:131
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/sched/core.c:sched_init
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:irq_affinity_setup
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/smp.c:on_each_cpu_cond
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:__tracing_open
  - kernel/events/core.c:perf_event_init
  - lib/cpu_rmap.c:cpu_rmap_update
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - net/core/net-sysfs.c:show_xps_map
  - net/core/net-sysfs.c:show_rps_map
```
**Symbols:**

```
ffffffff818ebce0-ffffffff818ebcf6: zalloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool zalloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81971cc0)
Location: lib/cpumask.c:148
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/membarrier.c:SyS_membarrier
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/smp.c:on_each_cpu_cond
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:__tracing_open
  - kernel/events/core.c:perf_event_init
  - lib/cpu_rmap.c:cpu_rmap_update
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
```
**Symbols:**

```
ffffffff81971cc0-ffffffff81971cd6: zalloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool zalloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff819ce070)
Location: lib/cpumask.c:149
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/smp.c:on_each_cpu_cond
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:__tracing_open
  - kernel/events/core.c:perf_event_init
  - lib/cpu_rmap.c:cpu_rmap_update
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
```
**Symbols:**

```
ffffffff819ce070-ffffffff819ce086: zalloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool zalloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a07530)
Location: lib/cpumask.c:149
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:__tracing_open
  - kernel/events/core.c:perf_event_init
  - lib/cpu_rmap.c:cpu_rmap_update
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
```
**Symbols:**

```
ffffffff81a07530-ffffffff81a07546: zalloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool zalloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a76e90)
Location: lib/cpumask.c:150
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:__tracing_open
  - kernel/events/core.c:perf_event_init
  - lib/cpu_rmap.c:cpu_rmap_update
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
```
**Symbols:**

```
ffffffff81a76e90-ffffffff81a76ea6: zalloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool zalloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81aae390)
Location: lib/cpumask.c:150
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:__tracing_open
  - kernel/events/core.c:perf_event_init
  - lib/cpu_rmap.c:cpu_rmap_update
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
```
**Symbols:**

```
ffffffff81aae390-ffffffff81aae3a6: zalloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool zalloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff815e80b0)
Location: lib/cpumask.c:150
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/irq/irqdesc.c:init_irq_default_affinity
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:__tracing_open
  - kernel/events/core.c:perf_event_init_all_cpus
  - lib/cpu_rmap.c:cpu_rmap_update
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
```
**Symbols:**

```
ffffffff815e80b0-ffffffff815e80c6: zalloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool zalloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8160d210)
Location: lib/cpumask.c:150
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/irq/irqdesc.c:init_irq_default_affinity
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:__tracing_open
  - kernel/events/core.c:perf_event_init_all_cpus
  - lib/cpu_rmap.c:cpu_rmap_update
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
```
**Symbols:**

```
ffffffff8160d210-ffffffff8160d226: zalloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool zalloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff815f06b0)
Location: lib/cpumask.c:150
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:__tracing_open
  - kernel/events/core.c:perf_event_init
  - lib/cpu_rmap.c:cpu_rmap_update
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - net/core/net-sysfs.c:show_rps_map
```
**Symbols:**

```
ffffffff815f06b0-ffffffff815f06c6: zalloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool zalloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8165d790)
Location: lib/cpumask.c:150
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/time/hrtimer.c:clock_was_set
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:__tracing_open
  - kernel/events/core.c:perf_event_init
  - lib/cpu_rmap.c:cpu_rmap_update
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - net/core/net-sysfs.c:show_rps_map
```
**Symbols:**

```
ffffffff8165d790-ffffffff8165d7a6: zalloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool zalloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81776cf0)
Location: lib/cpumask.c:150
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/build_policy.c:cpudl_init
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:cpupri_init
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/time/hrtimer.c:clock_was_set
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:__tracing_open
  - kernel/events/core.c:perf_event_init
  - lib/cpu_rmap.c:cpu_rmap_update
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - net/core/dev.c:netif_get_num_default_rss_queues
  - net/core/net-sysfs.c:show_rps_map
```
**Symbols:**

```
ffffffff81776cf0-ffffffff81776d10: zalloc_cpumask_var (STB_GLOBAL)
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff83e7f6dd)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108954e)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8108b988)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108e1c1)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In arch/x86/kernel/smpboot.c (ffffffff83e8997a)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a95af)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In kernel/workqueue.c (ffffffff81117d9b)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
```
```
In kernel/sched/fair.c (ffffffff83ea8927)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_sched_fair_class
```
```
In kernel/sched/build_policy.c (ffffffff81160e21)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_init
```
```
In kernel/sched/build_utility.c (ffffffff8116dc8a)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:cpupri_init
```
```
In kernel/irq/irqdesc.c (ffffffff83eab1e4)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:init_irq_default_affinity
```
```
In kernel/irq/proc.c (ffffffff811a1c6b)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (ffffffff811a66df)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
```
In kernel/profile.c (ffffffff811d197b)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
```
```
In kernel/time/hrtimer.c (ffffffff811d9f66)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set
```
```
In kernel/time/tick-broadcast.c (ffffffff83eae865)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
```
```
In kernel/cgroup/cpuset.c (ffffffff8121dd70)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/trace/ring_buffer.c (ffffffff8125e6dc)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff81270791)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/events/core.c (ffffffff83eb93ec)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In lib/cpu_rmap.c (ffffffff818912bf)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/pci-driver.c (ffffffff818e663e)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_call_probe
```
```
In drivers/acpi/acpi_processor.c (ffffffff8196595c)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
```
In drivers/acpi/processor_throttling.c (ffffffff819d655b)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff819d7fae)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/base/power/domain.c (ffffffff81b0c1ca)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff83efed3a)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d2ddc2)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d36b99)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81d3906a)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff81d3bd63)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In net/core/dev.c (ffffffff81dc21d9)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
```
```
In net/core/net-sysfs.c (ffffffff81e0b16b)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - net/core/net-sysfs.c:show_rps_map
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8369ddb5)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_ap_register
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff836a242d)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81089b43)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8108e8d8)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81091071)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In arch/x86/kernel/smpboot.c (ffffffff836ad036)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810acee9)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In kernel/workqueue.c (ffffffff81124fbb)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
```
```
In kernel/sched/core.c (ffffffff8114c5b2)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
```
```
In kernel/sched/fair.c (ffffffff836cd373)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_sched_fair_class
```
```
In kernel/sched/build_policy.c (ffffffff81171571)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_init
```
```
In kernel/sched/build_utility.c (ffffffff8117e250)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:cpupri_init
```
```
In kernel/irq/irqdesc.c (ffffffff836d01a4)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:init_irq_default_affinity
```
```
In kernel/irq/proc.c (ffffffff811b3901)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/profile.c (ffffffff811e5c11)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
```
```
In kernel/time/hrtimer.c (ffffffff811ee456)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set
```
```
In kernel/time/tick-broadcast.c (ffffffff836d3825)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
```
```
In kernel/compat.c (ffffffff81217e82)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
```
In kernel/cgroup/cpuset.c (ffffffff81233e70)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/trace/ring_buffer.c (ffffffff812758bc)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff81280c98)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/trace_osnoise.c (ffffffff81297633)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:osnoise_cpus_write
```
```
In kernel/events/core.c (ffffffff836dea1c)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In lib/cpu_rmap.c (ffffffff818d35cf)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In lib/group_cpus.c (ffffffff818e70f1)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - lib/group_cpus.c:group_cpus_evenly
  - lib/group_cpus.c:group_cpus_evenly
  - lib/group_cpus.c:group_cpus_evenly
```
```
In drivers/pci/pci-driver.c (ffffffff81929c7e)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_call_probe
```
```
In drivers/acpi/acpi_processor.c (ffffffff819abebc)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a1de9b)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff81a1f9b2)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/base/power/domain.c (ffffffff81b5a20a)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/net/virtio_net.c (ffffffff81c4cdbe)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_affinity
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff83724bb2)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d97032)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d9ff46)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81da3b0a)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff81da68c3)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In net/core/dev.c (ffffffff81e31739)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
```
```
In net/core/net-sysfs.c (ffffffff81e7e51b)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - net/core/net-sysfs.c:show_rps_map
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
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff838cd975)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_ap_register
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff838d252d)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81090c5c)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81095c68)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81098431)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
```
```
In arch/x86/kernel/smpboot.c (ffffffff838dd527)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b3b09)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In kernel/workqueue.c (ffffffff838fbcbf)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - kernel/workqueue.c:init_pod_type
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_unbound_exclude_cpumask
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (ffffffff81158272)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
```
```
In kernel/sched/fair.c (ffffffff838fe781)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_sched_fair_class
```
```
In kernel/sched/build_policy.c (ffffffff8117ee81)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_init
```
```
In kernel/sched/build_utility.c (ffffffff8118fb9e)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:init_rootdomain
  - kernel/sched/build_utility.c:cpupri_init
```
```
In kernel/irq/irqdesc.c (ffffffff839015c4)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:init_irq_default_affinity
```
```
In kernel/irq/proc.c (ffffffff811c3781)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/rcu/tree.c (ffffffff83903bce)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_nohz
```
```
In kernel/profile.c (ffffffff811fb961)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
```
```
In kernel/time/hrtimer.c (ffffffff812045d6)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set
```
```
In kernel/time/tick-broadcast.c (ffffffff839055e5)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
```
```
In kernel/compat.c (ffffffff8122fa42)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
```
In kernel/cgroup/cpuset.c (ffffffff8124dac0)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/trace/ring_buffer.c (ffffffff8129011c)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff8129aeca)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create_systems
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b2c83)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:osnoise_cpus_write
```
```
In kernel/events/core.c (ffffffff8391105c)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In lib/cpu_rmap.c (ffffffff819256af)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In lib/group_cpus.c (ffffffff8192e111)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - lib/group_cpus.c:group_cpus_evenly
  - lib/group_cpus.c:group_cpus_evenly
  - lib/group_cpus.c:group_cpus_evenly
```
```
In drivers/pci/pci-driver.c (ffffffff8197247e)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_call_probe
```
```
In drivers/acpi/acpi_processor.c (ffffffff819f628b)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a691ab)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff81a6acd2)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/pmdomain/core.c (ffffffff81aa1c04)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - drivers/pmdomain/core.c:pm_genpd_init
```
```
In drivers/net/virtio_net.c (ffffffff81d0265e)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_affinity
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff83958a22)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e4ecc1)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81e57dc5)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81e5bb9a)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff81e5e953)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In net/core/dev.c (ffffffff81eefeb9)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
```
```
In net/core/net-sysfs.c (ffffffff81f3f42b)
Location: include/linux/cpumask.h:918
Inline: True
Inline callers:
  - net/core/net-sysfs.c:show_rps_map
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
In virt/kvm/kvm_main.c (ffff8000100b6ae0)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_init
  - virt/kvm/kvm_main.c:kvm_make_all_cpus_request
```
```
In kernel/workqueue.c (ffff8000101232d0)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
```
```
In kernel/sched/fair.c (ffff800011445088)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_sched_fair_class
```
```
In kernel/sched/cpupri.c (ffff80001015a044)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffff80001015a898)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/topology.c (ffff80001015d224)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
```
```
In kernel/sched/membarrier.c (ffff800010166268)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__arm64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:767
Inline: True
```
```
In kernel/irq/proc.c (ffff800010185788)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (ffff8000101881d8)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffff800011449108)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
```
```
In kernel/smp.c (ffff8000101bd7b8)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
```
```
In kernel/cgroup/cpuset.c (ffff8000101e3f08)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/trace/ring_buffer.c (ffff80001021a130)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffff800010226618)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/events/core.c (ffff800011451240)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_all_cpus
```
```
In lib/cpu_rmap.c (ffff80001066286c)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/acpi_processor.c (ffff80001076f648)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
```
In drivers/acpi/processor_perflib.c (ffff8000107a3a18)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffff8000107a8cbc)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/base/power/domain.c (ffff800010907f80)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b216b8)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In net/core/net-sysfs.c (ffff800010c0b96c)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
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
Location: include/linux/cpumask.h:767
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:767
Inline: True
```
```
In kernel/sched/cpupri.c (c03a6dfc)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (c03a7534)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/topology.c (c03a78a4)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/cpumask.h:767
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:767
Inline: True
```
```
In kernel/irq/proc.c (0)
Location: include/linux/cpumask.h:767
Inline: True
```
```
In kernel/irq/affinity.c (c03d6c04)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/time/tick-broadcast.c (c15231ec)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
```
```
In kernel/smp.c (0)
Location: include/linux/cpumask.h:767
Inline: True
```
```
In kernel/cgroup/cpuset.c (c152583c)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/trace/ring_buffer.c (c04575e8)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (c0463d04)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/events/core.c (c152bd34)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In lib/cpu_rmap.c (c080b4dc)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/base/power/domain.c (c09f2454)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/cpufreq/cpufreq.c (c0bfbcf8)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:767
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
In arch/powerpc/sysdev/xive/common.c (c0000000000be434)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_pick_irq_target
```
```
In arch/powerpc/platforms/pseries/hotplug-cpu.c (c0000000000f9f3c)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
```
```
In kernel/workqueue.c (c00000000016d1d4)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
```
```
In kernel/sched/fair.c (c0000000013699a0)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_sched_fair_class
```
```
In kernel/sched/cpupri.c (c0000000001ae2e4)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (c0000000001aeb6c)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/topology.c (c0000000001b1d68)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
```
```
In kernel/sched/membarrier.c (c0000000001bd270)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:767
Inline: True
```
```
In kernel/irq/proc.c (c0000000001dfc28)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (c0000000001e1f24)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (c00000000136e56c)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
```
```
In kernel/smp.c (c000000000223c2c)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
```
```
In kernel/cgroup/cpuset.c (c00000000025438c)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/trace/ring_buffer.c (c00000000029d434)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (c0000000002ac494)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/events/core.c (c000000001378cb4)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In lib/cpu_rmap.c (c0000000008169dc)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/base/power/domain.c (c0000000009a7b00)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/cpufreq/cpufreq.c (c000000000c15634)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In net/core/net-sysfs.c (c000000000cf6a04)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
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
Location: include/linux/cpumask.h:767
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:767
Inline: True
```
```
In kernel/sched/cpupri.c (ffffffe0000ffa98)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffe00010010c)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/topology.c (ffffffe000100214)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/cpumask.h:767
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/linux/cpumask.h:767
Inline: True
```
```
In kernel/irq/proc.c (0)
Location: include/linux/cpumask.h:767
Inline: True
```
```
In kernel/irq/affinity.c (ffffffe00011d99c)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/smp.c (0)
Location: include/linux/cpumask.h:767
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffe00015763c)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/trace/ring_buffer.c (ffffffe000177e3a)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffe00018139e)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/events/core.c (0)
Location: include/linux/cpumask.h:767
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/cpumask.h:767
Inline: True
```
```
In drivers/base/power/domain.c (ffffffe00058daf8)
Location: include/linux/cpumask.h:767
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:767
Inline: True
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
bool zalloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a4d1e0)
Location: lib/cpumask.c:150
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:__tracing_open
  - kernel/events/core.c:perf_event_init
  - lib/cpu_rmap.c:cpu_rmap_update
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
```
**Symbols:**

```
ffffffff81a4d1e0-ffffffff81a4d1f6: zalloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool zalloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a0a310)
Location: lib/cpumask.c:150
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/rcu/tree.c:rcu_init_nohz
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:__tracing_open
  - kernel/events/core.c:perf_event_init
  - lib/cpu_rmap.c:cpu_rmap_update
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
```
**Symbols:**

```
ffffffff81a0a310-ffffffff81a0a326: zalloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool zalloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81ab95d0)
Location: lib/cpumask.c:150
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:__tracing_open
  - kernel/events/core.c:perf_event_init
  - lib/cpu_rmap.c:cpu_rmap_update
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
```
**Symbols:**

```
ffffffff81ab95d0-ffffffff81ab95e6: zalloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool zalloc_cpumask_var(cpumask_var_t *mask, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81ac5a20)
Location: lib/cpumask.c:150
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_locked_in_hierarchy
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/cpupri.c:cpupri_init
  - kernel/sched/cpudeadline.c:cpudl_init
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/trace.c:__tracing_open
  - kernel/events/core.c:perf_event_init
  - lib/cpu_rmap.c:cpu_rmap_update
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/base/power/domain.c:pm_genpd_init
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
```
**Symbols:**

```
ffffffff81ac5a20-ffffffff81ac5a36: zalloc_cpumask_var (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
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
