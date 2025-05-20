# Function: <code>op_is_sync</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81411b06)
Location: include/linux/blk_types.h:228
Inline: True
Inline callers:
  - block/elevator.c:elv_completed_request
  - block/elevator.c:elv_requeue_request
```
```
In block/blk-core.c (ffffffff8141875e)
Location: include/linux/blk_types.h:228
Inline: True
Inline callers:
  - block/blk-core.c:blk_dequeue_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:get_request
```
```
In block/blk-tag.c (ffffffff81419525)
Location: include/linux/blk_types.h:228
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_start_tag
```
```
In block/blk-mq.c (ffffffff814245a0)
Location: include/linux/blk_types.h:228
Inline: True
Inline callers:
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_free_hctx_request
  - block/blk-mq.c:__blk_mq_alloc_request
```
```
In block/cfq-iosched.c (ffffffff81444ae8)
Location: include/linux/blk_types.h:228
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_may_queue
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_allow_bio_merge
  - block/cfq-iosched.c:cfq_allow_bio_merge
  - block/cfq-iosched.c:cfq_merged_requests
  - block/cfq-iosched.c:cfq_bio_merged
  - block/cfq-iosched.c:cfq_merge
  - block/cfq-iosched.c:cfq_remove_request
  - block/cfq-iosched.c:cfq_remove_request
  - block/cfq-iosched.c:cfq_add_rq_rb
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
In block/elevator.c (ffffffff8141f6d5)
Location: include/linux/blk_types.h:288
Inline: True
Inline callers:
  - block/elevator.c:elv_completed_request
  - block/elevator.c:elv_requeue_request
```
```
In block/blk-core.c (ffffffff81426752)
Location: include/linux/blk_types.h:288
Inline: True
Inline callers:
  - block/blk-core.c:blk_dequeue_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:get_request
```
```
In block/blk-tag.c (ffffffff81427455)
Location: include/linux/blk_types.h:288
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_start_tag
```
```
In block/blk-mq.c (ffffffff814312e6)
Location: include/linux/blk_types.h:288
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/cfq-iosched.c (ffffffff81453924)
Location: include/linux/blk_types.h:288
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_may_queue
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_allow_bio_merge
  - block/cfq-iosched.c:cfq_allow_bio_merge
  - block/cfq-iosched.c:cfq_merged_requests
  - block/cfq-iosched.c:cfq_bio_merged
  - block/cfq-iosched.c:cfq_merge
  - block/cfq-iosched.c:cfq_remove_request
  - block/cfq-iosched.c:cfq_remove_request
  - block/cfq-iosched.c:cfq_add_rq_rb
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
In block/elevator.c (ffffffff8144a1f9)
Location: include/linux/blk_types.h:296
Inline: True
Inline callers:
  - block/elevator.c:elv_completed_request
  - block/elevator.c:elv_requeue_request
```
```
In block/blk-core.c (ffffffff8144cc33)
Location: include/linux/blk_types.h:296
Inline: True
Inline callers:
  - block/blk-core.c:blk_start_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:get_request
```
```
In block/blk-tag.c (ffffffff81452455)
Location: include/linux/blk_types.h:296
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_start_tag
```
```
In block/blk-mq.c (ffffffff8145ccd6)
Location: include/linux/blk_types.h:296
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/cfq-iosched.c (ffffffff8147e5bc)
Location: include/linux/blk_types.h:296
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_may_queue
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_allow_bio_merge
  - block/cfq-iosched.c:cfq_allow_bio_merge
  - block/cfq-iosched.c:cfq_merged_requests
  - block/cfq-iosched.c:cfq_bio_merged
  - block/cfq-iosched.c:cfq_merge
  - block/cfq-iosched.c:cfq_remove_request
  - block/cfq-iosched.c:cfq_remove_request
  - block/cfq-iosched.c:cfq_add_rq_rb
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
In block/elevator.c (ffffffff8147cf49)
Location: include/linux/blk_types.h:392
Inline: True
Inline callers:
  - block/elevator.c:elv_completed_request
  - block/elevator.c:elv_requeue_request
```
```
In block/blk-core.c (ffffffff8147fec2)
Location: include/linux/blk_types.h:392
Inline: True
Inline callers:
  - block/blk-core.c:blk_start_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:get_request
