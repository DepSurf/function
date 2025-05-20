# Function: <code>tick_nohz_dep_set_cpu</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tick_nohz_dep_set_cpu(int cpu, enum tick_dep_bits bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-sched.c (0)
Location: kernel/time/tick-sched.c:445
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:__dequeue_dl_entity
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_utility.c:dequeue_task_stop
  - kernel/sched/build_utility.c:enqueue_task_stop
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:__rcu_irq_enter_check_tick
  - kernel/events/core.c:__perf_event_account_interrupt
```
**Symbols:**

```
ffffffff821b6018-ffffffff821b6036: tick_nohz_dep_set_cpu.cold (STB_LOCAL)
ffffffff8121c5e0-ffffffff8121c6bb: tick_nohz_dep_set_cpu (STB_GLOBAL)
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
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tick_nohz_dep_set_cpu(int cpu, enum tick_dep_bits bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-sched.c (ffffffff811347c0)
Location: kernel/time/tick-sched.c:310
Inline: False
Direct callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/stop_task.c:dequeue_task_stop
  - kernel/sched/stop_task.c:enqueue_task_stop
```
**Symbols:**

```
ffffffff811347c0-ffffffff8113482f: tick_nohz_dep_set_cpu (STB_GLOBAL)
```
</details>
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
</ul>
<b>Flavor</b>
<ul>
</ul>
