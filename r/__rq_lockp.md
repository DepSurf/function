# Function: <code>__rq_lockp</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81d5208b)
Location: kernel/sched/sched.h:1180
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:double_rq_lock
  - kernel/sched/core.c:double_rq_lock
  - kernel/sched/core.c:raw_spin_rq_trylock
  - kernel/sched/core.c:raw_spin_rq_trylock
```
```
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:1180
Inline: True
```
```
In kernel/sched/rt.c (ffffffff81112de6)
Location: kernel/sched/sched.h:1180
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:find_lock_lowest_rq
  - kernel/sched/rt.c:find_lock_lowest_rq
  - kernel/sched/rt.c:find_lock_lowest_rq
  - kernel/sched/rt.c:find_lock_lowest_rq
  - kernel/sched/rt.c:find_lock_lowest_rq
  - kernel/sched/rt.c:find_lock_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffff81115f55)
Location: kernel/sched/sched.h:1180
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/stop_task.c (0)
Location: kernel/sched/sched.h:1180
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: kernel/sched/sched.h:1180
Inline: True
```
```
In kernel/sched/core_sched.c (0)
Location: kernel/sched/sched.h:1180
Inline: True
```
```
In kernel/livepatch/transition.c (0)
Location: kernel/sched/sched.h:1180
Inline: True
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
In kernel/sched/core.c (ffffffff81f22749)
Location: kernel/sched/sched.h:1177
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:double_rq_lock
  - kernel/sched/core.c:double_rq_lock
  - kernel/sched/core.c:raw_spin_rq_trylock
  - kernel/sched/core.c:raw_spin_rq_trylock
```
```
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:1177
Inline: True
```
```
In kernel/sched/build_policy.c (ffffffff8112fc58)
Location: kernel/sched/sched.h:1177
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:find_lock_lowest_rq
  - kernel/sched/build_policy.c:find_lock_lowest_rq
  - kernel/sched/build_policy.c:find_lock_lowest_rq
  - kernel/sched/build_policy.c:find_lock_lowest_rq
```
```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/sched.h:1177
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
In kernel/sched/core.c (ffffffff820cd059)
Location: kernel/sched/sched.h:1231
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:double_rq_lock
  - kernel/sched/core.c:double_rq_lock
  - kernel/sched/core.c:raw_spin_rq_trylock
  - kernel/sched/core.c:raw_spin_rq_trylock
```
```
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:1231
Inline: True
```
```
In kernel/sched/build_policy.c (ffffffff81159d1e)
Location: kernel/sched/sched.h:1231
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:find_lock_lowest_rq
  - kernel/sched/build_policy.c:find_lock_lowest_rq
  - kernel/sched/build_policy.c:find_lock_lowest_rq
  - kernel/sched/build_policy.c:find_lock_lowest_rq
```
```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/sched.h:1231
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
In kernel/sched/core.c (ffffffff82151459)
Location: kernel/sched/sched.h:1238
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:double_rq_lock
  - kernel/sched/core.c:double_rq_lock
  - kernel/sched/core.c:raw_spin_rq_trylock
  - kernel/sched/core.c:raw_spin_rq_trylock
```
```
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:1238
Inline: True
```
```
In kernel/sched/build_policy.c (ffffffff81169f2e)
Location: kernel/sched/sched.h:1238
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:find_lock_lowest_rq
  - kernel/sched/build_policy.c:find_lock_lowest_rq
  - kernel/sched/build_policy.c:find_lock_lowest_rq
  - kernel/sched/build_policy.c:find_lock_lowest_rq
```
```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/sched.h:1238
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
In kernel/sched/core.c (ffffffff82234271)
Location: kernel/sched/sched.h:1256
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:double_rq_lock
  - kernel/sched/core.c:double_rq_lock
  - kernel/sched/core.c:raw_spin_rq_trylock
  - kernel/sched/core.c:raw_spin_rq_trylock
```
```
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:1256
Inline: True
```
```
In kernel/sched/build_policy.c (ffffffff811775ce)
Location: kernel/sched/sched.h:1256
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:find_lock_lowest_rq
  - kernel/sched/build_policy.c:find_lock_lowest_rq
  - kernel/sched/build_policy.c:find_lock_lowest_rq
  - kernel/sched/build_policy.c:find_lock_lowest_rq
```
```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/sched.h:1256
Inline: True
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
