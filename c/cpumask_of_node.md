# Function: <code>cpumask_of_node</code>

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
In arch/x86/kernel/apic/vector.c (ffffffff8105563c)
Location: arch/x86/include/asm/topology.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In kernel/workqueue.c (ffffffff8109763a)
Location: arch/x86/include/asm/topology.h:79
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/sched/core.c (ffffffff810a48b6)
Location: arch/x86/include/asm/topology.h:79
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cpu_mask
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:sched_init_smp
```
```
In kernel/sched/fair.c (ffffffff810b5642)
Location: arch/x86/include/asm/topology.h:79
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/irq/manage.c (ffffffff810dc011)
Location: arch/x86/include/asm/topology.h:79
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_affinity
```
```
In kernel/smp.c (ffffffff81103b3c)
Location: arch/x86/include/asm/topology.h:79
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
```
```
In mm/page_alloc.c (ffffffff8119203d)
Location: arch/x86/include/asm/topology.h:79
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/vmscan.c (ffffffff811a0d1a)
Location: arch/x86/include/asm/topology.h:79
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In lib/cpumask.c (0)
Location: arch/x86/include/asm/topology.h:79
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff81415e66)
Location: arch/x86/include/asm/topology.h:79
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/pci-driver.c (ffffffff8143a858)
Location: arch/x86/include/asm/topology.h:79
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff8143b9ef)
Location: arch/x86/include/asm/topology.h:79
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
```
```
In drivers/dma/dmaengine.c (ffffffff814bcd26)
Location: arch/x86/include/asm/topology.h:79
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
```
In drivers/base/node.c (ffffffff81560714)
Location: arch/x86/include/asm/topology.h:79
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
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
In arch/x86/kernel/apic/vector.c (ffffffff810558d1)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In kernel/workqueue.c (ffffffff8109ad3f)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/sched/core.c (ffffffff81fa6b61)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:cpu_cpu_mask
```
```
In kernel/sched/fair.c (ffffffff810b7c52)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/irq/manage.c (ffffffff810e173a)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_affinity
```
```
In kernel/smp.c (ffffffff8110af5d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
```
```
In mm/page_alloc.c (ffffffff811a6b05)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/vmscan.c (ffffffff811bc2c1)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/compaction.c (ffffffff811d1dd5)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In lib/cpumask.c (0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff8145dca6)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/pci-driver.c (ffffffff8148677a)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff81487900)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/dma/dmaengine.c (0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
```
```
In drivers/base/node.c (ffffffff815b4e74)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
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
In arch/x86/kernel/smpboot.c (ffffffff81053886)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
```
```
In kernel/workqueue.c (ffffffff810a129d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
```
```
In kernel/sched/core.c (ffffffff81fe26e2)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:cpu_cpu_mask
```
```
In kernel/sched/fair.c (ffffffff810be810)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/irq/manage.c (0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
```
```
In kernel/irq/affinity.c (ffffffff810efbef)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/smp.c (ffffffff8111277d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
```
```
In mm/page_alloc.c (0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
```
```
In mm/vmscan.c (ffffffff811c6e27)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
```
```
In mm/vmstat.c (ffffffff81fee8f9)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:setup_vmstat
```
```
In mm/compaction.c (ffffffff811df357)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
```
In lib/cpumask.c (0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff8147c796)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/pci-driver.c (0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffffffff814a90e0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/dma/dmaengine.c (0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
```
```
In drivers/base/node.c (ffffffff815e4121)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
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
In arch/x86/kernel/smpboot.c (ffffffff810531e6)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
```
```
In kernel/workqueue.c (ffffffff8109f221)
Location: arch/x86/include/asm/topology.h:70
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810b900f)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/topology.c (ffffffff810cbe37)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/irq/manage.c (0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
```
```
In kernel/smp.c (ffffffff81113c6d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
```
```
In mm/page_alloc.c (0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
```
```
In mm/vmscan.c (ffffffff811cf5c5)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
```
```
In mm/vmstat.c (ffffffff820d098c)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff811e8ff5)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
```
In lib/cpu_rmap.c (ffffffff81485ac6)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/pci-driver.c (0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffffffff814b2840)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/dma/dmaengine.c (0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
```
```
In drivers/base/node.c (ffffffff815f8d31)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
```
```
In lib/cpumask.c (0)
Location: arch/x86/include/asm/topology.h:70
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
In arch/x86/kernel/smpboot.c (ffffffff81056f56)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105c3a4)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/workqueue.c (ffffffff810a5911)
Location: arch/x86/include/asm/topology.h:70
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b72ce)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
```
```
In kernel/sched/fair.c (ffffffff810c10be)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/topology.c (ffffffff810d463a)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/irq/manage.c (0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
```
```
In kernel/smp.c (ffffffff8111f21d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
```
```
In mm/page_alloc.c (0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
```
```
In mm/vmscan.c (ffffffff811e4975)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
```
```
In mm/vmstat.c (ffffffff826d93c3)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff811ff355)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
```
In lib/cpu_rmap.c (ffffffff814c1be2)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/pci-driver.c (0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffffffff814f1f30)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/dma/dmaengine.c (0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
```
```
In drivers/base/node.c (ffffffff81660e80)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
```
```
In lib/cpumask.c (0)
Location: arch/x86/include/asm/topology.h:70
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
In arch/x86/kernel/smpboot.c (ffffffff81059dc3)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105f378)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/workqueue.c (ffffffff810ab7c7)
Location: arch/x86/include/asm/topology.h:70
Inline: True
```
```
In kernel/sched/core.c (ffffffff810bee7e)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
```
```
In kernel/sched/fair.c (ffffffff810c8007)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/topology.c (ffffffff810dc21a)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/irq/manage.c (ffffffff810f7f96)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/smp.c (ffffffff8112c54d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
```
```
In mm/page_alloc.c (ffffffff811f4cd2)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/vmscan.c (ffffffff81206185)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
```
```
In mm/vmstat.c (ffffffff8270386d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/compaction.c (ffffffff812207f5)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
```
In lib/cpu_rmap.c (ffffffff814f2b22)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/pci-driver.c (ffffffff81521852)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff815221d0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/dma/dmaengine.c (ffffffff815e80d5)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
```
In drivers/base/node.c (ffffffff8169c640)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
```
```
In lib/cpumask.c (ffffffff819ce101)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
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
In arch/x86/kernel/smpboot.c (ffffffff8105fa43)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81064fef)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/workqueue.c (ffffffff810b4a8f)
Location: arch/x86/include/asm/topology.h:70
Inline: True
```
```
In kernel/sched/core.c (ffffffff810c810e)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
```
```
In kernel/sched/fair.c (ffffffff810d11de)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/topology.c (ffffffff810e5e54)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/irq/manage.c (ffffffff81103708)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/smp.c (ffffffff81137e1d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
```
```
In mm/page_alloc.c (ffffffff812070b2)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/vmscan.c (ffffffff81218e05)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
```
```
In mm/vmstat.c (ffffffff828baf96)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/compaction.c (ffffffff81233845)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
```
In lib/cpu_rmap.c (ffffffff81506e52)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/pci-driver.c (ffffffff81537682)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff81538000)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/dma/dmaengine.c (ffffffff81602105)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
```
In drivers/base/node.c (ffffffff816bcfd0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
```
```
In lib/cpumask.c (ffffffff81a075c1)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
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
In arch/x86/kernel/smpboot.c (ffffffff81062e92)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810686fa)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/workqueue.c (ffffffff810bb412)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_work_node
```
```
In kernel/sched/core.c (ffffffff810cf771)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
```
```
In kernel/sched/fair.c (ffffffff810d9122)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/topology.c (ffffffff810ecab9)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/irq/manage.c (ffffffff8110c132)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/smp.c (ffffffff81142f9d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
```
```
In mm/vmscan.c (ffffffff8122881d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
```
```
In mm/vmstat.c (ffffffff828d23f7)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/compaction.c (ffffffff81243bfd)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff8126d10c)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In lib/cpu_rmap.c (ffffffff81535066)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/pci-driver.c (ffffffff81566fd3)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff815679f0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/dma/dmaengine.c (ffffffff816349dd)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
```
In drivers/base/node.c (ffffffff816f7800)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
```
```
In lib/cpumask.c (ffffffff81a76f20)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
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
In arch/x86/kernel/smpboot.c (ffffffff81063542)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81068fda)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/workqueue.c (ffffffff810c1682)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_work_node
```
```
In kernel/sched/core.c (ffffffff810d9611)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
```
```
In kernel/sched/fair.c (ffffffff810e3892)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/topology.c (ffffffff810f8559)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/irq/manage.c (ffffffff81118562)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/smp.c (ffffffff8114eadd)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
```
```
In mm/vmscan.c (ffffffff812366bd)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
```
```
In mm/vmstat.c (ffffffff828da869)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/compaction.c (ffffffff812520bd)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff8127c18c)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In lib/cpu_rmap.c (ffffffff81555e76)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/pci-driver.c (ffffffff81588333)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff81588cc0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/dma/dmaengine.c (ffffffff816566fd)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
```
In drivers/base/node.c (ffffffff8171bc60)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
```
```
In lib/cpumask.c (ffffffff81aae278)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
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
In arch/x86/kernel/smpboot.c (ffffffff81069702)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8106f6de)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In kernel/workqueue.c (ffffffff810c8415)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:queue_work_node
```
```
In kernel/sched/core.c (ffffffff810e2861)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
```
```
In kernel/sched/fair.c (ffffffff810efafc)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/topology.c (ffffffff8110258c)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/irq/manage.c (ffffffff81123e52)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/smp.c (ffffffff8115f5bd)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
```
```
In mm/vmscan.c (ffffffff81269cd6)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/vmstat.c (ffffffff82cf8c9e)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/compaction.c (ffffffff81280acd)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff812ae4b6)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:find_next_best_node
```
```
In lib/cpu_rmap.c (ffffffff815df7e5)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In lib/cpumask.c (ffffffff815e7f94)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
```
```
In drivers/pci/pci-driver.c (ffffffff8162e060)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_call_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff8162fc30)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/dma/dmaengine.c (ffffffff81706e91)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:min_chan
```
```
In drivers/base/node.c (ffffffff817d7cb0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
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
In arch/x86/kernel/smpboot.c (ffffffff8106b2e2)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81070bde)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In kernel/workqueue.c (ffffffff810c3570)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:queue_work_node
```
```
In kernel/sched/core.c (ffffffff810dc637)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
```
```
In kernel/sched/fair.c (ffffffff810edb00)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/topology.c (ffffffff811011ac)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/irq/manage.c (ffffffff8111fcb2)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/smp.c (ffffffff8115b55d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
```
```
In mm/vmscan.c (ffffffff81274806)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/vmstat.c (ffffffff82fe5976)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/compaction.c (ffffffff8128ab9d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff812ba0d6)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:find_next_best_node
```
```
In fs/io-wq.c (ffffffff8139b3ea)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_worker_affinity
  - fs/io-wq.c:create_io_worker
```
```
In lib/cpu_rmap.c (ffffffff815fcf85)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In lib/cpumask.c (ffffffff8160d0f4)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
```
```
In drivers/pci/pci-driver.c (ffffffff8165377a)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_call_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff816552c0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/dma/dmaengine.c (ffffffff817242d1)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:min_chan
```
```
In drivers/base/node.c (ffffffff817ec6c0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff81020f0a)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff8102222c)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106bd62)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810713fe)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In kernel/workqueue.c (ffffffff810c42e9)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:queue_work_node
```
```
In kernel/sched/core.c (ffffffff810ddb5e)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
```
```
In kernel/sched/fair.c (ffffffff810efb60)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/topology.c (ffffffff8110355e)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/irq/manage.c (ffffffff8111ff62)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/smp.c (ffffffff8115cc21)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
```
```
In mm/vmscan.c (ffffffff81279b16)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/vmstat.c (ffffffff831eff75)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/compaction.c (ffffffff81290258)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff812bf080)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:find_next_best_node
```
```
In fs/io-wq.c (ffffffff813a1f15)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_worker_affinity
  - fs/io-wq.c:create_io_worker
