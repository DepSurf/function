# Function: <code>cgroup_path</code>

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
In kernel/sched/debug.c (ffffffff810c65bc)
Location: include/linux/cgroup.h:520
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81236569)
Location: include/linux/cgroup.h:520
Inline: True
Inline callers:
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
```
```
In block/blk-throttle.c (ffffffff813d9d84)
Location: include/linux/cgroup.h:520
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_extend_slice
  - block/blk-throttle.c:throtl_start_new_slice
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:blk_throtl_bio
```
```
In block/cfq-iosched.c (ffffffff813dfc62)
Location: include/linux/cgroup.h:520
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_set_prio_slice
  - block/cfq-iosched.c:cfq_activate_request
  - block/cfq-iosched.c:cfq_deactivate_request
  - block/cfq-iosched.c:cfq_check_fifo
  - block/cfq-iosched.c:cfq_add_cfqq_rr
  - block/cfq-iosched.c:cfq_dispatch_insert
  - block/cfq-iosched.c:__cfq_set_active_queue
  - block/cfq-iosched.c:cfq_group_notify_queue_del
  - block/cfq-iosched.c:cfq_del_cfqq_rr
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_should_idle
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_preempt_queue
  - block/cfq-iosched.c:cfq_put_queue
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:check_blkcg_changed
  - block/cfq-iosched.c:check_blkcg_changed
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_arm_slice_timer
  - block/cfq-iosched.c:cfq_arm_slice_timer
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
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
In kernel/sched/debug.c (ffffffff810ca509)
Location: include/linux/cgroup.h:541
Inline: True
```
```
In block/blk-throttle.c (ffffffff81421bb8)
Location: include/linux/cgroup.h:541
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_extend_slice
  - block/blk-throttle.c:throtl_start_new_slice
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_schedule_pending_timer
```
```
In block/cfq-iosched.c (ffffffff8142a848)
Location: include/linux/cgroup.h:541
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_preempt_queue
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:check_blkcg_changed
  - block/cfq-iosched.c:check_blkcg_changed
  - block/cfq-iosched.c:cfq_put_queue
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_check_fifo
  - block/cfq-iosched.c:cfq_dispatch_insert
  - block/cfq-iosched.c:cfq_arm_slice_timer
  - block/cfq-iosched.c:cfq_arm_slice_timer
  - block/cfq-iosched.c:cfq_should_idle
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_set_active_queue
  - block/cfq-iosched.c:cfq_deactivate_request
  - block/cfq-iosched.c:cfq_activate_request
  - block/cfq-iosched.c:cfq_del_cfqq_rr
  - block/cfq-iosched.c:cfq_add_cfqq_rr
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_group_notify_queue_del
  - block/cfq-iosched.c:cfq_set_prio_slice
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
In kernel/sched/debug.c (ffffffff810d0532)
Location: include/linux/cgroup.h:558
Inline: True
```
```
In kernel/cgroup.c (ffffffff81122d40)
Location: include/linux/cgroup.h:558
Inline: True
Inline callers:
  - kernel/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup.c:perf_trace_cgroup
  - kernel/cgroup.c:perf_trace_cgroup
  - kernel/cgroup.c:trace_event_raw_event_cgroup_migrate
  - kernel/cgroup.c:trace_event_raw_event_cgroup_migrate
  - kernel/cgroup.c:trace_event_raw_event_cgroup
  - kernel/cgroup.c:trace_event_raw_event_cgroup
