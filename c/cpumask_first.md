# Function: <code>cpumask_first</code>

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
In arch/x86/events/intel/p4.c (ffffffff81012a68)
Location: include/linux/cpumask.h:172
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103e8b6)
Location: include/linux/cpumask.h:172
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104ac38)
Location: include/linux/cpumask.h:172
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state
```
```
In arch/x86/kernel/smpboot.c (ffffffff81051516)
Location: include/linux/cpumask.h:172
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810747c9)
Location: include/linux/cpumask.h:172
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff81081b67)
Location: include/linux/cpumask.h:172
Inline: True
Inline callers:
  - kernel/cpu.c:disable_nonboot_cpus
```
```
In kernel/reboot.c (ffffffff810a29eb)
Location: include/linux/cpumask.h:172
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810a5baf)
Location: include/linux/cpumask.h:172
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
```
```
In kernel/sched/fair.c (ffffffff810bcbb5)
Location: include/linux/cpumask.h:172
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:trigger_load_balance
```
```
In kernel/sched/rt.c (ffffffff810bf1c0)
Location: include/linux/cpumask.h:172
Inline: True
Inline callers:
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:find_next_push_cpu
```
```
In kernel/sched/deadline.c (ffffffff810c14eb)
Location: include/linux/cpumask.h:172
Inline: True
Inline callers:
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/cpupri.c (ffffffff810c415f)
Location: include/linux/cpumask.h:172
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/cpudeadline.c (ffffffff810c45f6)
Location: include/linux/cpumask.h:172
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/stats.c (ffffffff810c53db)
Location: include/linux/cpumask.h:172
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_start
```
```
In kernel/sched/debug.c (ffffffff810c5a5b)
Location: include/linux/cpumask.h:172
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_start
```
```
In kernel/power/poweroff.c (ffffffff810d6566)
Location: include/linux/cpumask.h:172
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/irq/manage.c (ffffffff810db3b5)
Location: include/linux/cpumask.h:172
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/time/clocksource.c (ffffffff810f7f38)
Location: include/linux/cpumask.h:172
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/time/tick-common.c (ffffffff810fca36)
Location: include/linux/cpumask.h:172
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffffffff810fce3e)
Location: include/linux/cpumask.h:172
Inline: True
```
```
In kernel/stop_machine.c (ffffffff81120039)
Location: include/linux/cpumask.h:172
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/padata.c (ffffffff8118989e)
Location: include/linux/cpumask.h:172
Inline: True
Inline callers:
  - kernel/padata.c:padata_index_to_cpu
```
```
In block/blk-mq.c (ffffffff813c381e)
Location: include/linux/cpumask.h:172
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In block/blk-mq-cpumap.c (ffffffff813c862e)
Location: include/linux/cpumask.h:172
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_update_queue_map
  - block/blk-mq-cpumap.c:blk_mq_update_queue_map
```
```
In lib/percpu_ida.c (ffffffff813ffada)
Location: include/linux/cpumask.h:172
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In drivers/cpufreq/cpufreq.c (ffffffff816b0466)
Location: include/linux/cpumask.h:172
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline_prepare
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff816b8792)
Location: include/linux/cpumask.h:172
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In arch/x86/power/cpu.c (ffffffff816faedc)
Location: include/linux/cpumask.h:172
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:bsp_pm_callback
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
In arch/x86/events/intel/p4.c (ffffffff810127ba)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103e6e6)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104ad88)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105167f)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81075da6)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff81084cbe)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/cpu.c:disable_nonboot_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/reboot.c (ffffffff810a60f4)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810b202b)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810c1ed1)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
```
```
In kernel/sched/rt.c (ffffffff810c2ba3)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/sched/rt.c:find_next_push_cpu
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffff810c4fa6)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/cpupri.c (ffffffff810c7e2b)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/cpudeadline.c (ffffffff810c82cb)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/stats.c (ffffffff810c907b)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_start
```
```
In kernel/sched/debug.c (ffffffff810c999b)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_start
```
```
In kernel/power/poweroff.c (ffffffff810db3e6)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/irq/irqdesc.c (ffffffff81892c2a)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/manage.c (ffffffff810e0a42)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/irq/affinity.c (ffffffff810e8ead)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_mask
```
```
In kernel/time/clocksource.c (ffffffff810ff059)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/time/tick-common.c (ffffffff81103da6)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffffffff8110419b)
Location: include/linux/cpumask.h:176
Inline: True
```
```
In kernel/stop_machine.c (ffffffff81127faf)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/padata.c (ffffffff8119bf7e)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/padata.c:padata_index_to_cpu
```
```
In block/blk-mq.c (ffffffff8140851e)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In block/blk-mq-cpumap.c (ffffffff8140c892)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_update_queue_map
  - block/blk-mq-cpumap.c:blk_mq_update_queue_map