```
```
In block/blk-tag.c (ffffffff814858c6)
Location: include/linux/blk_types.h:392
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_start_tag
```
```
In block/blk-mq.c (ffffffff81490570)
Location: include/linux/blk_types.h:392
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/cfq-iosched.c (ffffffff814b259a)
Location: include/linux/blk_types.h:392
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_may_queue
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_allow_bio_merge
  - block/cfq-iosched.c:cfq_allow_bio_merge
  - block/cfq-iosched.c:cfq_merged_requests
  - block/cfq-iosched.c:cfq_bio_merged
  - block/cfq-iosched.c:cfq_merge
  - block/cfq-iosched.c:cfq_remove_request
  - block/cfq-iosched.c:cfq_remove_request
  - block/cfq-iosched.c:cfq_add_rq_rb
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
In block/blk-core.c (ffffffff8149d5f2)
Location: include/linux/blk_types.h:400
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-mq.c (ffffffff814aa990)
Location: include/linux/blk_types.h:400
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-core.c (ffffffff814cb834)
Location: include/linux/blk_types.h:401
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-mq.c (ffffffff814d8440)
Location: include/linux/blk_types.h:401
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-core.c (ffffffff814e4af7)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-mq.c (ffffffff814f17f0)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-mq.c (ffffffff81550edf)
Location: include/linux/blk_types.h:434
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In block/blk-throttle.c (ffffffff8156ff08)
Location: include/linux/blk_types.h:434
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
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
In block/blk-mq.c (ffffffff8156ed9a)
Location: include/linux/blk_types.h:498
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In block/blk-throttle.c (ffffffff8158ad52)
Location: include/linux/blk_types.h:498
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
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
In block/blk-mq.c (ffffffff8157697f)
Location: include/linux/blk_types.h:472
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In block/blk-throttle.c (ffffffff8159183e)
Location: include/linux/blk_types.h:472
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
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
In block/blk-mq.c (ffffffff815db62f)
Location: include/linux/blk_types.h:463
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In block/blk-throttle.c (ffffffff815f8a85)
Location: include/linux/blk_types.h:463
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
```
```
In block/mq-deadline.c (ffffffff81600234)
Location: include/linux/blk_types.h:463
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_limit_depth
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
In block/blk-mq.c (ffffffff81689769)
Location: include/linux/blk_types.h:495
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In block/blk-throttle.c (ffffffff816aabfb)
Location: include/linux/blk_types.h:495
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
```
```
In block/mq-deadline.c (ffffffff816b2955)
Location: include/linux/blk_types.h:495
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_limit_depth
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
In block/blk-mq.c (ffffffff81747c1f)
Location: include/linux/blk_types.h:494
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In block/blk-throttle.c (ffffffff817695fb)
Location: include/linux/blk_types.h:494
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
```
```
In block/mq-deadline.c (ffffffff81771eb5)
Location: include/linux/blk_types.h:494
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_limit_depth
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
In block/blk-core.c (ffffffff81772107)
Location: include/linux/blk_types.h:499
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-mq.c (ffffffff817842c7)
Location: include/linux/blk_types.h:499
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In block/mq-deadline.c (ffffffff817b1185)
Location: include/linux/blk_types.h:499
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_limit_depth
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
In block/blk-core.c (ffffffff817b43b1)
Location: include/linux/blk_types.h:498
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-mq.c (ffffffff817c65e6)
Location: include/linux/blk_types.h:498
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In block/mq-deadline.c (ffffffff817f4f95)
Location: include/linux/blk_types.h:498
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_limit_depth
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
In block/blk-core.c (ffff8000105e2e2c)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-mq.c (ffff8000105f0ea4)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-core.c (c078f1b0)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-mq.c (c079cf04)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-core.c (c00000000077540c)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-mq.c (c000000000787b40)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-core.c (ffffffe0004240f2)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-mq.c (ffffffe00042fb6c)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-core.c (ffffffff814dd0d7)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-mq.c (ffffffff814e9dd0)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-core.c (ffffffff814cda82)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-mq.c (ffffffff814da330)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-core.c (ffffffff814d9167)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-mq.c (ffffffff814e5e60)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-core.c (ffffffff814f1d7e)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-mq.c (ffffffff814fedd0)
Location: include/linux/blk_types.h:409
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_get_request
```
</details>
</li>
</ul>

## Differences
