# Function: <code>cpu_to_node</code>

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
In arch/x86/entry/vdso/vma.c (ffffffff81003e86)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/events/amd/core.c (ffffffff8100807e)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008ace)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff8100c7a5)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:allocate_shared_regs
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d174)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff8101039d)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff81014295)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/rapl.c (ffffffff81014df3)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - arch/x86/events/intel/rapl.c:rapl_cpu_prepare
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015946)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_cpu_prepare
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034575)
Location: include/linux/topology.h:82
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81042356)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/smpboot.c (ffffffff81050ee3)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81f725f6)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81f728a0)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In kernel/cpu.c (ffffffff810819ef)
Location: include/linux/topology.h:82
Inline: True
```
```
In kernel/sys.c (ffffffff81095f99)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - kernel/sys.c:SyS_getcpu
```
```
In kernel/workqueue.c (ffffffff810970ea)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
```
```
In kernel/kthread.c (ffffffff810a0c99)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/smpboot.c (ffffffff810a3b99)
Location: include/linux/topology.h:82
Inline: True
```
```
In kernel/sched/core.c (ffffffff810a48a0)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cpu_mask
  - kernel/sched/core.c:sd_numa_mask
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:sched_domains_numa_masks_update
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
```
```
In kernel/sched/fair.c (ffffffff810b3064)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:numa_migrate_preferred
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
```
```
In kernel/sched/rt.c (0)
Location: include/linux/topology.h:82
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/topology.h:82
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810c6982)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/profile.c (ffffffff8181903d)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:profile_cpu_callback
```
```
In kernel/smp.c (ffffffff81103b26)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
```
```
In kernel/taskstats.c (ffffffff8113e4e4)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ring_buffer.c (ffffffff811468e0)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/trace_uprobe.c (ffffffff8116f6a8)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/core.c (ffffffff8117ad55)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
```
```
In kernel/events/ring_buffer.c (ffffffff8118516e)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (ffffffff8118613a)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In mm/vmstat.c (ffffffff811ad85e)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpuup_callback
  - mm/vmstat.c:vmstat_cpuup_callback
  - mm/vmstat.c:vmstat_cpuup_callback
```
```
In mm/percpu.c (ffffffff811b0a87)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/zswap.c (ffffffff811d7b85)
Location: include/linux/topology.h:82
Inline: True
```
```
In mm/mempolicy.c (ffffffff811e2c46)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/memory_hotplug.c (ffffffff811efa56)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:try_offline_node
```
```
In security/apparmor/lsm.c (ffffffff81f9952b)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In block/blk-mq.c (ffffffff813c5299)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-mq-cpumap.c (ffffffff813c8844)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
```
```
In lib/cpu_rmap.c (ffffffff81415e30)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/acpi_processor.c (ffffffff8148270a)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/topology.h:82
Inline: True
```
```
In drivers/base/cpu.c (ffffffff8154e881)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_subsys_online
  - drivers/base/cpu.c:cpu_subsys_online
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:register_cpu
```
```
In drivers/base/node.c (ffffffff81560c79)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - drivers/base/node.c:register_one_node
```
```
In drivers/md/dm-stats.c (ffffffff816add5b)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/topology.h:82
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff817133c2)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81717cfe)
Location: include/linux/topology.h:82
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
```
```
In net/core/flow.c (ffffffff81734dd8)
Location: include/linux/topology.h:82
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
In arch/x86/entry/vdso/vma.c (ffffffff81003e3f)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/events/amd/core.c (ffffffff810082cf)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008c1f)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff8100caea)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
  - arch/x86/events/intel/core.c:allocate_shared_regs
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d334)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fd86)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff810142b1)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff81014d84)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_cpu_prepare
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103373f)
Location: include/linux/topology.h:78
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81042247)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/smpboot.c (ffffffff81051490)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81f9ae17)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81f9b0c8)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In kernel/fork.c (ffffffff81081e99)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/cpu.c (ffffffff8108489f)
Location: include/linux/topology.h:78
Inline: True
```
```
In kernel/sys.c (ffffffff81099349)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sys.c:SyS_getcpu
```
```
In kernel/workqueue.c (ffffffff81fa5222)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:__queue_work
```
```
In kernel/kthread.c (ffffffff810a4389)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/smpboot.c (ffffffff810a72b9)
Location: include/linux/topology.h:78
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b28c1)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:sd_numa_mask
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/core.c:cpu_cpu_mask
```
```
In kernel/sched/fair.c (ffffffff810c2410)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:numa_migrate_preferred
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/sched/rt.c (0)
Location: include/linux/topology.h:78
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/topology.h:78
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810cc9fc)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/irq/irqdesc.c (ffffffff81892b4f)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/profile.c (ffffffff810f1429)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/smp.c (ffffffff8110af46)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
```
```
In kernel/taskstats.c (ffffffff81146b34)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ring_buffer.c (ffffffff8114f130)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811579f8)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117cd8f)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/core.c (ffffffff81196ec2)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_addr_filter
```
```
In kernel/events/ring_buffer.c (ffffffff81196fce)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (ffffffff811983d2)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In mm/vmstat.c (ffffffff811c6ab2)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpuup_callback
  - mm/vmstat.c:vmstat_cpuup_callback
  - mm/vmstat.c:vmstat_cpuup_callback
```
```
In mm/percpu.c (ffffffff811c9ca7)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/zswap.c (ffffffff811f5c85)
Location: include/linux/topology.h:78
Inline: True
```
```
In mm/mempolicy.c (ffffffff81201626)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/memory_hotplug.c (ffffffff8120eeb1)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:try_offline_node
```
```
In security/apparmor/lsm.c (ffffffff81fc42cd)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In block/blk-mq.c (ffffffff8140934a)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-mq-cpumap.c (ffffffff8140caa4)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
```
```
In lib/cpu_rmap.c (ffffffff8145dc70)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/acpi_processor.c (ffffffff814d11fc)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/topology.h:78
Inline: True
```
```
In drivers/base/cpu.c (ffffffff815a0bd7)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/cpu.c:cpu_subsys_online
  - drivers/base/cpu.c:cpu_subsys_online
```
```
In drivers/base/node.c (ffffffff815b53b5)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/base/node.c:register_one_node
```
```
In drivers/md/dm-stats.c (ffffffff8170e237)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/topology.h:78
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff8177b01c)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff817800b8)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
```
```
In net/core/flow.c (ffffffff817a0f58)
Location: include/linux/topology.h:78
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff817d478e)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
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
In arch/x86/entry/vdso/vma.c (ffffffff81003e2f)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/events/amd/core.c (ffffffff810082ef)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008c5f)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff8100cbba)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
  - arch/x86/events/intel/core.c:allocate_shared_regs
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d3f4)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fef6)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff81014486)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101564c)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103336f)
Location: include/linux/topology.h:78
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81041cdb)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff810431d3)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff81053dc0)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81fd62e0)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81fd6601)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In kernel/fork.c (ffffffff810868f9)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/cpu.c (ffffffff8108982f)
Location: include/linux/topology.h:78
Inline: True
```
```
In kernel/sys.c (ffffffff8109e2f9)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sys.c:SyS_getcpu
```
```
In kernel/workqueue.c (ffffffff8109f10a)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810a9721)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/smpboot.c (ffffffff810acdc9)
Location: include/linux/topology.h:78
Inline: True
```
```
In kernel/sched/core.c (ffffffff81fe2b23)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:sd_numa_mask
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/core.c:cpu_cpu_mask
```
```
In kernel/sched/fair.c (ffffffff810c8460)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:numa_migrate_preferred
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/sched/rt.c (ffffffff81fe3036)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (ffffffff81fe30a2)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/debug.c (ffffffff810d2a17)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/irq/irqdesc.c (ffffffff818c74a1)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/profile.c (ffffffff810f8379)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/smp.c (ffffffff81112766)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/taskstats.c (ffffffff81150a35)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ring_buffer.c (ffffffff811592d0)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81162c2c)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811889a3)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/core.c (ffffffff811a68d2)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_addr_filter
```
```
In kernel/events/ring_buffer.c (ffffffff811a69de)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (ffffffff811a7db2)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In mm/vmstat.c (ffffffff811d6c35)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/percpu.c (ffffffff811d9d9e)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/zswap.c (ffffffff812069e9)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/zswap.c:zswap_dstmem_prepare
```
```
In mm/mempolicy.c (ffffffff81213116)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/memory_hotplug.c (ffffffff81220fab)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:try_offline_node
```
```
In security/apparmor/lsm.c (ffffffff82000d86)
Location: include/linux/topology.h:78
Inline: True
```
```
In crypto/scompress.c (ffffffff813fa889)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_scomp_alloc_scratches
```
```
In block/blk-mq.c (ffffffff81423d39)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-mq-cpumap.c (ffffffff81427d79)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
```
```
In lib/cpu_rmap.c (ffffffff8147c765)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/acpi_processor.c (ffffffff814f32d2)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff8200f534)
Location: include/linux/topology.h:78
Inline: True
```
```
In drivers/base/cpu.c (ffffffff815cf247)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/cpu.c:cpu_subsys_online
  - drivers/base/cpu.c:cpu_subsys_online
