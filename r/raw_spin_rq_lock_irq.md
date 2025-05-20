# Function: <code>raw_spin_rq_lock_irq</code>

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
In kernel/sched/core.c (ffffffff810f2d6f)
Location: kernel/sched/sched.h:1321
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_core_balance
```
```
In kernel/sched/idle.c (ffffffff810ff39b)
Location: kernel/sched/sched.h:1321
Inline: True
Inline callers:
  - kernel/sched/idle.c:dequeue_task_idle
```
```
In kernel/sched/fair.c (ffffffff81110e66)
Location: kernel/sched/sched.h:1321
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:active_load_balance_cpu_stop
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
In kernel/sched/core.c (ffffffff8110eb2a)
Location: kernel/sched/sched.h:1307
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_core_balance
```
```
In kernel/sched/fair.c (ffffffff8112d085)
Location: kernel/sched/sched.h:1307
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
```
In kernel/sched/build_policy.c (ffffffff8112e0a9)
Location: kernel/sched/sched.h:1307
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_task_idle
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
In kernel/sched/core.c (ffffffff811358f0)
Location: kernel/sched/sched.h:1361
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_core_balance
```
```
In kernel/sched/fair.c (ffffffff81156df1)
Location: kernel/sched/sched.h:1361
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
```
In kernel/sched/build_policy.c (ffffffff81157f99)
Location: kernel/sched/sched.h:1361
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_task_idle
```
```
In kernel/sched/build_utility.c (ffffffff8117b020)
Location: kernel/sched/sched.h:1361
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_restart
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
In kernel/sched/core.c (ffffffff81144a57)
Location: kernel/sched/sched.h:1369
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_core_balance
```
```
In kernel/sched/fair.c (ffffffff81166eb1)
Location: kernel/sched/sched.h:1369
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
```
In kernel/sched/build_policy.c (ffffffff81168099)
Location: kernel/sched/sched.h:1369
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_task_idle
```
```
In kernel/sched/build_utility.c (ffffffff8118bb5e)
Location: kernel/sched/sched.h:1369
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_restart
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
In kernel/sched/core.c (ffffffff8114ffa5)
Location: kernel/sched/sched.h:1388
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:sched_tick_remote
```
```
In kernel/sched/fair.c (ffffffff81173c31)
Location: kernel/sched/sched.h:1388
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
```
In kernel/sched/build_policy.c (ffffffff81174e49)
Location: kernel/sched/sched.h:1388
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_task_idle
```
```
In kernel/sched/build_utility.c (ffffffff8119a4be)
Location: kernel/sched/sched.h:1388
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_restart
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
