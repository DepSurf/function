# Function: <code>task_on_cpu</code>

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
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff820cd188)
Location: kernel/sched/sched.h:2071
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff8114e678)
Location: kernel/sched/sched.h:2071
Inline: True
Inline callers:
  - kernel/sched/fair.c:can_migrate_task
```
```
In kernel/sched/build_policy.c (ffffffff81159cdd)
Location: kernel/sched/sched.h:2071
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:find_lock_lowest_rq
```
```
In kernel/sched/build_utility.c (ffffffff81170d10)
Location: kernel/sched/sched.h:2071
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sched_core_set
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
In kernel/sched/core.c (ffffffff821515e2)
Location: kernel/sched/sched.h:2114
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
```
```
In kernel/sched/fair.c (ffffffff8115fc68)
Location: kernel/sched/sched.h:2114
Inline: True
Inline callers:
  - kernel/sched/fair.c:can_migrate_task
```
```
In kernel/sched/build_policy.c (ffffffff81169eed)
Location: kernel/sched/sched.h:2114
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:find_lock_lowest_rq
```
```
In kernel/sched/build_utility.c (ffffffff81180fde)
Location: kernel/sched/sched.h:2114
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sched_core_set
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
In kernel/sched/core.c (ffffffff8223435f)
Location: kernel/sched/sched.h:2156
Inline: True
Inline callers:
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
```
```
In kernel/sched/fair.c (ffffffff8116a098)
Location: kernel/sched/sched.h:2156
Inline: True
Inline callers:
  - kernel/sched/fair.c:can_migrate_task
```
```
In kernel/sched/build_policy.c (ffffffff8117758d)
Location: kernel/sched/sched.h:2156
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:find_lock_lowest_rq
```
```
In kernel/sched/build_utility.c (ffffffff8118f34e)
Location: kernel/sched/sched.h:2156
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sched_core_set
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