```
```
In drivers/base/node.c (ffffffff815e468c)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/base/node.c:register_one_node
```
```
In drivers/md/dm-stats.c (ffffffff8173f99d)
Location: include/linux/topology.h:78
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8201e620)
Location: include/linux/topology.h:78
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff817a866e)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff817ad806)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
```
```
In net/core/flow.c (ffffffff817cfb6c)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_cpu_up_prep
```
```
In net/ipv4/tcp.c (ffffffff818044ce)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
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
In arch/x86/entry/vdso/vma.c (ffffffff81003cbf)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/events/amd/core.c (ffffffff81007fc8)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff8100899e)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff8100c91a)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
  - arch/x86/events/intel/core.c:allocate_shared_regs
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d274)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e536)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff81012abe)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff81013b4a)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81031541)
Location: include/linux/topology.h:78
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8103fdeb)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff810414e6)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff81053771)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/vector.c (ffffffff820b6feb)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff820b7360)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In kernel/fork.c (ffffffff81083649)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/cpu.c (ffffffff81085cef)
Location: include/linux/topology.h:78
Inline: True
```
```
In kernel/sys.c (ffffffff8109b963)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sys.c:SyS_getcpu
```
```
In kernel/workqueue.c (ffffffff8109c93c)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810a63d2)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/smpboot.c (ffffffff810a99b9)
Location: include/linux/topology.h:78
Inline: True
```
```
In kernel/sched/core.c (ffffffff820c33bd)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/fair.c (ffffffff810c2140)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:numa_migrate_preferred
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/sched/rt.c (ffffffff820c3932)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (ffffffff820c39a2)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/topology.c (ffffffff810cc5b3)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sd_numa_mask
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/sched/debug.c (ffffffff810d1b62)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/irq/irqdesc.c (ffffffff818fec2a)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/affinity.c (ffffffff810ef8f8)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff810fa3a9)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/smp.c (ffffffff81113c56)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/taskstats.c (ffffffff811530bc)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ring_buffer.c (ffffffff8115e7a0)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811660cd)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118b651)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/core.c (ffffffff811ae018)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_init_cpu
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In kernel/events/ring_buffer.c (ffffffff811ae1ce)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (ffffffff811af55a)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In mm/vmstat.c (ffffffff811dfa95)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/percpu.c (ffffffff811e341d)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/zswap.c (ffffffff812120f9)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/zswap.c:zswap_dstmem_prepare
```
```
In mm/mempolicy.c (ffffffff8121e436)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/memory_hotplug.c (ffffffff8122c872)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:try_offline_node
```
```
In security/apparmor/lsm.c (ffffffff820e4668)
Location: include/linux/topology.h:78
Inline: True
```
```
In crypto/scompress.c (ffffffff81407199)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_scomp_alloc_scratches
```
```
In block/blk-mq.c (ffffffff81432dff)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-mq-cpumap.c (ffffffff81435167)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
```
```
In lib/cpu_rmap.c (ffffffff81485a95)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/msi.c (ffffffff814cc73e)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_irq_get_node
```
```
In drivers/acpi/acpi_processor.c (ffffffff815010ef)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff820f0fd8)
Location: include/linux/topology.h:78
Inline: True
```
```
In drivers/base/cpu.c (ffffffff815e3cc7)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/cpu.c:cpu_subsys_online
  - drivers/base/cpu.c:cpu_subsys_online
```
```
In drivers/base/node.c (ffffffff815f9318)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
```
```
In drivers/md/dm-stats.c (ffffffff8175971b)
Location: include/linux/topology.h:78
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff821011cf)
Location: include/linux/topology.h:78
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff817c6cf0)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff817cc3ba)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
```
```
In net/core/flow.c (ffffffff817eef7c)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_cpu_up_prep
```
```
In net/ipv4/tcp.c (ffffffff8182479f)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
```
In net/ipv6/seg6_hmac.c (ffffffff8210e868)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
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
In arch/x86/entry/vdso/vma.c (ffffffff81003f0f)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/events/amd/core.c (ffffffff81008448)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008bbe)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff8100ceba)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
  - arch/x86/events/intel/core.c:allocate_shared_regs
```
```
In arch/x86/events/intel/bts.c (ffffffff8100d814)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff8100ed31)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff81012b8e)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff810144bf)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81033771)
Location: include/linux/topology.h:78
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81043160)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81044946)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105759f)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff826bdd01)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81060616)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In kernel/fork.c (ffffffff81089f29)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/cpu.c (ffffffff8108ca0f)
Location: include/linux/topology.h:78
Inline: True
```
```
In kernel/sys.c (ffffffff810a2663)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sys.c:SyS_getcpu
```
```
In kernel/workqueue.c (ffffffff810a31dc)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810aca02)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/smpboot.c (ffffffff810b0249)
Location: include/linux/topology.h:78
Inline: True
```
```
In kernel/sched/core.c (ffffffff826cb470)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/fair.c (ffffffff810c987d)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:numa_migrate_preferred
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/sched/rt.c (ffffffff826cb951)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (ffffffff826cb9b9)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/topology.c (ffffffff810d329f)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sd_numa_mask
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/sched/debug.c (ffffffff810d9703)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/irq/irqdesc.c (ffffffff81988e3a)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/affinity.c (ffffffff810f84e8)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff81104d29)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/smp.c (ffffffff8111f206)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/taskstats.c (ffffffff8115f8f6)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ring_buffer.c (ffffffff8116b7a0)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8117305a)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff81199179)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/cpumap.c (ffffffff811aff06)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In kernel/events/core.c (ffffffff811c1b78)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_init_cpu
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In kernel/events/ring_buffer.c (ffffffff811c1e3e)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (ffffffff811c3108)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In mm/vmstat.c (ffffffff811f58a5)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/percpu.c (ffffffff811f8d5e)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/zswap.c (ffffffff8122cac9)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/zswap.c:zswap_dstmem_prepare
```
```
In mm/mempolicy.c (ffffffff812396b2)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/memory_hotplug.c (ffffffff812480a6)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:try_offline_node
```
```
In security/apparmor/lsm.c (ffffffff826ed2af)
Location: include/linux/topology.h:78
Inline: True
```
```
In crypto/scompress.c (ffffffff8142fcbc)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_scomp_alloc_scratches
```
```
In block/blk-mq.c (ffffffff8145e9c6)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-mq-cpumap.c (ffffffff81460d5a)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
```
```
In lib/cpu_rmap.c (ffffffff814c1bb3)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/msi.c (ffffffff8150cc6e)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_irq_get_node
```
```
In drivers/acpi/acpi_processor.c (ffffffff8154351f)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff826fa7e1)
Location: include/linux/topology.h:78
Inline: True
```
```
In drivers/base/cpu.c (ffffffff8164af87)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/cpu.c:cpu_subsys_online
  - drivers/base/cpu.c:cpu_subsys_online
```
```
In drivers/base/node.c (ffffffff81661402)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
```
```
In drivers/md/dm-stats.c (ffffffff817cb99f)
Location: include/linux/topology.h:78
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8270a8cc)
Location: include/linux/topology.h:78
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff81840949)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81845a7f)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
```
```
In net/ipv4/tcp.c (ffffffff818a3646)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
```
In net/ipv6/seg6_hmac.c (ffffffff82718d0d)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
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
In arch/x86/entry/vdso/vma.c (ffffffff81004758)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/events/amd/core.c (ffffffff81008bf8)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff810092de)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff8100d5ea)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_prepare
  - arch/x86/events/intel/core.c:allocate_shared_regs
```
```
In arch/x86/events/intel/bts.c (ffffffff8100dfa4)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f67f)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff81013501)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015045)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034af8)
Location: include/linux/topology.h:78
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81044fef)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81046cb8)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105a1f0)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff826e7abe)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810636e5)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff826e9a07)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
```
```
In kernel/fork.c (ffffffff8108d735)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/cpu.c (ffffffff81091151)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/cpu.c:store_smt_control
```
```
In kernel/sys.c (ffffffff810a2ffb)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getcpu
  - kernel/sys.c:__x64_sys_getcpu
```
```
In kernel/workqueue.c (ffffffff826f3d1e)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810b3452)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/smpboot.c (ffffffff810b7055)
Location: include/linux/topology.h:78
Inline: True
```
```
In kernel/sched/core.c (ffffffff826f55d4)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/fair.c (ffffffff810d19db)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:numa_migrate_preferred
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/sched/rt.c (ffffffff826f5ada)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (ffffffff826f5b42)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/topology.c (ffffffff810dafe4)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sd_numa_mask
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/sched/debug.c (ffffffff810e0718)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/irq/irqdesc.c (ffffffff819e57fc)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/affinity.c (ffffffff81100cee)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff8110fab5)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/smp.c (ffffffff8112c536)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/taskstats.c (ffffffff8116e84b)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ring_buffer.c (ffffffff8117ac53)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81182077)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ae858)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/cpumap.c (ffffffff811ca716)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/events/core.c (ffffffff811e1f08)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_init_cpu
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In kernel/events/ring_buffer.c (ffffffff811e21fe)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (ffffffff811e34ab)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In mm/vmstat.c (ffffffff81216b25)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/percpu.c (ffffffff8121a767)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/zswap.c (ffffffff8124f745)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/zswap.c:zswap_dstmem_prepare
```
```
In mm/mempolicy.c (ffffffff8125cc5f)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/memory_hotplug.c (ffffffff8126b9ff)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:try_offline_node
```
```
In security/apparmor/lsm.c (ffffffff82717625)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
```
```
In crypto/scompress.c (ffffffff81462a35)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_scomp_alloc_scratches
```
```
In block/blk-mq.c (ffffffff8149238e)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-mq-cpumap.c (ffffffff8149461a)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
```
```
In lib/cpu_rmap.c (ffffffff814f2b17)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/msi.c (ffffffff81541ade)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_irq_get_node
```
```
In drivers/acpi/acpi_processor.c (ffffffff81579461)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff82724b29)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
```
In drivers/base/cpu.c (ffffffff81686585)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/cpu.c:cpu_subsys_online
  - drivers/base/cpu.c:cpu_subsys_online
```
```
In drivers/base/node.c (ffffffff8169cc0a)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
```
```
In drivers/md/dm-stats.c (ffffffff81814788)
Location: include/linux/topology.h:78
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff82734b08)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
```
In net/core/sysctl_net_core.c (ffffffff8188b052)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff8188f138)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
```
```
In net/ipv4/tcp.c (ffffffff818f7b15)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
```
In net/ipv6/seg6_hmac.c (ffffffff8274347c)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
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
In arch/x86/events/amd/core.c (ffffffff81008b18)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008fa5)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
```
```
In arch/x86/events/intel/core.c (ffffffff8100d9a8)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff8100e474)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fc4b)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff81013771)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015645)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81035cd8)
Location: include/linux/topology.h:78
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81046a03)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81055cec)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105d615)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105fe70)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8289e607)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810693e5)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff828a0652)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
```
```
In kernel/fork.c (ffffffff810959d5)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/cpu.c (ffffffff810994e5)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/cpu.c:store_smt_control
```
```
In kernel/sys.c (ffffffff810abc0b)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getcpu
  - kernel/sys.c:__x64_sys_getcpu
```
```
In kernel/workqueue.c (ffffffff828aab06)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810bc592)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/smpboot.c (ffffffff810c01e5)
Location: include/linux/topology.h:78
Inline: True
```
```
In kernel/sched/core.c (ffffffff828ac419)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/fair.c (ffffffff810db32d)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/sched/rt.c (ffffffff828ac924)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (ffffffff828ac98c)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/topology.c (ffffffff810e4b94)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sd_numa_mask
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/sched/debug.c (ffffffff810eaece)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/irq/irqdesc.c (ffffffff81a2096f)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/affinity.c (ffffffff8110c4c4)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff8111b1a5)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/smp.c (ffffffff81137e06)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/taskstats.c (ffffffff8117c31b)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ring_buffer.c (ffffffff811876c3)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8118fa37)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bceec)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/cpumap.c (ffffffff811de048)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/events/core.c (ffffffff811f2378)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_init_cpu
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In kernel/events/ring_buffer.c (ffffffff811f266e)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (ffffffff811f396b)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In mm/vmstat.c (ffffffff81229a35)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/percpu.c (ffffffff8122d717)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/zswap.c (ffffffff81263e35)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/zswap.c:zswap_dstmem_prepare
```
```
In mm/mempolicy.c (ffffffff8127152b)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/memory_hotplug.c (ffffffff81280297)
Location: include/linux/topology.h:78
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff828ceff9)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
  - security/apparmor/lsm.c:alloc_buffers
```
```
In crypto/scompress.c (ffffffff814806b5)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_scomp_alloc_scratches
```
```
In block/blk-mq.c (ffffffff814abeaf)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-mq-cpumap.c (ffffffff814ae74d)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
```
```
In lib/cpu_rmap.c (ffffffff81506e47)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/msi.c (ffffffff81558d9e)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_irq_get_node
```
```
In drivers/acpi/acpi_processor.c (ffffffff815910e1)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff828dcd02)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
```
In drivers/base/cpu.c (ffffffff816a6225)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/cpu.c:cpu_subsys_online
  - drivers/base/cpu.c:cpu_subsys_online