```
```
In lib/cpu_rmap.c (ffffffff815dfd0e)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In lib/cpumask.c (ffffffff815f0905)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
```
```
In drivers/pci/pci-driver.c (ffffffff816370fd)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff81637ef0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/dma/dmaengine.c (ffffffff81705541)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:min_chan
```
```
In drivers/base/node.c (ffffffff817d0f30)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff81024ae3)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81025d9b)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
```
```
In arch/x86/kernel/smpboot.c (ffffffff81076872)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8107d198)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In kernel/workqueue.c (ffffffff810d6ebc)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:queue_work_node
```
```
In kernel/sched/core.c (ffffffff810f2312)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
```
```
In kernel/sched/fair.c (ffffffff81108515)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/topology.c (ffffffff811202ff)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/irq/manage.c (ffffffff81140472)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/smp.c (ffffffff81181e11)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
```
```
In mm/vmscan.c (ffffffff812b7abd)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/vmstat.c (ffffffff832d56ef)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/compaction.c (ffffffff812d028c)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff81301700)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:find_next_best_node
```
```
In fs/io-wq.c (ffffffff813f32bd)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_cpu_affinity
  - fs/io-wq.c:io_wq_create
```
```
In lib/cpu_rmap.c (ffffffff8164b958)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In lib/cpumask.c (ffffffff8165d9ec)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
```
```
In drivers/pci/pci-driver.c (ffffffff816a7340)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff816a8166)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/dma/dmaengine.c (ffffffff81780d20)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:min_chan
```
```
In drivers/base/node.c (ffffffff8185b8f2)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/base/node.c:cpulist_read
  - drivers/base/node.c:cpumap_read
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff81026c48)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81029dfd)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
```
```
In arch/x86/kernel/smpboot.c (ffffffff810856b2)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8108c848)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In kernel/workqueue.c (ffffffff810f375e)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:queue_work_node
```
```
In kernel/sched/core.c (ffffffff8110e132)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
```
```
In kernel/sched/fair.c (ffffffff81123447)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/build_utility.c (ffffffff8114a81e)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:cpu_cpu_mask
```
```
In kernel/irq/manage.c (ffffffff81163d98)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/smp.c (ffffffff811b8591)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
```
```
In mm/vmscan.c (ffffffff8131288e)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/vmstat.c (ffffffff83489f3f)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/compaction.c (ffffffff8132ecbc)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff81369010)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:find_next_best_node
```
```
In io_uring/io-wq.c (ffffffff816dbe46)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_cpu_affinity
  - io_uring/io-wq.c:io_wq_create
