# Function: <code>rt_task</code>

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
In kernel/sched/core.c (ffffffff810b02b0)
Location: include/linux/sched/rt.h:13
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/rt.c (ffffffff810bef8d)
Location: include/linux/sched/rt.h:13
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
```
```
In kernel/locking/mutex.c (ffffffff810c9bbc)
Location: include/linux/sched/rt.h:13
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_optimistic_spin
```
```
In kernel/locking/rwsem-xadd.c (ffffffff81823115)
Location: include/linux/sched/rt.h:13
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/sched/rt.h:13
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81157334)
Location: include/linux/sched/rt.h:13
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In mm/page_alloc.c (ffffffff81193074)
Location: include/linux/sched/rt.h:13
Inline: True
Inline callers:
  - mm/page_alloc.c:gfp_pfmemalloc_allowed
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/page-writeback.c (ffffffff81198024)
Location: include/linux/sched/rt.h:13
Inline: True
Inline callers:
  - mm/page-writeback.c:domain_dirty_limits
  - mm/page-writeback.c:zone_dirty_ok
```
```
In fs/select.c (ffffffff81220f8e)
Location: include/linux/sched/rt.h:13
Inline: True
Inline callers:
  - fs/select.c:do_select
  - fs/select.c:do_sys_poll
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
In kernel/sched/core.c (ffffffff810b2ee9)
Location: include/linux/sched/rt.h:13
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/rt.c (ffffffff810c2897)
Location: include/linux/sched/rt.h:13
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
```
```
In kernel/locking/mutex.c (ffffffff810ce529)
Location: include/linux/sched/rt.h:13
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_optimistic_spin
```
```
In kernel/locking/rwsem-xadd.c (ffffffff8189dc91)
Location: include/linux/sched/rt.h:13
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/sched/rt.h:13
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81161bb4)
Location: include/linux/sched/rt.h:13
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In mm/page_alloc.c (ffffffff811aa646)
Location: include/linux/sched/rt.h:13
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/page-writeback.c (ffffffff811b0019)
Location: include/linux/sched/rt.h:13
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:domain_dirty_limits
```
```
In fs/select.c (ffffffff81249cbe)
Location: include/linux/sched/rt.h:13
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
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
In kernel/sched/core.c (ffffffff810b94d3)
Location: include/linux/sched/rt.h:13
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/rt.c (ffffffff810c8913)
Location: include/linux/sched/rt.h:13
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
```
```
In kernel/locking/rwsem-xadd.c (ffffffff818d2b2e)
Location: include/linux/sched/rt.h:13
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/sched/rt.h:13
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116c714)
Location: include/linux/sched/rt.h:13
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In mm/page_alloc.c (ffffffff811bac6e)
Location: include/linux/sched/rt.h:13
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/page-writeback.c (ffffffff811c06d9)
Location: include/linux/sched/rt.h:13
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:domain_dirty_limits
```
```
In fs/select.c (ffffffff8125cc8e)
Location: include/linux/sched/rt.h:13
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
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
In kernel/sched/core.c (ffffffff810b40ad)
Location: include/linux/sched/rt.h:15
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/rt.c (ffffffff810c2b43)
Location: include/linux/sched/rt.h:15
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
```
```
In kernel/locking/rwsem-xadd.c (ffffffff81909759)
Location: include/linux/sched/rt.h:15
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/sched/rt.h:15
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116fab5)
Location: include/linux/sched/rt.h:15
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In mm/page_alloc.c (ffffffff811c2cd9)
Location: include/linux/sched/rt.h:15
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/page-writeback.c (ffffffff811c8829)
Location: include/linux/sched/rt.h:15
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:domain_dirty_limits
```
```
In fs/select.c (ffffffff81268b08)
Location: include/linux/sched/rt.h:15
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
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
In kernel/sched/core.c (ffffffff810bb35d)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/rt.c (ffffffff810cbb72)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
```
```
In kernel/locking/rwsem-xadd.c (ffffffff819939a8)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/sched/rt.h:16
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8117cbc7)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In mm/page_alloc.c (ffffffff811d7a23)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/page-writeback.c (ffffffff811dd689)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:domain_dirty_limits
```
```
In fs/select.c (ffffffff8128b3c8)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
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
In kernel/sched/core.c (ffffffff810c2816)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/rt.c (ffffffff810d42f4)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
```
```
In kernel/locking/rwsem-xadd.c (ffffffff819eff97)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In kernel/time/hrtimer.c (ffffffff81116799)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8118bc34)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In mm/page_alloc.c (ffffffff811f8c17)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/page-writeback.c (ffffffff811febb2)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:domain_dirty_limits
```
```
In fs/select.c (ffffffff812b1bf8)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
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
In kernel/sched/core.c (ffffffff810cbb16)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/rt.c (ffffffff810dd804)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
```
```
In kernel/locking/rwsem-xadd.c (ffffffff81a2b9b4)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
```
In kernel/time/hrtimer.c (ffffffff81121dd9)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81199654)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In mm/page_alloc.c (ffffffff8120b1a7)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/page-writeback.c (ffffffff81211465)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:domain_dirty_limits
```
```
In fs/select.c (ffffffff812c6d18)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
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
In kernel/sched/core.c (ffffffff810d3b86)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (ffffffff810e4806)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
```
```
In kernel/locking/rwsem.c (ffffffff810f84b1)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/time/hrtimer.c (ffffffff8112c729)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a7274)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In mm/page-writeback.c (ffffffff81220ad8)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/page_alloc.c (ffffffff8127142b)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In fs/select.c (ffffffff812e3898)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
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
In kernel/sched/core.c (ffffffff810de066)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/rt.c (ffffffff810f04a5)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_can_attach
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
```
```
In kernel/locking/rwsem.c (ffffffff811042eb)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/time/hrtimer.c (ffffffff8113873e)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b2a64)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In mm/page-writeback.c (ffffffff8122e588)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/page_alloc.c (ffffffff8128026b)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In fs/select.c (ffffffff812f52d8)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
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
In kernel/sched/core.c (ffffffff810e661a)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/rt.c (ffffffff810f94a0)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_woken_rt
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:find_lock_lowest_rq
```
```
In kernel/locking/rwsem.c (ffffffff8110eee0)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/time/hrtimer.c (ffffffff81147559)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811caf64)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In mm/page-writeback.c (ffffffff8125b5e7)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/page_alloc.c (ffffffff812b2aa2)
Location: include/linux/sched/rt.h:16
Inline: True
```
```
In fs/select.c (ffffffff8132d898)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
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
In kernel/sched/core.c (ffffffff810e451a)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:__setscheduler_uclamp
  - kernel/sched/core.c:uclamp_sync_util_min_rt_default
```
```
In kernel/sched/rt.c (ffffffff810f7790)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_woken_rt
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:find_lock_lowest_rq
```
```
In kernel/locking/rwsem.c (ffffffff8110c0ce)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/time/hrtimer.c (ffffffff81143a66)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c8644)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In mm/page-writeback.c (ffffffff81265a07)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/page_alloc.c (ffffffff812be618)
Location: include/linux/sched/rt.h:16
Inline: True
```
```
In fs/select.c (ffffffff813390f8)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
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
In kernel/sched/core.c (ffffffff810e64ca)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
```
```
In kernel/sched/rt.c (ffffffff810f9ca0)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_woken_rt
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:find_lock_lowest_rq
```
```
In kernel/locking/rwsem.c (ffffffff8110df05)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/time/hrtimer.c (ffffffff81144c16)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c98e2)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In mm/page-writeback.c (ffffffff8126a505)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/page_alloc.c (ffffffff812c36a8)
Location: include/linux/sched/rt.h:16
Inline: True
```
```
In fs/select.c (ffffffff8133f6b8)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
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
In kernel/sched/core.c (ffffffff810fda01)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
```
```
In kernel/sched/rt.c (ffffffff81112bf0)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_woken_rt
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:find_lock_lowest_rq
```
```
In kernel/locking/rwsem.c (ffffffff8112d6bf)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/time/hrtimer.c (ffffffff81168466)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811f539a)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In mm/page-writeback.c (ffffffff812a71b5)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/page_alloc.c (ffffffff81307528)
Location: include/linux/sched/rt.h:16
Inline: True
```
```
In fs/select.c (ffffffff8138d048)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
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
In kernel/sched/core.c (ffffffff8111a41e)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
```
```
In kernel/sched/build_policy.c (ffffffff8112df73)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_pushable_task
  - kernel/sched/build_policy.c:find_lock_lowest_rq
```
```
In kernel/locking/rwsem.c (ffffffff81f25939)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/time/hrtimer.c (ffffffff8119bea8)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122ebf3)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In mm/page-writeback.c (ffffffff812ff952)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/page_alloc.c (ffffffff8136fcfb)
Location: include/linux/sched/rt.h:16
Inline: True
```
```
In fs/select.c (ffffffff8140e39e)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
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
In kernel/sched/core.c (ffffffff81141c8e)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
```
```
In kernel/sched/build_policy.c (ffffffff81157f03)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_pushable_task
  - kernel/sched/build_policy.c:find_lock_lowest_rq
```
```
In kernel/locking/rwsem.c (ffffffff820d131e)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/time/hrtimer.c (ffffffff811da818)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127ac13)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In mm/page-writeback.c (ffffffff81369cc2)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/page_alloc.c (ffffffff813ec2fd)
Location: include/linux/sched/rt.h:16
Inline: True
```
```
In fs/select.c (ffffffff81498f1e)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
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
In kernel/sched/core.c (ffffffff8114d95e)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
```
```
In kernel/sched/build_policy.c (ffffffff81168003)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_pushable_task
  - kernel/sched/build_policy.c:find_lock_lowest_rq
```
```
In kernel/locking/rwsem.c (ffffffff8215566f)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/time/hrtimer.c (ffffffff8215828d)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81292733)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In mm/page-writeback.c (ffffffff8139be62)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/page_alloc.c (ffffffff81421317)
Location: include/linux/sched/rt.h:16
Inline: True
```
```
In fs/select.c (ffffffff814cdfae)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
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
In kernel/sched/core.c (ffffffff8115976e)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
```
```
In kernel/sched/build_policy.c (ffffffff81174db3)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_pushable_task
  - kernel/sched/build_policy.c:find_lock_lowest_rq
```
```
In kernel/locking/rwsem.c (ffffffff822384af)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/time/hrtimer.c (ffffffff8223b0fd)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812ade19)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In mm/page-writeback.c (ffffffff813c5b42)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/page_alloc.c (ffffffff8144e07f)
Location: include/linux/sched/rt.h:16
Inline: True
```
```
In fs/select.c (ffffffff815008ee)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
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
In kernel/sched/core.c (ffff80001013dab0)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/rt.c (ffff800010151b6c)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_can_attach
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
```
```
In kernel/locking/rwsem.c (ffff800010169bd8)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/time/hrtimer.c (ffff8000101a23ec)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffff800010230928)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In mm/page-writeback.c (ffff8000102bd4c8)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/page_alloc.c (ffff8000103181ac)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In fs/select.c (ffff8000103a2618)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
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
In kernel/sched/core.c (c038da8c)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/rt.c (c039ee1c)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_can_attach
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
```
```
In kernel/locking/rwsem.c (c03b5ef0)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/time/hrtimer.c (c03ec0f0)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (c046c6bc)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In mm/page-writeback.c (c04e9950)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/page_alloc.c (c0532728)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In fs/select.c (c0585010)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
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
In kernel/sched/core.c (c00000000018ca4c)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (c0000000001a5478)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_can_attach
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
```
```
In kernel/locking/rwsem.c (c0000000001c1a9c)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/time/hrtimer.c (c0000000002038d8)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (c0000000002bad4c)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In mm/page-writeback.c (c000000000376140)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/page_alloc.c (c0000000003ea87c)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In fs/select.c (c00000000049bf6c)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
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
In kernel/sched/core.c (ffffffe0000ec95a)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/rt.c (ffffffe0000f9d50)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_can_attach
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
```
```
In kernel/locking/rwsem.c (ffffffe00010accc)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
```
In kernel/time/hrtimer.c (ffffffe00012f4f8)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffe00018929e)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In mm/page-writeback.c (ffffffe0001e0204)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/page_alloc.c (ffffffe00021dffc)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In fs/select.c (ffffffe00026aa20)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
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
In kernel/sched/core.c (ffffffff810d8256)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/rt.c (ffffffff810e92c5)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
```
```
In kernel/locking/rwsem.c (ffffffff810fd5fb)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/time/hrtimer.c (ffffffff81130eee)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811ab084)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In mm/page-writeback.c (ffffffff81226bd8)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/page_alloc.c (ffffffff812788bb)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In fs/select.c (ffffffff812ed8b8)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
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
In kernel/sched/core.c (ffffffff810c6c66)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/rt.c (ffffffff810d9865)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_can_attach
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
```
```
In kernel/locking/rwsem.c (ffffffff810ed7fb)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/time/hrtimer.c (ffffffff8112395e)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8119e394)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In mm/page-writeback.c (ffffffff81219d48)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/page_alloc.c (ffffffff8126a7ab)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In fs/select.c (ffffffff812de4e8)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
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
In kernel/sched/core.c (ffffffff810d4a46)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/rt.c (ffffffff810e69d5)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_can_attach
  - kernel/sched/rt.c:tg_rt_schedulable
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
```
```
In kernel/locking/rwsem.c (ffffffff810fa7bb)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/time/hrtimer.c (ffffffff8112ec0e)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a8e54)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In mm/page-writeback.c (ffffffff81224978)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/page_alloc.c (ffffffff8127665b)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In fs/select.c (ffffffff812eb6c8)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
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
In kernel/sched/core.c (ffffffff810dfe36)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/rt.c (ffffffff810f0672)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
```
```
In kernel/locking/rwsem.c (ffffffff81105983)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/time/hrtimer.c (ffffffff8113b60e)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b6c94)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In mm/page-writeback.c (ffffffff81233c48)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page-writeback.c:node_dirty_ok
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/page_alloc.c (ffffffff8128621b)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In fs/select.c (ffffffff812fc6b8)
Location: include/linux/sched/rt.h:16
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
```
</details>
</li>
</ul>

## Differences