```
```
In drivers/base/node.c (ffffffff816bd395)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
```
```
In drivers/md/dm-stats.c (ffffffff81840798)
Location: include/linux/topology.h:78
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff828ee9cf)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
```
In net/core/sysctl_net_core.c (ffffffff818ac092)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff818b2d81)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/ipv4/tcp.c (ffffffff81926185)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
```
In net/ipv6/seg6_hmac.c (ffffffff828fd772)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
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
In arch/x86/events/amd/core.c (ffffffff810090b8)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009435)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
```
```
In arch/x86/events/intel/core.c (ffffffff8100e27b)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff8100ed3c)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff81010d62)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff81014bb3)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016043)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81037e38)
Location: include/linux/topology.h:78
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049402)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81058f4a)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106097e)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
```
```
In arch/x86/kernel/smpboot.c (ffffffff81063717)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828b647a)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106cc35)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff828b8831)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
```
```
In kernel/fork.c (ffffffff81099d01)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/cpu.c (ffffffff8109ddf8)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/sys.c (ffffffff810b18eb)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getcpu
  - kernel/sys.c:__x64_sys_getcpu
```
```
In kernel/workqueue.c (ffffffff828c32e4)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810c24a9)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/smpboot.c (ffffffff810c6305)
Location: include/linux/topology.h:78
Inline: True
```
```
In kernel/sched/core.c (ffffffff828c4cdf)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/fair.c (ffffffff810e27a2)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/sched/rt.c (ffffffff828c5268)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (ffffffff828c52d2)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/topology.c (ffffffff810ebb4f)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sd_numa_mask
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/sched/debug.c (ffffffff810f1d02)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/irq/irqdesc.c (ffffffff81a90eb3)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/affinity.c (ffffffff81115c64)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff81125875)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/smp.c (ffffffff81142f95)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/taskstats.c (ffffffff8118914d)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ring_buffer.c (ffffffff81194bd9)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8119d447)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cc595)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/cpumap.c (ffffffff811f3706)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/events/core.c (ffffffff8120a03f)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
```
```
In kernel/events/ring_buffer.c (ffffffff8120a33e)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (ffffffff8120b5c4)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - kernel/events/callchain.c:alloc_callchain_buffers
```
```
In mm/vmstat.c (ffffffff812396d5)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/percpu.c (ffffffff8123d443)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/zswap.c (ffffffff8127eda5)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/zswap.c:zswap_dstmem_prepare
```
```
In mm/mempolicy.c (ffffffff8128cb42)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/memory_hotplug.c (ffffffff8129bf46)
Location: include/linux/topology.h:78
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff828e8b47)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
```
```
In crypto/scompress.c (ffffffff814ae7f9)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_init_tfm
```
```
In block/blk-mq.c (ffffffff814da107)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-mq-cpumap.c (ffffffff814dca04)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
```
```
In lib/cpu_rmap.c (ffffffff81535066)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/msi.c (ffffffff81588e5e)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_irq_get_node
```
```
In drivers/acpi/acpi_processor.c (ffffffff815c1e90)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff828f75f6)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
```
In drivers/base/cpu.c (ffffffff816df255)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/cpu.c:cpu_subsys_online
  - drivers/base/cpu.c:cpu_subsys_online
```
```
In drivers/base/node.c (ffffffff816f817d)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
```
```
In drivers/md/dm-stats.c (ffffffff81883655)
Location: include/linux/topology.h:78
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff82909e70)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
```
In net/core/sysctl_net_core.c (ffffffff818f7960)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff818ffa89)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/ipv4/tcp.c (ffffffff819872bd)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
```
In net/ipv6/seg6_hmac.c (ffffffff8291a308)
Location: include/linux/topology.h:78
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
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
In arch/x86/events/amd/core.c (ffffffff81009468)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009835)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
```
```
In arch/x86/events/intel/core.c (ffffffff8100e8bb)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff8100eecd)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff81011442)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff81015503)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff810169f3)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038608)
Location: include/linux/topology.h:93
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049ced)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105981a)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106122e)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
```
```
In arch/x86/kernel/smpboot.c (ffffffff81063dc7)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828b993d)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bd311)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106e395)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff828bed1f)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828c9273)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff81099149)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff828ca003)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
```
```
In kernel/fork.c (ffffffff810a02e1)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/cpu.c (ffffffff810a4348)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/sys.c (ffffffff810b7fbb)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getcpu
  - kernel/sys.c:__x64_sys_getcpu
```
```
In kernel/workqueue.c (ffffffff810bee06)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810c8be9)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/smpboot.c (ffffffff810cf3d5)
Location: include/linux/topology.h:93
Inline: True
```
```
In kernel/sched/core.c (ffffffff828cd2cd)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/fair.c (ffffffff810ece52)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/sched/rt.c (ffffffff828cd8d1)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/deadline.c (ffffffff828cd93b)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/topology.c (ffffffff810f7516)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_numa_find_closest
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sd_numa_mask
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/sched/debug.c (ffffffff810fd9c2)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/irq/irqdesc.c (ffffffff81ac81f3)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/affinity.c (ffffffff81122052)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff81131845)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/smp.c (ffffffff8114ead5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/taskstats.c (ffffffff8119508d)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ring_buffer.c (ffffffff811a0699)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811a8e08)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d8b5d)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/cpumap.c (ffffffff812004a6)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/events/core.c (ffffffff812173af)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
```
```
In kernel/events/ring_buffer.c (ffffffff8121761e)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (ffffffff812188a4)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/events/callchain.c:alloc_callchain_buffers
```
```
In mm/vmstat.c (ffffffff812479d5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/percpu.c (ffffffff8124b893)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/zswap.c (ffffffff8128e7f5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/zswap.c:zswap_dstmem_prepare
```
```
In mm/mempolicy.c (ffffffff8129c772)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/memory_hotplug.c (ffffffff812abcb3)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
```
```
In security/apparmor/lsm.c (ffffffff828f1633)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
```
```
In crypto/scompress.c (ffffffff814c9489)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_init_tfm
```
```
In block/blk-mq.c (ffffffff814f34ad)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-mq-cpumap.c (ffffffff814f5e74)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
```
```
In lib/cpu_rmap.c (ffffffff81555e76)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/msi.c (ffffffff815aa7fe)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_irq_get_node
```
```
In drivers/acpi/acpi_processor.c (ffffffff815e3150)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff82900595)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
```
In drivers/base/cpu.c (ffffffff817034a5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/cpu.c:cpu_subsys_online
  - drivers/base/cpu.c:cpu_subsys_online
```
```
In drivers/base/node.c (ffffffff8171c57d)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
```
```
In drivers/md/dm-stats.c (ffffffff818b553d)
Location: include/linux/topology.h:93
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff82913867)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
```
In net/core/sysctl_net_core.c (ffffffff819296e0)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81931da9)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/ipv4/tcp.c (ffffffff819bda5d)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
```
In net/ipv6/seg6_hmac.c (ffffffff82924177)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
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
In arch/x86/events/amd/core.c (ffffffff8100a435)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_alloc_nb
```
```
In arch/x86/events/amd/uncore.c (ffffffff8100aba5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
```
```
In arch/x86/events/intel/core.c (ffffffff8100fbc3)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff8101040c)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff81011116)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff81016ca9)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff81018183)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103afb7)
Location: include/linux/topology.h:93
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104e38d)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105ec63)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81066dd0)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106aaf5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff82cded6e)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82ce1883)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810756e5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff82ce3025)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff82cebd68)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:get_cpu_topology
  - arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109e645)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_rtc_set_timer
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff82cec94f)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
```
```
In kernel/fork.c (ffffffff810a71c1)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/cpu.c (ffffffff810ab5f8)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/sys.c (ffffffff810c07ab)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getcpu
  - kernel/sys.c:__x64_sys_getcpu