```
```
In lib/cpu_rmap.c (ffffffff8176245b)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In lib/cpumask.c (ffffffff81776fc0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
```
```
In drivers/pci/pci-driver.c (ffffffff817c8d76)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_call_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff817cad05)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/dma/dmaengine.c (ffffffff818b796f)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
```
In drivers/base/node.c (ffffffff819a28fb)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/base/node.c:cpulist_read
  - drivers/base/node.c:cpumap_read
```
```
In drivers/nvdimm/nd_perf.c (ffffffff819d93f7)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102dea0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff810308c1)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81083376)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
```
```
In arch/x86/kernel/smpboot.c (ffffffff81098a02)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810a0e28)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In kernel/workqueue.c (ffffffff8111589e)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:queue_work_node
```
```
In kernel/sched/core.c (ffffffff81134e6d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
```
```
In kernel/sched/fair.c (ffffffff8114b3ed)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/build_utility.c (ffffffff811791ae)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:cpu_cpu_mask
```
```
In kernel/irq/manage.c (ffffffff81197ab8)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/smp.c (ffffffff811f98ed)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
```
```
In mm/vmscan.c (ffffffff81385cdd)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/vmstat.c (ffffffff83eba89f)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/compaction.c (ffffffff813a586c)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff813e51bf)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:find_next_best_node
```
```
In io_uring/io-wq.c (ffffffff817a7f4e)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_cpu_affinity
  - io_uring/io-wq.c:io_wq_create
```
```
In lib/cpu_rmap.c (ffffffff8189134e)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/pci-driver.c (ffffffff818e667b)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_call_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff818e88a5)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/dma/dmaengine.c (ffffffff81a04b8a)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
```
In drivers/base/node.c (ffffffff81b148b0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/base/node.c:cpulist_read
  - drivers/base/node.c:cpumap_read
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81b54466)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In lib/cpumask.c (ffffffff8201f9c8)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
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
In arch/x86/events/intel/uncore.c (ffffffff8102487d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_device_to_die
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81085826)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109bbb2)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810a3e18)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In kernel/workqueue.c (ffffffff81122474)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:queue_work_node
```
```
In kernel/sched/core.c (ffffffff8114406d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
```
```
In kernel/sched/fair.c (ffffffff8115d64d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/build_utility.c (ffffffff81189d9e)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:cpu_cpu_mask
```
```
In kernel/irq/manage.c (ffffffff811a9778)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/smp.c (ffffffff8120ef8d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
```
```
In mm/vmscan.c (ffffffff813b8f9d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/vmstat.c (ffffffff836dfeaf)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/compaction.c (ffffffff813d8ebc)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff81419c0f)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:find_next_best_node
```
```
In lib/cpu_rmap.c (ffffffff818d365e)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/pci-driver.c (ffffffff81929cbb)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_call_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff8192beb5)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/dma/dmaengine.c (ffffffff81a4d9ea)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
```
In drivers/base/node.c (ffffffff81b63620)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/base/node.c:cpulist_read
  - drivers/base/node.c:cpumap_read
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81ba79b6)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
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
In arch/x86/events/intel/uncore.c (ffffffff8102a9ad)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_device_to_die
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108c87b)
Location: arch/x86/include/asm/topology.h:70
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a3132)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810aae48)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In kernel/workqueue.c (ffffffff8112b947)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_work_node
```
```
In kernel/sched/core.c (ffffffff8114f58d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
```
```
In kernel/sched/fair.c (ffffffff8116896d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/build_utility.c (ffffffff8119869e)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:cpu_cpu_mask
```
```
In kernel/irq/manage.c (ffffffff811b92d8)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/smp.c (ffffffff8122672d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
```
```
In mm/vmscan.c (ffffffff813e1f9d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/vmstat.c (ffffffff8391275f)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/compaction.c (ffffffff81402c3c)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff81446a22)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:find_next_best_node
```
```
In lib/cpu_rmap.c (ffffffff8192573e)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/pci-driver.c (ffffffff819724bb)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_call_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff819747a5)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/dma/dmaengine.c (ffffffff81a9968a)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
```
In drivers/base/node.c (ffffffff81bb7130)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/base/node.c:cpulist_read
  - drivers/base/node.c:cpumap_read
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81bfbd22)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
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
In kernel/workqueue.c (ffff80001011d854)
Location: arch/arm64/include/asm/numa.h:26
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:queue_work_node
```
```
In kernel/sched/core.c (ffff800010139470)
Location: arch/arm64/include/asm/numa.h:26
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
```
```
In kernel/sched/fair.c (ffff800010143940)
Location: arch/arm64/include/asm/numa.h:26
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/topology.c (ffff80001015cb6c)
Location: arch/arm64/include/asm/numa.h:26
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/irq/manage.c (ffff80001017adb8)
Location: arch/arm64/include/asm/numa.h:26
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/smp.c (ffff8000101bd160)
Location: arch/arm64/include/asm/numa.h:26
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
```
```
In mm/vmscan.c (ffff8000102c62b4)
Location: arch/arm64/include/asm/numa.h:26
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
```
```
In mm/vmstat.c (ffff800011453490)
Location: arch/arm64/include/asm/numa.h:26
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/compaction.c (ffff8000102e8be4)
Location: arch/arm64/include/asm/numa.h:26
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffff80001031376c)
Location: arch/arm64/include/asm/numa.h:26
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In lib/cpu_rmap.c (ffff800010662918)
Location: arch/arm64/include/asm/numa.h:26
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010672db4)
Location: arch/arm64/include/asm/numa.h:26
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_activate
  - drivers/irqchip/irq-gic-v3-its.c:its_set_affinity
