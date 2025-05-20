# Function: <code>finish_rcuwait</code>

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
In kernel/workqueue.c (ffffffff810c8b29)
Location: include/linux/rcuwait.h:50
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110f464)
Location: include/linux/rcuwait.h:50
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
In kernel/workqueue.c (ffffffff810c3c89)
Location: include/linux/rcuwait.h:50
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
```
```
In kernel/sched/core.c (ffffffff810e42e2)
Location: include/linux/rcuwait.h:50
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_wait_empty
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110c624)
Location: include/linux/rcuwait.h:50
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
In kernel/workqueue.c (ffffffff810c54a6)
Location: include/linux/rcuwait.h:50
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
```
```
In kernel/sched/core.c (ffffffff810e62b3)
Location: include/linux/rcuwait.h:50
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_wait_empty
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110e45a)
Location: include/linux/rcuwait.h:50
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
In kernel/workqueue.c (ffffffff810d8086)
Location: include/linux/rcuwait.h:50
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
```
```
In kernel/sched/core.c (ffffffff810fd76f)
Location: include/linux/rcuwait.h:50
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_wait_empty
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8112db96)
Location: include/linux/rcuwait.h:50
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void finish_rcuwait(struct rcuwait *w);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81174214)
Location: kernel/rcu/update.c:410
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/sched/core.c:sched_cpu_wait_empty
  - kernel/locking/percpu-rwsem.c:percpu_down_write
```
**Symbols:**

```
ffffffff811723d0-ffffffff811723fa: finish_rcuwait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void finish_rcuwait(struct rcuwait *w);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811a9b84)
Location: kernel/rcu/update.c:410
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_one_gp
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/sched/core.c:sched_cpu_wait_empty
  - kernel/locking/percpu-rwsem.c:percpu_down_write
```
**Symbols:**

```
ffffffff811a8b80-ffffffff811a8baa: finish_rcuwait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void finish_rcuwait(struct rcuwait *w);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811bba74)
Location: kernel/rcu/update.c:449
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_one_gp
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/sched/core.c:sched_cpu_wait_empty
  - kernel/locking/percpu-rwsem.c:percpu_down_write
```
**Symbols:**

```
ffffffff811ba8d0-ffffffff811ba8fa: finish_rcuwait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void finish_rcuwait(struct rcuwait *w);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811cbf79)
Location: kernel/rcu/update.c:450
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_one_gp
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/sched/core.c:sched_cpu_wait_empty
  - kernel/locking/percpu-rwsem.c:percpu_down_write
```
**Symbols:**

```
ffffffff811ca800-ffffffff811ca82a: finish_rcuwait (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