```
```
In kernel/workqueue.c (ffffffff82ced898)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810d0e95)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/smpboot.c (ffffffff810d9245)
Location: include/linux/topology.h:93
Inline: True
```
```
In kernel/sched/core.c (ffffffff82cee742)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
```
```
In kernel/sched/fair.c (ffffffff810f6d5f)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/sched/rt.c (ffffffff82ceec95)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (ffffffff82ceecff)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/topology.c (ffffffff811011d8)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:sched_numa_find_closest
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sd_numa_mask
  - kernel/sched/topology.c:build_group_from_child_sched_domain
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/sched/debug.c (ffffffff81105afb)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_show_numa
  - kernel/sched/debug.c:sched_show_numa
```
```
In kernel/irq/irqdesc.c (ffffffff81121a88)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/irq/affinity.c (ffffffff8112e549)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
```
In kernel/profile.c (ffffffff81140bb5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/smp.c (ffffffff8115f5b5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/taskstats.c (ffffffff811aa14d)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ring_buffer.c (ffffffff811b6c79)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811c10e8)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4f67)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/cpumap.c (ffffffff81227ee5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In kernel/events/core.c (ffffffff81231978)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_init_cpu
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_cgroup_ensure_storage
```
```
In kernel/events/ring_buffer.c (ffffffff81242ece)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (ffffffff812445e4)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/events/callchain.c:alloc_callchain_buffers
```
```
In mm/vmstat.c (ffffffff81275bc5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/percpu.c (ffffffff8127983f)
Location: include/linux/topology.h:93
Inline: True
```
```
In mm/zswap.c (ffffffff812c10e5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/zswap.c:zswap_dstmem_prepare
```
```
In mm/mempolicy.c (ffffffff812d03be)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/memory_hotplug.c (ffffffff812e05b3)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
```
```
In crypto/scompress.c (ffffffff815287e0)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_scomp_alloc_scratches
  - crypto/scompress.c:crypto_scomp_alloc_scratches
```
```
In block/blk-mq.c (ffffffff8154e7e3)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_cpu_queues
```
```
In block/blk-mq-cpumap.c (ffffffff81556894)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
```
```
In lib/cpu_rmap.c (ffffffff815df7e5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/acpi_processor.c (ffffffff8168e5a2)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff82d17991)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
```
In drivers/base/cpu.c (ffffffff817bd825)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/cpu.c:cpu_subsys_online
  - drivers/base/cpu.c:cpu_subsys_online
```
```
In drivers/base/node.c (ffffffff817d8682)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
```
```
In drivers/md/dm-stats.c (ffffffff81986272)
Location: include/linux/topology.h:93
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff82d263c2)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init
```
```
In net/core/sysctl_net_core.c (ffffffff819fd66f)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81a05b99)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/ipv4/tcp.c (ffffffff81aa8571)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b818b2)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
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
In arch/x86/events/amd/core.c (ffffffff810092b5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_alloc_nb
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009b35)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
```
```
In arch/x86/events/intel/core.c (ffffffff8100f2d3)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff8100f96c)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff81010746)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff81017149)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff81018856)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b7c7)
Location: include/linux/topology.h:93
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104d8cd)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d19c)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81065010)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106c7c5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff82fcb11e)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82fce631)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075d29)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff82fd0317)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109a1c5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_rtc_set_timer
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff82fd8fa9)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
```
```
In kernel/fork.c (ffffffff810a2e91)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/cpu.c (ffffffff810a6e78)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/sys.c (ffffffff810bb918)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getcpu
  - kernel/sys.c:__x64_sys_getcpu
```
```
In kernel/workqueue.c (ffffffff82fd9ef2)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810cb945)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/smpboot.c (ffffffff810d43e9)
Location: include/linux/topology.h:93
Inline: True
```
```
In kernel/sched/core.c (ffffffff82fdae40)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
```
```
In kernel/sched/fair.c (ffffffff810f4f3f)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/sched/rt.c (ffffffff82fdb3ac)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (ffffffff82fdb416)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/topology.c (ffffffff810ffd38)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:sched_numa_find_closest
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sd_numa_mask
  - kernel/sched/topology.c:build_group_from_child_sched_domain
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/sched/debug.c (ffffffff8110414b)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_show_numa
  - kernel/sched/debug.c:sched_show_numa
```
```
In kernel/irq/irqdesc.c (ffffffff8111dae8)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/irq/affinity.c (ffffffff8112a139)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
```
In kernel/profile.c (ffffffff8113cee9)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/smp.c (ffffffff8115b555)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/taskstats.c (ffffffff811a76ed)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ring_buffer.c (ffffffff811b4819)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811bed18)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f38f7)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/cpumap.c (ffffffff8122e745)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In kernel/events/core.c (ffffffff8123b5e8)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_init_cpu
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_cgroup_ensure_storage
```
```
In kernel/events/ring_buffer.c (ffffffff8124d56e)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (ffffffff8124ebb4)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/events/callchain.c:alloc_callchain_buffers
```
```
In mm/vmstat.c (ffffffff812804a5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/percpu.c (ffffffff812840af)
Location: include/linux/topology.h:93
Inline: True
```
```
In mm/zswap.c (ffffffff812ccaff)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/zswap.c:zswap_dstmem_prepare
```
```
In mm/mempolicy.c (ffffffff812dbede)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/memory_hotplug.c (ffffffff812ebd93)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
```
```
In crypto/scompress.c (ffffffff815457b0)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_scomp_alloc_scratches
  - crypto/scompress.c:crypto_scomp_alloc_scratches
```
```
In block/blk-mq.c (ffffffff8156acc3)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_cpu_queues
```
```
In block/blk-mq-cpumap.c (ffffffff815730e4)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
```
```
In lib/cpu_rmap.c (ffffffff815fcf85)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/acpi_processor.c (ffffffff816ac382)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff8300557f)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
```
In drivers/base/cpu.c (ffffffff817d25a3)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/cpu.c:cpu_subsys_online
  - drivers/base/cpu.c:cpu_subsys_online
```
```
In drivers/base/node.c (ffffffff817ed0c2)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
```
```
In drivers/md/dm-stats.c (ffffffff8198a2d2)
Location: include/linux/topology.h:93
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff830149cc)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init
```
```
In net/core/sysctl_net_core.c (ffffffff819fd2ab)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81a07399)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/ipv4/tcp.c (ffffffff81ab2ae1)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c3312f)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
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
In arch/x86/events/amd/core.c (ffffffff81009ccf)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff8100a515)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
```
```
In arch/x86/events/intel/core.c (ffffffff810102e8)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff810109bc)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff810116e6)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/lbr.c (ffffffff81015c21)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff810190b6)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff81019b76)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81020f3a)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81022256)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103d166)
Location: include/linux/topology.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104f362)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d90c)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106567f)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106d177)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff831d59bc)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d90a6)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81076755)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff831dad2c)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109aafc)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff831e3826)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
```
```
In kernel/fork.c (ffffffff831e3bf9)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/cpu.c (ffffffff810a7f38)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/sys.c (ffffffff810bd1c8)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getcpu
  - kernel/sys.c:__x64_sys_getcpu
```
```
In kernel/workqueue.c (ffffffff831e4892)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810cd1c5)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/smpboot.c (ffffffff810d6029)
Location: include/linux/topology.h:94
Inline: True
```
```
In kernel/sched/core.c (ffffffff831e593e)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
```
```
In kernel/sched/fair.c (ffffffff810f702f)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/sched/rt.c (ffffffff831e5f61)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (ffffffff831e5fcb)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/topology.c (ffffffff81101938)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:sched_numa_find_closest
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sd_numa_mask
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/sched/debug.c (ffffffff81106e6b)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_show_numa
  - kernel/sched/debug.c:sched_show_numa
```
```
In kernel/irq/irqdesc.c (ffffffff8111ddf8)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/irq/affinity.c (ffffffff8112a3b9)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
```
In kernel/profile.c (ffffffff8113e129)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/smp.c (ffffffff8115cc19)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/taskstats.c (ffffffff811a80cd)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ring_buffer.c (ffffffff811b3bd2)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811bf5e8)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4e6d)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/cpumap.c (ffffffff81233626)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In kernel/events/core.c (ffffffff81251e0f)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_cgroup_ensure_storage
```
```
In kernel/events/ring_buffer.c (ffffffff812530c0)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (ffffffff812534c4)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/events/callchain.c:alloc_callchain_buffers
```
```
In mm/vmstat.c (ffffffff812855a5)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/percpu.c (ffffffff81288cef)
Location: include/linux/topology.h:94
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff812c670e)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
```
```
In mm/zswap.c (ffffffff812d36cf)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/zswap.c:zswap_dstmem_prepare
```
```
In mm/mempolicy.c (ffffffff812e3751)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In crypto/scompress.c (ffffffff8154dec9)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_init_tfm
```
```
In block/blk-mq.c (ffffffff81578002)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-mq-cpumap.c (ffffffff8157b12c)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
```
```
In lib/cpu_rmap.c (ffffffff815dfd0e)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/acpi_processor.c (ffffffff8168ea32)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff83210125)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
```
In drivers/base/cpu.c (ffffffff817b5fc3)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/cpu.c:cpu_subsys_online
  - drivers/base/cpu.c:cpu_subsys_online
