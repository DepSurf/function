# Function: <code>rq_unlock</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3d74)
Location: kernel/sched/sched.h:1758
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sys_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff810bb5e2)
Location: kernel/sched/sched.h:1758
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:cpu_load_update_nohz_stop
  - kernel/sched/fair.c:distribute_cfs_runtime
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
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1797
Inline: False
```
```
In kernel/sched/fair.c (ffffffff810c3342)
Location: kernel/sched/sched.h:1797
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:cpu_load_update_nohz_stop
  - kernel/sched/fair.c:distribute_cfs_runtime
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
In kernel/sched/core.c (ffffffff810c24ec)
Location: kernel/sched/sched.h:1841
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff810c9852)
Location: kernel/sched/sched.h:1841
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:cpu_load_update_nohz_stop
  - kernel/sched/fair.c:distribute_cfs_runtime
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
In kernel/sched/core.c (ffffffff810cb7dc)
Location: kernel/sched/sched.h:1178
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff810d3bf9)
Location: kernel/sched/sched.h:1178
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:cpu_load_update_nohz_stop
  - kernel/sched/fair.c:distribute_cfs_runtime
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
In kernel/sched/core.c (ffffffff810d37fc)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff810db0f8)
Location: kernel/sched/sched.h:1236
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/core.c (ffffffff810ddd46)
Location: kernel/sched/sched.h:1244
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff810e5008)
Location: kernel/sched/sched.h:1244
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/core.c (ffffffff810e3025)
Location: kernel/sched/sched.h:1292
Inline: True
Inline callers:
  - kernel/sched/core.c:migrate_tasks
  - kernel/sched/core.c:migrate_tasks
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_invoke_on_locked_down_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff810ee578)
Location: kernel/sched/sched.h:1292
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/core.c (ffffffff810e0883)
Location: kernel/sched/sched.h:1350
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_invoke_on_locked_down_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff810ec39a)
Location: kernel/sched/sched.h:1350
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/core.c (ffffffff810e26a3)
Location: kernel/sched/sched.h:1363
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_invoke_on_locked_down_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff810eed3a)
Location: kernel/sched/sched.h:1363
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/core.c (ffffffff810f8cb7)
Location: kernel/sched/sched.h:1650
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_invoke_on_locked_down_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff8110760b)
Location: kernel/sched/sched.h:1650
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/core.c (ffffffff811150a5)
Location: kernel/sched/sched.h:1623
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_call_func
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff81124846)
Location: kernel/sched/sched.h:1623
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/build_policy.c (ffffffff811320d3)
Location: kernel/sched/sched.h:1623
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
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
In kernel/sched/core.c (ffffffff8113c445)
Location: kernel/sched/sched.h:1669
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_call_func
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff8114c866)
Location: kernel/sched/sched.h:1669
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/build_policy.c (ffffffff8115c3a3)
Location: kernel/sched/sched.h:1669
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
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
In kernel/sched/core.c (ffffffff81150085)
Location: kernel/sched/sched.h:1696
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_call_func
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff8115c836)
Location: kernel/sched/sched.h:1696
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:__cfsb_csd_unthrottle
```
```
In kernel/sched/build_policy.c (ffffffff8116c763)
Location: kernel/sched/sched.h:1696
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
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
In kernel/sched/core.c (ffffffff8115bf55)
Location: kernel/sched/sched.h:1720
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_call_func
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff8116bd68)
Location: kernel/sched/sched.h:1720
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:__cfsb_csd_unthrottle
```
```
In kernel/sched/build_policy.c (ffffffff81179ff3)
Location: kernel/sched/sched.h:1720
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
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
In kernel/sched/core.c (ffff80001013d65c)
Location: kernel/sched/sched.h:1244
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffff800010144fa8)
Location: kernel/sched/sched.h:1244
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/core.c (c038d6bc)
Location: kernel/sched/sched.h:1244
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (c03928f4)
Location: kernel/sched/sched.h:1244
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/core.c (c00000000018c4ec)
Location: kernel/sched/sched.h:1244
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (c0000000001960f8)
Location: kernel/sched/sched.h:1244
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/core.c (ffffffe0000e8c40)
Location: kernel/sched/sched.h:1244
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffe0000f194a)
Location: kernel/sched/sched.h:1244
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/core.c (ffffffff810d7f36)
Location: kernel/sched/sched.h:1244
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff810df1b8)
Location: kernel/sched/sched.h:1244
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/core.c (ffffffff810c6907)
Location: kernel/sched/sched.h:1244
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff810ce1c8)
Location: kernel/sched/sched.h:1244
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/core.c (ffffffff810d4726)
Location: kernel/sched/sched.h:1244
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff810db538)
Location: kernel/sched/sched.h:1244
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/core.c (ffffffff810dfb30)
Location: kernel/sched/sched.h:1244
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff810e7228)
Location: kernel/sched/sched.h:1244
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
</details>
</li>
</ul>

## Differences
