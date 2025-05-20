# Function: <code>dl_time_before</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/linux/sched/deadline.h:24
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched/deadline.h:24
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/sched/deadline.h:24
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/sched/deadline.h:24
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/linux/sched/deadline.h:24
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched/deadline.h:24
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/sched/deadline.h:24
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/sched/deadline.h:24
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/linux/sched/deadline.h:24
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/sched/deadline.h:24
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/sched/deadline.h:24
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/sched/deadline.h:24
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/linux/sched/deadline.h:26
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810c79c7)
Location: include/linux/sched/deadline.h:26
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/sched/deadline.h:26
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/sched/deadline.h:26
Inline: True
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
Location: include/linux/sched/deadline.h:27
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810cef95)
Location: include/linux/sched/deadline.h:27
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/linux/sched/deadline.h:27
Inline: True
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/sched/deadline.h:27
Inline: True
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
In kernel/sched/core.c (ffffffff810c13ab)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (ffffffff810d5e1d)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:replenish_dl_entity
```
```
In kernel/sched/cpudeadline.c (ffffffff810da480)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
```
In kernel/locking/rtmutex.c (ffffffff810e5706)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/sched/core.c (ffffffff810ca716)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (ffffffff810dfced)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:replenish_dl_entity
```
```
In kernel/sched/cpudeadline.c (ffffffff810e3fd0)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
```
In kernel/locking/rtmutex.c (ffffffff810f0c96)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/sched/core.c (ffffffff810d23c8)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (ffffffff810e6724)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
```
```
In kernel/sched/cpudeadline.c (ffffffff810eabc9)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
```
In kernel/locking/rtmutex.c (ffffffff810f93bf)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/sched/core.c (ffffffff810dc672)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (ffffffff810f1fb2)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
```
```
In kernel/sched/cpudeadline.c (ffffffff810f6593)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
```
In kernel/locking/rtmutex.c (ffffffff811051af)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/sched/core.c (ffffffff810e5405)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (ffffffff810fd262)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:update_dl_entity
  - kernel/sched/deadline.c:update_dl_entity
  - kernel/sched/deadline.c:update_dl_entity
  - kernel/sched/deadline.c:update_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
```
```
In kernel/sched/cpudeadline.c (ffffffff810fff1c)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify_up
  - kernel/sched/cpudeadline.c:cpudl_heapify_down
  - kernel/sched/cpudeadline.c:cpudl_heapify_down
```
```
In kernel/locking/rtmutex.c (ffffffff8110ffa2)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/sched/core.c (ffffffff810e2eb4)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (ffffffff810fb770)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:update_dl_entity
  - kernel/sched/deadline.c:update_dl_entity
  - kernel/sched/deadline.c:update_dl_entity
  - kernel/sched/deadline.c:update_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
```
```
In kernel/sched/cpudeadline.c (ffffffff810fe9d0)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify_up
  - kernel/sched/cpudeadline.c:cpudl_heapify_down
  - kernel/sched/cpudeadline.c:cpudl_heapify_down
```
```
In kernel/locking/rtmutex.c (ffffffff8110d152)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/sched/core.c (ffffffff810e4d7f)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (ffffffff810fda8f)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
```
```
In kernel/sched/cpudeadline.c (ffffffff81100d99)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify_up
```
```
In kernel/locking/rtmutex.c (ffffffff81c37050)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
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
In kernel/sched/core.c (ffffffff810fbc5f)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
```
```
In kernel/sched/deadline.c (ffffffff81115f41)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
```
```
In kernel/sched/cpudeadline.c (ffffffff8111cf09)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify_up
```
```
In kernel/locking/rtmutex_api.c (ffffffff81d555a4)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
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
In kernel/sched/core.c (ffffffff811180f6)
Location: include/linux/sched/deadline.h:25
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:pick_next_task
```
```
In kernel/sched/build_policy.c (ffffffff8112fbbf)
Location: include/linux/sched/deadline.h:25
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:check_preempt_curr_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:replenish_dl_entity
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:cpudl_heapify
  - kernel/sched/build_policy.c:cpudl_heapify
  - kernel/sched/build_policy.c:cpudl_heapify
  - kernel/sched/build_policy.c:cpudl_heapify_up