```
```
In lib/percpu_ida.c (ffffffff814471ca)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In drivers/pci/msi.c (ffffffff814a0f7f)
Location: include/linux/cpumask.h:176
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81712347)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8171a4eb)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
```
In arch/x86/power/cpu.c (ffffffff81760038)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:bsp_pm_callback
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
In arch/x86/events/intel/p4.c (ffffffff810128aa)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103e068)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81043e64)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
```
```
In arch/x86/kernel/cpu/intel_rdt_schemata.c (ffffffff81044d1b)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104d1e8)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state
```
```
In arch/x86/kernel/smpboot.c (ffffffff81053fb0)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81079961)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff81089dcd)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/reboot.c (ffffffff810abd54)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810b8403)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domain
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810c7ed9)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/rt.c (ffffffff810c8c08)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/sched/rt.c:find_next_push_cpu
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffff810cafd6)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/cpupri.c (ffffffff810cde19)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/cpudeadline.c (ffffffff810ce2ec)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/stats.c (ffffffff810cf08b)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_start
```
```
In kernel/sched/debug.c (ffffffff810cf9bb)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_start
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810d485d)
Location: include/linux/cpumask.h:176
Inline: True
```
```
In kernel/power/poweroff.c (ffffffff810e1eb5)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/irq/irqdesc.c (ffffffff818c74fb)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/manage.c (ffffffff810e7466)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/irq/affinity.c (ffffffff810efca1)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/time/clocksource.c (ffffffff81101ec9)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/time/tick-common.c (ffffffff8110b495)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffffffff8110b8cb)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_do_broadcast
```
```
In kernel/stop_machine.c (ffffffff81131c3f)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace_hwlat.c (ffffffff8116d4c8)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811969c1)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
```
In kernel/padata.c (ffffffff811abcb0)
Location: include/linux/cpumask.h:176
Inline: True
```
```
In block/blk-mq.c (ffffffff81422fc6)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In block/blk-mq-cpumap.c (ffffffff81427b48)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:get_first_sibling
```
```
In lib/percpu_ida.c (ffffffff814659fd)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81744c91)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8174c2a0)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
```
In arch/x86/power/cpu.c (ffffffff8178d037)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:bsp_pm_callback
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
In arch/x86/events/intel/p4.c (ffffffff81010f27)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103c078)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81042e2d)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
```
```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff8104475e)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff81044da9)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104d190)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state
```
```
In arch/x86/kernel/smpboot.c (ffffffff810538fb)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81056e1f)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:default_cpu_mask_to_apicid
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c80d)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cpu_mask_to_apicid
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81078210)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff81086c94)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/reboot.c (ffffffff810a8924)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810b1ce9)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810c1b83)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/rt.c (ffffffff810c2d34)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/sched/rt.c:find_next_push_cpu
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffff810c92a3)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/cpupri.c (ffffffff810ca788)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/cpudeadline.c (ffffffff810cac1b)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff810ccf4e)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/stats.c (ffffffff810ce291)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_start
```
```
In kernel/sched/debug.c (ffffffff810cea31)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_start
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810d3bbf)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
```
In kernel/power/poweroff.c (ffffffff810e0ff5)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/irq/irqdesc.c (ffffffff818fec88)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/manage.c (ffffffff810e6a55)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/irq/affinity.c (ffffffff810efc75)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/time/clocksource.c (ffffffff81104034)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/time/tick-common.c (ffffffff8110d386)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffffffff8110d90b)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_do_broadcast
```
```
In kernel/stop_machine.c (ffffffff81133211)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace_hwlat.c (ffffffff81170a10)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff8119dd63)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
```
In kernel/padata.c (ffffffff811b3110)
Location: include/linux/cpumask.h:176
Inline: True
```
```
In block/blk-mq.c (ffffffff81432b1e)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_hctx_next_cpu
  - block/blk-mq.c:blk_mq_alloc_request_hctx
```
```
In block/blk-mq-cpumap.c (ffffffff814350b0)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In lib/percpu_ida.c (ffffffff8146a7ae)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In drivers/pci/msi.c (ffffffff814cc730)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_irq_get_node
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81763329)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8176a5bd)
Location: include/linux/cpumask.h:176
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In arch/x86/power/cpu.c (ffffffff817ab1c7)
Location: include/linux/cpumask.h:176
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
In arch/x86/events/intel/p4.c (ffffffff81011747)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103ec88)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/intel_cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/intel_cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810462cd)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
```
```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff81047f2e)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff8104867c)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
```
```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff81050a90)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_save_state
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105763d)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105b466)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107e56c)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff8108da2f)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/reboot.c (ffffffff810af194)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810b90c5)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810c92f3)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/rt.c (ffffffff810ca4ce)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffff810d0993)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/cpupri.c (ffffffff810d1f98)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/topology.c (ffffffff810d35e4)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/stats.c (ffffffff810d5b6b)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_start
```
```
In kernel/sched/debug.c (ffffffff810d630b)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_start
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810db88f)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
```
In kernel/power/poweroff.c (ffffffff810e92c5)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/irq/irqdesc.c (ffffffff81988e70)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/manage.c (ffffffff810eec83)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/irq/affinity.c (ffffffff810f884e)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/time/clocksource.c (ffffffff8110f0ce)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/time/tick-common.c (ffffffff8111860a)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffffffff81118b8b)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_do_broadcast
```
```
In kernel/stop_machine.c (ffffffff811401d9)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace_hwlat.c (ffffffff8117dbd8)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811ad91b)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
```
In kernel/padata.c (ffffffff811c6d5e)
Location: include/linux/cpumask.h:182
Inline: True
```
```
In block/blk-mq.c (ffffffff8145e6e2)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_hctx_next_cpu
  - block/blk-mq.c:blk_mq_alloc_request_hctx
```
```
In block/blk-mq-cpumap.c (ffffffff81460cb2)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In lib/percpu_ida.c (ffffffff81496a8c)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In drivers/pci/msi.c (ffffffff8150cc60)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_irq_get_node
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817d92df)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff817e0467)
Location: include/linux/cpumask.h:182
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In arch/x86/power/cpu.c (ffffffff818226b7)
Location: include/linux/cpumask.h:182
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
In arch/x86/events/intel/p4.c (ffffffff81011f55)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81040274)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81048232)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:set_cache_qos_cfg
```
```
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff8104a79e)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff8104af5e)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8105368f)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105a530)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105e3b5)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810815f0)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff8109148f)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/reboot.c (ffffffff810b600a)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810c0bb4)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810c4be4)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/rt.c (ffffffff810d24ac)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffff810d8eb3)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/cpupri.c (ffffffff810da029)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/topology.c (ffffffff810db2a6)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/stats.c (ffffffff810ddb1b)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_start
```
```
In kernel/sched/debug.c (ffffffff810de1cb)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_start
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810e397e)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
```
In kernel/power/poweroff.c (ffffffff810f15f5)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/irq/irqdesc.c (ffffffff819e57ee)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/manage.c (ffffffff810f7073)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/irq/affinity.c (ffffffff8110092c)
Location: include/linux/cpumask.h:184
Inline: True
```
```
In kernel/time/clocksource.c (ffffffff8111aa9a)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/time/tick-common.c (ffffffff811251aa)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffffffff81125743)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_do_broadcast
```
```
In kernel/stop_machine.c (ffffffff8114ea0b)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace_hwlat.c (ffffffff8118ccd9)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811c4f37)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
```
In kernel/padata.c (ffffffff811e70c5)
Location: include/linux/cpumask.h:184
Inline: True
```
```
In block/blk-mq.c (ffffffff814920dc)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
```
In block/blk-mq-cpumap.c (ffffffff81494582)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In lib/percpu_ida.c (ffffffff814cbdfa)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In drivers/pci/msi.c (ffffffff81541ad0)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_irq_get_node
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81821e4f)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818290e3)
Location: include/linux/cpumask.h:184
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
```
In arch/x86/power/cpu.c (ffffffff8186c9a7)
Location: include/linux/cpumask.h:184
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
In arch/x86/events/intel/p4.c (ffffffff810125cf)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81041834)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81050d0f)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81057c12)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105ab1e)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105b371)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105d495)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
```
```
In arch/x86/kernel/smpboot.c (ffffffff810601b0)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81064045)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81088200)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff8109976f)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/reboot.c (ffffffff810bf29a)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810c9f24)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810cdfb4)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/rt.c (ffffffff810dbe1c)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffff810e29b3)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/cpupri.c (ffffffff810e3b79)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/topology.c (ffffffff810e4ea5)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/stats.c (ffffffff810e828b)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_start
```
```
In kernel/sched/debug.c (ffffffff810e894b)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_start
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810edf8e)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
```
In kernel/power/poweroff.c (ffffffff810fcc85)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/irq/irqdesc.c (ffffffff81a20954)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/manage.c (ffffffff811027e3)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/irq/affinity.c (ffffffff8110c0eb)
Location: include/linux/cpumask.h:196
Inline: True
```
```
In kernel/time/clocksource.c (ffffffff81125fba)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/time/tick-common.c (ffffffff8113089a)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffffffff81130e33)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_do_broadcast
```
```
In kernel/stop_machine.c (ffffffff8115b7eb)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace_hwlat.c (ffffffff8119a7e9)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811d6b9e)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
```
In kernel/padata.c (ffffffff811f7cf5)
Location: include/linux/cpumask.h:196
Inline: True
```
```
In block/blk-mq.c (ffffffff814abb90)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
```
In block/blk-mq-cpumap.c (ffffffff814ae6b6)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In drivers/pci/msi.c (ffffffff81558d90)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_irq_get_node
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8184dccf)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81855173)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
```
In arch/x86/power/cpu.c (ffffffff8188c9b7)
Location: include/linux/cpumask.h:196
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
In arch/x86/events/intel/p4.c (ffffffff81013acc)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81043ce1)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81053ddf)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ae89)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105de1f)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105e6e1)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060825)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
```
```
In arch/x86/kernel/smpboot.c (ffffffff81063ac1)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81067705)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108be4e)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff8109daba)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/reboot.c (ffffffff810c53ba)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810d1bca)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810d73ea)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/rt.c (ffffffff810e2dd7)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffff810e94c3)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/cpupri.c (ffffffff810ea78d)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/topology.c (ffffffff810ebe50)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/stats.c (ffffffff810ef20b)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_start
```
```
In kernel/sched/debug.c (ffffffff810ef73b)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_start
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f4d47)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
```
In kernel/power/poweroff.c (ffffffff81105375)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/irq/irqdesc.c (ffffffff81a90e98)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/manage.c (ffffffff8110afe7)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/irq/affinity.c (ffffffff81115864)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/clocksource.c (ffffffff811309ea)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/time/tick-common.c (ffffffff8113b3f5)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffffffff8113b992)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_do_broadcast
```
```
In kernel/stop_machine.c (ffffffff81167fed)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace_hwlat.c (ffffffff811a8441)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811eb484)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/padata.c (ffffffff8120fb75)
Location: include/linux/cpumask.h:196
Inline: True
```
```
In block/blk-mq.c (ffffffff814d9de2)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
```
In block/blk-mq-cpumap.c (ffffffff814dc952)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In drivers/pci/msi.c (ffffffff81588e50)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_irq_get_node
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81890d31)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81897d9e)
Location: include/linux/cpumask.h:196
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
```
In arch/x86/power/cpu.c (ffffffff818d72e2)
Location: include/linux/cpumask.h:196
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
In arch/x86/events/intel/p4.c (ffffffff8101427c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044431)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810546cf)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b779)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e6df)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105ef61)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810610d5)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064171)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81068045)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c4c0)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108cabe)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810990c5)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
```
In kernel/cpu.c (ffffffff810a4006)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/reboot.c (ffffffff810ce4ba)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810dbbb0)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810e19f9)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/rt.c (ffffffff810ed607)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffff810f4fa3)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/cpupri.c (ffffffff810f615d)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/topology.c (ffffffff810f8e52)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/stats.c (ffffffff810faebb)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_start
```
```
In kernel/sched/debug.c (ffffffff810fb57b)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_start
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff811009b7)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
```
In kernel/power/poweroff.c (ffffffff811116f5)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/irq/irqdesc.c (ffffffff81ac81d8)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/manage.c (ffffffff81117547)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/irq/affinity.c (ffffffff81121cb6)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/clocksource.c (ffffffff8113c92a)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/time/tick-common.c (ffffffff81147005)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffffffff811475a2)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_do_broadcast
```
```
In kernel/stop_machine.c (ffffffff81173eae)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace_hwlat.c (ffffffff811b3c55)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811f7be4)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/padata.c (ffffffff8121d94c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In block/blk-mq.c (ffffffff814f317a)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
```
In block/blk-mq-cpumap.c (ffffffff814f5dee)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In drivers/pci/msi.c (ffffffff815aa7f0)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_irq_get_node
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818c2e11)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818c9bdf)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
```
In arch/x86/power/cpu.c (ffffffff81909662)
Location: include/linux/cpumask.h:212
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
In arch/x86/events/intel/p4.c (ffffffff8101589d)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_swap_config_ts
  - arch/x86/events/intel/p4.c:p4_pmu_swap_config_ts
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810481e1)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8105976f)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105bb6a)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060d83)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810641ef)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81064ac1)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81065be7)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106abdb)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8106f891)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81073750)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093ce6)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109e6d5)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
```
In kernel/cpu.c (ffffffff810ab241)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/reboot.c (ffffffff810d822d)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810e4a6e)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810eb5f5)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/rt.c (ffffffff810f7d91)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffff810fe6c3)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/topology.c (ffffffff81102bf3)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sd_init
  - kernel/sched/topology.c:init_sched_groups_capacity
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:update_top_cache_domain
  - kernel/sched/topology.c:build_perf_domains
  - kernel/sched/topology.c:build_perf_domains
```
```
In kernel/sched/stats.c (ffffffff81105486)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_next
```
```
In kernel/sched/debug.c (ffffffff81106496)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_next
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110aff9)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
```
```
In kernel/power/poweroff.c (ffffffff8111c7c5)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/power/energy_model.c (ffffffff8111ca05)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_create_pd
```
```
In kernel/irq/irqdesc.c (ffffffff81121a6d)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/irq/manage.c (ffffffff81122ae7)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/irq/affinity.c (ffffffff8112df87)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/time/clocksource.c (ffffffff8114b7ea)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/time/tick-common.c (ffffffff81156e85)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffffffff8115728a)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_do_broadcast
```
```
In kernel/stop_machine.c (ffffffff81185e97)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace_hwlat.c (ffffffff811cc3a2)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:start_kthread
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff8121ba1a)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/padata.c (ffffffff81249a5e)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
```
```
In block/blk-mq.c (ffffffff815537cb)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
```
In block/blk-mq-cpumap.c (ffffffff8155680e)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In drivers/cpufreq/cpufreq.c (ffffffff819951fd)
Location: include/linux/cpumask.h:217
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199b745)
Location: include/linux/cpumask.h:217
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/powernow-k8.c:fill_powernow_table
```
```
In arch/x86/power/cpu.c (ffffffff81bb9f74)
Location: include/linux/cpumask.h:217
Inline: True
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
In arch/x86/events/intel/p4.c (ffffffff81015d3d)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_swap_config_ts
  - arch/x86/events/intel/p4.c:p4_pmu_swap_config_ts
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81047691)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8105852f)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105a5ba)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105e630)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810625ef)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81062cc9)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81063e97)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106c8ab)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81070da1)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81074540)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093236)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109a2a5)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
```
In kernel/cpu.c (ffffffff810a6acd)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/reboot.c (ffffffff810d34ed)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810e2399)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810e93d0)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (ffffffff810fd013)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/topology.c (ffffffff81101813)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sd_init
  - kernel/sched/topology.c:init_sched_groups_capacity
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:update_top_cache_domain
  - kernel/sched/topology.c:build_perf_domains
  - kernel/sched/topology.c:build_perf_domains
```
```
In kernel/sched/stats.c (ffffffff81103af6)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_next
```
```
In kernel/sched/debug.c (ffffffff81104ae6)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_next
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81107f29)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
```
```
In kernel/power/poweroff.c (ffffffff81117125)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/irq/irqdesc.c (ffffffff8111dae0)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/irq/manage.c (ffffffff8111e917)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/irq/affinity.c (ffffffff81129b77)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/time/clocksource.c (ffffffff81147c4a)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/time/tick-common.c (ffffffff81152fa5)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffffffff8115335a)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_do_broadcast
```
```
In kernel/stop_machine.c (ffffffff81182ff7)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace_hwlat.c (ffffffff811c99fd)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:start_kthread
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff8121e99a)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/padata.c (ffffffff81253c35)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
```
```
In block/blk-mq.c (ffffffff8156fe88)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
```
In block/blk-mq-cpumap.c (ffffffff8157305e)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In lib/cpumask.c (ffffffff8160d27a)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_distribute
```
```
In drivers/cpufreq/cpufreq.c (ffffffff819998b8)
Location: include/linux/cpumask.h:222
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199e7e5)
Location: include/linux/cpumask.h:222
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/powernow-k8.c:fill_powernow_table
```
```
In arch/x86/power/cpu.c (ffffffff81bce7e4)
Location: include/linux/cpumask.h:222
Inline: True
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
In arch/x86/events/core.c (ffffffff810064f9)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
```
```
In arch/x86/events/intel/core.c (ffffffff8100dc53)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:hybrid_format_is_visible
  - arch/x86/events/intel/core.c:hybrid_tsx_is_visible
