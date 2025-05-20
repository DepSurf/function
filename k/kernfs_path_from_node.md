# Function: <code>kernfs_path_from_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kernfs_path_from_node(struct kernfs_node *to, struct kernfs_node *from, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812895f0)
Location: fs/kernfs/dir.c:227
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - fs/kernfs/dir.c:kernfs_path
```
**Symbols:**

```
ffffffff812895f0-ffffffff8128964c: kernfs_path_from_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kernfs_path_from_node(struct kernfs_node *to, struct kernfs_node *from, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812b6ab0)
Location: fs/kernfs/dir.c:226
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_show_path
  - fs/kernfs/dir.c:kernfs_path
```
**Symbols:**

```
ffffffff812b6ab0-ffffffff812b6b0c: kernfs_path_from_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kernfs_path_from_node(struct kernfs_node *to, struct kernfs_node *from, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812cc240)
Location: fs/kernfs/dir.c:198
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_show_path
  - kernel/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup.c:perf_trace_cgroup
  - kernel/cgroup.c:perf_trace_cgroup
  - kernel/cgroup.c:trace_event_raw_event_cgroup_migrate
  - kernel/cgroup.c:trace_event_raw_event_cgroup_migrate
  - kernel/cgroup.c:trace_event_raw_event_cgroup
  - kernel/cgroup.c:trace_event_raw_event_cgroup
  - fs/sysfs/dir.c:sysfs_warn_dup
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_extend_slice
  - block/blk-throttle.c:throtl_start_new_slice
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_schedule_pending_timer
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
**Symbols:**

```
ffffffff812cc240-ffffffff812cc29c: kernfs_path_from_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kernfs_path_from_node(struct kernfs_node *to, struct kernfs_node *from, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812d9960)
Location: fs/kernfs/dir.c:208
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup
  - fs/sysfs/dir.c:sysfs_warn_dup
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
**Symbols:**

```
ffffffff812d9960-ffffffff812d99bc: kernfs_path_from_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kernfs_path_from_node(struct kernfs_node *to, struct kernfs_node *from, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812fe130)
Location: fs/kernfs/dir.c:209
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup
  - fs/sysfs/dir.c:sysfs_warn_dup
```
**Symbols:**

```
ffffffff812fe130-ffffffff812fe18c: kernfs_path_from_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kernfs_path_from_node(struct kernfs_node *to, struct kernfs_node *from, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8132bd70)
Location: fs/kernfs/dir.c:209
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup
  - fs/sysfs/dir.c:sysfs_warn_dup
