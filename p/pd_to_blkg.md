# Function: <code>pd_to_blkg</code>

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
In block/blk-throttle.c (ffffffff813d92b6)
Location: include/linux/blk-cgroup.h:326
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_add_bio_tg
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
```
In block/cfq-iosched.c (ffffffff813dd71d)
Location: include/linux/blk-cgroup.h:326
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_group_service_tree_del
  - block/cfq-iosched.c:cfq_group_service_tree_add
  - block/cfq-iosched.c:cfqg_prfill_rwstat_recursive
  - block/cfq-iosched.c:cfqg_prfill_stat_recursive
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_init_queue
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
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:cfq_preempt_queue
  - block/cfq-iosched.c:cfq_put_queue
  - block/cfq-iosched.c:cfq_put_queue
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:check_blkcg_changed
  - block/cfq-iosched.c:check_blkcg_changed
  - block/cfq-iosched.c:cfq_set_request
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
In block/blk-throttle.c (ffffffff81420635)
Location: include/linux/blk-cgroup.h:326
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/cfq-iosched.c (ffffffff81425aa4)
Location: include/linux/blk-cgroup.h:326
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_preempt_queue
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:check_blkcg_changed
  - block/cfq-iosched.c:check_blkcg_changed
  - block/cfq-iosched.c:cfq_put_queue
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
  - block/cfq-iosched.c:cfqg_prfill_rwstat_recursive
  - block/cfq-iosched.c:cfqg_prfill_stat_recursive
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_group_notify_queue_del
  - block/cfq-iosched.c:cfq_group_service_tree_del
  - block/cfq-iosched.c:cfq_group_service_tree_add
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
In block/blk-throttle.c (ffffffff8143bcb5)
Location: include/linux/blk-cgroup.h:326
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/cfq-iosched.c (ffffffff81444864)
Location: include/linux/blk-cgroup.h:326
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_preempt_queue
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:check_blkcg_changed
  - block/cfq-iosched.c:check_blkcg_changed
  - block/cfq-iosched.c:cfq_put_queue
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
  - block/cfq-iosched.c:cfqg_prfill_rwstat_recursive
  - block/cfq-iosched.c:cfqg_prfill_stat_recursive
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_group_notify_queue_del
  - block/cfq-iosched.c:cfq_group_service_tree_del
  - block/cfq-iosched.c:cfq_group_service_tree_add
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
In block/blk-throttle.c (ffffffff8144bd27)
Location: include/linux/blk-cgroup.h:326
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
  - block/blk-throttle.c:tg_iops_limit
  - block/blk-throttle.c:tg_bps_limit
```
```
In block/cfq-iosched.c (ffffffff81453d86)
Location: include/linux/blk-cgroup.h:326
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_preempt_queue
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:check_blkcg_changed
  - block/cfq-iosched.c:check_blkcg_changed
  - block/cfq-iosched.c:cfq_put_queue
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
  - block/cfq-iosched.c:cfqg_prfill_rwstat_recursive
  - block/cfq-iosched.c:cfqg_prfill_stat_recursive
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_group_notify_queue_del
  - block/cfq-iosched.c:cfq_group_service_tree_del
  - block/cfq-iosched.c:cfq_group_service_tree_add
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
In block/blk-throttle.c (ffffffff8147826d)
Location: include/linux/blk-cgroup.h:322
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:tg_iops_limit
  - block/blk-throttle.c:tg_bps_limit
```
```
In block/cfq-iosched.c (ffffffff8147d2e9)
Location: include/linux/blk-cgroup.h:322
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:cfq_put_queue
  - block/cfq-iosched.c:cfq_put_queue
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_insert
  - block/cfq-iosched.c:cfq_should_idle
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_set_active_queue
  - block/cfq-iosched.c:cfq_deactivate_request
  - block/cfq-iosched.c:cfq_activate_request
  - block/cfq-iosched.c:cfq_add_rq_rb
  - block/cfq-iosched.c:cfq_del_cfqq_rr
  - block/cfq-iosched.c:cfq_del_cfqq_rr
  - block/cfq-iosched.c:cfqg_prfill_rwstat_recursive
  - block/cfq-iosched.c:cfqg_prfill_stat_recursive
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_group_service_tree_del
  - block/cfq-iosched.c:cfq_group_service_tree_add
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
In block/blk-throttle.c (ffffffff814ace60)
Location: include/linux/blk-cgroup.h:340
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
  - block/blk-throttle.c:tg_iops_limit
  - block/blk-throttle.c:tg_bps_limit
```
```
In block/cfq-iosched.c (ffffffff814b4262)
Location: include/linux/blk-cgroup.h:340
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:cfq_put_queue
  - block/cfq-iosched.c:cfq_put_queue
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_insert
  - block/cfq-iosched.c:cfq_should_idle
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_set_active_queue
  - block/cfq-iosched.c:cfq_deactivate_request
  - block/cfq-iosched.c:cfq_activate_request
  - block/cfq-iosched.c:cfq_add_rq_rb
  - block/cfq-iosched.c:cfq_del_cfqq_rr
  - block/cfq-iosched.c:cfq_del_cfqq_rr
  - block/cfq-iosched.c:cfqg_prfill_rwstat_recursive
  - block/cfq-iosched.c:cfqg_prfill_stat_recursive
  - block/cfq-iosched.c:cfq_pd_offline
  - block/cfq-iosched.c:cfq_group_service_tree_del
  - block/cfq-iosched.c:cfq_group_service_tree_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814c71ea)
Location: include/linux/blk-cgroup.h:416
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
  - block/blk-throttle.c:tg_iops_limit
  - block/blk-throttle.c:tg_bps_limit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814f5a48)
Location: include/linux/blk-cgroup.h:423
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
  - block/blk-throttle.c:tg_iops_limit
  - block/blk-throttle.c:tg_bps_limit
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
In block/blk-throttle.c (ffffffff8150f270)
Location: include/linux/blk-cgroup.h:425
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
  - block/blk-throttle.c:tg_iops_limit
  - block/blk-throttle.c:tg_bps_limit
```
```
In block/blk-iocost.c (ffffffff81510a66)
Location: include/linux/blk-cgroup.h:425
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:weight_updated
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
In block/blk-throttle.c (ffffffff815702ad)
Location: include/linux/blk-cgroup.h:403
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_downgrade_check
  - block/blk-throttle.c:throtl_hierarchy_can_downgrade
  - block/blk-throttle.c:throtl_hierarchy_can_downgrade
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_prfill_rwstat_recursive
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
  - block/blk-throttle.c:throtl_trim_slice
  - block/blk-throttle.c:throtl_extend_slice
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:tg_iops_limit
  - block/blk-throttle.c:tg_bps_limit
```
```
In block/blk-iocost.c (ffffffff81572556)
Location: include/linux/blk-cgroup.h:403
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:weight_updated
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
In block/blk-throttle.c (ffffffff8158b0bd)
Location: include/linux/blk-cgroup.h:393
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_downgrade_check
  - block/blk-throttle.c:throtl_hierarchy_can_downgrade
  - block/blk-throttle.c:throtl_hierarchy_can_downgrade
  - block/blk-throttle.c:throtl_downgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_prfill_rwstat_recursive
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
  - block/blk-throttle.c:throtl_trim_slice
  - block/blk-throttle.c:throtl_extend_slice
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:tg_iops_limit
  - block/blk-throttle.c:tg_bps_limit
```
```
In block/blk-iocost.c (ffffffff8158e506)
Location: include/linux/blk-cgroup.h:393
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:weight_updated
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
In block/blk-throttle.c (ffffffff81591d63)
Location: include/linux/blk-cgroup.h:393
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_prfill_rwstat_recursive
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
  - block/blk-throttle.c:throtl_trim_slice
  - block/blk-throttle.c:throtl_extend_slice
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:tg_iops_limit
  - block/blk-throttle.c:tg_bps_limit
```
```
In block/blk-iocost.c (ffffffff81595266)
Location: include/linux/blk-cgroup.h:393
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:weight_updated
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
In block/blk-throttle.c (ffffffff815f8e05)
Location: include/linux/blk-cgroup.h:398
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_downgrade_check
  - block/blk-throttle.c:throtl_downgrade_check
  - block/blk-throttle.c:throtl_downgrade_check
  - block/blk-throttle.c:throtl_downgrade_check
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_prfill_rwstat_recursive
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
  - block/blk-throttle.c:throtl_trim_slice
  - block/blk-throttle.c:throtl_extend_slice
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:tg_iops_limit
  - block/blk-throttle.c:tg_bps_limit
```
```
In block/blk-iocost.c (ffffffff815fc168)
Location: include/linux/blk-cgroup.h:398
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:weight_updated
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
In block/blk-throttle.c (ffffffff816aae91)
Location: block/blk-cgroup.h:307
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:throtl_downgrade_check
  - block/blk-throttle.c:throtl_downgrade_check
  - block/blk-throttle.c:throtl_downgrade_check
  - block/blk-throttle.c:throtl_downgrade_check
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_can_upgrade
  - block/blk-throttle.c:throtl_can_upgrade
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_prfill_rwstat_recursive
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:throtl_trim_slice
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:tg_iops_limit
  - block/blk-throttle.c:tg_bps_limit
```
```
In block/blk-iocost.c (ffffffff816b0508)
Location: block/blk-cgroup.h:307
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:weight_updated
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
In block/blk-throttle.c (ffffffff8176976e)
Location: block/blk-cgroup.h:291
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:tg_prfill_rwstat_recursive
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_update_carryover
  - block/blk-throttle.c:throtl_trim_slice
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
  - block/blk-throttle.c:tg_iops_limit
  - block/blk-throttle.c:tg_bps_limit
```
```
In block/blk-iocost.c (ffffffff81770378)
Location: block/blk-cgroup.h:291
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:weight_updated
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
In block/blk-throttle.c (ffffffff817a886e)
Location: block/blk-cgroup.h:292
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:tg_prfill_rwstat_recursive
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_update_carryover
  - block/blk-throttle.c:throtl_trim_slice
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
  - block/blk-throttle.c:tg_iops_limit
  - block/blk-throttle.c:tg_bps_limit
```
```
In block/blk-iocost.c (ffffffff817af3a8)
Location: block/blk-cgroup.h:292
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:weight_updated
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
In block/blk-throttle.c (ffffffff817ec5db)
Location: block/blk-cgroup.h:291
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:tg_prfill_rwstat_recursive
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_update_carryover
  - block/blk-throttle.c:throtl_trim_slice
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
  - block/blk-throttle.c:tg_iops_limit
  - block/blk-throttle.c:tg_bps_limit
```
```
In block/blk-iocost.c (ffffffff817f31b8)
Location: block/blk-cgroup.h:291
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:weight_updated
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
In block/blk-throttle.c (ffff800010612e04)
Location: include/linux/blk-cgroup.h:425
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
  - block/blk-throttle.c:tg_iops_limit
  - block/blk-throttle.c:tg_bps_limit
```
```
In block/blk-iocost.c (ffff8000106159dc)
Location: include/linux/blk-cgroup.h:425
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:weight_updated
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
In block/blk-throttle.c (c07bd790)
Location: include/linux/blk-cgroup.h:425
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_downgrade_check
  - block/blk-throttle.c:throtl_downgrade_check
  - block/blk-throttle.c:throtl_downgrade_check
  - block/blk-throttle.c:throtl_downgrade_check
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
  - block/blk-throttle.c:tg_iops_limit
  - block/blk-throttle.c:tg_bps_limit
```
```
In block/blk-iocost.c (c07c13e8)
Location: include/linux/blk-cgroup.h:425
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_activate
  - block/blk-iocost.c:weight_updated
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
In block/blk-throttle.c (c0000000007b1138)
Location: include/linux/blk-cgroup.h:425
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
  - block/blk-throttle.c:tg_iops_limit
  - block/blk-throttle.c:tg_bps_limit
```
```
In block/blk-iocost.c (c0000000007b3a8c)
Location: include/linux/blk-cgroup.h:425
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:weight_updated
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
In block/blk-throttle.c (ffffffe00044a384)
Location: include/linux/blk-cgroup.h:425
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
  - block/blk-throttle.c:tg_iops_limit
  - block/blk-throttle.c:tg_bps_limit
```
```
In block/blk-iocost.c (ffffffe00044b092)
Location: include/linux/blk-cgroup.h:425
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:weight_updated
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
In block/blk-throttle.c (ffffffff81507850)
Location: include/linux/blk-cgroup.h:425
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
  - block/blk-throttle.c:tg_iops_limit
  - block/blk-throttle.c:tg_bps_limit
```
```
In block/blk-iocost.c (ffffffff81509046)
Location: include/linux/blk-cgroup.h:425
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:weight_updated
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
In block/blk-throttle.c (ffffffff814f7d0a)
Location: include/linux/blk-cgroup.h:425
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
  - block/blk-throttle.c:tg_iops_limit
  - block/blk-throttle.c:tg_bps_limit
```
```
In block/blk-iocost.c (ffffffff814f94f6)
Location: include/linux/blk-cgroup.h:425
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:weight_updated
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
In block/blk-throttle.c (ffffffff815038e0)
Location: include/linux/blk-cgroup.h:425
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
  - block/blk-throttle.c:tg_iops_limit
  - block/blk-throttle.c:tg_bps_limit
```
```
In block/blk-iocost.c (ffffffff815050d6)
Location: include/linux/blk-cgroup.h:425
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:weight_updated
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
In block/blk-throttle.c (ffffffff8151ce91)
Location: include/linux/blk-cgroup.h:425
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:throtl_pd_init
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
  - block/blk-throttle.c:tg_iops_limit
  - block/blk-throttle.c:tg_bps_limit
```
```
In block/blk-iocost.c (ffffffff8151e736)
Location: include/linux/blk-cgroup.h:425
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:weight_updated
```
</details>
</li>
</ul>

## Differences