```
```
In drivers/base/node.c (ffffffff817d1892)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
```
```
In drivers/md/dm-stats.c (ffffffff8196e887)
Location: include/linux/topology.h:94
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8321fabc)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
```
In net/core/sysctl_net_core.c (ffffffff819e3b1c)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff819eae6e)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:expand_xps_map
```
```
In net/ipv4/tcp.c (ffffffff81a9dd31)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c25436)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
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
In arch/x86/events/amd/core.c (ffffffff8100ada4)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff81010e67)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff810116ac)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff81012540)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/lbr.c (ffffffff8101725e)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff81019fcb)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101c2c9)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81024b33)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81025de8)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81042c95)
Location: include/linux/topology.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810574b6)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81066fe8)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106f76c)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
```
```
In arch/x86/kernel/smpboot.c (ffffffff810782da)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff832b85f1)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832bc5a7)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81083e60)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff832bdf89)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810aad24)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff832c728a)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
```
```
In kernel/fork.c (ffffffff832c7772)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/cpu.c (ffffffff810b99ca)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/sys.c (ffffffff810cfe52)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getcpu
  - kernel/sys.c:__x64_sys_getcpu
```
```
In kernel/workqueue.c (ffffffff832c84d4)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810e039a)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/smpboot.c (ffffffff810e9270)
Location: include/linux/topology.h:94
Inline: True
```
```
In kernel/sched/core.c (ffffffff832c98c4)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
```
```
In kernel/sched/fair.c (ffffffff8111138a)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/sched/rt.c (ffffffff832ca002)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (ffffffff832ca0a7)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/topology.c (ffffffff8111dc27)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:__sdt_alloc
  - kernel/sched/topology.c:sched_numa_find_closest
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sd_numa_mask
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/sched/debug.c (ffffffff81124a4d)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_show_numa
  - kernel/sched/debug.c:sched_show_numa
```
```
In kernel/irq/irqdesc.c (ffffffff8113e231)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/irq/affinity.c (ffffffff8114ad1a)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
```
In kernel/profile.c (ffffffff81161492)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/smp.c (ffffffff81181dfd)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/taskstats.c (ffffffff811d1e90)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ring_buffer.c (ffffffff811ddb77)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811e9ec1)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff8122709d)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/cpumap.c (ffffffff8126d280)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In kernel/events/core.c (ffffffff8128d64e)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_cgroup_ensure_storage
```
```
In kernel/events/ring_buffer.c (ffffffff8128e9b0)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (ffffffff8128ede4)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/events/callchain.c:alloc_callchain_buffers
```
```
In mm/vmstat.c (ffffffff812c3f45)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/percpu.c (ffffffff812c876e)
Location: include/linux/topology.h:94
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff8130b167)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
```
```
In mm/zswap.c (ffffffff8131918e)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/zswap.c:zswap_dstmem_prepare
```
```
In mm/mempolicy.c (ffffffff8132a96e)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In crypto/scompress.c (ffffffff815ae6e8)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_init_tfm
```
```
In block/blk-mq.c (ffffffff815dcfbb)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-mq-cpumap.c (ffffffff815e0481)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
```
```
In lib/cpu_rmap.c (ffffffff8164b941)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/acpi_processor.c (ffffffff817043d7)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff832f90f9)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
```
In drivers/base/cpu.c (ffffffff8183f53e)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/cpu.c:cpu_subsys_online
  - drivers/base/cpu.c:cpu_subsys_online
```
```
In drivers/base/node.c (ffffffff8185c4d4)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
```
```
In drivers/md/dm-stats.c (ffffffff81a170ec)
Location: include/linux/topology.h:94
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff83309268)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
```
In net/core/sysctl_net_core.c (ffffffff81a940c7)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81a9bd83)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:expand_xps_map
```
```
In net/ipv4/tcp.c (ffffffff81b59786)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
```
In net/ipv6/seg6_hmac.c (ffffffff81d417ca)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
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
In arch/x86/events/amd/core.c (ffffffff8100a4b0)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff81012608)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff81012ebc)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff81014130)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/lbr.c (ffffffff810195ba)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff8101be3d)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101ea99)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81026c91)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81029e48)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8104abce)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8106382a)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81073c59)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107cfe9)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
```
```
In arch/x86/kernel/smpboot.c (ffffffff81086fb2)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8346a330)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346dec1)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81093ea0)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff8346fb2f)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810c07a3)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8347a0a1)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
```
```
In kernel/fork.c (ffffffff8347a624)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/cpu.c (ffffffff810d0454)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/sys.c (ffffffff810e9172)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getcpu
  - kernel/sys.c:__x64_sys_getcpu
```
```
In kernel/workqueue.c (ffffffff8347b5e0)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810fa0c3)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/smpboot.c (ffffffff81104043)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/smpboot.c:__smpboot_create_thread
```
```
In kernel/sched/core.c (ffffffff8347cb5f)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
```
```
In kernel/sched/fair.c (ffffffff8112d5ae)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/sched/build_policy.c (ffffffff8347d350)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:init_sched_dl_class
  - kernel/sched/build_policy.c:init_sched_rt_class
```
```
In kernel/sched/build_utility.c (ffffffff8113fdd8)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:sched_numa_find_closest
  - kernel/sched/build_utility.c:sched_domains_numa_masks_set
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sd_numa_mask
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_show_numa
  - kernel/sched/build_utility.c:sched_show_numa
  - kernel/sched/build_utility.c:cpu_cpu_mask
```
```
In kernel/irq/irqdesc.c (ffffffff81161809)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/irq/affinity.c (ffffffff8117038a)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
```
In kernel/profile.c (ffffffff811942d2)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/smp.c (ffffffff811b857c)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/taskstats.c (ffffffff812066b6)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ring_buffer.c (ffffffff81214cc7)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81221d00)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff81266be4)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/cpumap.c (ffffffff812bc3bf)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In kernel/events/core.c (ffffffff812e23bf)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_cgroup_ensure_storage
```
```
In kernel/events/ring_buffer.c (ffffffff812e3891)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (ffffffff812e3cdc)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/events/callchain.c:alloc_callchain_buffers
```
```
In mm/vmstat.c (ffffffff81321765)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:vmstat_cpu_online
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/percpu.c (ffffffff8132611d)
Location: include/linux/topology.h:94
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81373c02)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
```
```
In mm/zswap.c (ffffffff813843ce)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/zswap.c:zswap_dstmem_prepare
```
```
In mm/mempolicy.c (ffffffff8139a322)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In crypto/scompress.c (ffffffff81656c2f)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_init_tfm
```
```
In block/blk-mq.c (ffffffff8168aba2)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-mq-cpumap.c (ffffffff8168eec9)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
```
```
In lib/cpu_rmap.c (ffffffff81762443)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/acpi_processor.c (ffffffff81832476)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff834b18fe)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
```
In drivers/base/cpu.c (ffffffff8198262e)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/cpu.c:cpu_subsys_online
  - drivers/base/cpu.c:cpu_subsys_online
```
```
In drivers/base/node.c (ffffffff819a364d)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
```
```
In drivers/nvdimm/nd_perf.c (ffffffff819d90fe)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In drivers/md/dm-stats.c (ffffffff81b7fdb6)
Location: include/linux/topology.h:94
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff834c28dd)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
```
In net/core/sysctl_net_core.c (ffffffff81c0a492)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81c13540)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:expand_xps_map
```
```
In net/ipv4/tcp.c (ffffffff81ce8298)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
```
In net/ipv6/seg6_hmac.c (ffffffff81f0e12b)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
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
In arch/x86/events/amd/core.c (ffffffff8100c01e)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff81016588)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff81016efc)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff810182e0)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/lbr.c (ffffffff8101d554)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff8102017d)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff81023029)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102de6c)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81030915)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810568be)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8107292a)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81083855)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81084006)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810861d3)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mba_sc_domain_allocate
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108e43d)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109a5f2)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff83e8f266)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e93d03)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a9545)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff83e96384)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810dc753)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff83ea471b)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
```
```
In kernel/fork.c (ffffffff83ea4e67)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/cpu.c (ffffffff810eecad)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/sys.c (ffffffff8110a012)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getcpu
  - kernel/sys.c:__x64_sys_getcpu
```
```
In kernel/workqueue.c (ffffffff83ea6459)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff8111ce43)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/smpboot.c (ffffffff811297f3)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/smpboot.c:__smpboot_create_thread
```
```
In kernel/sched/core.c (ffffffff83ea839a)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
```
```
In kernel/sched/fair.c (ffffffff83ea884b)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/sched/build_policy.c (ffffffff83ea8b76)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:init_sched_dl_class
  - kernel/sched/build_policy.c:init_sched_rt_class
```
```
In kernel/sched/build_utility.c (ffffffff8116bde5)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:sched_numa_find_closest
  - kernel/sched/build_utility.c:sched_domains_numa_masks_set
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sd_numa_mask
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_show_numa
  - kernel/sched/build_utility.c:sched_show_numa
  - kernel/sched/build_utility.c:cpu_cpu_mask
```
```
In kernel/irq/irqdesc.c (ffffffff81194e99)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/irq/affinity.c (ffffffff811a67f6)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
```
In kernel/profile.c (ffffffff811d1a32)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/smp.c (ffffffff811f98d0)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/taskstats.c (ffffffff8124eac8)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ring_buffer.c (ffffffff8125e387)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8126cc87)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b886e)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/memalloc.c (ffffffff8131bfb1)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:prefill_mem_cache
```
```
In kernel/bpf/cpumap.c (ffffffff8131f8bf)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In kernel/events/core.c (ffffffff8134a940)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In kernel/events/ring_buffer.c (ffffffff8134bf41)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (ffffffff8134c3c9)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/events/callchain.c:alloc_callchain_buffers
```
```
In mm/vmstat.c (ffffffff81395775)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:vmstat_cpu_online
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/percpu.c (ffffffff8139c880)
Location: include/linux/topology.h:94
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff813f133d)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
```
```
In mm/zswap.c (ffffffff81401f1e)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/zswap.c:zswap_dstmem_prepare
```
```
In mm/mempolicy.c (ffffffff8141a342)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In crypto/scompress.c (ffffffff8171106b)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_init_tfm
```
```
In block/blk-mq.c (ffffffff81749d87)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-mq-cpumap.c (ffffffff8174d97c)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
```
```
In lib/cpu_rmap.c (ffffffff81891337)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/acpi_processor.c (ffffffff81965ce6)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff83eebba3)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
```
In drivers/base/cpu.c (ffffffff81af04ae)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/cpu.c:cpu_subsys_online
  - drivers/base/cpu.c:cpu_subsys_online
```
```
In drivers/base/node.c (ffffffff81b15601)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81b54168)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In drivers/md/dm-stats.c (ffffffff81d1d4ce)
Location: include/linux/topology.h:94
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff83f02453)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init
```
```
In net/core/sysctl_net_core.c (ffffffff81dba530)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81dc5519)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:expand_xps_map
```
```
In net/ipv4/tcp.c (ffffffff81eabbf2)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbe50a)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
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
In arch/x86/events/amd/core.c (ffffffff8100b7c2)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff81015ec2)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff8101689c)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff81017bc0)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/lbr.c (ffffffff8101d254)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff8101fecd)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff81022d29)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
  - arch/x86/events/intel/uncore.c:uncore_device_to_die
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105788e)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8107451a)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81085d05)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810865a6)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81088d73)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mba_sc_domain_allocate
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810912ed)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109dae2)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff836b2b06)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b796a)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810aceb6)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff836b9f04)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff836c85ae)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff836c8a9b)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
```
```
In kernel/fork.c (ffffffff836c91f5)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/cpu.c (ffffffff810fac5d)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/sys.c (ffffffff81116922)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getcpu
  - kernel/sys.c:__x64_sys_getcpu
```
```
In kernel/workqueue.c (ffffffff836cac19)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff81129f63)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/smpboot.c (ffffffff81136c93)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/smpboot.c:__smpboot_create_thread
```
```
In kernel/sched/core.c (ffffffff836ccc6a)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
```
```
In kernel/sched/fair.c (ffffffff836cd20e)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/sched/build_policy.c (ffffffff836cd636)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:init_sched_dl_class
  - kernel/sched/build_policy.c:init_sched_rt_class
```
```
In kernel/sched/build_utility.c (ffffffff8117c345)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:sched_numa_find_closest
  - kernel/sched/build_utility.c:sched_domains_numa_masks_set
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sd_numa_mask
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_show_numa
  - kernel/sched/build_utility.c:sched_show_numa
  - kernel/sched/build_utility.c:cpu_cpu_mask
```
```
In kernel/irq/irqdesc.c (ffffffff811a66a9)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/profile.c (ffffffff811e5d22)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/smp.c (ffffffff8120ef70)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/taskstats.c (ffffffff81265e78)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ring_buffer.c (ffffffff81275567)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81283e17)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff812dbeae)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/memalloc.c (ffffffff8134ba61)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:prefill_mem_cache
```
```
In kernel/bpf/cpumap.c (ffffffff8134f8bf)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In kernel/events/core.c (ffffffff8137b980)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In kernel/events/ring_buffer.c (ffffffff8137cf91)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (ffffffff8137d419)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/events/callchain.c:alloc_callchain_buffers
```
```
In kernel/rseq.c (ffffffff813880e4)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_update_cpu_node_id
  - kernel/rseq.c:perf_trace_rseq_update
  - kernel/rseq.c:trace_event_raw_event_rseq_update
```
```
In mm/vmstat.c (ffffffff813c8395)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:vmstat_cpu_online
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/percpu.c (ffffffff813cf960)
Location: include/linux/topology.h:94
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81424e7d)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
```
```
In mm/zswap.c (ffffffff81434e1e)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
  - mm/zswap.c:zswap_dstmem_prepare
  - mm/zswap.c:zswap_dstmem_prepare
```
```
In mm/mempolicy.c (ffffffff8144d8e2)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In crypto/scompress.c (ffffffff8174bb5b)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_init_tfm
```
```
In block/blk-mq.c (ffffffff8178649a)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-mq-cpumap.c (ffffffff81789efc)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
```
```
In lib/cpu_rmap.c (ffffffff818d3647)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In lib/group_cpus.c (ffffffff818e7226)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - lib/group_cpus.c:group_cpus_evenly
```
```
In drivers/acpi/acpi_processor.c (ffffffff819ac246)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff837117e3)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
```
In drivers/base/cpu.c (ffffffff81b3e60e)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/cpu.c:cpu_subsys_online
  - drivers/base/cpu.c:cpu_subsys_online
