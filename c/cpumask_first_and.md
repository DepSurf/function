# Function: <code>cpumask_first_and</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101ede2)
Location: include/linux/cpumask.h:228
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8103eb9f)
Location: include/linux/cpumask.h:228
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
```
In kernel/workqueue.c (ffffffff810f1ad3)
Location: include/linux/cpumask.h:228
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:wq_select_unbound_cpu
```
```
In kernel/sched/core.c (ffffffff811195e6)
Location: include/linux/cpumask.h:228
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
```
```
In kernel/sched/build_policy.c (ffffffff8113458a)
Location: include/linux/cpumask.h:228
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_task_offline_migration
```
```
In kernel/sched/build_utility.c (ffffffff8114acbc)
Location: include/linux/cpumask.h:228
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_any_cpu
  - kernel/sched/build_utility.c:sched_numa_find_closest
  - kernel/sched/build_utility.c:cpupri_find_fitness
```
```
In kernel/irq/chip.c (ffffffff811677bb)
Location: include/linux/cpumask.h:228
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/migration.c (ffffffff8116d6b5)
Location: include/linux/cpumask.h:228
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
```
```
In kernel/irq/cpuhotplug.c (ffffffff8116d920)
Location: include/linux/cpumask.h:228
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
```
```
In kernel/smp.c (ffffffff811b7e2f)
Location: include/linux/cpumask.h:228
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
```
```
In mm/compaction.c (ffffffff8132ecd8)
Location: include/linux/cpumask.h:228
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
```
```
In block/blk-mq.c (ffffffff8168a68a)
Location: include/linux/cpumask.h:228
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
```
```
In lib/cpumask.c (ffffffff81776d85)
Location: include/linux/cpumask.h:228
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_and_distribute
```
```
In drivers/pci/pci-driver.c (ffffffff817c8d7f)
Location: include/linux/cpumask.h:228
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_call_probe
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff8196ef17)
Location: include/linux/cpumask.h:228
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff81b9a999)
Location: include/linux/cpumask.h:228
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
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
In arch/x86/events/intel/uncore.c (ffffffff810234d2)
Location: include/linux/cpumask.h:151
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81047b8f)
Location: include/linux/cpumask.h:151
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
```
In kernel/workqueue.c (ffffffff811151e8)
Location: include/linux/cpumask.h:151
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:wq_select_unbound_cpu
```
```
In kernel/sched/core.c (ffffffff81140ec6)
Location: include/linux/cpumask.h:151
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
```
```
In kernel/sched/build_policy.c (ffffffff8115eaab)
Location: include/linux/cpumask.h:151
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_task_offline_migration
```
```
In kernel/sched/build_utility.c (ffffffff81179670)
Location: include/linux/cpumask.h:151
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_any_cpu
  - kernel/sched/build_utility.c:sched_numa_find_closest
  - kernel/sched/build_utility.c:cpupri_find_fitness
```
```
In kernel/irq/chip.c (ffffffff8119bb8b)
Location: include/linux/cpumask.h:151
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/migration.c (ffffffff811a2855)
Location: include/linux/cpumask.h:151
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
```
```
In kernel/irq/cpuhotplug.c (ffffffff811a2b20)
Location: include/linux/cpumask.h:151
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
```
```
In kernel/smp.c (ffffffff811f90de)
Location: include/linux/cpumask.h:151
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
```
```
In mm/compaction.c (ffffffff813a5884)
Location: include/linux/cpumask.h:151
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
```
```
In block/blk-mq.c (ffffffff81748c8c)
Location: include/linux/cpumask.h:151
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
```
```
In drivers/pci/pci-driver.c (ffffffff818e6684)
Location: include/linux/cpumask.h:151
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_call_probe
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81ad9897)
Location: include/linux/cpumask.h:151
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff81d3be60)
Location: include/linux/cpumask.h:151
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
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
In arch/x86/events/intel/uncore.c (ffffffff810231ca)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff81047e7f)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
```
In kernel/workqueue.c (ffffffff811211b8)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:wq_select_unbound_cpu
```
```
In kernel/sched/build_policy.c (ffffffff8116f19b)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_task_offline_migration
```
```
In kernel/sched/build_utility.c (ffffffff8118a166)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_numa_find_closest
  - kernel/sched/build_utility.c:cpupri_find_fitness
```
```
In kernel/irq/chip.c (ffffffff811ad9db)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/migration.c (ffffffff811b4755)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
```
```
In kernel/irq/cpuhotplug.c (ffffffff811b4a20)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
```
```
In kernel/smp.c (ffffffff8120dd8e)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
```
```
In kernel/cgroup/cpuset.c (ffffffff8122e2a2)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
```
In kernel/bpf/cpumask.c (ffffffff8135d725)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_first_and
```
```
In mm/compaction.c (ffffffff813d8ed4)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
```
```
In block/blk-mq.c (ffffffff817853a1)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
```
```
In drivers/pci/pci-driver.c (ffffffff81929cc4)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_call_probe
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81b27a17)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff81da69c0)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
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
In arch/x86/events/intel/uncore.c (ffffffff810292f9)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8104e5af)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
```
In kernel/workqueue.c (ffffffff8112b950)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:wq_select_unbound_cpu
```
```
In kernel/sched/build_policy.c (ffffffff8117ca1b)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_task_offline_migration
```
```
In kernel/sched/build_utility.c (ffffffff81198a66)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_numa_find_closest
  - kernel/sched/build_utility.c:cpupri_find_fitness
```
```
In kernel/irq/chip.c (ffffffff811bd5db)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
```
In kernel/irq/migration.c (ffffffff811c45d5)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
```
```
In kernel/irq/cpuhotplug.c (ffffffff811c48a0)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
```
```
In kernel/rcu/tree.c (ffffffff811d47e6)
Location: include/linux/cpumask.h:184
Inline: True
```
```
In kernel/smp.c (ffffffff8122551e)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
```
```
In kernel/cgroup/cpuset.c (ffffffff81246838)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
```
In kernel/bpf/cpumask.c (ffffffff813864c5)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_first_and
```
```
In mm/compaction.c (ffffffff81402c54)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
```
```
In block/blk-mq.c (ffffffff817c78ed)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
```
```
In drivers/pci/pci-driver.c (ffffffff819724c4)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_call_probe
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81b7e8d7)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff81e5ea50)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
