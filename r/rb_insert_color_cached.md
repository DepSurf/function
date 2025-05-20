# Function: <code>rb_insert_color_cached</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rb_insert_color_cached(struct rb_node *node, struct rb_root_cached *root, bool leftmost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81979ce0)
Location: lib/rbtree.c:466
Inline: False
Direct callers:
  - kernel/sched/fair.c:__enqueue_entity
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - fs/eventpoll.c:SyS_epoll_ctl
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_group_service_tree_add
```
**Symbols:**

```
ffffffff81979ce0-ffffffff81979e78: rb_insert_color_cached (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rb_insert_color_cached(struct rb_node *node, struct rb_root_cached *root, bool leftmost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff819d5f40)
Location: lib/rbtree.c:466
Inline: False
Direct callers:
  - kernel/sched/fair.c:__enqueue_entity
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - fs/eventpoll.c:ep_insert
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_group_service_tree_add
```
**Symbols:**

```
ffffffff819d5f40-ffffffff819d6095: rb_insert_color_cached (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rb_insert_color_cached(struct rb_node *node, struct rb_root_cached *root, bool leftmost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a0e170)
Location: lib/rbtree.c:466
Inline: False
Direct callers:
  - kernel/sched/fair.c:__enqueue_entity
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - fs/eventpoll.c:ep_insert
```
**Symbols:**

```
ffffffff81a0e170-ffffffff81a0e2c5: rb_insert_color_cached (STB_GLOBAL)
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
In kernel/sched/fair.c (ffffffff810d6359)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff810e764e)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
```
In kernel/locking/rtmutex.c (ffffffff810f93ad)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In fs/eventpoll.c (ffffffff81320dc9)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In block/blk-throttle.c (ffffffff814f2b07)
Location: include/linux/rbtree.h:135
Inline: True
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
In kernel/sched/fair.c (ffffffff810e09d9)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff810f2c6e)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
```
In kernel/locking/rtmutex.c (ffffffff8110519d)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In fs/eventpoll.c (ffffffff81333b69)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In block/blk-throttle.c (ffffffff8150c087)
Location: include/linux/rbtree.h:135
Inline: True
```
```
In lib/timerqueue.c (ffffffff81ab8c9b)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In kernel/sched/fair.c (ffffffff810f104c)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff810fa0b5)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
```
```
In kernel/locking/rtmutex.c (ffffffff8110ff90)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In fs/eventpoll.c (ffffffff8136e071)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In block/blk-throttle.c (ffffffff8156d455)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - block/blk-throttle.c:__throtl_enqueue_tg
```
```
In lib/timerqueue.c (ffffffff815f394b)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In kernel/sched/fair.c (ffffffff810efccc)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff810f84a7)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
```
```
In kernel/locking/rtmutex.c (ffffffff8110d140)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In fs/eventpoll.c (ffffffff8137b2dd)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In block/blk-throttle.c (ffffffff81587d05)
Location: include/linux/rbtree.h:135
Inline: True
```
```
In lib/timerqueue.c (ffffffff81617fcb)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In kernel/sched/fair.c (ffffffff810f16fe)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff810fa627)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
```
```
In kernel/locking/rtmutex.c (ffffffff81c36f66)
Location: include/linux/rbtree.h:135
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
In fs/eventpoll.c (ffffffff8138309a)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In block/blk-throttle.c (ffffffff8158eb55)
Location: include/linux/rbtree.h:135
Inline: True
```
```
In lib/timerqueue.c (ffffffff815fb5ee)
Location: include/linux/rbtree.h:135
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
In kernel/sched/fair.c (ffffffff8110b23c)
Location: include/linux/rbtree.h:108
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff81115356)
Location: include/linux/rbtree.h:108
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
```
```
In kernel/locking/rtmutex_api.c (ffffffff81d554d6)
Location: include/linux/rbtree.h:108
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In fs/eventpoll.c (ffffffff813d031b)
Location: include/linux/rbtree.h:108
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In block/blk-throttle.c (ffffffff815f4bb5)
Location: include/linux/rbtree.h:108
Inline: True
```
```
In lib/timerqueue.c (ffffffff81668ebe)
Location: include/linux/rbtree.h:108
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
In kernel/sched/fair.c (ffffffff81126bc3)
Location: include/linux/rbtree.h:108
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/build_policy.c (ffffffff81135104)
Location: include/linux/rbtree.h:108
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
```
```
In kernel/locking/rtmutex_api.c (ffffffff81f2714b)
Location: include/linux/rbtree.h:108
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In fs/eventpoll.c (ffffffff81458a66)
Location: include/linux/rbtree.h:108
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In block/blk-throttle.c (ffffffff816a65e5)
Location: include/linux/rbtree.h:108
Inline: True
```
```
In lib/timerqueue.c (ffffffff817828f9)
Location: include/linux/rbtree.h:108
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
In kernel/sched/fair.c (ffffffff81150166)
Location: include/linux/rbtree.h:108
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/build_policy.c (ffffffff8115f654)
Location: include/linux/rbtree.h:108
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
```
```
In kernel/locking/rtmutex_api.c (ffffffff820d2c0b)
Location: include/linux/rbtree.h:108
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In fs/eventpoll.c (ffffffff814e7596)
Location: include/linux/rbtree.h:108
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In block/blk-throttle.c (ffffffff81764b83)
Location: include/linux/rbtree.h:108
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_service_queue_add
```
```
In lib/timerqueue.c (ffffffff8203f829)
Location: include/linux/rbtree.h:108
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
In kernel/sched/fair.c (ffffffff8115efd7)
Location: include/linux/rbtree.h:108
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/build_policy.c (ffffffff8116fdcd)
Location: include/linux/rbtree.h:108
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
```
```
In kernel/locking/rtmutex_api.c (ffffffff82156f70)
Location: include/linux/rbtree.h:108
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/bpf/helpers.c (ffffffff8132129f)
Location: include/linux/rbtree.h:108
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_rbtree_add_impl
```
```
In fs/eventpoll.c (ffffffff8151f3bd)
Location: include/linux/rbtree.h:108
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In block/blk-throttle.c (ffffffff817a3c63)
Location: include/linux/rbtree.h:108
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_service_queue_add
```
```
In lib/timerqueue.c (ffffffff820bdd49)
Location: include/linux/rbtree.h:108
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
In kernel/sched/build_policy.c (ffffffff8117d3bb)
Location: include/linux/rbtree.h:108
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
```
```
In kernel/locking/rtmutex_api.c (ffffffff82239db0)
Location: include/linux/rbtree.h:108
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/bpf/helpers.c (ffffffff81343922)
Location: include/linux/rbtree.h:108
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_rbtree_add_impl
```
```
In fs/eventpoll.c (ffffffff815539cd)
Location: include/linux/rbtree.h:108
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In block/blk-throttle.c (ffffffff817e77d3)
Location: include/linux/rbtree.h:108
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_service_queue_add
```
```
In drivers/gpu/drm/drm_mm.c (ffffffff81ca1087)
Location: include/linux/rbtree.h:108
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mm.c:add_hole
```
```
In lib/timerqueue.c (ffffffff821985c9)
Location: include/linux/rbtree.h:108
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff800010140830)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/deadline.c (ffff800010154ee0)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
```
In kernel/locking/rtmutex.c (ffff80001016ae2c)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In fs/eventpoll.c (ffff8000103f1904)
Location: include/linux/rbtree.h:135
Inline: True
```
```
In block/blk-throttle.c (ffff80001060fc58)
Location: include/linux/rbtree.h:135
Inline: True
```
```
In lib/timerqueue.c (ffff800010d93284)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In kernel/sched/fair.c (c0390e64)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/deadline.c (c03a2348)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
```
```
In kernel/locking/rtmutex.c (c03b698c)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In fs/eventpoll.c (c05c72dc)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In block/blk-throttle.c (c07ba35c)
Location: include/linux/rbtree.h:135
Inline: True
```
```
In lib/timerqueue.c (c0e8fa0c)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In kernel/sched/fair.c (c0000000001906d8)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/deadline.c (c0000000001a8da0)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_pushable_dl_task
```
```
In kernel/locking/rtmutex.c (c0000000001c271c)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In fs/eventpoll.c (c0000000004f9180)
Location: include/linux/rbtree.h:135
Inline: True
```
```
In block/blk-throttle.c (c0000000007ad198)
Location: include/linux/rbtree.h:135
Inline: True
```
```
In lib/timerqueue.c (c000000000ed74d8)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In kernel/sched/fair.c (ffffffe0000eed7a)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffe0000fc98c)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
```
In kernel/locking/rtmutex.c (ffffffe00010b482)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In fs/eventpoll.c (ffffffe0002a4216)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In block/blk-throttle.c (ffffffe000447b16)
Location: include/linux/rbtree.h:135
Inline: True
```
```
In lib/timerqueue.c (ffffffe0008bd44a)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In kernel/sched/fair.c (ffffffff810dab89)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff810ec06e)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
```
In kernel/locking/rtmutex.c (ffffffff810fe4ad)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In fs/eventpoll.c (ffffffff8132c149)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In block/blk-throttle.c (ffffffff81504667)
Location: include/linux/rbtree.h:135
Inline: True
```
```
In lib/timerqueue.c (ffffffff81a57aeb)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In kernel/sched/fair.c (ffffffff810c9b99)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff810dc08e)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
```
In kernel/locking/rtmutex.c (ffffffff810ee6ad)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In fs/eventpoll.c (ffffffff8131d4b9)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In block/blk-throttle.c (ffffffff814f4b27)
Location: include/linux/rbtree.h:135
Inline: True
```
```
In lib/timerqueue.c (ffffffff81a14bcb)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In kernel/sched/fair.c (ffffffff810d6f09)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff810e919e)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
```
In kernel/locking/rtmutex.c (ffffffff810fb66d)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In fs/eventpoll.c (ffffffff81329c19)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In block/blk-throttle.c (ffffffff815006f7)
Location: include/linux/rbtree.h:135
Inline: True
```
```
In lib/timerqueue.c (ffffffff81ac3edb)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
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
In kernel/sched/fair.c (ffffffff810e28b9)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffff810f414e)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
```
```
In kernel/locking/rtmutex.c (ffffffff8110683d)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In fs/eventpoll.c (ffffffff8133c5c5)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In block/blk-throttle.c (ffffffff81519707)
Location: include/linux/rbtree.h:135
Inline: True
```
```
In lib/timerqueue.c (ffffffff81ad03ab)
Location: include/linux/rbtree.h:135
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_add
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