```
```
In drivers/base/node.c (ffffffff81b64371)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81ba76b8)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In drivers/md/dm-stats.c (ffffffff81d866c3)
Location: include/linux/topology.h:94
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff83728343)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init
```
```
In net/core/sysctl_net_core.c (ffffffff81e2ac8c)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81e33fea)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:expand_xps_map
```
```
In net/ipv4/tcp.c (ffffffff81f0a3b2)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201f36a)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
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
In arch/x86/events/amd/core.c (ffffffff81010f42)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff8101b996)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff8101c3dc)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff8101d700)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/lbr.c (ffffffff810231e4)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
```
```
In arch/x86/events/intel/pt.c (ffffffff81025f8d)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff81028e59)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
  - arch/x86/events/intel/uncore.c:uncore_device_to_die
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105eb2e)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8107b9fa)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108d486)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108fc83)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mba_sc_domain_allocate
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810986d0)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a50f0)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff838e3406)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e82b6)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b3ad6)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff838ea834)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff838f91ae)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff838f96ca)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
```
```
In kernel/fork.c (ffffffff838f9e45)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/cpu.c (ffffffff8110407d)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/sys.c (ffffffff81120312)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getcpu
  - kernel/sys.c:__x64_sys_getcpu
```
```
In kernel/workqueue.c (ffffffff838fb865)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/workqueue.c:cpus_share_numa
  - kernel/workqueue.c:cpus_share_numa
  - kernel/workqueue.c:init_pod_type
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff81134600)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/smpboot.c (ffffffff81141d03)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/smpboot.c:__smpboot_create_thread
```
```
In kernel/sched/core.c (ffffffff838fe04b)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
```
```
In kernel/sched/fair.c (ffffffff838fe5de)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/sched/build_policy.c (ffffffff838fea86)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:init_sched_dl_class
  - kernel/sched/build_policy.c:init_sched_rt_class
```
```
In kernel/sched/build_utility.c (ffffffff8118a025)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:sched_numa_find_closest
  - kernel/sched/build_utility.c:sched_domains_numa_masks_set
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sd_numa_mask
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_show_numa
  - kernel/sched/build_utility.c:sched_show_numa
  - kernel/sched/build_utility.c:cpu_cpu_mask
```
```
In kernel/irq/irqdesc.c (ffffffff811b61c9)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/profile.c (ffffffff811fba72)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/smp.c (ffffffff81226710)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/taskstats.c (ffffffff8127fd38)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ring_buffer.c (ffffffff8128fc17)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8129eda7)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff812f9f8e)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/memalloc.c (ffffffff8137322a)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_alloc_percpu_unit_init
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
```
```
In kernel/bpf/cpumap.c (ffffffff81376dcf)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In kernel/events/core.c (ffffffff813a4b80)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_parse_addr_filter
```
```
In kernel/events/ring_buffer.c (ffffffff813a61f1)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (ffffffff813a6679)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/events/callchain.c:alloc_callchain_buffers
```
```
In kernel/rseq.c (ffffffff813b1b44)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_update_cpu_node_id
  - kernel/rseq.c:perf_trace_rseq_update
  - kernel/rseq.c:trace_event_raw_event_rseq_update
```
```
In mm/vmstat.c (ffffffff813f2d85)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:vmstat_cpu_online
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/percpu.c (ffffffff813fa560)
Location: include/linux/topology.h:94
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff814520bd)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
```
```
In mm/zswap.c (ffffffff8146dd15)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In mm/mempolicy.c (ffffffff81487529)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In crypto/scompress.c (ffffffff8178da3b)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_init_tfm
```
```
In block/blk-mq.c (ffffffff817c8b73)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-mq-cpumap.c (ffffffff817cc67c)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
```
```
In lib/cpu_rmap.c (ffffffff81925727)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In lib/group_cpus.c (ffffffff8192e241)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - lib/group_cpus.c:group_cpus_evenly
```
```
In drivers/acpi/acpi_processor.c (ffffffff819f5426)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff83945173)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
```
In drivers/base/cpu.c (ffffffff81b9654c)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/base/cpu.c:arch_unregister_cpu
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:cpu_subsys_online
  - drivers/base/cpu.c:cpu_subsys_online
```
```
In drivers/base/node.c (ffffffff81bb7f48)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81bfb968)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In drivers/md/dm-stats.c (ffffffff81e3ddfb)
Location: include/linux/topology.h:94
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8395c2d3)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init
```
```
In net/core/sysctl_net_core.c (ffffffff81ee8a9c)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81ef2b25)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:expand_xps_map
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204cc7d)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:sigpool_reserve_scratch
```
```
In net/ipv6/seg6_hmac.c (ffffffff820ee49a)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
```
In lib/objpool.c (ffffffff82191b37)
Location: include/linux/topology.h:94
Inline: True
Inline callers:
  - lib/objpool.c:objpool_init_percpu_slots
  - lib/objpool.c:objpool_init_percpu_slots
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
In arch/arm64/kernel/irq.c (ffff8000114336f8)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/arm64/kernel/irq.c:init_IRQ
```
```
In arch/arm64/kernel/sdei.c (ffff8000100abbb8)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/arm64/kernel/sdei.c:_init_sdei_stack
```
```
In arch/arm64/mm/numa.c (ffff8000100b211c)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/arm64/mm/numa.c:numa_update_cpu
```
```
In kernel/fork.c (ffff8000100f4b3c)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/cpu.c (ffff8000100f95e4)
Location: include/linux/topology.h:93
Inline: True
```
```
In kernel/sys.c (ffff8000101173e8)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_sys_getcpu
```
```
In kernel/workqueue.c (ffff800011442ffc)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffff80001012824c)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/smpboot.c (ffff80001012f21c)
Location: include/linux/topology.h:93
Inline: True
```
```
In kernel/sched/core.c (ffff800010139450)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/fair.c (ffff80001014d4d4)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/sched/rt.c (ffff8000114450cc)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/deadline.c (ffff800011445140)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/topology.c (ffff80001015b86c)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_numa_find_closest
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sd_numa_mask
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/sched/debug.c (ffff8000101631bc)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/irq/irqdesc.c (ffff800010d9c060)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/affinity.c (ffff80001018822c)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffff8000101989b8)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/smp.c (ffff8000101bd140)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/taskstats.c (ffff80001020cfa8)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ring_buffer.c (ffff800010219ec0)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffff800010225b3c)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffff800010259bbc)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/cpumap.c (ffff80001028879c)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/events/core.c (ffff8000102a1674)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
```
```
In kernel/events/ring_buffer.c (ffff8000102a2048)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (ffff8000102a36c4)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_buffers
```
```
In mm/vmstat.c (ffff8000102dbec0)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/percpu.c (ffff8000102e1b84)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/zswap.c (ffff80001032b080)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/zswap.c:zswap_dstmem_prepare
```
```
In mm/mempolicy.c (ffff80001033b724)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In security/apparmor/lsm.c (ffff80001146b760)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
  - security/apparmor/lsm.c:alloc_buffers