```
```
In drivers/pci/pci-driver.c (ffff8000106ec734)
Location: arch/arm64/include/asm/numa.h:26
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (ffff8000106ed40c)
Location: arch/arm64/include/asm/numa.h:26
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/dma/dmaengine.c (0)
Location: arch/arm64/include/asm/numa.h:26
Inline: True
```
```
In drivers/base/node.c (ffff80001090f59c)
Location: arch/arm64/include/asm/numa.h:26
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
```
```
In drivers/base/arch_topology.c (ffff800010920504)
Location: arch/arm64/include/asm/numa.h:26
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:cpu_coregroup_mask
```
```
In lib/cpumask.c (ffff800010d84624)
Location: arch/arm64/include/asm/numa.h:26
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In arch/x86/kernel/smpboot.c (ffffffff81063032)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81068aca)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/workqueue.c (ffffffff810bb9f2)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_work_node
```
```
In kernel/sched/core.c (ffffffff810d3ae1)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
```
```
In kernel/sched/fair.c (ffffffff810dda42)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/topology.c (ffffffff810f1959)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/irq/manage.c (ffffffff81110b42)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/smp.c (ffffffff811470fd)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
```
```
In mm/vmscan.c (ffffffff8122ed0d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
```
```
In mm/vmstat.c (ffffffff828c371d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/compaction.c (ffffffff8124a70d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff812747dc)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In lib/cpu_rmap.c (ffffffff8154e456)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/pci-driver.c (ffffffff8157c1c3)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157cb50)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/dma/dmaengine.c (ffffffff8161c59d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
```
In drivers/base/node.c (ffffffff816e1f90)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
```
```
In lib/cpumask.c (ffffffff81a4d0c8)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
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
In arch/x86/kernel/smpboot.c (ffffffff81053342)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81058e3a)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/workqueue.c (ffffffff810aa478)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_work_node
```
```
In kernel/sched/core.c (ffffffff810c2111)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
```
```
In kernel/sched/fair.c (ffffffff810cca52)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/topology.c (ffffffff810e19c9)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/irq/manage.c (ffffffff81101872)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/smp.c (ffffffff8113a3dd)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
```
```
In mm/vmscan.c (ffffffff81221dcd)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
```
```
In mm/vmstat.c (ffffffff828bbe42)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/compaction.c (ffffffff8123d6bd)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff8126674c)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In lib/cpu_rmap.c (ffffffff8153e736)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/pci-driver.c (ffffffff8156af93)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff8156b920)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/dma/dmaengine.c (ffffffff81610c8d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
```
In drivers/base/node.c (ffffffff816bc5d0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
```
```
In drivers/scsi/storvsc_drv.c (ffffffff81714360)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/scsi/storvsc_drv.c:storvsc_queuecommand
  - drivers/scsi/storvsc_drv.c:storvsc_queuecommand
```
```
In drivers/hv/channel_mgmt.c (ffffffff81852a6c)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/hv/channel_mgmt.c:init_vp_index
  - drivers/hv/channel_mgmt.c:init_vp_index
  - drivers/hv/channel_mgmt.c:init_vp_index
  - drivers/hv/channel_mgmt.c:init_vp_index
  - drivers/hv/channel_mgmt.c:init_vp_index
```
```
In lib/cpumask.c (ffffffff81a0a1f8)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
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
In arch/x86/kernel/smpboot.c (ffffffff810634e2)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81068f7a)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/workqueue.c (ffffffff810baf52)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_work_node
```
```
In kernel/sched/core.c (ffffffff810d0d41)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
```
```
In kernel/sched/fair.c (ffffffff810d9dc2)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/topology.c (ffffffff810eea89)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/irq/manage.c (ffffffff8110ea32)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/smp.c (ffffffff81144fad)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
```
```
In mm/vmscan.c (ffffffff8122caad)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
```
```
In mm/vmstat.c (ffffffff828d649d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/compaction.c (ffffffff812484ad)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff8127257c)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In lib/cpu_rmap.c (ffffffff8154a196)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/pci-driver.c (ffffffff8157c083)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157ca10)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/dma/dmaengine.c (ffffffff8164a53d)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
```
In drivers/base/node.c (ffffffff8170f4c0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
```
```
In lib/cpumask.c (ffffffff81ab94b8)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
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
In arch/x86/kernel/smpboot.c (ffffffff81064aa2)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8106a67e)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/workqueue.c (ffffffff810c2802)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_work_node
```
```
In kernel/sched/core.c (ffffffff810db281)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
```
```
In kernel/sched/fair.c (ffffffff810e57e6)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/topology.c (ffffffff810f9ac9)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/irq/manage.c (ffffffff81119f60)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/smp.c (ffffffff81151b71)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
```
```
In mm/vmscan.c (ffffffff8123bedd)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
```
```
In mm/vmstat.c (ffffffff828db8be)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/compaction.c (ffffffff81257cdd)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff81281eac)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In lib/cpu_rmap.c (ffffffff81563fe6)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/pci-driver.c (ffffffff81596533)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff81596ec0)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/dma/dmaengine.c (ffffffff81664add)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_channel_rebalance
```
```
In drivers/base/node.c (ffffffff8172a280)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
```
```
In lib/cpumask.c (ffffffff81ac5908)
Location: arch/x86/include/asm/topology.h:70
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
```
</details>
</li>
</ul>

## Differences
