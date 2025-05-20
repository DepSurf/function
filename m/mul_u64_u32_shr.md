# Function: <code>mul_u64_u32_shr</code>

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
In arch/x86/kernel/tsc.c (0)
Location: include/linux/math64.h:139
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810b2be9)
Location: include/linux/math64.h:139
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:remove_entity_load_avg
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
In arch/x86/kernel/tsc.c (ffffffff8103701d)
Location: include/linux/math64.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
```
In kernel/sched/fair.c (ffffffff810b9dbc)
Location: include/linux/math64.h:139
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_task_cfs_rq
  - kernel/sched/fair.c:attach_task_cfs_rq
  - kernel/sched/fair.c:attach_task_cfs_rq
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:remove_entity_load_avg
  - kernel/sched/fair.c:remove_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:__calc_delta
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
In arch/x86/kernel/tsc.c (ffffffff81036d5d)
Location: include/linux/math64.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff81fd0d4e)
Location: include/linux/math64.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In kernel/sched/fair.c (ffffffff810c3c09)
Location: include/linux/math64.h:139
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:sync_entity_load_avg
  - kernel/sched/fair.c:sync_entity_load_avg
  - kernel/sched/fair.c:__calc_delta
```
```
In kernel/time/timekeeping.c (ffffffff810ffd1e)
Location: include/linux/math64.h:139
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
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
In arch/x86/kernel/tsc.c (ffffffff81034e47)
Location: include/linux/math64.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff820b1874)
Location: include/linux/math64.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In kernel/sched/fair.c (ffffffff810b5be0)
Location: include/linux/math64.h:149
Inline: True
Inline callers:
  - kernel/sched/fair.c:__accumulate_pelt_segments
  - kernel/sched/fair.c:__accumulate_pelt_segments
  - kernel/sched/fair.c:__calc_delta
```
```
In kernel/time/timekeeping.c (ffffffff81101f04)
Location: include/linux/math64.h:149
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
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
In arch/x86/kernel/tsc.c (ffffffff810371a7)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff826b80c5)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In kernel/sched/fair.c (ffffffff810bcec0)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/sched/fair.c:__accumulate_pelt_segments
  - kernel/sched/fair.c:__accumulate_pelt_segments
  - kernel/sched/fair.c:__calc_delta
```
```
In kernel/time/timekeeping.c (ffffffff8110ce67)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
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
In arch/x86/kernel/tsc.c (ffffffff81038189)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff826e1db3)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In kernel/sched/fair.c (ffffffff810c49af)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/sched/fair.c:__accumulate_pelt_segments
  - kernel/sched/fair.c:__accumulate_pelt_segments
  - kernel/sched/fair.c:__calc_delta
```
```
In kernel/time/timekeeping.c (ffffffff81118af3)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
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
In arch/x86/kernel/tsc.c (ffffffff810398e8)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff828986ec)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In kernel/sched/fair.c (ffffffff810cd962)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/sched/fair.c:__calc_delta
```
```
In kernel/sched/pelt.c (ffffffff810e7907)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__accumulate_pelt_segments
  - kernel/sched/pelt.c:__accumulate_pelt_segments
```
```
In kernel/time/clocksource.c (ffffffff81126c1a)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
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
In arch/x86/kernel/tsc.c (ffffffff8103be84)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff828b02c3)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In kernel/sched/fair.c (ffffffff810d6038)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/sched/fair.c:__calc_delta
```
```
In kernel/sched/pelt.c (ffffffff810ee817)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__accumulate_pelt_segments
  - kernel/sched/pelt.c:__accumulate_pelt_segments
```
```
In kernel/time/clocksource.c (ffffffff811315ce)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
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
In arch/x86/kernel/tsc.c (ffffffff8103c644)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff828b364a)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81095afb)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_show
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_show
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
```
```
In kernel/sched/fair.c (ffffffff810e06b8)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/sched/fair.c:__calc_delta
```
```
In kernel/sched/pelt.c (ffffffff810fa3f7)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__accumulate_pelt_segments
  - kernel/sched/pelt.c:__accumulate_pelt_segments
```
```
In kernel/time/clocksource.c (ffffffff8113d51e)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
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
In arch/x86/kernel/tsc.c (ffffffff8103f434)
Location: include/linux/math64.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff82cd84e2)
Location: include/linux/math64.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_paravirt_ops_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_steal_clock
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109ae43)
Location: include/linux/math64.h:159
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_show
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_show
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
```
```
In kernel/sched/fair.c (ffffffff810e8b8c)
Location: include/linux/math64.h:159
Inline: True
Inline callers:
  - kernel/sched/fair.c:__calc_delta
```
```
In kernel/sched/pelt.c (ffffffff811046e9)
Location: include/linux/math64.h:159
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
```
In kernel/time/clocksource.c (ffffffff8114c6a6)
Location: include/linux/math64.h:159
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
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
In arch/x86/kernel/tsc.c (ffffffff8103f4f4)
Location: include/linux/math64.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff82fc48b4)
Location: include/linux/math64.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_paravirt_ops_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_steal_clock
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In kernel/sched/fair.c (ffffffff810e691c)
Location: include/linux/math64.h:159
Inline: True
Inline callers:
  - kernel/sched/fair.c:__calc_delta