```
```
In crypto/scompress.c (ffff8000105c4e74)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_init_tfm
```
```
In block/blk-mq.c (ffff8000105f2cf4)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-mq-cpumap.c (ffff8000105f6234)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
```
```
In lib/cpu_rmap.c (ffff800010662918)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/msi.c (ffff800010713dd0)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_irq_get_node
```
```
In drivers/acpi/acpi_processor.c (ffff80001076f898)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
```
```
In drivers/base/cpu.c (ffff8000108ef120)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/cpu.c:cpu_subsys_online
  - drivers/base/cpu.c:cpu_subsys_online
```
```
In drivers/base/node.c (ffff800010910224)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
```
```
In drivers/base/arch_topology.c (ffff8000109204e0)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:cpu_coregroup_mask
```
```
In drivers/md/dm-stats.c (ffff800010b0d32c)
Location: include/linux/topology.h:93
Inline: True
```
```
In net/core/sysctl_net_core.c (ffff800010bc5c50)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffff800010bca7c4)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/ipv4/tcp.c (ffff800010c6f60c)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
```
In net/ipv6/seg6_hmac.c (ffff8000114b51d4)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/vdso.c (c000000000020068)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/powerpc/kernel/vdso.c:vdso_getcpu_init
```
```
In arch/powerpc/kernel/smp.c (c000000001350750)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:cpu_cpu_mask
  - arch/powerpc/kernel/smp.c:cpu_cpu_mask
```
```
In arch/powerpc/mm/numa.c (c0000000000a14e0)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:update_cpu_topology
  - arch/powerpc/mm/numa.c:find_and_online_cpu_nid
  - arch/powerpc/mm/numa.c:ppc_numa_cpu_prepare
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000bf0b0)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_queue_page_alloc
  - arch/powerpc/sysdev/xive/common.c:xive_prepare_cpu
```
```
In arch/powerpc/platforms/powernv/setup.c (c00000000135abd4)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/setup.c:pnv_probe
```
```
In arch/powerpc/platforms/pseries/dtl.c (c0000000000fce68)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/dtl.c:dtl_file_open
```
```
In arch/powerpc/perf/imc-pmu.c (c00000000012d680)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/imc-pmu.c:trace_imc_mem_alloc
  - arch/powerpc/perf/imc-pmu.c:thread_imc_mem_alloc
  - arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_online
  - arch/powerpc/perf/imc-pmu.c:nest_imc_event_init
  - arch/powerpc/perf/imc-pmu.c:nest_imc_counters_release
  - arch/powerpc/perf/imc-pmu.c:ppc_nest_imc_cpu_online
  - arch/powerpc/perf/imc-pmu.c:ppc_nest_imc_cpu_online
  - arch/powerpc/perf/imc-pmu.c:ppc_nest_imc_cpu_offline
```
```
In kernel/fork.c (c00000000013ab7c)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/cpu.c (c000000000140434)
Location: include/linux/topology.h:93
Inline: True
```
```
In kernel/sys.c (c00000000015e070)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_getcpu
```
```
In kernel/workqueue.c (c000000000163780)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (c000000000172880)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/smpboot.c (c00000000017899c)
Location: include/linux/topology.h:93
Inline: True
```
```
In kernel/sched/core.c (c000000000186120)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/fair.c (c0000000001a0380)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/sched/rt.c (c000000001369a0c)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/deadline.c (c000000001369abc)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/topology.c (c0000000001aff30)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_numa_find_closest
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sd_numa_mask
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_cpu_mask
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/sched/debug.c (c0000000001b99cc)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
```
```
In kernel/irq/irqdesc.c (c0000000001d2074)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/affinity.c (c0000000001e1fd0)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
```
In kernel/smp.c (c0000000002230e8)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/taskstats.c (c00000000028aca0)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ring_buffer.c (c00000000029bfa0)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (c0000000002ab2dc)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (c0000000002fd4c4)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/cpumap.c (c000000000333c74)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/events/core.c (c000000000353ab0)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
```
```
In kernel/events/ring_buffer.c (c000000000353db4)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (c000000000355930)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/events/callchain.c:alloc_callchain_buffers
```
```
In mm/vmstat.c (c00000000039ba60)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/percpu.c (c0000000003a19fc)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/page_alloc.c (c0000000003eca80)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:__build_all_zonelists
```
```
In mm/zswap.c (c0000000004020b4)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/zswap.c:zswap_dstmem_prepare
```
```
In mm/mempolicy.c (c000000000416484)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/memory_hotplug.c (c00000000042d590)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
```
```
In security/apparmor/lsm.c (c00000000139a324)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
```
```
In crypto/scompress.c (c00000000074e63c)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_init_tfm
```
```
In block/blk-mq.c (c00000000078a3f0)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-mq-cpumap.c (c00000000078e3a0)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
```
```
In lib/cpu_rmap.c (c000000000816a90)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/msi.c (c000000000883710)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_irq_get_node
```
```
In drivers/base/cpu.c (c00000000098809c)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/cpu.c:cpu_subsys_online
  - drivers/base/cpu.c:cpu_subsys_online
```
```
In drivers/base/node.c (c0000000009b0e80)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
```
```
In drivers/md/dm-stats.c (c000000000bffc90)
Location: include/linux/topology.h:93
Inline: True
```
```
In net/core/sysctl_net_core.c (c000000000ca08f8)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (c000000000cadb74)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/ipv4/tcp.c (c000000000d76420)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
```
In net/ipv6/seg6_hmac.c (c0000000013c7170)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
</details>
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
In arch/x86/events/amd/core.c (ffffffff81009468)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009835)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
```
```
In arch/x86/events/intel/core.c (ffffffff8100e8bb)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff8100eecd)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff81011442)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff81015503)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff810169f3)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038768)
Location: include/linux/topology.h:93
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049e5d)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105939a)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060dae)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
```
```
In arch/x86/kernel/smpboot.c (ffffffff810638b7)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828a7955)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d335)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff828a9cf5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
```
```
In kernel/fork.c (ffffffff81099c01)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/cpu.c (ffffffff8109dc68)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/sys.c (ffffffff810b232b)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getcpu
  - kernel/sys.c:__x64_sys_getcpu
```
```
In kernel/workqueue.c (ffffffff810b9176)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810c2f69)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/smpboot.c (ffffffff810c9755)
Location: include/linux/topology.h:93
Inline: True
```
```
In kernel/sched/core.c (ffffffff828b60a9)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/fair.c (ffffffff810e6fb2)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/sched/rt.c (ffffffff828b6661)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (ffffffff828b66cb)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/topology.c (ffffffff810f0916)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_numa_find_closest
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sd_numa_mask
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/sched/debug.c (ffffffff810f6ce2)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/irq/irqdesc.c (ffffffff81a67063)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/affinity.c (ffffffff8111a632)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff81129ff5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/smp.c (ffffffff811470f5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/taskstats.c (ffffffff8118d6ad)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ring_buffer.c (ffffffff81198cb9)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811a1428)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d117d)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/cpumap.c (ffffffff811f8ac6)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/events/core.c (ffffffff8120f9ff)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
```
```
In kernel/events/ring_buffer.c (ffffffff8120fc6e)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (ffffffff81210ef4)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/events/callchain.c:alloc_callchain_buffers
```
```
In mm/vmstat.c (ffffffff81240025)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/percpu.c (ffffffff81243ee3)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/zswap.c (ffffffff81286dd5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/zswap.c:zswap_dstmem_prepare
```
```
In mm/mempolicy.c (ffffffff81294d52)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/memory_hotplug.c (ffffffff812a4293)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
```
```
In security/apparmor/lsm.c (ffffffff828da4e7)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
```
```
In crypto/scompress.c (ffffffff814c1a69)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_init_tfm
```
```
In block/blk-mq.c (ffffffff814eba8d)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-mq-cpumap.c (ffffffff814ee454)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
```
```
In lib/cpu_rmap.c (ffffffff8154e456)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/msi.c (ffffffff8159dfce)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_irq_get_node
```
```
In drivers/acpi/acpi_processor.c (ffffffff815d5090)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff828e7db2)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
```
In drivers/base/cpu.c (ffffffff816c8bf5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/cpu.c:cpu_subsys_online
  - drivers/base/cpu.c:cpu_subsys_online
```
```
In drivers/base/node.c (ffffffff816e28ad)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
```
```
In drivers/md/dm-stats.c (ffffffff8185b3bd)
Location: include/linux/topology.h:93
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff828f967b)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
```
In net/core/sysctl_net_core.c (ffffffff818c96e0)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff818d1da9)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/ipv4/tcp.c (ffffffff8195d8cd)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
```
In net/ipv6/seg6_hmac.c (ffffffff82908e7b)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
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
In arch/x86/events/amd/core.c (ffffffff81007bf8)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff81007fd5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
```
```
In arch/x86/events/intel/core.c (ffffffff8100d5bb)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff8100dc2d)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff810101e2)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff810147d3)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015e23)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81028145)
Location: include/linux/topology.h:93
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8103919a)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810495ba)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105120e)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
```
```
In arch/x86/kernel/smpboot.c (ffffffff81053bc7)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8289fa2c)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d6b5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff828a1e65)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
```
```
In kernel/fork.c (ffffffff81088641)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/cpu.c (ffffffff8108c688)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/sys.c (ffffffff810a0c4b)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getcpu
  - kernel/sys.c:__x64_sys_getcpu
