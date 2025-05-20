# Function: <code>cpu_active</code>

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
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e4592)
Location: include/linux/cpumask.h:908
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:is_cpu_allowed
```
```
In kernel/sched/fair.c (ffffffff810f6ad0)
Location: include/linux/cpumask.h:908
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff810fae6f)
Location: include/linux/cpumask.h:908
Inline: True
```
```
In kernel/stop_machine.c (ffffffff81184591)
Location: include/linux/cpumask.h:908
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
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
In kernel/sched/core.c (ffffffff810fb332)
Location: include/linux/cpumask.h:908
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
```
```
In kernel/sched/fair.c (ffffffff81110a90)
Location: include/linux/cpumask.h:908
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/deadline.c (ffffffff81116a5c)
Location: include/linux/cpumask.h:908
Inline: True
```
```
In kernel/stop_machine.c (ffffffff811ac8c1)
Location: include/linux/cpumask.h:908
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
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
In kernel/sched/core.c (ffffffff811151d2)
Location: include/linux/cpumask.h:934
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migration_cpu_stop
```
```
In kernel/sched/fair.c (ffffffff8112cc79)
Location: include/linux/cpumask.h:934
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/build_policy.c (ffffffff81138e9d)
Location: include/linux/cpumask.h:934
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff811b0370)
Location: include/linux/cpumask.h:934
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:can_stop_idle_tick
```
```
In kernel/stop_machine.c (ffffffff811de3f8)
Location: include/linux/cpumask.h:934
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
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
In kernel/sched/core.c (ffffffff8113c572)
Location: include/linux/cpumask.h:1043
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migration_cpu_stop
```
```
In kernel/sched/fair.c (ffffffff81156989)
Location: include/linux/cpumask.h:1043
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/build_policy.c (ffffffff8116354d)
Location: include/linux/cpumask.h:1043
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff811f0e40)
Location: include/linux/cpumask.h:1043
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:can_stop_idle_tick
```
```
In kernel/stop_machine.c (ffffffff81223f48)
Location: include/linux/cpumask.h:1043
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
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
In kernel/sched/core.c (ffffffff811501c0)
Location: include/linux/cpumask.h:1095
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migration_cpu_stop
```
```
In kernel/sched/fair.c (ffffffff811669f9)
Location: include/linux/cpumask.h:1095
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/build_policy.c (ffffffff81173d2d)
Location: include/linux/cpumask.h:1095
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81205878)
Location: include/linux/cpumask.h:1095
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:can_stop_idle_tick
```
```
In kernel/stop_machine.c (ffffffff8123a568)
Location: include/linux/cpumask.h:1095
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
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
In kernel/sched/core.c (ffffffff8115c090)
Location: include/linux/cpumask.h:1117
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migration_cpu_stop
```
```
In kernel/sched/fair.c (ffffffff81166718)
Location: include/linux/cpumask.h:1117
Inline: True
Inline callers:
  - kernel/sched/fair.c:switched_from_fair
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
```
In kernel/sched/build_policy.c (ffffffff81181936)
Location: include/linux/cpumask.h:1117
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_task_dl
```
```
In kernel/time/tick-sched.c (ffffffff8121bf18)
Location: include/linux/cpumask.h:1117
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:can_stop_idle_tick
```
```
In kernel/stop_machine.c (ffffffff81254238)
Location: include/linux/cpumask.h:1117
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
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
