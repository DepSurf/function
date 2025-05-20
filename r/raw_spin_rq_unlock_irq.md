# Function: <code>raw_spin_rq_unlock_irq</code>

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
In kernel/sched/core.c (ffffffff810f2d2d)
Location: kernel/sched/sched.h:1327
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_core_balance
```
```
In kernel/sched/idle.c (ffffffff810ff37e)
Location: kernel/sched/sched.h:1327
Inline: True
Inline callers:
  - kernel/sched/idle.c:dequeue_task_idle
```
```
In kernel/sched/fair.c (ffffffff81110ebe)
Location: kernel/sched/sched.h:1327
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
```
```
In kernel/sched/psi.c (ffffffff8112ba74)
Location: kernel/sched/sched.h:1327
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
In kernel/sched/core.c (ffffffff8110eae9)
Location: kernel/sched/sched.h:1313
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_core_balance
```
```
In kernel/sched/fair.c (ffffffff8112d0eb)
Location: kernel/sched/sched.h:1313
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
```
```
In kernel/sched/build_policy.c (ffffffff8112e085)
Location: kernel/sched/sched.h:1313
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_task_idle
```
```
In kernel/sched/build_utility.c (ffffffff8114c221)
Location: kernel/sched/sched.h:1313
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
In kernel/sched/core.c (ffffffff811358a5)
Location: kernel/sched/sched.h:1367
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_core_balance
```
```
In kernel/sched/fair.c (ffffffff81156e5a)
Location: kernel/sched/sched.h:1367
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
```
```
In kernel/sched/build_policy.c (ffffffff81157f75)
Location: kernel/sched/sched.h:1367
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_task_idle
```
```
In kernel/sched/build_utility.c (ffffffff8117b07f)
Location: kernel/sched/sched.h:1367
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_restart
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
In kernel/sched/core.c (ffffffff81144a07)
Location: kernel/sched/sched.h:1375
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_core_balance
```
```
In kernel/sched/fair.c (ffffffff81166f09)
Location: kernel/sched/sched.h:1375
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
```
```
In kernel/sched/build_policy.c (ffffffff81168075)
Location: kernel/sched/sched.h:1375
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_task_idle
```
```
In kernel/sched/build_utility.c (ffffffff8118bbbd)
Location: kernel/sched/sched.h:1375
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_restart
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
In kernel/sched/core.c (ffffffff8114ff55)
Location: kernel/sched/sched.h:1394
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:sched_tick_remote
```
```
In kernel/sched/fair.c (ffffffff81173c89)
Location: kernel/sched/sched.h:1394
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
```
```
In kernel/sched/build_policy.c (ffffffff81174e25)
Location: kernel/sched/sched.h:1394
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_task_idle
```
```
In kernel/sched/build_utility.c (ffffffff8119a51d)
Location: kernel/sched/sched.h:1394
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:psi_memstall_enter
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