```
```
In block/blk-throttle.c (ffffffff8143cd65)
Location: include/linux/cgroup.h:558
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_extend_slice
  - block/blk-throttle.c:throtl_start_new_slice
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_schedule_pending_timer
```
```
In block/cfq-iosched.c (ffffffff81444b9f)
Location: include/linux/cgroup.h:558
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_preempt_queue
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:check_blkcg_changed
  - block/cfq-iosched.c:check_blkcg_changed
  - block/cfq-iosched.c:cfq_put_queue
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_request
  - block/cfq-iosched.c:cfq_dispatch_insert
  - block/cfq-iosched.c:cfq_arm_slice_timer
  - block/cfq-iosched.c:cfq_arm_slice_timer
  - block/cfq-iosched.c:cfq_should_idle
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_set_active_queue
  - block/cfq-iosched.c:cfq_deactivate_request
  - block/cfq-iosched.c:cfq_activate_request
  - block/cfq-iosched.c:cfq_del_cfqq_rr
  - block/cfq-iosched.c:cfq_add_cfqq_rr
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_group_notify_queue_del
  - block/cfq-iosched.c:cfq_set_prio_slice
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
In kernel/sched/debug.c (ffffffff810cf5a2)
Location: include/linux/cgroup.h:578
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81122f61)
Location: include/linux/cgroup.h:578
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup
```
```
In block/blk-throttle.c (ffffffff8144c037)
Location: include/linux/cgroup.h:578
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_extend_slice
  - block/blk-throttle.c:throtl_start_new_slice
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_schedule_pending_timer
```
```
In block/cfq-iosched.c (ffffffff814539e7)
Location: include/linux/cgroup.h:578
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_preempt_queue
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:check_blkcg_changed
  - block/cfq-iosched.c:check_blkcg_changed
  - block/cfq-iosched.c:cfq_put_queue
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_request
  - block/cfq-iosched.c:cfq_dispatch_insert
  - block/cfq-iosched.c:cfq_arm_slice_timer
  - block/cfq-iosched.c:cfq_arm_slice_timer
  - block/cfq-iosched.c:cfq_should_idle
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_set_active_queue
  - block/cfq-iosched.c:cfq_deactivate_request
  - block/cfq-iosched.c:cfq_activate_request
  - block/cfq-iosched.c:cfq_del_cfqq_rr
  - block/cfq-iosched.c:cfq_add_cfqq_rr
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_group_notify_queue_del
  - block/cfq-iosched.c:cfq_set_prio_slice
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
In kernel/sched/debug.c (ffffffff810d6ef2)
Location: include/linux/cgroup.h:615
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8112ebe1)
Location: include/linux/cgroup.h:615
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup
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
In kernel/sched/debug.c (ffffffff810de9c2)
Location: include/linux/cgroup.h:615
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8113cf1a)
Location: include/linux/cgroup.h:615
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup
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
In kernel/sched/debug.c (ffffffff810e9142)
Location: include/linux/cgroup.h:638
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8114e5cc)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81150e4a)
Location: include/linux/cgroup.h:638
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
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
In kernel/sched/fair.c (ffffffff810d6507)
Location: include/linux/cgroup.h:651
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
```
```
In kernel/sched/debug.c (ffffffff810eff12)
Location: include/linux/cgroup.h:651
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115a117)
Location: include/linux/cgroup.h:651
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115c4f9)
Location: include/linux/cgroup.h:651
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff8115e52f)
Location: include/linux/cgroup.h:651
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
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
In kernel/sched/fair.c (ffffffff810e0b87)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
```
```
In kernel/sched/debug.c (ffffffff810fbd52)
Location: include/linux/cgroup.h:653
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81165db7)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81168499)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff8116a14f)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In block/blk-iocost.c (ffffffff81513b1d)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
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
In kernel/sched/fair.c (ffffffff810e90b9)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
```
```
In kernel/sched/debug.c (ffffffff81107385)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cfs_rq
```
```
In kernel/cgroup/cgroup.c (ffffffff81176ef7)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81179f19)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff8117bc9f)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/events/core.c (ffffffff812339ba)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_cgroup
```
```
In block/blk-iocost.c (ffffffff81574cb6)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_activate
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
In kernel/sched/fair.c (ffffffff810e6e69)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
```
```
In kernel/sched/debug.c (ffffffff81105b95)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cfs_rq
```
```
In kernel/cgroup/cgroup.c (ffffffff81173be6)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81176c80)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff81178aef)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/events/core.c (ffffffff8123d78a)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_cgroup
```
```
In mm/mmap_lock.c (ffffffff81295f5c)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In block/blk-iocost.c (ffffffff81590450)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_activate
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
In kernel/sched/fair.c (ffffffff810e8f19)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
```
```
In kernel/sched/debug.c (ffffffff81107fb4)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
```
```
In kernel/cgroup/cgroup.c (ffffffff811747b6)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811776c9)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff8117965f)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/events/core.c (ffffffff812421fa)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_cgroup
```
```
In mm/mmap_lock.c (ffffffff8129b879)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In block/blk-iocost.c (ffffffff81597200)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_activate
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
In kernel/sched/fair.c (ffffffff81100639)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
```
```
In kernel/sched/debug.c (ffffffff811260ef)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
```
```
In kernel/cgroup/cgroup.c (ffffffff8119b863)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8119ee38)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff811a0f7c)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/events/core.c (ffffffff8127cb0a)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_cgroup
```
```
In mm/mmap_lock.c (ffffffff812dc369)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In block/blk-iocost.c (ffffffff815fe819)
Location: include/linux/cgroup.h:659
Inline: True
Inline callers:
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_activate
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
In kernel/sched/build_utility.c (ffffffff81140308)
Location: include/linux/cgroup.h:660
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff811cba9c)
Location: include/linux/cgroup.h:660
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811cf5d1)
Location: include/linux/cgroup.h:660
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff811d17b9)
Location: include/linux/cgroup.h:660
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/events/core.c (ffffffff812d1335)
Location: include/linux/cgroup.h:660
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_cgroup
```
```
In mm/mmap_lock.c (ffffffff8133c2d9)
Location: include/linux/cgroup.h:660
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In block/blk-iocost.c (ffffffff816b1f6e)
Location: include/linux/cgroup.h:660
Inline: True
Inline callers:
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_activate
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
In kernel/sched/build_utility.c (ffffffff8116aa48)
Location: include/linux/cgroup.h:600
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8120ef3c)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81213401)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff81215399)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/events/core.c (ffffffff81338b25)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_cgroup
```
```
In mm/vmscan.c (ffffffff8137f15f)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_seq_show
```
```
In mm/mmap_lock.c (ffffffff813b3e19)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In block/blk-iocost.c (ffffffff81770bab)
Location: include/linux/cgroup.h:600
Inline: True
Inline callers:
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_activate
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
In kernel/sched/build_utility.c (ffffffff8117b158)
Location: include/linux/cgroup.h:599
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8122494c)
Location: include/linux/cgroup.h:599
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81228d11)
Location: include/linux/cgroup.h:599
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff8122acc9)
Location: include/linux/cgroup.h:599
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/events/core.c (ffffffff81369bd5)
Location: include/linux/cgroup.h:599
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_cgroup
```
```
In mm/vmscan.c (ffffffff813b0709)
Location: include/linux/cgroup.h:599
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_seq_show
```
```
In mm/mmap_lock.c (ffffffff813e8769)
Location: include/linux/cgroup.h:599
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In block/blk-iocost.c (ffffffff817b0774)
Location: include/linux/cgroup.h:599
Inline: True
Inline callers:
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_activate
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
In kernel/sched/build_utility.c (ffffffff81188b08)
Location: include/linux/cgroup.h:597
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8123c62c)
Location: include/linux/cgroup.h:597
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81240b61)
Location: include/linux/cgroup.h:597
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff81242c89)
Location: include/linux/cgroup.h:597
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/events/core.c (ffffffff81392ae4)
Location: include/linux/cgroup.h:597
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_cgroup
```
```
In mm/vmscan.c (ffffffff813d9c1e)
Location: include/linux/cgroup.h:597
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_seq_show
```
```
In mm/mmap_lock.c (ffffffff814133f9)
Location: include/linux/cgroup.h:597
Inline: True
Inline callers:
  - mm/mmap_lock.c:get_mm_memcg_path