```
**Symbols:**

```
ffffffff8132bd70-ffffffff8132bdcc: kernfs_path_from_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kernfs_path_from_node(struct kernfs_node *to, struct kernfs_node *from, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813430d0)
Location: fs/kernfs/dir.c:209
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - fs/sysfs/dir.c:sysfs_warn_dup
```
**Symbols:**

```
ffffffff813430d0-ffffffff8134312c: kernfs_path_from_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kernfs_path_from_node(struct kernfs_node *to, struct kernfs_node *from, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136b320)
Location: fs/kernfs/dir.c:208
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - fs/sysfs/dir.c:sysfs_warn_dup
```
**Symbols:**

```
ffffffff8136b320-ffffffff8136b37e: kernfs_path_from_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kernfs_path_from_node(struct kernfs_node *to, struct kernfs_node *from, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81383500)
Location: fs/kernfs/dir.c:210
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - fs/sysfs/dir.c:sysfs_warn_dup
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff81383500-ffffffff8138355e: kernfs_path_from_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kernfs_path_from_node(struct kernfs_node *to, struct kernfs_node *from, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813cde40)
Location: fs/kernfs/dir.c:210
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/events/core.c:perf_event_cgroup
  - fs/sysfs/dir.c:sysfs_warn_dup
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff813cde40-ffffffff813cde9e: kernfs_path_from_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kernfs_path_from_node(struct kernfs_node *to, struct kernfs_node *from, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813dfa70)
Location: fs/kernfs/dir.c:210
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/events/core.c:perf_event_cgroup
  - mm/mmap_lock.c:get_mm_memcg_path
  - fs/sysfs/dir.c:sysfs_warn_dup
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff813dfa70-ffffffff813dface: kernfs_path_from_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kernfs_path_from_node(struct kernfs_node *to, struct kernfs_node *from, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e6700)
Location: fs/kernfs/dir.c:210
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/events/core.c:perf_event_cgroup
  - mm/mmap_lock.c:get_mm_memcg_path
  - fs/sysfs/dir.c:sysfs_warn_dup
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff813e6700-ffffffff813e675e: kernfs_path_from_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kernfs_path_from_node(struct kernfs_node *to, struct kernfs_node *from, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81438300)
Location: fs/kernfs/dir.c:210
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/events/core.c:perf_event_cgroup
  - mm/mmap_lock.c:get_mm_memcg_path
  - fs/sysfs/dir.c:sysfs_warn_dup
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff81438300-ffffffff8143835e: kernfs_path_from_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int kernfs_path_from_node(struct kernfs_node *to, struct kernfs_node *from, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814b4287)
Location: fs/kernfs/dir.c:217
Inline: True
Inline callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/events/core.c:perf_event_cgroup
  - mm/mmap_lock.c:get_mm_memcg_path
  - fs/sysfs/dir.c:sysfs_warn_dup
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff814b3110-ffffffff814b3178: kernfs_path_from_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int kernfs_path_from_node(struct kernfs_node *to, struct kernfs_node *from, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8154b0a7)
Location: fs/kernfs/dir.c:224
Inline: True
Inline callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/events/core.c:perf_event_cgroup
  - mm/vmscan.c:lru_gen_seq_show
  - mm/mmap_lock.c:get_mm_memcg_path
  - fs/sysfs/dir.c:sysfs_warn_dup
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff81549d60-ffffffff81549dc8: kernfs_path_from_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int kernfs_path_from_node(struct kernfs_node *to, struct kernfs_node *from, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81582cf7)
Location: fs/kernfs/dir.c:221
Inline: True
Inline callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
Direct callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_path_ns
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/events/core.c:perf_event_cgroup
  - mm/vmscan.c:lru_gen_seq_show
  - mm/mmap_lock.c:get_mm_memcg_path
  - fs/sysfs/dir.c:sysfs_warn_dup
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff81581980-ffffffff815819e8: kernfs_path_from_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int kernfs_path_from_node(struct kernfs_node *to, struct kernfs_node *from, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815bb927)
Location: fs/kernfs/dir.c:223
Inline: True
Inline callers:
  - fs/kernfs/dir.c:pr_cont_kernfs_path
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/events/core.c:perf_event_cgroup
  - mm/vmscan.c:lru_gen_seq_show
  - mm/mmap_lock.c:get_mm_memcg_path
  - fs/sysfs/dir.c:sysfs_warn_dup
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
ffffffff815ba460-ffffffff815ba4c8: kernfs_path_from_node (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int kernfs_path_from_node(struct kernfs_node *to, struct kernfs_node *from, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffff800010452870)
Location: fs/kernfs/dir.c:210
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - fs/sysfs/dir.c:sysfs_warn_dup
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffff800010452870-ffff800010452948: kernfs_path_from_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kernfs_path_from_node(struct kernfs_node *to, struct kernfs_node *from, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c0614a10)
Location: fs/kernfs/dir.c:210
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - fs/sysfs/dir.c:sysfs_warn_dup
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:iocg_activate
```
**Symbols:**

```
c0614a10-c0614a78: kernfs_path_from_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kernfs_path_from_node(struct kernfs_node *to, struct kernfs_node *from, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c00000000056a410)
Location: fs/kernfs/dir.c:210
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - fs/sysfs/dir.c:sysfs_warn_dup
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
c00000000056a410-c00000000056a4a8: kernfs_path_from_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kernfs_path_from_node(struct kernfs_node *to, struct kernfs_node *from, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffe0002e45e6)
Location: fs/kernfs/dir.c:210
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - fs/sysfs/dir.c:sysfs_warn_dup
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffe0002e45e6-ffffffe0002e4654: kernfs_path_from_node (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int kernfs_path_from_node(struct kernfs_node *to, struct kernfs_node *from, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137bae0)
Location: fs/kernfs/dir.c:210
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - fs/sysfs/dir.c:sysfs_warn_dup
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff8137bae0-ffffffff8137bb3e: kernfs_path_from_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kernfs_path_from_node(struct kernfs_node *to, struct kernfs_node *from, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136c5b0)
Location: fs/kernfs/dir.c:210
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - fs/sysfs/dir.c:sysfs_warn_dup
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff8136c5b0-ffffffff8136c60e: kernfs_path_from_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kernfs_path_from_node(struct kernfs_node *to, struct kernfs_node *from, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813795b0)
Location: fs/kernfs/dir.c:210
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - fs/sysfs/dir.c:sysfs_warn_dup
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff813795b0-ffffffff8137960e: kernfs_path_from_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kernfs_path_from_node(struct kernfs_node *to, struct kernfs_node *from, char *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8138d060)
Location: fs/kernfs/dir.c:210
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_path
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_path_ns_locked
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - fs/sysfs/dir.c:sysfs_warn_dup
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
```
**Symbols:**

```
ffffffff8138d060-ffffffff8138d0be: kernfs_path_from_node (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