```
```
In kernel/locking/rtmutex_api.c (ffffffff81f27229)
Location: include/linux/sched/deadline.h:25
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
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
In kernel/sched/core.c (ffffffff8113f731)
Location: include/linux/sched/deadline.h:25
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:pick_next_task
```
```
In kernel/sched/build_policy.c (ffffffff81159c85)
Location: include/linux/sched/deadline.h:25
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:check_preempt_curr_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:replenish_dl_entity
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:cpudl_heapify
  - kernel/sched/build_policy.c:cpudl_heapify
  - kernel/sched/build_policy.c:cpudl_heapify
  - kernel/sched/build_policy.c:cpudl_heapify_up
```
```
In kernel/locking/rtmutex_api.c (ffffffff820d2ce9)
Location: include/linux/sched/deadline.h:25
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
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
In kernel/sched/core.c (ffffffff8114bc83)
Location: include/linux/sched/deadline.h:25
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:pick_next_task
```
```
In kernel/sched/build_policy.c (ffffffff81169e95)
Location: include/linux/sched/deadline.h:25
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:check_preempt_curr_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:replenish_dl_entity
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:cpudl_heapify
  - kernel/sched/build_policy.c:cpudl_heapify
  - kernel/sched/build_policy.c:cpudl_heapify
  - kernel/sched/build_policy.c:cpudl_heapify_up
```
```
In kernel/locking/rtmutex_api.c (ffffffff8215704a)
Location: include/linux/sched/deadline.h:25
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
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
In kernel/sched/core.c (ffffffff81157a33)
Location: include/linux/sched/deadline.h:27
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:pick_next_task
```
```
In kernel/sched/build_policy.c (ffffffff81177535)
Location: include/linux/sched/deadline.h:27
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:wakeup_preempt_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:dl_server_start
  - kernel/sched/build_policy.c:replenish_dl_entity
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:cpudl_heapify
  - kernel/sched/build_policy.c:cpudl_heapify
  - kernel/sched/build_policy.c:cpudl_heapify
  - kernel/sched/build_policy.c:cpudl_heapify_up
```
```
In kernel/locking/rtmutex_api.c (ffffffff82239e8a)
Location: include/linux/sched/deadline.h:27
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
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
In kernel/sched/core.c (ffff80001013c350)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (ffff800010153b10)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
```
```
In kernel/sched/cpudeadline.c (ffff80001015a438)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
```
In kernel/locking/rtmutex.c (ffff80001016ae40)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/sched/core.c (c038be1c)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (c039fe30)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
```
```
In kernel/sched/cpudeadline.c (c03a7208)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify_up
```
```
In kernel/locking/rtmutex.c (c03b6998)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/sched/core.c (c00000000018a7dc)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (c0000000001a6964)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
```
```
In kernel/sched/cpudeadline.c (c0000000001ae700)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify_up
```
```
In kernel/locking/rtmutex.c (c0000000001c2740)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/sched/core.c (ffffffe0000eb71a)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (ffffffe0000fb86c)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
```
```
In kernel/sched/cpudeadline.c (ffffffe0000ffdf2)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify_up
```
```
In kernel/locking/rtmutex.c (ffffffe00010b49a)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/sched/core.c (ffffffff810d68a8)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (ffffffff810eb3b2)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
```
```
In kernel/sched/cpudeadline.c (ffffffff810ef993)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
```
In kernel/locking/rtmutex.c (ffffffff810fe4bf)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/sched/core.c (ffffffff810c5172)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (ffffffff810db3d2)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
```
```
In kernel/sched/cpudeadline.c (ffffffff810dfa03)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
```
In kernel/locking/rtmutex.c (ffffffff810ee6bf)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/sched/core.c (ffffffff810d3674)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (ffffffff810e84e2)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
```
```
In kernel/sched/cpudeadline.c (ffffffff810ecac3)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
```
In kernel/locking/rtmutex.c (ffffffff810fb67f)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
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
In kernel/sched/core.c (ffffffff810de440)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/deadline.c (ffffffff810f27e4)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:check_preempt_curr_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
```
```
In kernel/sched/cpudeadline.c (ffffffff810f7b03)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
  - kernel/sched/cpudeadline.c:cpudl_heapify
```
```
In kernel/locking/rtmutex.c (ffffffff8110684f)
Location: include/linux/sched/deadline.h:23
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
</details>
</li>
</ul>

## Differences
