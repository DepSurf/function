# Function: <code>bio_blkcg</code>

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
In block/blk-core.c (ffffffff813b61ba)
Location: include/linux/blk-cgroup.h:231
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
```
```
In block/cfq-iosched.c (ffffffff813e1834)
Location: include/linux/blk-cgroup.h:231
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:check_blkcg_changed
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
In block/blk-core.c (ffffffff813faff0)
Location: include/linux/blk-cgroup.h:231
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
```
```
In block/cfq-iosched.c (ffffffff81427a64)
Location: include/linux/blk-cgroup.h:231
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:check_blkcg_changed
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
In block/blk-core.c (ffffffff81414abb)
Location: include/linux/blk-cgroup.h:231
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
```
```
In block/cfq-iosched.c (ffffffff81441664)
Location: include/linux/blk-cgroup.h:231
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:check_blkcg_changed
  - block/cfq-iosched.c:check_blkcg_changed
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
In block/blk-core.c (ffffffff81424769)
Location: include/linux/blk-cgroup.h:231
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
```
```
In block/cfq-iosched.c (ffffffff81450954)
Location: include/linux/blk-cgroup.h:231
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:check_blkcg_changed
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
In block/blk-core.c (ffffffff8144d895)
Location: include/linux/blk-cgroup.h:228
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
```
```
In block/blk-mq.c (ffffffff8145bee9)
Location: include/linux/blk-cgroup.h:228
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_bio_to_request
```
```
In block/cfq-iosched.c (ffffffff8147e60e)
Location: include/linux/blk-cgroup.h:228
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_get_queue
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
In block/blk-core.c (ffffffff814827cb)
Location: include/linux/blk-cgroup.h:229
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
```
```
In block/blk-mq.c (ffffffff8148eabc)
Location: include/linux/blk-cgroup.h:229
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_bio_to_request
```
```
In block/cfq-iosched.c (ffffffff814b25db)
Location: include/linux/blk-cgroup.h:229
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_get_queue
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
In kernel/trace/blktrace.c (ffffffff8119fb0c)
Location: include/linux/blk-cgroup.h:284
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
```
```
In block/bio.c (ffffffff81498346)
Location: include/linux/blk-cgroup.h:284
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
```
```
In drivers/block/loop.c (ffffffff816cc710)
Location: include/linux/blk-cgroup.h:284
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/trace/blktrace.c (ffffffff811ad85c)
Location: include/linux/blk-cgroup.h:291
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
```
```
In block/bio.c (ffffffff814c61c6)
Location: include/linux/blk-cgroup.h:291
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
```
```
In drivers/block/loop.c (ffffffff817081a5)
Location: include/linux/blk-cgroup.h:291
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/trace/blktrace.c (ffffffff811b90d8)
Location: include/linux/blk-cgroup.h:293
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_bio
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
```
```
In block/bio.c (ffffffff814de5c6)
Location: include/linux/blk-cgroup.h:293
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
```
```
In drivers/block/loop.c (ffffffff8172c3f5)
Location: include/linux/blk-cgroup.h:293
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/trace/blktrace.c (ffffffff811d23ad)
Location: include/linux/blk-cgroup.h:271
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_bio_queue
  - kernel/trace/blktrace.c:blk_add_trace_bio_frontmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_backmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_complete
  - kernel/trace/blktrace.c:blk_add_trace_bio_bounce
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
```
```
In block/bio.c (ffffffff8153ea77)
Location: include/linux/blk-cgroup.h:271
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
```
```
In drivers/block/loop.c (ffffffff817e7bb5)
Location: include/linux/blk-cgroup.h:271
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/trace/blktrace.c (ffffffff811cefe0)
Location: include/linux/blk-cgroup.h:261
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_bio
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_merge
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
```
```
In block/blk-cgroup.c (ffffffff81586496)
Location: include/linux/blk-cgroup.h:261
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_associate_blkg
```
```
In drivers/block/loop.c (ffffffff817fca95)
Location: include/linux/blk-cgroup.h:261
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/trace/blktrace.c (ffffffff811d084e)
Location: include/linux/blk-cgroup.h:261
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_bio
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_merge
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
```
```
In block/blk-cgroup.c (ffffffff8158cea6)
Location: include/linux/blk-cgroup.h:261
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_associate_blkg
```
```
In drivers/block/loop.c (ffffffff817e1665)
Location: include/linux/blk-cgroup.h:261
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/trace/blktrace.c (ffffffff811fd17e)
Location: include/linux/blk-cgroup.h:266
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_bio
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_merge
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
```
```
In block/blk-cgroup.c (ffffffff815f2706)
Location: include/linux/blk-cgroup.h:266
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_associate_blkg
```
```
In drivers/block/loop.c (ffffffff8186fef1)
Location: include/linux/blk-cgroup.h:266
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/trace/blktrace.c (ffff800010237ce0)
Location: include/linux/blk-cgroup.h:293
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_bio
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
```
```
In block/bio.c (ffff8000105dba18)
Location: include/linux/blk-cgroup.h:293
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
```
```
In drivers/block/loop.c (ffff800010924f04)
Location: include/linux/blk-cgroup.h:293
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/trace/blktrace.c (c0473340)
Location: include/linux/blk-cgroup.h:293
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_bio
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
```
```
In block/bio.c (c07885b0)
Location: include/linux/blk-cgroup.h:293
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
```
```
In drivers/block/loop.c (c0a07cdc)
Location: include/linux/blk-cgroup.h:293
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/trace/blktrace.c (c0000000002c3754)
Location: include/linux/blk-cgroup.h:293
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_bio
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
```
```
In block/bio.c (c00000000076b9b0)
Location: include/linux/blk-cgroup.h:293
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
```
```
In drivers/block/loop.c (c0000000009c791c)
Location: include/linux/blk-cgroup.h:293
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/trace/blktrace.c (ffffffe00018e64a)
Location: include/linux/blk-cgroup.h:293
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_bio
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
```
```
In block/bio.c (ffffffe00041e63a)
Location: include/linux/blk-cgroup.h:293
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
```
```
In drivers/block/loop.c (ffffffe0005a106a)
Location: include/linux/blk-cgroup.h:293
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/trace/blktrace.c (ffffffff811b16f8)
Location: include/linux/blk-cgroup.h:293
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_bio
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
```
```
In block/bio.c (ffffffff814d6ba6)
Location: include/linux/blk-cgroup.h:293
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
```
```
In drivers/block/loop.c (ffffffff816f21d5)
Location: include/linux/blk-cgroup.h:293
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/trace/blktrace.c (ffffffff811a4698)
Location: include/linux/blk-cgroup.h:293
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_bio
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
```
```
In block/bio.c (ffffffff814c7566)
Location: include/linux/blk-cgroup.h:293
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
```
```
In drivers/block/loop.c (ffffffff816cc2d5)
Location: include/linux/blk-cgroup.h:293
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/trace/blktrace.c (ffffffff811af4c8)
Location: include/linux/blk-cgroup.h:293
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_bio
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
```
```
In block/bio.c (ffffffff814d2c36)
Location: include/linux/blk-cgroup.h:293
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
```
```
In drivers/block/loop.c (ffffffff8171f8b5)
Location: include/linux/blk-cgroup.h:293
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
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
In kernel/trace/blktrace.c (ffffffff811bd4b0)
Location: include/linux/blk-cgroup.h:293
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_bio
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
```
```
In block/bio.c (ffffffff814eb7bd)
Location: include/linux/blk-cgroup.h:293
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
```
```
In drivers/block/loop.c (ffffffff8173acf5)
Location: include/linux/blk-cgroup.h:293
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
```
</details>
</li>
</ul>

## Differences