```
```
In block/blk-iocost.c (ffffffff817f4584)
Location: include/linux/cgroup.h:597
Inline: True
Inline callers:
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_activate
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
In kernel/sched/fair.c (ffff80001014097c)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
```
```
In kernel/sched/debug.c (ffff8000101605dc)
Location: include/linux/cgroup.h:653
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffff8000101d78d0)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101db75c)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffff8000101ddb2c)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In block/blk-iocost.c (ffff800010617fa8)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
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
In kernel/sched/fair.c (c03910a0)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
```
```
In kernel/sched/debug.c (c03ac6bc)
Location: include/linux/cgroup.h:653
Inline: True
```
```
In kernel/cgroup/cgroup.c (c041a604)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (c041d90c)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (c041f8e8)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In block/blk-iocost.c (c07c32bc)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_activate
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
In kernel/sched/fair.c (c000000000190bfc)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
```
```
In kernel/sched/debug.c (c0000000001b6848)
Location: include/linux/cgroup.h:653
Inline: True
```
```
In kernel/cgroup/cgroup.c (c000000000244638)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (c0000000002482ec)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (c00000000024b938)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In block/blk-iocost.c (c0000000007b7750)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
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
In kernel/sched/fair.c (ffffffe0000eef90)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
```
```
In kernel/sched/debug.c (ffffffe000104b22)
Location: include/linux/cgroup.h:653
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffe0001509e8)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe0001534d8)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffe0001553f6)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In block/blk-iocost.c (ffffffe00044e55a)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
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
In kernel/sched/fair.c (ffffffff810dad37)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
```
```
In kernel/sched/debug.c (ffffffff810f5082)
Location: include/linux/cgroup.h:653
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115e3d7)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81160ab9)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff8116276f)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In block/blk-iocost.c (ffffffff8150c0fd)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
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
In kernel/sched/fair.c (ffffffff810c9d47)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
```
```
In kernel/sched/debug.c (ffffffff810e5242)
Location: include/linux/cgroup.h:653
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff811516a7)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81153d29)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff811559bf)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In block/blk-iocost.c (ffffffff814fc535)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
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
In kernel/sched/fair.c (ffffffff810d70b7)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
```
```
In kernel/sched/debug.c (ffffffff810f2282)
Location: include/linux/cgroup.h:653
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8115c1a7)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115e889)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff8116053f)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In block/blk-iocost.c (ffffffff8150818d)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
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
In kernel/sched/fair.c (ffffffff810e2a67)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
```
```
In kernel/sched/debug.c (ffffffff810fd272)
Location: include/linux/cgroup.h:653
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff811692d7)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116bcb9)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff8116d89f)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In block/blk-iocost.c (ffffffff8151f4ae)
Location: include/linux/cgroup.h:653
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
```
</details>
</li>
</ul>

## Differences
