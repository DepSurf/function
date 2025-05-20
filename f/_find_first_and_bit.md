# Function: <code>_find_first_and_bit</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int _find_first_and_bit(const long unsigned int *addr1, const long unsigned int *addr2, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff816e7410)
Location: lib/find_bit.c:96
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:wq_select_unbound_cpu
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_utility.c:housekeeping_any_cpu
  - kernel/sched/build_utility.c:sched_numa_find_closest
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - mm/compaction.c:kcompactd_cpu_online
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - lib/cpumask.c:cpumask_any_and_distribute
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
**Symbols:**

```
ffffffff816e7410-ffffffff816e746b: _find_first_and_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int _find_first_and_bit(const long unsigned int *addr1, const long unsigned int *addr2, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff817d6cc0)
Location: lib/find_bit.c:110
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:wq_select_unbound_cpu
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_utility.c:housekeeping_any_cpu
  - kernel/sched/build_utility.c:sched_numa_find_closest
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - mm/compaction.c:kcompactd_cpu_online
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - lib/cpumask.c:cpumask_any_and_distribute
```
**Symbols:**

```
ffffffff817d6cc0-ffffffff817d6d1b: _find_first_and_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int _find_first_and_bit(const long unsigned int *addr1, const long unsigned int *addr2, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81815cd0)
Location: lib/find_bit.c:110
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:wq_select_unbound_cpu
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_utility.c:sched_numa_find_closest
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/bpf/cpumask.c:bpf_cpumask_first_and
  - mm/compaction.c:kcompactd_cpu_online
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - lib/cpumask.c:cpumask_any_and_distribute
```
**Symbols:**

```
ffffffff81815cd0-ffffffff81815d2b: _find_first_and_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int _find_first_and_bit(const long unsigned int *addr1, const long unsigned int *addr2, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8185ae10)
Location: lib/find_bit.c:110
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:wq_select_unbound_cpu
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_utility.c:sched_numa_find_closest
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/bpf/cpumask.c:bpf_cpumask_first_and
  - mm/compaction.c:kcompactd_cpu_online
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - lib/cpumask.c:cpumask_any_and_distribute
```
**Symbols:**

```
ffffffff8185ae10-ffffffff8185ae6b: _find_first_and_bit (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