```
```
In arch/x86/events/intel/p4.c (ffffffff810170b9)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81049161)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81058e7f)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105af5a)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105f5d3)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81062d5e)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81063399)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81064537)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106d39c)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81070eb5)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81074ff0)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093c36)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109aa75)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
```
In kernel/cpu.c (ffffffff810a7bb2)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/reboot.c (ffffffff810d51dd)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810e41a9)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810eaff0)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/deadline.c (ffffffff810ff3b3)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/topology.c (ffffffff81103b90)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sd_init
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:update_top_cache_domain
  - kernel/sched/topology.c:build_perf_domains
  - kernel/sched/topology.c:build_perf_domains
```
```
In kernel/sched/stats.c (ffffffff81105d9f)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_start
```
```
In kernel/sched/debug.c (ffffffff8110648f)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_start
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110a069)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
```
```
In kernel/power/poweroff.c (ffffffff81117855)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/irq/irqdesc.c (ffffffff8111ddf0)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/irq/manage.c (ffffffff8111edb8)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/irq/affinity.c (ffffffff81129e0c)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/time/clocksource.c (ffffffff811493da)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/time/tick-common.c (ffffffff811543a5)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffffffff8115475a)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_do_broadcast
```
```
In kernel/stop_machine.c (ffffffff81183fff)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace_hwlat.c (ffffffff811caddf)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff8122229a)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/padata.c (ffffffff812582ce)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
```
```
In mm/percpu.c (ffffffff831f0370)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In block/blk-mq.c (ffffffff81577d31)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
```
In block/blk-mq-cpumap.c (ffffffff8157b093)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In lib/cpumask.c (ffffffff815f0728)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_distribute
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8197e3e8)
Location: include/linux/cpumask.h:193
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81983405)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/powernow-k8.c:fill_powernow_table
```
```
In arch/x86/power/cpu.c (ffffffff81bc2194)
Location: include/linux/cpumask.h:193
Inline: True
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
In arch/x86/events/core.c (ffffffff81006876)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
```
```
In arch/x86/events/intel/core.c (ffffffff8100e2c3)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:hybrid_format_is_visible
  - arch/x86/events/intel/core.c:hybrid_tsx_is_visible
