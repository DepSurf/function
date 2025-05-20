# Function: <code>find_next_and_bit</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int find_next_and_bit(const long unsigned int *addr1, const long unsigned int *addr2, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff814ca390)
Location: lib/find_bit.c:89
Inline: False
Direct callers:
  - lib/cpumask.c:cpumask_local_spread
```
**Symbols:**

```
ffffffff814ca390-ffffffff814ca403: find_next_and_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int find_next_and_bit(const long unsigned int *addr1, const long unsigned int *addr2, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff814df0b0)
Location: lib/find_bit.c:89
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
  - lib/cpumask.c:cpumask_local_spread
```
**Symbols:**

```
ffffffff814df0b0-ffffffff814df123: find_next_and_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int find_next_and_bit(const long unsigned int *addr1, const long unsigned int *addr2, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8150afe0)
Location: lib/find_bit.c:85
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
  - lib/cpumask.c:cpumask_local_spread
```
**Symbols:**

```
ffffffff8150afe0-ffffffff8150b04d: find_next_and_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int find_next_and_bit(const long unsigned int *addr1, const long unsigned int *addr2, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81528e00)
Location: lib/find_bit.c:85
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
  - lib/cpumask.c:cpumask_local_spread
```
**Symbols:**

```
ffffffff81528e00-ffffffff81528e6d: find_next_and_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int find_next_and_bit(const long unsigned int *addr1, const long unsigned int *addr2, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8158c7a0)
Location: lib/find_bit.c:93
Inline: False
Direct callers:
  - lib/cpumask.c:cpumask_any_and_distribute
  - lib/cpumask.c:cpumask_any_and_distribute
  - lib/cpumask.c:cpumask_local_spread
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff8158c7a0-ffffffff8158c7ae: find_next_and_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int find_next_and_bit(const long unsigned int *addr1, const long unsigned int *addr2, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff815a9210)
Location: lib/find_bit.c:95
Inline: False
Direct callers:
  - lib/cpumask.c:cpumask_any_and_distribute
  - lib/cpumask.c:cpumask_any_and_distribute
  - lib/cpumask.c:cpumask_local_spread
  - net/core/dev.c:__netif_set_xps_queue
```
**Symbols:**

```
ffffffff815a9210-ffffffff815a921e: find_next_and_bit (STB_GLOBAL)
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
In lib/cpumask.c (ffffffff815f0877)
Location: include/asm-generic/bitops/find.h:52
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_and_distribute
  - lib/cpumask.c:cpumask_any_and_distribute
  - lib/cpumask.c:cpumask_local_spread
```
```
In net/core/dev.c (ffffffff819ead7c)
Location: include/asm-generic/bitops/find.h:52
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
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
In lib/cpumask.c (ffffffff8165d957)
Location: include/asm-generic/bitops/find.h:52
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_and_distribute
  - lib/cpumask.c:cpumask_any_and_distribute
  - lib/cpumask.c:cpumask_local_spread
```
```
In net/core/dev.c (ffffffff81a9bc9d)
Location: include/asm-generic/bitops/find.h:52
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
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
In lib/cpumask.c (ffffffff81776d56)
Location: include/linux/find.h:60
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_and_distribute
  - lib/cpumask.c:cpumask_local_spread
