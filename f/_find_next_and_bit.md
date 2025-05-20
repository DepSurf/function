# Function: <code>_find_next_and_bit</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int _find_next_and_bit(const long unsigned int *addr1, const long unsigned int *addr2, long unsigned int nbits, long unsigned int start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff817d6f50)
Location: lib/find_bit.c:159
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
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
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
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
  - drivers/xen/events/events_base.c:select_target_cpu
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
  - drivers/powercap/idle_inject.c:idle_inject_wakeup
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/net-sysfs.c:store_rps_map
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
  - lib/cpumask.c:cpumask_any_and_distribute
```
**Symbols:**

```
ffffffff817d6f50-ffffffff817d6fd7: _find_next_and_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int _find_next_and_bit(const long unsigned int *addr1, const long unsigned int *addr2, long unsigned int nbits, long unsigned int start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81815f80)
Location: lib/find_bit.c:168
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/kernel/smpboot.c:smp_park_other_cpus_in_init
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/workqueue.c:wq_select_unbound_cpu
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
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
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_delay_run_hw_queue
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/xen/events/events_base.c:select_target_cpu
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
  - drivers/powercap/idle_inject.c:idle_inject_wakeup
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/net-sysfs.c:netdev_rx_queue_set_rps_mask
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
  - lib/cpumask.c:cpumask_any_and_distribute
```
**Symbols:**

```
ffffffff81815f80-ffffffff81816004: _find_next_and_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int _find_next_and_bit(const long unsigned int *addr1, const long unsigned int *addr2, long unsigned int nbits, long unsigned int start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8185b0c0)
Location: lib/find_bit.c:168
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - kernel/cpu.c:cpu_down_maps_locked
  - kernel/workqueue.c:wq_select_unbound_cpu
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:should_we_balance
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
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
  - kernel/time/tick-sched.c:tick_nohz_dep_set
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_delay_run_hw_queue
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/pmdomain/governor.c:cpu_power_down_ok
  - drivers/xen/events/events_base.c:select_target_cpu
  - drivers/powercap/idle_inject.c:idle_inject_wakeup
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/net-sysfs.c:netdev_rx_queue_set_rps_mask
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
  - lib/cpumask.c:cpumask_any_and_distribute
```
**Symbols:**

```
ffffffff8185b0c0-ffffffff8185b144: _find_next_and_bit (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