```
```
In arch/x86/events/intel/p4.c (ffffffff81018d01)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8104fb21)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8106203f)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8106449b)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81069e23)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8106cbeb)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8106d330)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106e539)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
```
```
In arch/x86/kernel/smpboot.c (ffffffff81078636)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81079a48)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8107cb95)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810824a0)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810a3a16)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810aac85)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
```
In kernel/cpu.c (ffffffff810b9612)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/reboot.c (ffffffff810e83e0)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810faeb9)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff81102eed)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:find_idlest_group_cpu
```
```
In kernel/sched/deadline.c (ffffffff8111b397)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/topology.c (ffffffff81120bb9)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sd_init
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:update_top_cache_domain
  - kernel/sched/topology.c:build_perf_domains
  - kernel/sched/topology.c:build_perf_domains
```
```
In kernel/sched/stats.c (ffffffff81123c6f)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_start
```
```
In kernel/sched/debug.c (ffffffff8112413f)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_start
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81128607)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
```
```
In kernel/power/poweroff.c (ffffffff81137bb5)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/irq/irqdesc.c (ffffffff8113e229)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/irq/manage.c (ffffffff8113f388)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/irq/affinity.c (ffffffff8114a740)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/time/clocksource.c (ffffffff8116cd9a)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/time/tick-common.c (ffffffff81178ba5)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffffffff811791b6)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_do_broadcast
```
```
In kernel/stop_machine.c (ffffffff811ac3af)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace_hwlat.c (ffffffff811f6e22)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff81259eb4)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/padata.c (ffffffff81293e68)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
```
```
In mm/percpu.c (ffffffff832d5b83)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In block/blk-mq.c (ffffffff815dcac3)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
```
In block/blk-mq-cpumap.c (ffffffff815e03b0)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In lib/cpumask.c (ffffffff8165d808)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_distribute
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81a2752a)
Location: include/linux/cpumask.h:193
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81a2c9fa)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/powernow-k8.c:fill_powernow_table
```
```
In arch/x86/power/cpu.c (ffffffff81c927a4)
Location: include/linux/cpumask.h:193
Inline: True
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
In arch/x86/events/core.c (ffffffff81005cd9)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
```
```
In arch/x86/events/intel/core.c (ffffffff8100f413)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:hybrid_format_is_visible
  - arch/x86/events/intel/core.c:hybrid_tsx_is_visible
