# Function: <code>prepare_to_rcuwait</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c8aea)
Location: include/linux/rcuwait.h:45
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110f3fd)
Location: include/linux/rcuwait.h:45
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
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
In kernel/workqueue.c (ffffffff810c3c4a)
Location: include/linux/rcuwait.h:45
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
```
```
In kernel/sched/core.c (ffffffff810e429f)
Location: include/linux/rcuwait.h:45
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_wait_empty
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110c5bd)
Location: include/linux/rcuwait.h:45
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
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
In kernel/workqueue.c (ffffffff810c546a)
Location: include/linux/rcuwait.h:45
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
```
```
In kernel/sched/core.c (ffffffff810e626f)
Location: include/linux/rcuwait.h:45
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_wait_empty
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110e3f3)
Location: include/linux/rcuwait.h:45
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
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
In kernel/workqueue.c (ffffffff810d805a)
Location: include/linux/rcuwait.h:45
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
```
```
In kernel/sched/core.c (ffffffff810fd73b)
Location: include/linux/rcuwait.h:45
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_wait_empty
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8112db33)
Location: include/linux/rcuwait.h:45
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
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
In kernel/workqueue.c (ffffffff810ee928)
Location: include/linux/rcuwait.h:45
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
```
```
In kernel/sched/core.c (ffffffff8111a15b)
Location: include/linux/rcuwait.h:45
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_wait_empty
```
```
In kernel/locking/percpu-rwsem.c (ffffffff81f25e08)
Location: include/linux/rcuwait.h:45
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
```
```
In kernel/rcu/update.c (ffffffff811741f7)
Location: include/linux/rcuwait.h:45
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/irq_work.c (ffffffff81269373)
Location: include/linux/rcuwait.h:45
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
In kernel/workqueue.c (ffffffff8110ffd8)
Location: include/linux/rcuwait.h:45
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
```
```
In kernel/sched/core.c (ffffffff811418ab)
Location: include/linux/rcuwait.h:45
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_wait_empty
```
```
In kernel/locking/percpu-rwsem.c (ffffffff820d187a)
Location: include/linux/rcuwait.h:45
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
```
```
In kernel/rcu/update.c (ffffffff811a9b65)
Location: include/linux/rcuwait.h:45
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_one_gp
```
```
In kernel/irq_work.c (ffffffff812be1b3)
Location: include/linux/rcuwait.h:45
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
In kernel/workqueue.c (ffffffff81120b6a)
Location: include/linux/rcuwait.h:45
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
```
```
In kernel/sched/core.c (ffffffff8114d55b)
Location: include/linux/rcuwait.h:45
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_wait_empty
```
```
In kernel/locking/percpu-rwsem.c (ffffffff82155bea)
Location: include/linux/rcuwait.h:45
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
```
```
In kernel/rcu/update.c (ffffffff811bba55)
Location: include/linux/rcuwait.h:45
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_one_gp
```
```
In kernel/irq_work.c (ffffffff812e4d73)
Location: include/linux/rcuwait.h:45
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
In kernel/workqueue.c (ffffffff8112a41a)
Location: include/linux/rcuwait.h:45
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
```
```
In kernel/sched/core.c (ffffffff8115930b)
Location: include/linux/rcuwait.h:45
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_wait_empty
```
```
In kernel/locking/percpu-rwsem.c (ffffffff82238a2a)
Location: include/linux/rcuwait.h:45
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
```
```
In kernel/rcu/update.c (ffffffff811cbf41)
Location: include/linux/rcuwait.h:45
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_one_gp
```
```
In kernel/irq_work.c (ffffffff81302e23)
Location: include/linux/rcuwait.h:45
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