```
```
In kernel/workqueue.c (ffffffff810a7ab6)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810b17a9)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/smpboot.c (ffffffff810b7f75)
Location: include/linux/topology.h:93
Inline: True
```
```
In kernel/sched/core.c (ffffffff828ae24b)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/fair.c (ffffffff810d6152)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/sched/rt.c (ffffffff828ae857)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/deadline.c (ffffffff828ae8c1)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/topology.c (ffffffff810e0986)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_numa_find_closest
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sd_numa_mask
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/sched/debug.c (ffffffff810e6eb2)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/irq/irqdesc.c (ffffffff81a23b23)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/affinity.c (ffffffff8110b6a2)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff8111c885)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/smp.c (ffffffff8113a3d5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/taskstats.c (ffffffff811807cd)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ring_buffer.c (ffffffff8118c4f9)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811943f8)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c3f4d)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/cpumap.c (ffffffff811eb816)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/events/core.c (ffffffff8120278f)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
```
```
In kernel/events/ring_buffer.c (ffffffff812029fe)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (ffffffff81203c84)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/events/callchain.c:alloc_callchain_buffers
```
```
In mm/vmstat.c (ffffffff81233025)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/percpu.c (ffffffff81236eb3)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/zswap.c (ffffffff81278c35)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/zswap.c:zswap_dstmem_prepare
```
```
In mm/mempolicy.c (ffffffff81286962)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/memory_hotplug.c (ffffffff81295d63)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
```
```
In security/apparmor/lsm.c (ffffffff828d2c03)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
```
```
In crypto/scompress.c (ffffffff814b2489)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_init_tfm
```
```
In block/blk-mq.c (ffffffff814dbfdd)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-mq-cpumap.c (ffffffff814de9a4)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
```
```
In lib/cpu_rmap.c (ffffffff8153e736)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/msi.c (ffffffff8158d15e)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_irq_get_node
```
```
In drivers/acpi/acpi_processor.c (ffffffff815bec50)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
```
```
In drivers/base/cpu.c (ffffffff816a3f25)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/cpu.c:cpu_subsys_online
  - drivers/base/cpu.c:cpu_subsys_online
```
```
In drivers/base/node.c (ffffffff816bceed)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
```
```
In drivers/scsi/storvsc_drv.c (ffffffff8171433d)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/scsi/storvsc_drv.c:storvsc_queuecommand
  - drivers/scsi/storvsc_drv.c:storvsc_queuecommand
```
```
In drivers/md/dm-stats.c (ffffffff81822987)
Location: include/linux/topology.h:93
Inline: True
```
```
In drivers/edac/mce_amd.c (ffffffff8182a290)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/edac/mce_amd.c:amd_decode_mce
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff828f1164)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
```
In drivers/hv/channel.c (ffffffff81850ed6)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/hv/channel.c:vmbus_alloc_ring
```
```
In net/core/sysctl_net_core.c (ffffffff81883620)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff8188bc39)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/ipv4/tcp.c (ffffffff819173bd)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
```
In net/ipv6/seg6_hmac.c (ffffffff829011c9)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
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
In arch/x86/events/amd/core.c (ffffffff81009428)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff810097f5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
```
```
In arch/x86/events/intel/core.c (ffffffff8100e87b)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff8100ee8d)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff81011402)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff810154c3)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff810169b3)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810385c8)
Location: include/linux/topology.h:93
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049c9d)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810597ca)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810611de)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
```
```
In arch/x86/kernel/smpboot.c (ffffffff81063d67)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828ba854)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d7e5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff828bcbf4)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
```
```
In kernel/fork.c (ffffffff81099bb1)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/cpu.c (ffffffff8109dc18)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/sys.c (ffffffff810b188b)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getcpu
  - kernel/sys.c:__x64_sys_getcpu
```
```
In kernel/workqueue.c (ffffffff810b86d6)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810c24b9)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/smpboot.c (ffffffff810c8c85)
Location: include/linux/topology.h:93
Inline: True
```
```
In kernel/sched/core.c (ffffffff828c8fbf)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/fair.c (ffffffff810e3382)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/sched/rt.c (ffffffff828c9505)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/rt.c:alloc_rt_sched_group
```
```
In kernel/sched/deadline.c (ffffffff828c956f)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/topology.c (ffffffff810eda46)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_numa_find_closest
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sd_numa_mask
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/sched/debug.c (ffffffff810f3ef2)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/irq/irqdesc.c (ffffffff81ad3473)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/affinity.c (ffffffff81118522)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff81127d15)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/smp.c (ffffffff81144fa5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/taskstats.c (ffffffff8118b47d)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ring_buffer.c (ffffffff81196a89)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8119f1f8)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cef4d)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/cpumap.c (ffffffff811f6896)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/events/core.c (ffffffff8120d79f)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
```
```
In kernel/events/ring_buffer.c (ffffffff8120da0e)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (ffffffff8120ec94)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/events/callchain.c:alloc_callchain_buffers
```
```
In mm/vmstat.c (ffffffff8123ddc5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/percpu.c (ffffffff81241c83)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/zswap.c (ffffffff81284be5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/zswap.c:zswap_dstmem_prepare
```
```
In mm/mempolicy.c (ffffffff81292b62)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/memory_hotplug.c (ffffffff812a20a3)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
```
```
In security/apparmor/lsm.c (ffffffff828ed25b)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
```
```
In crypto/scompress.c (ffffffff814bdaf9)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_init_tfm
```
```
In block/blk-mq.c (ffffffff814e7b1d)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-mq-cpumap.c (ffffffff814ea4e4)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
```
```
In lib/cpu_rmap.c (ffffffff8154a196)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/msi.c (ffffffff8159e54e)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_irq_get_node
```
```
In drivers/acpi/acpi_processor.c (ffffffff815d7430)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff828fb8b8)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
```
In drivers/base/cpu.c (ffffffff816f7165)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/cpu.c:cpu_subsys_online
  - drivers/base/cpu.c:cpu_subsys_online
```
```
In drivers/base/node.c (ffffffff8170faad)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
```
```
In drivers/md/dm-stats.c (ffffffff818aa9ed)
Location: include/linux/topology.h:93
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8290deb3)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
```
In net/core/sysctl_net_core.c (ffffffff8191a6e0)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81922da9)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/ipv4/tcp.c (ffffffff819c809d)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
```
In net/ipv6/seg6_hmac.c (ffffffff8291e775)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
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
In arch/x86/events/amd/core.c (ffffffff81009588)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009955)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_alloc
```
```
In arch/x86/events/intel/core.c (ffffffff8100ea4b)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (ffffffff8100f05d)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
```
In arch/x86/events/intel/ds.c (ffffffff81011612)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff81015703)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016bf3)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:allocate_boxes
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810395c8)
Location: include/linux/topology.h:93
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104b0ad)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105ac6a)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106279e)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
```
```
In arch/x86/kernel/smpboot.c (ffffffff81065327)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:cpu_cpu_mask
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828ba96a)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828be33e)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106fa65)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff828bfd4c)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828ca2b0)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109a619)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff828cb040)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
```
```
In kernel/fork.c (ffffffff810a1801)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/fork.c:fork_idle
```
```
In kernel/cpu.c (ffffffff810a5b08)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/sys.c (ffffffff810b9c7b)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getcpu
  - kernel/sys.c:__x64_sys_getcpu
```
```
In kernel/workqueue.c (ffffffff810c1b12)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/kthread.c (ffffffff810caa79)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_cpu
```
```
In kernel/smpboot.c (ffffffff810d11f5)
Location: include/linux/topology.h:93
Inline: True
```
```
In kernel/sched/core.c (ffffffff828ce2ff)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/fair.c (ffffffff810eef62)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In kernel/sched/rt.c (ffffffff828ce8b7)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (ffffffff828ce921)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/topology.c (ffffffff810f8a86)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_numa_find_closest
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sd_numa_mask
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_cpu_mask
```
```
In kernel/sched/debug.c (ffffffff810feee5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/irq/irqdesc.c (ffffffff81adf973)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/affinity.c (ffffffff81123bb2)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff81134395)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/smp.c (ffffffff81151b69)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/taskstats.c (ffffffff81198ded)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/trace/ring_buffer.c (ffffffff811a4699)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811acf47)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dd1dd)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/cpumap.c (ffffffff812054c6)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In kernel/events/core.c (ffffffff8121c63f)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:perf_event_set_filter
```
```
In kernel/events/ring_buffer.c (ffffffff8121c8be)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/callchain.c (ffffffff8121dba4)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - kernel/events/callchain.c:alloc_callchain_buffers
```
```
In mm/vmstat.c (ffffffff8124d4f5)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/percpu.c (ffffffff81251423)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/zswap.c (ffffffff81294885)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/zswap.c:zswap_dstmem_prepare
```
```
In mm/mempolicy.c (ffffffff812a2952)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/memory_hotplug.c (ffffffff812b2333)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
```
```
In security/apparmor/lsm.c (ffffffff828f267d)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
```
```
In crypto/scompress.c (ffffffff814d65c9)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_init_tfm
```
```
In block/blk-mq.c (ffffffff81500abd)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-mq-cpumap.c (ffffffff815034b4)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
```
```
In lib/cpu_rmap.c (ffffffff81563fe6)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pci/msi.c (ffffffff815b897e)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_irq_get_node
```
```
In drivers/acpi/acpi_processor.c (ffffffff815f12f0)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff829015e9)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
```
In drivers/base/cpu.c (ffffffff81711a05)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:register_cpu
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/cpu.c:cpu_subsys_online
  - drivers/base/cpu.c:cpu_subsys_online
```
```
In drivers/base/node.c (ffffffff8172ab9d)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
```
```
In drivers/md/dm-stats.c (ffffffff818c6605)
Location: include/linux/topology.h:93
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff829148c9)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
```
In net/core/sysctl_net_core.c (ffffffff8193b92a)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff819441d9)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/ipv4/tcp.c (ffffffff819d1bed)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
```
In net/ipv6/seg6_hmac.c (ffffffff829251d9)
Location: include/linux/topology.h:93
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
</details>
</li>
</ul>

## Differences
