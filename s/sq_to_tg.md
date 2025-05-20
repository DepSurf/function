# Function: <code>sq_to_tg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff813d930d)
Location: block/blk-throttle.c:181
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_update_has_rules
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_extend_slice
  - block/blk-throttle.c:throtl_start_new_slice
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81421b09)
Location: block/blk-throttle.c:176
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_extend_slice
  - block/blk-throttle.c:throtl_start_new_slice
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:tg_update_has_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8143ccb2)
Location: block/blk-throttle.c:176
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_extend_slice
  - block/blk-throttle.c:throtl_start_new_slice
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:tg_update_has_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8144bf43)
Location: block/blk-throttle.c:251
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_last_low_overflow_time
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_extend_slice
  - block/blk-throttle.c:throtl_start_new_slice
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:tg_update_has_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814785d1)
Location: block/blk-throttle.c:252
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_last_low_overflow_time
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_update_has_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814acc86)
Location: block/blk-throttle.c:250
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_last_low_overflow_time
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_update_has_rules
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
In block/blk-throttle.c (ffffffff814c7027)
Location: block/blk-throttle.c:249
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_last_low_overflow_time
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_update_has_rules
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
In block/blk-throttle.c (ffffffff814f5881)
Location: block/blk-throttle.c:249
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_last_low_overflow_time
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_update_has_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8150ef21)
Location: block/blk-throttle.c:249
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_last_low_overflow_time
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_update_has_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff815701c5)
Location: block/blk-throttle.c:253
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_hierarchy_can_downgrade
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_last_low_overflow_time
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_trim_slice
  - block/blk-throttle.c:throtl_trim_slice
  - block/blk-throttle.c:throtl_extend_slice
  - block/blk-throttle.c:throtl_extend_slice
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:tg_update_has_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8158afcb)
Location: block/blk-throttle.c:253
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_hierarchy_can_downgrade
  - block/blk-throttle.c:throtl_downgrade_state
  - block/blk-throttle.c:throtl_downgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_last_low_overflow_time
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_trim_slice
  - block/blk-throttle.c:throtl_trim_slice
  - block/blk-throttle.c:throtl_extend_slice
  - block/blk-throttle.c:throtl_extend_slice
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:tg_update_has_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81591c7b)
Location: block/blk-throttle.c:253
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_last_low_overflow_time
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_trim_slice
  - block/blk-throttle.c:throtl_trim_slice
  - block/blk-throttle.c:throtl_extend_slice
  - block/blk-throttle.c:throtl_extend_slice
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:tg_update_has_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff815f8d13)
Location: block/blk-throttle.c:256
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_charge_bio_split
  - block/blk-throttle.c:throtl_downgrade_check
  - block/blk-throttle.c:throtl_downgrade_check
  - block/blk-throttle.c:throtl_downgrade_check
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_last_low_overflow_time
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_trim_slice
  - block/blk-throttle.c:throtl_trim_slice
  - block/blk-throttle.c:throtl_extend_slice
  - block/blk-throttle.c:throtl_extend_slice
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:tg_update_has_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff816aac8c)
Location: block/blk-throttle.c:104
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:throtl_downgrade_check
  - block/blk-throttle.c:throtl_downgrade_check
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_can_upgrade
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_last_low_overflow_time
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:throtl_trim_slice
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:tg_update_has_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8176967e)
Location: block/blk-throttle.c:104
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_update_carryover
  - block/blk-throttle.c:throtl_trim_slice
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:tg_update_has_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff817a877f)
Location: block/blk-throttle.c:104
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_update_carryover
  - block/blk-throttle.c:throtl_trim_slice
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:tg_update_has_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff817ec4ec)
Location: block/blk-throttle.c:104
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_update_carryover
  - block/blk-throttle.c:throtl_trim_slice
  - block/blk-throttle.c:throtl_start_new_slice_with_credit
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:throtl_schedule_pending_timer
  - block/blk-throttle.c:tg_update_has_rules
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffff800010612b44)
Location: block/blk-throttle.c:249
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_last_low_overflow_time
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_update_has_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (c07bd544)
Location: block/blk-throttle.c:249
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_downgrade_check
  - block/blk-throttle.c:throtl_downgrade_check
  - block/blk-throttle.c:throtl_downgrade_check
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_last_low_overflow_time
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_update_has_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (c0000000007b10e0)
Location: block/blk-throttle.c:249
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_last_low_overflow_time
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_update_has_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffe00044a12c)
Location: block/blk-throttle.c:249
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_last_low_overflow_time
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_update_has_rules
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81507501)
Location: block/blk-throttle.c:249
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_last_low_overflow_time
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_update_has_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814f79bb)
Location: block/blk-throttle.c:249
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_last_low_overflow_time
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_update_has_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81503591)
Location: block/blk-throttle.c:249
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_last_low_overflow_time
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_update_has_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8151ca9b)
Location: block/blk-throttle.c:249
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:throtl_tg_is_idle
  - block/blk-throttle.c:tg_last_low_overflow_time
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_update_has_rules
```
</details>
</li>
</ul>

## Differences