```
```
In kernel/sched/pelt.c (ffffffff81102d78)
Location: include/linux/math64.h:159
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
```
In kernel/time/clocksource.c (ffffffff81148b06)
Location: include/linux/math64.h:159
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
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
In arch/x86/kernel/tsc.c (ffffffff81040e64)
Location: include/linux/math64.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff831cf16f)
Location: include/linux/math64.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_steal_clock
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In kernel/sched/fair.c (0)
Location: include/linux/math64.h:159
Inline: True
Inline callers:
  - kernel/sched/fair.c:__calc_delta
```
```
In kernel/sched/pelt.c (ffffffff811050bf)
Location: include/linux/math64.h:159
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
```
In kernel/time/clocksource.c (ffffffff8114a006)
Location: include/linux/math64.h:159
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
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
In arch/x86/kernel/tsc.c (ffffffff81046f8d)
Location: include/linux/math64.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff832b14d8)
Location: include/linux/math64.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_steal_clock
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In kernel/sched/fair.c (ffffffff81100011)
Location: include/linux/math64.h:160
Inline: True
Inline callers:
  - kernel/sched/fair.c:__calc_delta
```
```
In kernel/sched/pelt.c (ffffffff81122add)
Location: include/linux/math64.h:160
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
```
In kernel/time/clocksource.c (ffffffff8116dd16)
Location: include/linux/math64.h:160
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
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
In arch/x86/kernel/tsc.c (ffffffff8104fd34)
Location: include/linux/math64.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff834627ba)
Location: include/linux/math64.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_steal_clock
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In kernel/sched/fair.c (ffffffff8111b2dd)
Location: include/linux/math64.h:160
Inline: True
Inline callers:
  - kernel/sched/fair.c:__calc_delta
```
```
In kernel/sched/build_policy.c (ffffffff811386f9)
Location: include/linux/math64.h:160
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
```
```
In kernel/time/clocksource.c (ffffffff811a1efa)
Location: include/linux/math64.h:160
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
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
In arch/x86/kernel/tsc.c (ffffffff8105d0b4)
Location: include/linux/math64.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff83e84c06)
Location: include/linux/math64.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_steal_clock
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In kernel/sched/fair.c (ffffffff81142d8d)
Location: include/linux/math64.h:164
Inline: True
Inline callers:
  - kernel/sched/fair.c:__calc_delta
```
```
In kernel/sched/build_policy.c (ffffffff81162d89)
Location: include/linux/math64.h:164
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
```
```
In kernel/time/clocksource.c (ffffffff811e138a)
Location: include/linux/math64.h:164
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
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
In arch/x86/kernel/tsc.c (ffffffff8105e624)
Location: include/linux/math64.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff836a810d)
Location: include/linux/math64.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_steal_clock
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In kernel/sched/fair.c (ffffffff81152d8b)
Location: include/linux/math64.h:164
Inline: True
Inline callers:
  - kernel/sched/fair.c:__calc_delta
```
```
In kernel/sched/build_policy.c (ffffffff811735f6)
Location: include/linux/math64.h:164
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
```
```
In kernel/time/clocksource.c (ffffffff811f58ea)
Location: include/linux/math64.h:164
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
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
In arch/x86/kernel/tsc.c (ffffffff810656e4)
Location: include/linux/math64.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff838d864b)
Location: include/linux/math64.h:164
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_steal_clock
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In kernel/sched/fair.c (ffffffff8115ef7e)
Location: include/linux/math64.h:164
Inline: True
```
```
In kernel/sched/build_policy.c (ffffffff81180f26)
Location: include/linux/math64.h:164
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
```
```
In kernel/time/clocksource.c (ffffffff8120ba8a)
Location: include/linux/math64.h:164
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
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
In kernel/sched/fair.c (ffff800010140550)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/sched/fair.c:__calc_delta
```
```
In kernel/sched/pelt.c (ffff80001015edd0)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__accumulate_pelt_segments
  - kernel/sched/pelt.c:__accumulate_pelt_segments
```
```
In kernel/time/clocksource.c (ffff8000101a70d4)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
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
In kernel/sched/fair.c (c039041c)
Location: include/linux/math64.h:193
Inline: True
Inline callers:
  - kernel/sched/fair.c:__calc_delta
```
```
In kernel/sched/pelt.c (c03ab520)
Location: include/linux/math64.h:193
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__accumulate_pelt_segments
  - kernel/sched/pelt.c:__accumulate_pelt_segments
```
```
In kernel/time/clocksource.c (c03f2180)
Location: include/linux/math64.h:193
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
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
In kernel/sched/fair.c (c00000000018f7b4)
Location: include/linux/math64.h:193
Inline: True
Inline callers:
  - kernel/sched/fair.c:__calc_delta
```
```
In kernel/sched/pelt.c (c0000000001b4058)
Location: include/linux/math64.h:193
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__accumulate_pelt_segments
  - kernel/sched/pelt.c:__accumulate_pelt_segments
```
```
In kernel/time/clocksource.c (c000000000209a84)
Location: include/linux/math64.h:193
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
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
In kernel/sched/fair.c (ffffffe0000ee58e)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/sched/fair.c:__calc_delta
```
```
In kernel/sched/pelt.c (ffffffe0001031c4)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__accumulate_pelt_segments
  - kernel/sched/pelt.c:__accumulate_pelt_segments
```
```
In kernel/time/clocksource.c (ffffffe00013310c)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
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
In arch/x86/kernel/tsc.c (ffffffff8103c7a4)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff828a1669)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In kernel/sched/fair.c (ffffffff810da868)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/sched/fair.c:__calc_delta
```
```
In kernel/sched/pelt.c (ffffffff810f37f7)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__accumulate_pelt_segments
  - kernel/sched/pelt.c:__accumulate_pelt_segments
```
```
In kernel/time/clocksource.c (ffffffff81135cce)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
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
In arch/x86/kernel/tsc.c (ffffffff8102be94)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff82899842)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In kernel/sched/fair.c (ffffffff810c9878)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/sched/fair.c:__calc_delta
```
```
In kernel/sched/pelt.c (ffffffff810e3907)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__accumulate_pelt_segments
  - kernel/sched/pelt.c:__accumulate_pelt_segments
```
```
In kernel/time/clocksource.c (ffffffff8112871e)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
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
In arch/x86/kernel/tsc.c (ffffffff8103c604)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff828b462c)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In kernel/sched/fair.c (ffffffff810d6be8)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/sched/fair.c:__calc_delta
```
```
In kernel/sched/pelt.c (ffffffff810f0927)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__accumulate_pelt_segments
  - kernel/sched/pelt.c:__accumulate_pelt_segments
```
```
In kernel/time/clocksource.c (ffffffff811339ee)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
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
In arch/x86/kernel/tsc.c (ffffffff8103d67b)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff828b464d)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/cpu/vmware.c:vmware_sched_clock
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109708b)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_show
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_show
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
```
```
In kernel/sched/fair.c (ffffffff810e24f8)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/sched/fair.c:__calc_delta
```
```
In kernel/sched/pelt.c (ffffffff810fb9c7)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__accumulate_pelt_segments
  - kernel/sched/pelt.c:__accumulate_pelt_segments
```
```
In kernel/time/clocksource.c (ffffffff8114040e)
Location: include/linux/math64.h:177
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_stop_suspend_timing
```
</details>
</li>
</ul>

## Differences
