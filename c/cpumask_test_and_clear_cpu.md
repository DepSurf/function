# Function: <code>cpumask_test_and_clear_cpu</code>

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
In arch/x86/events/intel/cqm.c (ffffffff8100eced)
Location: include/linux/cpumask.h:320
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_cpu_notifier
```
```
In arch/x86/events/intel/cstate.c (ffffffff8100f2c2)
Location: include/linux/cpumask.h:320
Inline: True
Inline callers:
  - arch/x86/events/intel/cstate.c:cstate_cpu_notifier
  - arch/x86/events/intel/cstate.c:cstate_cpu_notifier
```
```
In arch/x86/events/intel/rapl.c (ffffffff81014f75)
Location: include/linux/cpumask.h:320
Inline: True
Inline callers:
  - arch/x86/events/intel/rapl.c:rapl_cpu_notifier
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015f06)
Location: include/linux/cpumask.h:320
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_cpu_notifier
```
```
In kernel/time/tick-broadcast.c (ffffffff810fd5db)
Location: include/linux/cpumask.h:320
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In mm/vmstat.c (ffffffff811ad16c)
Location: include/linux/cpumask.h:320
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_shepherd
```
```
In net/core/flow.c (ffffffff817352b9)
Location: include/linux/cpumask.h:320
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
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
In arch/x86/events/intel/cqm.c (ffffffff8100e1d5)
Location: include/linux/cpumask.h:324
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015355)
Location: include/linux/cpumask.h:324
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In kernel/time/tick-broadcast.c (ffffffff8110494c)
Location: include/linux/cpumask.h:324
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In net/core/flow.c (ffffffff817a1440)
Location: include/linux/cpumask.h:324
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
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
In arch/x86/events/intel/cqm.c (ffffffff8100e295)
Location: include/linux/cpumask.h:324
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015450)
Location: include/linux/cpumask.h:324
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81043092)
Location: include/linux/cpumask.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
```
In kernel/irq/affinity.c (ffffffff810efcff)
Location: include/linux/cpumask.h:324
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff8110c08b)
Location: include/linux/cpumask.h:324
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/base/cacheinfo.c (ffffffff815d2b2f)
Location: include/linux/cpumask.h:324
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In net/core/flow.c (ffffffff817cfd5a)
Location: include/linux/cpumask.h:324
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
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
In arch/x86/events/intel/uncore.c (ffffffff81013970)
Location: include/linux/cpumask.h:352
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff8104135d)
Location: include/linux/cpumask.h:352
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
```
In kernel/irq/affinity.c (ffffffff810efcd6)
Location: include/linux/cpumask.h:352
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff8110e43b)
Location: include/linux/cpumask.h:352
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/base/cacheinfo.c (ffffffff815e76a1)
Location: include/linux/cpumask.h:352
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In net/core/flow.c (ffffffff817ef158)
Location: include/linux/cpumask.h:352
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
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
In arch/x86/events/intel/uncore.c (ffffffff810141b0)
Location: include/linux/cpumask.h:356
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff8104474d)
Location: include/linux/cpumask.h:356
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
```
In kernel/irq/affinity.c (ffffffff810f88a3)
Location: include/linux/cpumask.h:356
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff811196bb)
Location: include/linux/cpumask.h:356
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/base/cacheinfo.c (ffffffff8164ea51)
Location: include/linux/cpumask.h:356
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
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
In arch/x86/events/intel/uncore.c (ffffffff81014cf2)
Location: include/linux/cpumask.h:358
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff8104696a)
Location: include/linux/cpumask.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
```
In kernel/irq/affinity.c (ffffffff8110098c)
Location: include/linux/cpumask.h:358
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff8112622b)
Location: include/linux/cpumask.h:358
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/base/cacheinfo.c (ffffffff8168a1a5)
Location: include/linux/cpumask.h:358
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
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
In arch/x86/events/intel/uncore.c (ffffffff81015402)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810558fb)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In kernel/irq/affinity.c (ffffffff8110c14b)
Location: include/linux/cpumask.h:370
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff8113190b)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/base/cacheinfo.c (ffffffff816a96a5)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
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
In arch/x86/events/intel/uncore.c (ffffffff810168a5)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81058b52)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In kernel/irq/affinity.c (ffffffff811158c0)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff8113c48b)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/base/cacheinfo.c (ffffffff816e2cb5)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
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
In arch/x86/events/intel/uncore.c (ffffffff81017255)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059422)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In kernel/cpu.c (ffffffff810a4584)
Location: include/linux/cpumask.h:386
Inline: True
```
```
In kernel/irq/affinity.c (ffffffff81121d11)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff8114809b)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/base/cacheinfo.c (ffffffff81706e65)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
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
In arch/x86/events/intel/uncore.c (ffffffff81018705)
Location: include/linux/cpumask.h:393
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105e7cf)
Location: include/linux/cpumask.h:393
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In kernel/cpu.c (ffffffff810ab854)
Location: include/linux/cpumask.h:393
Inline: True
```
```
In kernel/irq/affinity.c (ffffffff8112dfd4)
Location: include/linux/cpumask.h:393
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/time/tick-broadcast.c (ffffffff81157edb)
Location: include/linux/cpumask.h:393
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/base/cacheinfo.c (ffffffff817c1c15)
Location: include/linux/cpumask.h:393
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
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
In arch/x86/events/intel/uncore.c (ffffffff81018de0)
Location: include/linux/cpumask.h:399
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105ccef)
Location: include/linux/cpumask.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In kernel/cpu.c (ffffffff810a70d4)
Location: include/linux/cpumask.h:399
Inline: True
```
```
In kernel/irq/affinity.c (ffffffff81129bc4)
Location: include/linux/cpumask.h:399
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/time/tick-broadcast.c (ffffffff81153fcb)
Location: include/linux/cpumask.h:399
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/base/cacheinfo.c (ffffffff817d6e35)
Location: include/linux/cpumask.h:399
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
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
In arch/x86/events/intel/uncore.c (ffffffff8101a100)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d64f)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In kernel/cpu.c (ffffffff810a8174)
Location: include/linux/cpumask.h:370
Inline: True
```
```
In kernel/irq/affinity.c (ffffffff81129e60)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/time/tick-broadcast.c (ffffffff81155442)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/base/cacheinfo.c (ffffffff817ba855)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
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
In arch/x86/events/intel/uncore.c (ffffffff8101c990)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81066d60)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In kernel/cpu.c (ffffffff810b9c24)
Location: include/linux/cpumask.h:370
Inline: True
```
```
In kernel/irq/affinity.c (ffffffff8114a7a3)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/time/tick-broadcast.c (ffffffff811798f8)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/base/cacheinfo.c (ffffffff818446e0)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
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
In arch/x86/events/intel/uncore.c (ffffffff8101f340)
Location: include/linux/cpumask.h:405
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81073ab0)
Location: include/linux/cpumask.h:405
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In kernel/cpu.c (ffffffff810d072c)
Location: include/linux/cpumask.h:405
Inline: True
```
```
In kernel/irq/affinity.c (ffffffff8116fc14)
Location: include/linux/cpumask.h:405
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/time/tick-broadcast.c (ffffffff811aee80)
Location: include/linux/cpumask.h:405
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/base/cacheinfo.c (ffffffff819888c0)
Location: include/linux/cpumask.h:405
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/nd_perf.c (ffffffff819d90b6)
Location: include/linux/cpumask.h:405
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9b73c)
Location: include/linux/cpumask.h:405
Inline: True
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
In arch/x86/events/intel/uncore.c (ffffffff81023a30)
Location: include/linux/cpumask.h:470
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81083e50)
Location: include/linux/cpumask.h:470
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In kernel/cpu.c (ffffffff810ef00c)
Location: include/linux/cpumask.h:470
Inline: True
```
```
In kernel/irq/affinity.c (ffffffff811a6052)
Location: include/linux/cpumask.h:470
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/time/tick-broadcast.c (ffffffff811ef640)
Location: include/linux/cpumask.h:470
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/base/cacheinfo.c (ffffffff81af76a0)
Location: include/linux/cpumask.h:470
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81b540f6)
Location: include/linux/cpumask.h:470
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81d3d08c)
Location: include/linux/cpumask.h:470
Inline: True
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
In arch/x86/events/intel/uncore.c (ffffffff81023750)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810863f0)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In kernel/cpu.c (ffffffff810fafbc)
Location: include/linux/cpumask.h:530
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff81203ded)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/bpf/cpumask.c (ffffffff8135d863)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_test_and_clear_cpu
```
```
In lib/group_cpus.c (ffffffff818e6a8d)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - lib/group_cpus.c:grp_spread_init_one
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b1af3f)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline
```
```
In drivers/base/cacheinfo.c (ffffffff81b458e0)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81ba7646)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81da7c5c)
Location: include/linux/cpumask.h:530
Inline: True
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
In arch/x86/events/intel/uncore.c (ffffffff81029880)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108d2d0)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In kernel/cpu.c (ffffffff8110445c)
Location: include/linux/cpumask.h:530
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff8121a3ad)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/bpf/cpumask.c (ffffffff81386603)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_test_and_clear_cpu
```
```
In lib/group_cpus.c (ffffffff8192daad)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - lib/group_cpus.c:grp_spread_init_one
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b70a6f)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline
```
```
In drivers/base/cacheinfo.c (ffffffff81b9dd90)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81bfb8f6)
Location: include/linux/cpumask.h:530
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81e5f98c)
Location: include/linux/cpumask.h:530
Inline: True
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
In arch/arm64/mm/context.c (ffff8000100afb1c)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:check_and_switch_context
```
```
In kernel/cpu.c (ffff8000100fa244)
Location: include/linux/cpumask.h:386
Inline: True
```
```
In kernel/irq/affinity.c (ffff800010187ee4)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffff8000101b3a6c)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/base/cacheinfo.c (ffff8000108f43e8)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
```
In drivers/perf/hisilicon/hisi_uncore_pmu.c (ffff800010b96b3c)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_offline_cpu
```
```
In drivers/perf/qcom_l3_pmu.c (ffff800010b9a804)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_offline_cpu
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9c4f0)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - drivers/perf/xgene_pmu.c:xgene_pmu_offline_cpu
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
In arch/arm/mm/context.c (c0322360)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - arch/arm/mm/context.c:check_and_switch_context
```
```
In arch/arm/mm/cache-l2x0-pmu.c (c0324eb8)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_offline_cpu
```
```
In arch/arm/mach-imx/mmdc.c (c0332ed8)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_offline_cpu
```
```
In kernel/cpu.c (c03583e0)
Location: include/linux/cpumask.h:386
Inline: True
```
```
In kernel/irq/affinity.c (c03d6950)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (c03fdb68)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/base/cacheinfo.c (c09e0980)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
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
In arch/powerpc/perf/imc-pmu.c (c00000000012a178)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_offline
  - arch/powerpc/perf/imc-pmu.c:ppc_nest_imc_cpu_offline
```
```
In kernel/cpu.c (c0000000001413f0)
Location: include/linux/cpumask.h:386
Inline: True
```
```
In kernel/irq/affinity.c (c0000000001e1c70)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (c000000000219188)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/base/cacheinfo.c (c00000000098e3b0)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
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
In kernel/cpu.c (ffffffe0000c43bc)
Location: include/linux/cpumask.h:386
Inline: True
```
```
In kernel/irq/affinity.c (ffffffe00011d81a)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In drivers/base/cacheinfo.c (ffffffe0005859ce)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
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
In arch/x86/events/intel/uncore.c (ffffffff81017255)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81058fa2)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In kernel/cpu.c (ffffffff8109dea4)
Location: include/linux/cpumask.h:386
Inline: True
```
```
In kernel/irq/affinity.c (ffffffff8111a2f1)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff811406bb)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/base/cacheinfo.c (ffffffff816cc5b5)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
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
In arch/x86/events/intel/uncore.c (ffffffff81016685)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810491a2)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In kernel/cpu.c (ffffffff8108c8c4)
Location: include/linux/cpumask.h:386
Inline: True
```
```
In kernel/irq/affinity.c (ffffffff8110b361)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff8113343b)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/base/cacheinfo.c (ffffffff816a78e5)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
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
In arch/x86/events/intel/uncore.c (ffffffff81017215)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810593d2)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In kernel/cpu.c (ffffffff8109de54)
Location: include/linux/cpumask.h:386
Inline: True
```
```
In kernel/irq/affinity.c (ffffffff811181e1)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff8113e56b)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/base/cacheinfo.c (ffffffff816fab25)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
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
In arch/x86/events/intel/uncore.c (ffffffff81017455)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105a872)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In kernel/cpu.c (ffffffff810a5d44)
Location: include/linux/cpumask.h:386
Inline: True
```
```
In kernel/irq/affinity.c (ffffffff81123871)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff8114b07b)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/base/cacheinfo.c (ffffffff817153c5)
Location: include/linux/cpumask.h:386
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down
```
</details>
</li>
</ul>

## Differences
