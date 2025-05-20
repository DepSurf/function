# Function: <code>cpumask_next_and</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cpumask_next_and(int n, const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff813e91a0)
Location: lib/cpumask.c:16
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/apic/apic.c:default_cpu_mask_to_apicid_and
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cpu_mask_to_apicid_and
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cpu_mask_to_apicid_and
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/watchdog.c:watchdog_park_threads
  - kernel/watchdog.c:watchdog_unpark_threads
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
  - lib/cpumask.c:cpumask_local_spread
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff813e91a0-ffffffff813e91e0: cpumask_next_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cpumask_next_and(int n, const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8142f3b0)
Location: lib/cpumask.c:16
Inline: False
Direct callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_cpu_starting
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/apic/apic.c:default_cpu_mask_to_apicid_and
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cpu_mask_to_apicid_and
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cpu_mask_to_apicid_and
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/watchdog.c:watchdog_unpark_threads
  - kernel/watchdog.c:watchdog_park_threads
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
  - lib/cpumask.c:cpumask_local_spread
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff8142f3b0-ffffffff8142f3ec: cpumask_next_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cpumask_next_and(int n, const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8144b520)
Location: lib/cpumask.c:16
Inline: False
Direct callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_cpu_starting
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/apic/apic.c:default_cpu_mask_to_apicid_and
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cpu_mask_to_apicid_and
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cpu_mask_to_apicid_and
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/watchdog.c:watchdog_unpark_threads
  - kernel/watchdog.c:watchdog_park_threads
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
  - mm/vmscan.c:kswapd_cpu_online
  - mm/compaction.c:kcompactd_cpu_online
  - lib/cpumask.c:cpumask_local_spread
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff8144b520-ffffffff8144b561: cpumask_next_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cpumask_next_and(int n, const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff818ebb70)
Location: lib/cpumask.c:16
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/kernel/apic/vector.c:apic_retrigger_irq
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/watchdog.c:watchdog_unpark_threads
  - kernel/watchdog.c:watchdog_park_threads
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
  - mm/vmscan.c:kswapd_cpu_online
  - mm/compaction.c:kcompactd_cpu_online
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:store_rps_map
  - lib/cpumask.c:cpumask_local_spread
```
**Symbols:**

```
ffffffff818ebb70-ffffffff818ebbaf: cpumask_next_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cpumask_next_and(int n, const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81971b50)
Location: lib/cpumask.c:33
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - mm/vmscan.c:kswapd_cpu_online
  - mm/compaction.c:kcompactd_cpu_online
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:store_rps_map
  - lib/cpumask.c:cpumask_local_spread