```
```
In net/core/dev.c (ffffffff81c13306)
Location: include/linux/find.h:60
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2f817)
Location: include/linux/find.h:60
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
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
In arch/x86/xen/smp.c (ffffffff81043612)
Location: include/linux/find.h:78
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a97e8)
Location: include/linux/find.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In kernel/workqueue.c (ffffffff811122b2)
Location: include/linux/find.h:78
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_select_unbound_cpu
```
```
In kernel/sched/core.c (ffffffff8113a46d)
Location: include/linux/find.h:78
Inline: True
Inline callers:
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/fair.c (ffffffff811563b6)
Location: include/linux/find.h:78
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:find_idlest_group_cpu
```
```
In kernel/sched/build_policy.c (ffffffff81165b51)
Location: include/linux/find.h:78
Inline: True
Inline callers:
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
```
```
In kernel/sched/build_utility.c (ffffffff8116f738)
Location: include/linux/find.h:78
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
```
```
In kernel/smp.c (ffffffff811f938f)
Location: include/linux/find.h:78
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
```
```
In kernel/trace/ring_buffer.c (ffffffff81262a84)
Location: include/linux/find.h:78
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
```
```
In block/blk-mq.c (ffffffff817422ea)
Location: include/linux/find.h:78
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
```
In drivers/acpi/processor_throttling.c (ffffffff819d69ea)
Location: include/linux/find.h:78
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
```
```
In drivers/xen/events/events_base.c (ffffffff81a1d78d)
Location: include/linux/find.h:78
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:select_target_cpu
```
```
In drivers/base/power/domain_governor.c (ffffffff81b0ebde)
Location: include/linux/find.h:78
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
```
```
In drivers/powercap/idle_inject.c (ffffffff81d87b57)
Location: include/linux/find.h:78
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_wakeup
```
```
In net/core/dev.c (ffffffff81dc5191)
Location: include/linux/find.h:78
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/net-sysfs.c (ffffffff81e0c027)
Location: include/linux/find.h:78
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/mptcp/pm_netlink.c (ffffffff82007f87)
Location: include/linux/find.h:78
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
```
```
In lib/cpumask.c (ffffffff8201f7da)
Location: include/linux/find.h:78
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_and_distribute
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
In arch/x86/xen/smp.c (ffffffff8104383b)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109ebd8)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:smp_park_other_cpus_in_init
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810aca03)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In kernel/workqueue.c (ffffffff8111e732)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_select_unbound_cpu
```
```
In kernel/sched/core.c (ffffffff8114979d)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/fair.c (ffffffff811665a1)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:find_idlest_group_cpu
```
```
In kernel/sched/build_policy.c (ffffffff8116d17e)
Location: include/linux/find.h:83
Inline: True
Inline callers:
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
```
```
In kernel/sched/build_utility.c (ffffffff8117f598)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
```
```
In kernel/smp.c (ffffffff8120e0ae)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
```
```
In kernel/trace/ring_buffer.c (ffffffff81279a68)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
```
```
In block/blk-mq.c (ffffffff8177f33a)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_delay_run_hw_queue
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a1e3aa)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
```
```
In drivers/xen/events/events_base.c (ffffffff81a6699d)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:select_target_cpu
```
```
In drivers/base/power/domain_governor.c (ffffffff81b5cc8e)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
```
```
In drivers/powercap/idle_inject.c (ffffffff81df60a7)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_wakeup
```
```
In net/core/dev.c (ffffffff81e33c82)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/net-sysfs.c (ffffffff81e7ec7f)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_rx_queue_set_rps_mask
```
```
In net/mptcp/pm_netlink.c (ffffffff82084387)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
```
```
In lib/cpumask.c (ffffffff8209f7ea)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_and_distribute
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
In arch/x86/xen/smp.c (ffffffff81049d3b)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b3683)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In kernel/cpu.c (ffffffff81100fad)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_down_maps_locked
```
```
In kernel/workqueue.c (ffffffff81127414)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_select_unbound_cpu
```
```
In kernel/sched/core.c (ffffffff8115519d)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/fair.c (ffffffff811732f4)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:should_we_balance
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:find_idlest_group_cpu
```
```
In kernel/sched/build_policy.c (ffffffff81179b82)
Location: include/linux/find.h:83
Inline: True
Inline callers:
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
```
```
In kernel/sched/build_utility.c (ffffffff8118ce98)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
```
```
In kernel/time/tick-sched.c (ffffffff8121c840)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_dep_set
```
```
In kernel/smp.c (ffffffff8122583e)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
```
```
In kernel/trace/ring_buffer.c (ffffffff81294548)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
```
```
In block/blk-mq.c (ffffffff817c1e2a)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:blk_mq_delay_run_hw_queue
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a696ba)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
```
```
In drivers/pmdomain/governor.c (ffffffff81aa478e)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - drivers/pmdomain/governor.c:cpu_power_down_ok
```
```
In drivers/xen/events/events_base.c (ffffffff81ab95ed)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:select_target_cpu
```
```
In drivers/powercap/idle_inject.c (ffffffff81eac797)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_wakeup
```
```
In net/core/dev.c (ffffffff81ef27c0)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/net-sysfs.c (ffffffff81f3fb8f)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_rx_queue_set_rps_mask
```
```
In net/mptcp/pm_netlink.c (ffffffff82159ae7)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
```
```
In lib/cpumask.c (ffffffff8217784a)
Location: include/linux/find.h:83
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_and_distribute
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
long unsigned int find_next_and_bit(const long unsigned int *addr1, const long unsigned int *addr2, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffff800010633700)
Location: lib/find_bit.c:85
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
  - lib/cpumask.c:cpumask_local_spread
```
**Symbols:**

```
ffff800010633700-ffff800010633770: find_next_and_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int find_next_and_bit(const long unsigned int *addr1, const long unsigned int *addr2, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (c07d9b94)
Location: lib/find_bit.c:85
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
  - lib/cpumask.c:cpumask_local_spread
```
**Symbols:**

```
c07d9b94-c07d9c20: find_next_and_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int find_next_and_bit(const long unsigned int *addr1, const long unsigned int *addr2, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (c0000000007d8a40)
Location: lib/find_bit.c:85
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
  - lib/cpumask.c:cpumask_local_spread
```
**Symbols:**

```
c0000000007d8a40-c0000000007d8ae4: find_next_and_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int find_next_and_bit(const long unsigned int *addr1, const long unsigned int *addr2, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffe0004616d2)
Location: lib/find_bit.c:85
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
  - lib/cpumask.c:cpumask_local_spread
```
**Symbols:**

```
ffffffe0004616d2-ffffffe000461772: find_next_and_bit (STB_GLOBAL)
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
long unsigned int find_next_and_bit(const long unsigned int *addr1, const long unsigned int *addr2, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff815213e0)
Location: lib/find_bit.c:85
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
  - lib/cpumask.c:cpumask_local_spread
```
**Symbols:**

```
ffffffff815213e0-ffffffff8152144d: find_next_and_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int find_next_and_bit(const long unsigned int *addr1, const long unsigned int *addr2, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff815116d0)
Location: lib/find_bit.c:85
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
  - lib/cpumask.c:cpumask_local_spread
```
**Symbols:**

```
ffffffff815116d0-ffffffff8151173d: find_next_and_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int find_next_and_bit(const long unsigned int *addr1, const long unsigned int *addr2, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8151d470)
Location: lib/find_bit.c:85
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
  - lib/cpumask.c:cpumask_local_spread
```
**Symbols:**

```
ffffffff8151d470-ffffffff8151d4dd: find_next_and_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int find_next_and_bit(const long unsigned int *addr1, const long unsigned int *addr2, long unsigned int size, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81536ce0)
Location: lib/find_bit.c:85
Inline: False
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
  - lib/cpumask.c:cpumask_local_spread
```
**Symbols:**

```
ffffffff81536ce0-ffffffff81536d4d: find_next_and_bit (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