```
```
In arch/x86/events/intel/p4.c (ffffffff8101aed4)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8105b321)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8106ea6f)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81075504)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8107a0ab)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8107a873)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107bd99)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
```
```
In arch/x86/kernel/smpboot.c (ffffffff81087350)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81088862)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8108c1d5)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81092088)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810b80f5)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810c06f5)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
```
In kernel/cpu.c (ffffffff810d000d)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/reboot.c (ffffffff81102d29)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff811172d9)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff8111e2f0)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:find_idlest_group_cpu
```
```
In kernel/sched/build_policy.c (ffffffff8113afee)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/build_policy.c:dl_task_offline_migration
```
```
In kernel/sched/build_utility.c (ffffffff8114afa3)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:update_top_cache_domain
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:sched_debug_start
  - kernel/sched/build_utility.c:sugov_kthread_create
```
```
In kernel/power/poweroff.c (ffffffff8115a215)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/power/energy_model.c (ffffffff8115a997)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
```
In kernel/irq/irqdesc.c (ffffffff81161809)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/irq/manage.c (ffffffff81162e0f)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/irq/affinity.c (ffffffff8116fbc0)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/time/clocksource.c (ffffffff811a1143)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-common.c (ffffffff811ade1f)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffffffff811ae81f)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_do_broadcast
```
```
In kernel/stop_machine.c (ffffffff811dddd4)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace_hwlat.c (ffffffff81230683)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff812a2ef1)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/padata.c (ffffffff812e9e93)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
```
```
In mm/percpu.c (ffffffff8348a41c)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In block/blk-mq.c (ffffffff8168a704)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
```
In block/blk-mq-cpumap.c (ffffffff8168edda)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In lib/cpumask.c (ffffffff81776e13)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_distribute
```
```
In drivers/nvdimm/nd_perf.c (ffffffff819d927f)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b908b2)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81b9822c)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/powernow-k8.c:fill_powernow_table
```
```
In drivers/devfreq/governor_passive.c (ffffffff81bd653e)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:get_parent_cpu_data
```
```
In arch/x86/power/cpu.c (ffffffff81e41f5d)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:bsp_pm_callback
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
In arch/x86/events/core.c (ffffffff81007639)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
```
```
In arch/x86/events/intel/core.c (ffffffff81012dd3)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:hybrid_format_is_visible
  - arch/x86/events/intel/core.c:hybrid_tsx_is_visible
```
```
In arch/x86/events/intel/p4.c (ffffffff8101f054)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81068cd1)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8107ed5f)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81083386)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810861ce)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mba_sc_domain_allocate
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108b1b5)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8108bad0)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108e2d6)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109a9e8)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109c370)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810a0945)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810a7078)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d37e7)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810dc695)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
```
In kernel/cpu.c (ffffffff810ee670)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/reboot.c (ffffffff811281e9)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff8113e7e9)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff81147629)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:update_cpu_capacity
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_idlest_group_cpu
```
```
In kernel/sched/build_policy.c (ffffffff81165920)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/build_policy.c:dl_task_offline_migration
```
```
In kernel/sched/build_utility.c (ffffffff811799c3)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:update_top_cache_domain
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:sched_debug_start
  - kernel/sched/build_utility.c:sugov_kthread_create
```
```
In kernel/power/poweroff.c (ffffffff8118c515)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/power/energy_model.c (ffffffff8118cd89)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
```
In kernel/irq/irqdesc.c (ffffffff81194e99)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/irq/manage.c (ffffffff811969ef)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/irq/affinity.c (ffffffff811a5fee)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/time/clocksource.c (ffffffff811e0063)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-common.c (ffffffff811ee45f)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffffffff811ef15f)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_do_broadcast
```
```
In kernel/stop_machine.c (ffffffff812238b6)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace_hwlat.c (ffffffff8127ccf7)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff81300a1d)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/padata.c (ffffffff81353df3)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
```
```
In mm/percpu.c (ffffffff83ebaea5)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In block/blk-mq.c (ffffffff81748d06)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
```
In block/blk-mq-cpumap.c (ffffffff8174d893)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In drivers/char/random.c (ffffffff81a94efc)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81b542ef)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d30ad9)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81d39048)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/powernow-k8.c:fill_powernow_table
```
```
In drivers/devfreq/governor_passive.c (ffffffff81d82c8a)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:get_parent_cpu_data
```
```
In arch/x86/power/cpu.c (ffffffff8201c72d)
Location: include/linux/cpumask.h:127
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:bsp_pm_callback
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
In arch/x86/events/core.c (ffffffff81006e43)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
```
```
In arch/x86/events/intel/core.c (ffffffff810123a3)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:hybrid_format_is_visible
  - arch/x86/events/intel/core.c:hybrid_tsx_is_visible
```
```
In arch/x86/events/intel/p4.c (ffffffff8101ed43)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106a5e1)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81080edf)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81085836)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108ac50)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mba_sc_domain_allocate
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108e255)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8108e9fa)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81091186)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109ded8)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109f778)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810a3935)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810aa2d8)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d6bc7)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810e7c65)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
```
In kernel/cpu.c (ffffffff810fa650)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/reboot.c (ffffffff81135699)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff81151369)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff8115760e)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:find_idlest_group_cpu
```
```
In kernel/sched/build_policy.c (ffffffff811760e0)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/build_policy.c:dl_task_offline_migration
```
```
In kernel/sched/build_utility.c (ffffffff8118a4d3)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:update_top_cache_domain
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:sched_debug_start
  - kernel/sched/build_utility.c:sugov_kthread_create
```
```
In kernel/power/poweroff.c (ffffffff8119dc35)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/power/energy_model.c (ffffffff8119e52c)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
```
In kernel/irq/irqdesc.c (ffffffff811a66a9)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/irq/manage.c (ffffffff811a83af)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/time/clocksource.c (ffffffff811f452a)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-common.c (ffffffff81202b8f)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffffffff812036bf)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_do_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff8122d292)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
```
```
In kernel/stop_machine.c (ffffffff81239f46)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace_hwlat.c (ffffffff812949de)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff8132f57a)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/bpf/cpumask.c (ffffffff8135d6c5)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_first
```
```
In kernel/padata.c (ffffffff81384ff3)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
```
```
In mm/percpu.c (ffffffff836e34ca)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In block/blk-mq.c (ffffffff8178541b)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_delay_run_hw_queue
```
```
In lib/group_cpus.c (ffffffff818e6a29)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - lib/group_cpus.c:grp_spread_init_one
```
```
In drivers/char/random.c (ffffffff81ae071f)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b1af22)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81ba783f)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In drivers/net/virtio_net.c (ffffffff81c4ce02)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_affinity
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d99d59)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81da3ae8)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/powernow-k8.c:fill_powernow_table
```
```
In drivers/devfreq/governor_passive.c (ffffffff81df106a)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:get_parent_cpu_data
```
```
In arch/x86/power/cpu.c (ffffffff8209cdbd)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:bsp_pm_callback
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
In arch/x86/events/core.c (ffffffff8100c572)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
```
```
In arch/x86/events/intel/core.c (ffffffff81017cc3)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:hybrid_format_is_visible
  - arch/x86/events/intel/core.c:hybrid_tsx_is_visible
