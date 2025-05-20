# Function: <code>rq_lock</code>

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
In kernel/sched/core.c (ffffffff810b30a0)
Location: kernel/sched/sched.h:1726
Inline: True
Inline callers:
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
In kernel/sched/fair.c (ffffffff810bb538)
Location: kernel/sched/sched.h:1726
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
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
In kernel/sched/core.c (ffffffff810ba4a0)
Location: kernel/sched/sched.h:1765
Inline: True
Inline callers:
  - kernel/sched/core.c:sys_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff810c3298)
Location: kernel/sched/sched.h:1765
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
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
In kernel/sched/core.c (ffffffff810bec10)
Location: kernel/sched/sched.h:1809
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff810c9798)
Location: kernel/sched/sched.h:1809
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
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
In kernel/sched/core.c (ffffffff810c7eb0)
Location: kernel/sched/sched.h:1146
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff810d3b7b)
Location: kernel/sched/sched.h:1146
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:cpu_load_update_nohz_stop
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/psi.c (ffffffff810ef83e)
Location: kernel/sched/sched.h:1146
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810ceec1)
Location: kernel/sched/sched.h:1204
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff810db07b)
Location: kernel/sched/sched.h:1204
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/psi.c (ffffffff810f6cde)
Location: kernel/sched/sched.h:1204
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810d8c81)
Location: kernel/sched/sched.h:1212
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff810e4f8b)
Location: kernel/sched/sched.h:1212
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/psi.c (ffffffff81102a6e)
Location: kernel/sched/sched.h:1212
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810e1b11)
Location: kernel/sched/sched.h:1260
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff810ee4fb)
Location: kernel/sched/sched.h:1260
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/psi.c (ffffffff8110da8d)
Location: kernel/sched/sched.h:1260
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810e082c)
Location: kernel/sched/sched.h:1318
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff810ec2fb)
Location: kernel/sched/sched.h:1318
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/psi.c (ffffffff8110adad)
Location: kernel/sched/sched.h:1318
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810e264c)
Location: kernel/sched/sched.h:1331
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff810eec9b)
Location: kernel/sched/sched.h:1331
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/psi.c (ffffffff8110c9dd)
Location: kernel/sched/sched.h:1331
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810f8c4c)
Location: kernel/sched/sched.h:1618
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff8110755b)
Location: kernel/sched/sched.h:1618
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/psi.c (ffffffff8112ba1f)
Location: kernel/sched/sched.h:1618
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff8111503c)
Location: kernel/sched/sched.h:1599
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff8112479d)
Location: kernel/sched/sched.h:1599
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/build_policy.c (ffffffff8113204c)
Location: kernel/sched/sched.h:1599
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
```
```
In kernel/sched/build_utility.c (ffffffff8114c1b5)
Location: kernel/sched/sched.h:1599
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_memstall_leave
  - kernel/sched/build_utility.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff8113c3dc)
Location: kernel/sched/sched.h:1645
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff8114c7bd)
Location: kernel/sched/sched.h:1645
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/build_policy.c (ffffffff8115c31c)
Location: kernel/sched/sched.h:1645
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
```
```
In kernel/sched/build_utility.c (ffffffff8117a91d)
Location: kernel/sched/sched.h:1645
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff8115001c)
Location: kernel/sched/sched.h:1672
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff8115c78d)
Location: kernel/sched/sched.h:1672
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:__cfsb_csd_unthrottle
```
```
In kernel/sched/build_policy.c (ffffffff8116c6dc)
Location: kernel/sched/sched.h:1672
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
```
```
In kernel/sched/build_utility.c (ffffffff8118b47d)
Location: kernel/sched/sched.h:1672
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff8115beec)
Location: kernel/sched/sched.h:1696
Inline: True
Inline callers:
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff8116bcf6)
Location: kernel/sched/sched.h:1696
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:__cfsb_csd_unthrottle
```
```
In kernel/sched/build_policy.c (ffffffff81179f6c)
Location: kernel/sched/sched.h:1696
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
```
```
In kernel/sched/build_utility.c (ffffffff81199dae)
Location: kernel/sched/sched.h:1696
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_memstall_enter
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
In kernel/sched/core.c (ffff800010138ec4)
Location: kernel/sched/sched.h:1212
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffff800010144f14)
Location: kernel/sched/sched.h:1212
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/psi.c (ffff800010167868)
Location: kernel/sched/sched.h:1212
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (c038821c)
Location: kernel/sched/sched.h:1212
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (c0392820)
Location: kernel/sched/sched.h:1212
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/psi.c (c03b468c)
Location: kernel/sched/sched.h:1212
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (c000000000185414)
Location: kernel/sched/sched.h:1212
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (c000000000196054)
Location: kernel/sched/sched.h:1212
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/psi.c (c0000000001bf61c)
Location: kernel/sched/sched.h:1212
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffe0000e8c12)
Location: kernel/sched/sched.h:1212
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffe0000f18b8)
Location: kernel/sched/sched.h:1212
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/psi.c (ffffffe000109dd4)
Location: kernel/sched/sched.h:1212
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810d3151)
Location: kernel/sched/sched.h:1212
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff810df13b)
Location: kernel/sched/sched.h:1212
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/psi.c (ffffffff810fbd7e)
Location: kernel/sched/sched.h:1212
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810c177b)
Location: kernel/sched/sched.h:1212
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff810ce14b)
Location: kernel/sched/sched.h:1212
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/psi.c (ffffffff810ebf88)
Location: kernel/sched/sched.h:1212
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810d0831)
Location: kernel/sched/sched.h:1212
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff810db4bb)
Location: kernel/sched/sched.h:1212
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/psi.c (ffffffff810f8f3e)
Location: kernel/sched/sched.h:1212
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff810da8a1)
Location: kernel/sched/sched.h:1212
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
```
```
In kernel/sched/fair.c (ffffffff810e71ab)
Location: kernel/sched/sched.h:1212
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/psi.c (ffffffff8110407e)
Location: kernel/sched/sched.h:1212
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
</details>
</li>
</ul>

## Differences