```
**Symbols:**

```
ffffffff81971b50-ffffffff81971b8f: cpumask_next_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int cpumask_next_and(int n, const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff819ce101)
Location: lib/cpumask.c:33
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - mm/vmscan.c:kswapd_cpu_online
  - mm/compaction.c:kcompactd_cpu_online
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff819cdff0-ffffffff819ce010: cpumask_next_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int cpumask_next_and(int n, const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a075c1)
Location: lib/cpumask.c:33
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - mm/vmscan.c:kswapd_cpu_online
  - mm/compaction.c:kcompactd_cpu_online
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/powercap/idle_inject.c:idle_inject_wakeup
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff81a074b0-ffffffff81a074d0: cpumask_next_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int cpumask_next_and(int n, const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a76f20)
Location: lib/cpumask.c:34
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - mm/vmscan.c:kswapd_cpu_online
  - mm/compaction.c:kcompactd_cpu_online
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/powercap/idle_inject.c:idle_inject_wakeup
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff81a76e10-ffffffff81a76e30: cpumask_next_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int cpumask_next_and(int n, const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81aae278)
Location: lib/cpumask.c:34
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/topology.c:sched_numa_find_closest
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - mm/vmscan.c:kswapd_cpu_online
  - mm/compaction.c:kcompactd_cpu_online
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/powercap/idle_inject.c:idle_inject_wakeup
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff81aae220-ffffffff81aae240: cpumask_next_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int cpumask_next_and(int n, const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff815e7f0e)
Location: lib/cpumask.c:34
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_and_distribute
  - lib/cpumask.c:cpumask_any_and_distribute
  - lib/cpumask.c:cpumask_local_spread
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:wq_select_unbound_cpu
  - kernel/workqueue.c:wq_select_unbound_cpu
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/cpupri.c:cpupri_find_fitness
  - kernel/sched/topology.c:sched_numa_find_closest
  - kernel/sched/topology.c:init_overlap_sched_group
  - kernel/irq/chip.c:__irq_startup_managed
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - mm/compaction.c:kcompactd_cpu_online
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff815e7ee0-ffffffff815e7f00: cpumask_next_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int cpumask_next_and(int n, const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8160d081)
Location: lib/cpumask.c:34
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_and_distribute
  - lib/cpumask.c:cpumask_any_and_distribute
  - lib/cpumask.c:cpumask_local_spread
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:wq_select_unbound_cpu
  - kernel/workqueue.c:wq_select_unbound_cpu
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/cpupri.c:cpupri_find_fitness
  - kernel/sched/topology.c:sched_numa_find_closest
  - kernel/sched/topology.c:init_overlap_sched_group
  - kernel/irq/chip.c:__irq_startup_managed
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - mm/compaction.c:kcompactd_cpu_online
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff8160d040-ffffffff8160d060: cpumask_next_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int cpumask_next_and(int n, const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff815f0877)
Location: lib/cpumask.c:34
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_and_distribute
  - lib/cpumask.c:cpumask_any_and_distribute
  - lib/cpumask.c:cpumask_local_spread
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/cpupri.c:cpupri_find_fitness
  - kernel/sched/topology.c:sched_numa_find_closest
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - mm/compaction.c:kcompactd_cpu_online
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff815f0820-ffffffff815f0846: cpumask_next_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int cpumask_next_and(int n, const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8165d957)
Location: lib/cpumask.c:34
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_and_distribute
  - lib/cpumask.c:cpumask_any_and_distribute
  - lib/cpumask.c:cpumask_local_spread
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/cpupri.c:cpupri_find_fitness
  - kernel/sched/topology.c:sched_numa_find_closest
  - kernel/sched/topology.c:asym_cpu_capacity_scan
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/irq/cpuhotplug.c:migrate_one_irq
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - mm/compaction.c:kcompactd_cpu_online
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff8165d900-ffffffff8165d926: cpumask_next_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int cpumask_next_and(int n, const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81776d56)
Location: lib/cpumask.c:34
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_and_distribute
  - lib/cpumask.c:cpumask_local_spread
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/workqueue.c:wq_select_unbound_cpu
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:dl_add_task_root_domain
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff81776ee0-ffffffff81776f18: cpumask_next_and (STB_GLOBAL)
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
In kernel/workqueue.c (ffffffff811122b2)
Location: include/linux/cpumask.h:231
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_select_unbound_cpu
```
```
In kernel/smp.c (ffffffff811f938f)
Location: include/linux/cpumask.h:231
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
```
```
In block/blk-mq.c (ffffffff817422ea)
Location: include/linux/cpumask.h:231
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
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
In kernel/workqueue.c (ffffffff8111e732)
Location: include/linux/cpumask.h:264
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_select_unbound_cpu
```
```
In kernel/smp.c (ffffffff8120e0ae)
Location: include/linux/cpumask.h:264
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
```
```
In block/blk-mq.c (ffffffff8177f33a)
Location: include/linux/cpumask.h:264
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_delay_run_hw_queue
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
In kernel/workqueue.c (ffffffff81127414)
Location: include/linux/cpumask.h:264
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_select_unbound_cpu
```
```
In kernel/smp.c (ffffffff8122583e)
Location: include/linux/cpumask.h:264
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
```
```
In block/blk-mq.c (ffffffff817c1e2a)
Location: include/linux/cpumask.h:264
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_delay_run_hw_queue
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int cpumask_next_and(int n, const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffff800010d84624)
Location: lib/cpumask.c:34
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
Direct callers:
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_numa_find_closest
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - mm/vmscan.c:kswapd_cpu_online
  - mm/compaction.c:kcompactd_cpu_online
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - drivers/irqchip/irq-gic.c:gic_set_affinity
  - drivers/irqchip/irq-gic-v3.c:gic_set_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_activate
  - drivers/irqchip/irq-gic-v3-its.c:its_set_affinity
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_set_affinity
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_set_affinity
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/powercap/idle_inject.c:idle_inject_wakeup
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffff800010d84590-ffff800010d845bc: cpumask_next_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int cpumask_next_and(int n, const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (c0e7fb08)
Location: lib/cpumask.c:34
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
Direct callers:
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - mm/vmscan.c:kswapd_cpu_online
  - mm/compaction.c:kcompactd_cpu_online
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - drivers/irqchip/irq-hip04.c:hip04_irq_set_affinity
  - drivers/irqchip/irq-gic.c:gic_set_affinity
  - drivers/irqchip/irq-gic-v3.c:gic_set_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_activate
  - drivers/irqchip/irq-gic-v3-its.c:its_set_affinity
  - drivers/irqchip/irq-armada-370-xp.c:armada_xp_set_affinity
  - drivers/powercap/idle_inject.c:idle_inject_wakeup
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
c0e7fa88-c0e7fab0: cpumask_next_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int cpumask_next_and(int n, const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (c000000000ec38c0)
Location: lib/cpumask.c:34
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
Direct callers:
  - arch/powerpc/kernel/irq.c:irq_choose_cpu
  - arch/powerpc/kernel/watchdog.c:watchdog_nmi_start
  - arch/powerpc/sysdev/xics/xics-common.c:xics_get_irq_server
  - arch/powerpc/sysdev/xive/common.c:xive_irq_set_affinity
  - arch/powerpc/sysdev/xive/common.c:xive_pick_irq_target
  - arch/powerpc/sysdev/xive/common.c:xive_pick_irq_target
  - arch/powerpc/platforms/powernv/opal-imc.c:disable_nest_pmu_counters
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/topology.c:sched_numa_find_closest
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd_cpu_online
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd_cpu_online
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/powercap/idle_inject.c:idle_inject_wakeup
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
c000000000ec37f0-c000000000ec3838: cpumask_next_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int cpumask_next_and(int n, const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffe0008aeae2)
Location: lib/cpumask.c:34
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
Direct callers:
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/chip.c:irq_startup
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - mm/vmscan.c:kswapd_cpu_online
  - mm/compaction.c:kcompactd_cpu_online
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - drivers/irqchip/irq-sifive-plic.c:plic_set_affinity
  - drivers/irqchip/irq-sifive-plic.c:plic_irq_unmask
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffe0008aea90-ffffffe0008aeab6: cpumask_next_and (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int cpumask_next_and(int n, const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a4d0c8)
Location: lib/cpumask.c:34
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/topology.c:sched_numa_find_closest
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - mm/vmscan.c:kswapd_cpu_online
  - mm/compaction.c:kcompactd_cpu_online
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/xen/events/events_base.c:set_affinity_irq
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff81a4d070-ffffffff81a4d090: cpumask_next_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int cpumask_next_and(int n, const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a0a1f8)
Location: lib/cpumask.c:34
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/topology.c:sched_numa_find_closest
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/time/tick-sched.c:tick_nohz_dep_set_all
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - mm/vmscan.c:kswapd_cpu_online
  - mm/compaction.c:kcompactd_cpu_online
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff81a0a1a0-ffffffff81a0a1c0: cpumask_next_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int cpumask_next_and(int n, const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81ab94b8)
Location: lib/cpumask.c:34
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/topology.c:sched_numa_find_closest
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - mm/vmscan.c:kswapd_cpu_online
  - mm/compaction.c:kcompactd_cpu_online
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/powercap/idle_inject.c:idle_inject_wakeup
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff81ab9460-ffffffff81ab9480: cpumask_next_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int cpumask_next_and(int n, const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81ac5908)
Location: lib/cpumask.c:34
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/topology.c:sched_numa_find_closest
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/migration.c:irq_fixup_move_pending
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_any
  - mm/vmscan.c:kswapd_cpu_online
  - mm/compaction.c:kcompactd_cpu_online
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/powercap/idle_inject.c:idle_inject_wakeup
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff81ac58b0-ffffffff81ac58d0: cpumask_next_and (STB_GLOBAL)
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
