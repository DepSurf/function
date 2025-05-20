# Function: <code>is_migration_disabled</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dc7db)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
```
```
In kernel/sched/rt.c (ffffffff810f7939)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810fb8a6)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
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
In kernel/sched/core.c (ffffffff810de3c6)
Location: kernel/sched/sched.h:1107
Inline: True
Inline callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:is_cpu_allowed
```
```
In kernel/sched/rt.c (ffffffff810f96e3)
Location: kernel/sched/sched.h:1107
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810fdbc5)
Location: kernel/sched/sched.h:1107
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
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
In kernel/sched/core.c (ffffffff810f2808)
Location: kernel/sched/sched.h:1143
Inline: True
Inline callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
```
```
In kernel/sched/rt.c (ffffffff81112ed3)
Location: kernel/sched/sched.h:1143
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/deadline.c (ffffffff811160dc)
Location: kernel/sched/sched.h:1143
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
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
In kernel/sched/core.c (ffffffff8110e734)
Location: kernel/sched/sched.h:1140
Inline: True
Inline callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
```
```
In kernel/sched/build_policy.c (ffffffff8112fd2c)
Location: kernel/sched/sched.h:1140
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
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
In kernel/sched/core.c (ffffffff811354d4)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
```
```
In kernel/sched/build_policy.c (ffffffff81159df0)
Location: kernel/sched/sched.h:1186
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
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
In kernel/sched/core.c (ffffffff81144654)
Location: kernel/sched/sched.h:1193
Inline: True
Inline callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
```
```
In kernel/sched/build_policy.c (ffffffff8116a000)
Location: kernel/sched/sched.h:1193
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:find_lock_lowest_rq
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
In kernel/sched/core.c (ffffffff8114fb78)
Location: kernel/sched/sched.h:1211
Inline: True
Inline callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
```
```
In kernel/sched/build_policy.c (ffffffff811776b4)
Location: kernel/sched/sched.h:1211
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:find_lock_lowest_rq
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