```
```
In arch/x86/events/intel/p4.c (ffffffff81024e03)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81071ab1)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810889ef)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108c88b)
Location: include/linux/cpumask.h:160
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8109246c)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mba_sc_domain_allocate
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810955e5)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81095d8a)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81098546)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a5503)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810a6c08)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810aa965)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810b1368)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810df3f7)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810efff5)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
```
In kernel/cpu.c (ffffffff81103a70)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/reboot.c (ffffffff811406f9)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff8115d1f9)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff81162a6d)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:find_idlest_group_cpu
```
```
In kernel/sched/build_policy.c (ffffffff8118436e)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/build_policy.c:dl_task_offline_migration
```
```
In kernel/sched/build_utility.c (ffffffff81198dd3)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:init_sched_groups_capacity
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:update_top_cache_domain
  - kernel/sched/build_utility.c:update_top_cache_domain
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:sugov_kthread_create
```
```
In kernel/power/poweroff.c (ffffffff811acda5)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/power/energy_model.c (ffffffff811ad6ec)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_dev_register_perf_domain
```
```
In kernel/irq/irqdesc.c (ffffffff811b61c9)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/irq/manage.c (ffffffff811b7e2f)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/time/hrtimer.c (ffffffff81205515)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_cpu_dying
```
```
In kernel/time/clocksource.c (ffffffff8120a66c)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-common.c (ffffffff8121914f)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffffffff81219c7f)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_do_broadcast
```
```
In kernel/cgroup/cpuset.c (ffffffff812454e2)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
```
```
In kernel/stop_machine.c (ffffffff81253c16)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace_hwlat.c (ffffffff812b003e)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/trace/trace_events_filter.c (ffffffff812c8348)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff81353a9a)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/bpf/cpumask.c (ffffffff81386465)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_first
```
```
In kernel/padata.c (ffffffff813ae362)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
```
```
In mm/percpu.c (ffffffff83915d5a)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In block/blk-mq.c (ffffffff817c7967)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_delay_run_hw_queue
```
```
In lib/group_cpus.c (ffffffff8192da49)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - lib/group_cpus.c:grp_spread_init_one
```
```
In drivers/char/random.c (ffffffff81b33b1f)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b70a52)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81bfbb1e)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In drivers/net/virtio_net.c (ffffffff81d026a2)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_affinity
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e519f2)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81e5bb78)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernow_k8_cpu_init_acpi
  - drivers/cpufreq/powernow-k8.c:fill_powernow_table
```
```
In drivers/devfreq/governor_passive.c (ffffffff81ea76b9)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:get_parent_cpu_data
```
```
In arch/x86/power/cpu.c (ffffffff821745bd)
Location: include/linux/cpumask.h:160
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:bsp_pm_callback
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
In kernel/cpu.c (ffff8000100f9bec)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/reboot.c (ffff80001012df40)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffff80001013b8f8)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffff800010141f48)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/rt.c (ffff80001014e2c0)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (ffff8000101577b0)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/cpupri.c (ffff800010159dfc)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/topology.c (ffff80001015d578)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/stats.c (ffff80001015f99c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_start
```
```
In kernel/sched/debug.c (ffff80001015fc1c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_start
```
```
In kernel/sched/cpufreq_schedutil.c (ffff800010165178)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
```
In kernel/power/poweroff.c (ffff800010171bc0)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/irq/irqdesc.c (ffff800010d9c05c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/manage.c (ffff80001017a330)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/irq/affinity.c (ffff800010187e5c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-common.c (ffff8000101b1ef8)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffff8000101b27c4)
Location: include/linux/cpumask.h:212
Inline: True
```
```
In kernel/stop_machine.c (ffff8000101e86a8)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace_hwlat.c (ffff800010231fd0)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/bpf/bpf_lru_list.c (ffff80001027cbf8)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
```
In kernel/padata.c (ffff8000102a909c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In block/blk-mq.c (ffff8000105f29e4)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
```
In block/blk-mq-cpumap.c (ffff8000105f6184)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In drivers/irqchip/irq-gic.c (ffff80001066c3fc)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_set_affinity
```
```
In drivers/irqchip/irq-gic-v3.c (ffff80001066f160)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_set_affinity
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010671bbc)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_activate
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_activate
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff800010677248)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_cpu_offline
```
```
In drivers/irqchip/irq-ls-scfg-msi.c (ffff80001067b660)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_set_affinity
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_compose_msg
```
```
In drivers/pci/msi.c (ffff800010713dc4)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_irq_get_node
```
```
In drivers/pci/controller/pci-xgene-msi.c (ffff800010725514)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_set_affinity
```
```
In drivers/pci/controller/pcie-iproc-msi.c (ffff800010725e04)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_irq_set_affinity
```
```
In drivers/soc/fsl/qbman/bman.c (ffff8000108121e4)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman.c:bman_create_portal
```
```
In drivers/soc/fsl/qbman/qman.c (ffff800010815c54)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
```
```
In drivers/opp/of.c (ffff800010b1b298)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/opp/of.c:dev_pm_opp_of_register_em
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b1f8ac)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In drivers/cpuidle/dt_idle_states.c (ffff800010b2a280)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
```
```
In drivers/perf/qcom_l3_pmu.c (ffff800010b9a0c8)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__event_init
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9af1c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/perf/xgene_pmu.c:xgene_perf_event_init
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
In arch/arm/kernel/smp.c (c031235c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:cpufreq_callback
```
```
In arch/arm/mm/cache-l2x0-pmu.c (c0324d64)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_event_init
```
```
In arch/arm/mach-imx/mmdc.c (c0333010)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_init
```
```
In kernel/cpu.c (c0357e2c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/reboot.c (c037dd78)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (c038b180)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (c0390dc0)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/rt.c (c039b5f0)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (c03a5578)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/cpupri.c (c03a6c74)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/topology.c (c03a9668)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/stats.c (c03ac1d8)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_start
```
```
In kernel/sched/debug.c (c03ac630)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_start
```
```
In kernel/sched/cpufreq_schedutil.c (c03b17b8)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
```
In kernel/power/poweroff.c (c03c4540)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/irq/irqdesc.c (c0e986c0)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/manage.c (c03cad9c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/irq/affinity.c (c03d68e4)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-common.c (c03fc694)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (c03fcb14)
Location: include/linux/cpumask.h:212
Inline: True
```
```
In kernel/stop_machine.c (c0428790)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace_hwlat.c (c046d5cc)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/bpf/bpf_lru_list.c (c04ae624)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/padata.c (c04d8490)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In block/blk-mq.c (c079eb0c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
```
In block/blk-mq-cpumap.c (c07a1a80)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In drivers/irqchip/irq-hip04.c (c0813fec)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/irqchip/irq-hip04.c:hip04_irq_set_affinity
```
```
In drivers/irqchip/irq-gic.c (c0815760)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_set_affinity
```
```
In drivers/irqchip/irq-gic-v3.c (c0817f1c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_set_affinity
```
```
In drivers/irqchip/irq-gic-v3-its.c (c081b128)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_activate
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_activate
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_set_vcpu_affinity
```
```
In drivers/pci/msi.c (c089e9d0)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_irq_get_node
```
```
In drivers/opp/of.c (c0bf5e34)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/opp/of.c:dev_pm_opp_of_register_em
```
```
In drivers/cpufreq/cpufreq.c (c0bf9f90)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In drivers/cpuidle/dt_idle_states.c (c0c05844)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
  - drivers/cpuidle/dt_idle_states.c:dt_init_idle_driver
```
```
In drivers/clocksource/dw_apb_timer.c (c0c48a3c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/clocksource/dw_apb_timer.c:apbt_resume
  - drivers/clocksource/dw_apb_timer.c:apbt_set_periodic
  - drivers/clocksource/dw_apb_timer.c:apbt_set_oneshot
  - drivers/clocksource/dw_apb_timer.c:apbt_shutdown
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
In arch/powerpc/kernel/irq.c (c00000000001c358)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/powerpc/kernel/irq.c:irq_choose_cpu
```
```
In arch/powerpc/kernel/setup-common.c (c00000000002fbb0)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup-common.c:c_start
```
```
In arch/powerpc/kernel/rtasd.c (c00000000134da6c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/powerpc/kernel/rtasd.c:rtas_event_scan_init
  - arch/powerpc/kernel/rtasd.c:rtas_event_scan
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000bce50)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_find_target_in_mask
  - arch/powerpc/sysdev/xive/common.c:xive_find_target_in_mask
  - arch/powerpc/sysdev/xive/common.c:xive_find_target_in_mask
```
```
In arch/powerpc/platforms/powernv/smp.c (c0000000000ce240)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/smp.c:pnv_smp_cpu_disable
```
```
In arch/powerpc/platforms/pseries/hotplug-cpu.c (c0000000000f9a80)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_cpu_disable
```
```
In kernel/cpu.c (c000000000140c20)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/reboot.c (c000000000176e80)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (c000000000189760)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (c000000000190610)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/rt.c (c0000000001a0fc0)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (c0000000001ac35c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/cpupri.c (c0000000001ae094)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/topology.c (c0000000001b21f4)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/stats.c (c0000000001b4fdc)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_start
```
```
In kernel/sched/debug.c (c0000000001b675c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_start
```
```
In kernel/sched/cpufreq_schedutil.c (c0000000001bc360)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
```
In kernel/power/poweroff.c (c0000000001ca3fc)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/irq/irqdesc.c (c0000000001d2058)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/manage.c (c0000000001d39c0)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/irq/affinity.c (c0000000001e1ba4)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-common.c (c000000000217210)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (c00000000021795c)
Location: include/linux/cpumask.h:212
Inline: True
```
```
In kernel/stop_machine.c (c0000000002590b0)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace_hwlat.c (c0000000002bc760)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/bpf/bpf_lru_list.c (c0000000003265cc)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/padata.c (c00000000035d4e0)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In block/blk-mq.c (c000000000789ea4)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
```
In block/blk-mq-cpumap.c (c00000000078e29c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In drivers/pci/msi.c (c000000000883700)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_irq_get_node
```
```
In drivers/opp/of.c (c000000000c0d7f4)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/opp/of.c:dev_pm_opp_of_register_em
```
```
In drivers/cpufreq/cpufreq.c (c000000000c12ad0)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In drivers/cpufreq/powernv-cpufreq.c (c000000000c1ce78)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/cpufreq/powernv-cpufreq.c:gpstate_timer_handler
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
In kernel/reboot.c (ffffffe0000e1fac)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffe0000ead2c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffe0000eecfa)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/rt.c (ffffffe0000f6f56)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffe0000fe538)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/cpupri.c (ffffffe0000ff906)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/topology.c (ffffffe000101d60)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/stats.c (ffffffe000103b3a)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_start
```
```
In kernel/sched/debug.c (ffffffe000104a66)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_start
```
```
In kernel/power/poweroff.c (ffffffe00010de90)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/irq/irqdesc.c (ffffffe0008c42c6)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/manage.c (ffffffe000113d26)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/irq/affinity.c (ffffffe00011d79e)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/stop_machine.c (ffffffe00015d6ba)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace_hwlat.c (ffffffe000189668)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/bpf/bpf_lru_list.c (ffffffe0001b4290)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/padata.c (ffffffe0001d25a4)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In block/blk-mq.c (ffffffe000431252)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
```
In block/blk-mq-cpumap.c (ffffffe000433c6c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In drivers/irqchip/irq-sifive-plic.c (ffffffe000495a96)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/irqchip/irq-sifive-plic.c:plic_set_affinity
```
```
In drivers/pci/msi.c (ffffffe0004dd8a0)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_irq_get_node
```
```
In drivers/opp/of.c (ffffffe00070385a)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/opp/of.c:dev_pm_opp_of_register_em
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
In arch/x86/events/intel/p4.c (ffffffff8101427c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810445b1)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8105424f)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b2f9)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e25f)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105eae1)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060c55)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
```
```
In arch/x86/kernel/smpboot.c (ffffffff81063c61)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81067b35)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106bfb0)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108ba7e)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff8109d926)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/reboot.c (ffffffff810c883a)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810d601a)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810dbba9)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/rt.c (ffffffff810e7607)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffff810ee3a3)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/cpupri.c (ffffffff810ef55d)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/topology.c (ffffffff810f2252)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/stats.c (ffffffff810f41eb)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_start
```
```
In kernel/sched/debug.c (ffffffff810f48ab)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_start
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f9cc7)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
```
In kernel/power/poweroff.c (ffffffff81109cd5)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/irq/irqdesc.c (ffffffff81a67048)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/manage.c (ffffffff8110fb27)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/irq/affinity.c (ffffffff8111a296)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/clocksource.c (ffffffff811350da)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/time/tick-common.c (ffffffff8113f7b5)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffffffff8113fbc2)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_do_broadcast
```
```
In kernel/stop_machine.c (ffffffff8116c4ce)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace_hwlat.c (ffffffff811ac275)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811f0204)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/padata.c (ffffffff81215f9c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In block/blk-mq.c (ffffffff814eb75a)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
```
In block/blk-mq-cpumap.c (ffffffff814ee3ce)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In drivers/pci/msi.c (ffffffff8159dfc0)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_irq_get_node
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81867531)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8186e2ff)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
```
In arch/x86/power/cpu.c (ffffffff818a8a22)
Location: include/linux/cpumask.h:212
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
In arch/x86/events/intel/p4.c (ffffffff8101352c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81033bd1)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8104431f)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104b469)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8104e58f)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8104ee11)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810510b5)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
```
```
In arch/x86/kernel/smpboot.c (ffffffff81053f71)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81057ea5)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105c2d0)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107a59e)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff8108c346)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/reboot.c (ffffffff810b705a)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810c46b0)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810cabb9)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/rt.c (ffffffff810d6907)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffff810de433)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/cpupri.c (ffffffff810df5cd)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/topology.c (ffffffff810e22c2)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/stats.c (ffffffff810e43cb)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_start
```
```
In kernel/sched/debug.c (ffffffff810e4a6b)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_start
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810e9ea7)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
```
In kernel/power/poweroff.c (ffffffff810fabb5)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/irq/irqdesc.c (ffffffff81a23b08)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/manage.c (ffffffff81100867)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/irq/affinity.c (ffffffff8110b306)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/clocksource.c (ffffffff81127b3a)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/time/tick-common.c (ffffffff811323a5)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffffffff81132942)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_do_broadcast
```
```
In kernel/stop_machine.c (ffffffff8115f6aa)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace_hwlat.c (ffffffff8119f151)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811e2f54)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/padata.c (ffffffff81208cfc)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In block/blk-mq.c (ffffffff814dbcaa)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
```
In block/blk-mq-cpumap.c (ffffffff814de91e)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In drivers/pci/msi.c (ffffffff8158d150)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_irq_get_node
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818301e1)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8183791f)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
```
In arch/x86/power/cpu.c (ffffffff818634b2)
Location: include/linux/cpumask.h:212
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
In arch/x86/events/intel/p4.c (ffffffff8101423c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810443f1)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8105467f)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b729)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e68f)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105ef11)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81061085)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064111)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81067fe5)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c460)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108ba2e)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff8109d8d6)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/reboot.c (ffffffff810c7d6a)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810d2e50)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810d7f29)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/rt.c (ffffffff810e3b37)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffff810eb4d3)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/cpupri.c (ffffffff810ec68d)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/topology.c (ffffffff810ef382)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/stats.c (ffffffff810f13eb)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_start
```
```
In kernel/sched/debug.c (ffffffff810f1aab)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_start
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f6ee7)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
```
In kernel/power/poweroff.c (ffffffff81107bc5)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/irq/irqdesc.c (ffffffff81ad3458)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/manage.c (ffffffff8110da17)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/irq/affinity.c (ffffffff81118186)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/clocksource.c (ffffffff81132dfa)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/time/tick-common.c (ffffffff8113d4d5)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffffffff8113da72)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_do_broadcast
```
```
In kernel/stop_machine.c (ffffffff8116a29e)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace_hwlat.c (ffffffff811aa045)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811edfd4)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/padata.c (ffffffff81213d3c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In block/blk-mq.c (ffffffff814e77ea)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
```
In block/blk-mq-cpumap.c (ffffffff814ea45e)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In drivers/pci/msi.c (ffffffff8159e540)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_irq_get_node
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818b82c1)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818bf08f)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
```
In arch/x86/power/cpu.c (ffffffff818fa082)
Location: include/linux/cpumask.h:212
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
In arch/x86/events/intel/p4.c (ffffffff8101447c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810457f1)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_store
  - arch/x86/kernel/cpu/cacheinfo.c:subcaches_show
  - arch/x86/kernel/cpu/cacheinfo.c:store_cache_disable
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81055aff)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_save_state
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105cbd9)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105fbcf)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81060451)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81062645)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger
```
```
In arch/x86/kernel/smpboot.c (ffffffff810656d1)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810696b5)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:vector_assign_managed_shutdown
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106db60)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108dd8e)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109a595)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_shutdown
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
```
In kernel/cpu.c (ffffffff810a5766)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_report_idle_dead
```
```
In kernel/reboot.c (ffffffff810d025a)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/reboot.c:migrate_to_reboot_cpu
```
```
In kernel/sched/core.c (ffffffff810dd921)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
```
```
In kernel/sched/fair.c (ffffffff810e39c9)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/rt.c (ffffffff810ef5fc)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffff810f64fa)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/cpupri.c (ffffffff810f76cd)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/topology.c (ffffffff810fa3cc)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/stats.c (ffffffff810fc3db)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_start
```
```
In kernel/sched/debug.c (ffffffff810fca9b)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_start
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81101f67)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
```
In kernel/power/poweroff.c (ffffffff81112f75)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/power/poweroff.c:handle_poweroff
```
```
In kernel/irq/irqdesc.c (ffffffff81adf958)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
```
In kernel/irq/manage.c (ffffffff811191d7)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/irq/affinity.c (ffffffff81123816)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/clocksource.c (ffffffff8113f81c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_select_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/time/tick-common.c (ffffffff81149fc5)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_handover_do_timer
```
```
In kernel/time/tick-broadcast.c (ffffffff8114a582)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_do_broadcast
```
```
In kernel/stop_machine.c (ffffffff811779ee)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
```
```
In kernel/trace/trace_hwlat.c (ffffffff811b7e85)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811fc4a2)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
```
In kernel/padata.c (ffffffff81222f7c)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In block/blk-mq.c (ffffffff8150078a)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
```
In block/blk-mq-cpumap.c (ffffffff8150342e)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In drivers/pci/msi.c (ffffffff815b8970)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_irq_get_node
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818d4581)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818db39f)
Location: include/linux/cpumask.h:212
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/powernow-k8.c:find_psb_table
```
```
In arch/x86/power/cpu.c (ffffffff8191b1e2)
Location: include/linux/cpumask.h:212
Inline: True
```
</details>
</li>
</ul>

## Differences
