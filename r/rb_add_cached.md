# Function: <code>rb_add_cached</code>

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
In kernel/sched/fair.c (ffffffff810f16b4)
Location: include/linux/rbtree.h:192
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff810fa2d6)
Location: include/linux/rbtree.h:192
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
```
```
In kernel/locking/rtmutex.c (ffffffff81c36f07)
Location: include/linux/rbtree.h:192
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In lib/timerqueue.c (ffffffff815fb5a4)
Location: include/linux/rbtree.h:192
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In kernel/sched/fair.c (ffffffff8110b1f2)
Location: include/linux/rbtree.h:165
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff81115146)
Location: include/linux/rbtree.h:165
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
```
```
In kernel/locking/rtmutex_api.c (ffffffff81d55477)
Location: include/linux/rbtree.h:165
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In lib/timerqueue.c (ffffffff81668e74)
Location: include/linux/rbtree.h:165
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In kernel/sched/fair.c (ffffffff81126b7d)
Location: include/linux/rbtree.h:165
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/build_policy.c (ffffffff8112e4d6)
Location: include/linux/rbtree.h:165
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
```
```
In kernel/locking/rtmutex_api.c (ffffffff81f270ed)
Location: include/linux/rbtree.h:165
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In lib/timerqueue.c (ffffffff817828b3)
Location: include/linux/rbtree.h:165
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In kernel/sched/fair.c (ffffffff81150120)
Location: include/linux/rbtree.h:165
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/build_policy.c (ffffffff81158418)
Location: include/linux/rbtree.h:165
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
```
```
In kernel/locking/rtmutex_api.c (ffffffff820d2bad)
Location: include/linux/rbtree.h:165
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In lib/timerqueue.c (ffffffff8203f7e3)
Location: include/linux/rbtree.h:165
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In kernel/sched/fair.c (ffffffff8115ef8c)
Location: include/linux/rbtree.h:165
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/build_policy.c (ffffffff81168538)
Location: include/linux/rbtree.h:165
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
```
```
In kernel/locking/rtmutex_api.c (ffffffff82156f12)
Location: include/linux/rbtree.h:165
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In lib/timerqueue.c (ffffffff820bdd03)
Location: include/linux/rbtree.h:165
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In kernel/sched/build_policy.c (ffffffff8117d366)
Location: include/linux/rbtree.h:165
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
```
```
In kernel/locking/rtmutex_api.c (ffffffff82239d52)
Location: include/linux/rbtree.h:165
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In lib/timerqueue.c (ffffffff82198583)
Location: include/linux/rbtree.h:165
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
