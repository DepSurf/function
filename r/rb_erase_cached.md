# Function: <code>rb_erase_cached</code>

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
void rb_erase_cached(struct rb_node *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff8197a120)
Location: lib/rbtree.c:474
Inline: False
Direct callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_remove
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
  - block/cfq-iosched.c:cfq_rb_erase
```
**Symbols:**

```
ffffffff8197a120-ffffffff8197a4c7: rb_erase_cached (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rb_erase_cached(struct rb_node *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff819d66d0)
Location: lib/rbtree.c:474
Inline: False
Direct callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - block/cfq-iosched.c:cfq_rb_erase
```
**Symbols:**

```
ffffffff819d66d0-ffffffff819d6a6a: rb_erase_cached (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rb_erase_cached(struct rb_node *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a0e900)
Location: lib/rbtree.c:474
Inline: False
Direct callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
**Symbols:**

```
ffffffff81a0e900-ffffffff81a0ec9a: rb_erase_cached (STB_GLOBAL)
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
In kernel/sched/fair.c (ffffffff810dbce5)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffff810e5a3c)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
```
```
In kernel/locking/rtmutex.c (ffffffff810f9e87)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In fs/eventpoll.c (ffffffff81320e96)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In block/blk-throttle.c (ffffffff814f2a52)
Location: include/linux/rbtree.h:144
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
In kernel/sched/fair.c (ffffffff810e7815)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffff810f0e5c)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
```
```
In kernel/locking/rtmutex.c (ffffffff81105c77)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In fs/eventpoll.c (ffffffff81333c36)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In block/blk-throttle.c (ffffffff8150bfd2)
Location: include/linux/rbtree.h:144
Inline: True
```
```
In lib/timerqueue.c (ffffffff81ab8d22)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_del
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
In kernel/sched/fair.c (ffffffff810f2995)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffff810f9f4c)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
```
```
In kernel/locking/rtmutex.c (ffffffff81110b97)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In fs/eventpoll.c (ffffffff8136e145)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In block/blk-throttle.c (ffffffff8156ecd1)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
```
```
In lib/timerqueue.c (ffffffff815f39c2)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_del
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
In kernel/sched/fair.c (ffffffff810f0b6d)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffff810f830c)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
```
```
In kernel/locking/rtmutex.c (ffffffff8110dd47)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In fs/eventpoll.c (ffffffff8137adfd)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In block/blk-throttle.c (ffffffff81589a81)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
```
```
In lib/timerqueue.c (ffffffff81618042)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_del
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
In kernel/sched/fair.c (ffffffff810f06a9)
Location: include/linux/rbtree.h:146
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffff810fd7aa)
Location: include/linux/rbtree.h:146
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/locking/rtmutex.c (ffffffff81c36e47)
Location: include/linux/rbtree.h:146
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In fs/eventpoll.c (ffffffff81381969)
Location: include/linux/rbtree.h:146
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In block/blk-throttle.c (ffffffff81590498)
Location: include/linux/rbtree.h:146
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
```
```
In lib/timerqueue.c (ffffffff815fb682)
Location: include/linux/rbtree.h:146
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_del
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
In kernel/sched/fair.c (ffffffff81109128)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffff81119bba)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/locking/rtmutex_api.c (ffffffff81d553b7)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In fs/eventpoll.c (ffffffff813ceba9)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In block/blk-throttle.c (ffffffff815f7423)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
```
```
In lib/timerqueue.c (ffffffff81668f52)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_del
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
In kernel/sched/fair.c (ffffffff81124e70)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/build_policy.c (ffffffff81135f90)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:__dequeue_dl_entity
```
```
In kernel/locking/rtmutex_api.c (ffffffff81f27013)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In fs/eventpoll.c (ffffffff814576d6)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In block/blk-throttle.c (ffffffff816aa1c0)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
```
```
In lib/timerqueue.c (ffffffff817829a2)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_del
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
In kernel/sched/fair.c (ffffffff8114d220)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/build_policy.c (ffffffff81160401)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:__dequeue_task_dl
```
```
In kernel/locking/rtmutex_api.c (ffffffff820d2ad3)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In fs/eventpoll.c (ffffffff814e6986)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In block/blk-throttle.c (ffffffff81768149)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_update_disptime
```
```
In lib/timerqueue.c (ffffffff8203f8f2)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_del
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
In kernel/sched/fair.c (ffffffff8115c97b)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/build_policy.c (ffffffff81170b21)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:__dequeue_task_dl
```
```
In kernel/locking/rtmutex_api.c (ffffffff82156e3a)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/bpf/helpers.c (ffffffff813211c7)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_rbtree_remove
```
```
In fs/eventpoll.c (ffffffff8151d598)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - fs/eventpoll.c:__ep_remove
```
```
In block/blk-throttle.c (ffffffff817a72a4)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_update_disptime
```
```
In lib/timerqueue.c (ffffffff820bde12)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_del
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
In kernel/sched/build_policy.c (ffffffff8117e41b)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__dequeue_dl_entity
```
```
In kernel/locking/rtmutex_api.c (ffffffff82239c7a)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/bpf/helpers.c (ffffffff81343843)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_rbtree_remove
```
```
In fs/eventpoll.c (ffffffff81551b78)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - fs/eventpoll.c:__ep_remove
```
```
In block/blk-throttle.c (ffffffff817eb021)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_update_disptime
```
```
In drivers/gpu/drm/drm_mm.c (ffffffff81ca158e)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mm.c:rm_hole
```
```
In lib/timerqueue.c (ffffffff82198692)
Location: include/linux/rbtree.h:119
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_del
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
In kernel/sched/fair.c (ffff800010145fe8)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffff800010152e58)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
```
```
In kernel/locking/rtmutex.c (ffff80001016bcfc)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In fs/eventpoll.c (ffff8000103f02a0)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In block/blk-throttle.c (ffff80001060fb90)
Location: include/linux/rbtree.h:144
Inline: True
```
```
In lib/timerqueue.c (ffff800010d93318)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_del
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
In kernel/sched/fair.c (c0393c6c)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (c039f85c)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
```
```
In kernel/locking/rtmutex.c (c03b770c)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In fs/eventpoll.c (c05c73d8)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In block/blk-throttle.c (c07ba294)
Location: include/linux/rbtree.h:144
Inline: True
```
```
In lib/timerqueue.c (c0e8fab8)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_del
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
In kernel/sched/fair.c (c0000000001970d8)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (c0000000001a6380)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
```
```
In kernel/locking/rtmutex.c (c0000000001c3810)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In fs/eventpoll.c (c0000000004f99f0)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In block/blk-throttle.c (c0000000007ad08c)
Location: include/linux/rbtree.h:144
Inline: True
```
```
In lib/timerqueue.c (c000000000ed75d0)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_del
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
In kernel/sched/fair.c (ffffffe0000f1008)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffe0000fa76c)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
```
```
In kernel/locking/rtmutex.c (ffffffe00010c026)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In fs/eventpoll.c (ffffffe0002a42d8)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In block/blk-throttle.c (ffffffe000447a6a)
Location: include/linux/rbtree.h:144
Inline: True
```
```
In lib/timerqueue.c (ffffffe0008bd4ae)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_del
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
In kernel/sched/fair.c (ffffffff810e19c5)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffff810ea25c)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
```
```
In kernel/locking/rtmutex.c (ffffffff810fef87)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In fs/eventpoll.c (ffffffff8132c216)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In block/blk-throttle.c (ffffffff815045b2)
Location: include/linux/rbtree.h:144
Inline: True
```
```
In lib/timerqueue.c (ffffffff81a57b72)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_del
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
In kernel/sched/fair.c (ffffffff810d0aa5)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffff810da21e)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
```
```
In kernel/locking/rtmutex.c (ffffffff810ef177)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In fs/eventpoll.c (ffffffff8131d586)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In block/blk-throttle.c (ffffffff814f4a72)
Location: include/linux/rbtree.h:144
Inline: True
```
```
In lib/timerqueue.c (ffffffff81a14c52)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_del
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
In kernel/sched/fair.c (ffffffff810ddd45)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffff810e738c)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
```
```
In kernel/locking/rtmutex.c (ffffffff810fc147)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In fs/eventpoll.c (ffffffff81329ce6)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In block/blk-throttle.c (ffffffff81500642)
Location: include/linux/rbtree.h:144
Inline: True
```
```
In lib/timerqueue.c (ffffffff81ac3f62)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_del
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
In kernel/sched/fair.c (ffffffff810e9825)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffff810f234c)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:dequeue_pushable_dl_task
```
```
In kernel/locking/rtmutex.c (ffffffff81107387)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In fs/eventpoll.c (ffffffff8133c6e2)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_remove
```
```
In block/blk-throttle.c (ffffffff81519652)
Location: include/linux/rbtree.h:144
Inline: True
```
```
In lib/timerqueue.c (ffffffff81ad0432)
Location: include/linux/rbtree.h:144
Inline: True
Inline callers:
  - lib/timerqueue.c:timerqueue_del
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
