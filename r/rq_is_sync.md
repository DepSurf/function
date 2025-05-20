# Function: <code>rq_is_sync</code>

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
In block/elevator.c (0)
Location: include/linux/blkdev.h:620
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/blkdev.h:620
Inline: True
```
```
In block/blk-tag.c (0)
Location: include/linux/blkdev.h:620
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blkdev.h:620
Inline: True
```
```
In block/cfq-iosched.c (ffffffff813e44fa)
Location: include/linux/blkdev.h:620
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_set_request
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
In block/elevator.c (ffffffff813f80e6)
Location: include/linux/blkdev.h:638
Inline: True
Inline callers:
  - block/elevator.c:elv_completed_request
  - block/elevator.c:elv_requeue_request
```
```
In block/blk-core.c (ffffffff813fed6d)
Location: include/linux/blkdev.h:638
Inline: True
Inline callers:
  - block/blk-core.c:blk_dequeue_request
```
```
In block/blk-tag.c (ffffffff813ffc74)
Location: include/linux/blkdev.h:638
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_start_tag
```
```
In block/blk-mq.c (ffffffff81406c54)
Location: include/linux/blkdev.h:638
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_hctx_request
```
```
In block/cfq-iosched.c (ffffffff8142a75d)
Location: include/linux/blkdev.h:638
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_allow_bio_merge
  - block/cfq-iosched.c:cfq_remove_request
  - block/cfq-iosched.c:cfq_add_rq_rb
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
In block/elevator.c (ffffffff81411b06)
Location: include/linux/blkdev.h:747
Inline: True
Inline callers:
  - block/elevator.c:elv_completed_request
  - block/elevator.c:elv_requeue_request
```
```
In block/blk-core.c (ffffffff8141875e)
Location: include/linux/blkdev.h:747
Inline: True
Inline callers:
  - block/blk-core.c:blk_dequeue_request
```
```
In block/blk-tag.c (ffffffff81419525)
Location: include/linux/blkdev.h:747
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_start_tag
```
```
In block/blk-mq.c (ffffffff81421058)
Location: include/linux/blkdev.h:747
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_hctx_request
```
```
In block/cfq-iosched.c (ffffffff81444ae8)
Location: include/linux/blkdev.h:747
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_allow_bio_merge
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
Location: include/linux/blkdev.h:790
Inline: True
Inline callers:
  - block/elevator.c:elv_completed_request
  - block/elevator.c:elv_requeue_request
```
```
In block/blk-core.c (ffffffff81426752)
Location: include/linux/blkdev.h:790
Inline: True
Inline callers:
  - block/blk-core.c:blk_dequeue_request
```
```
In block/blk-tag.c (ffffffff81427455)
Location: include/linux/blkdev.h:790
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_start_tag
```
```
In block/blk-mq.c (ffffffff8142f73d)
Location: include/linux/blkdev.h:790
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/cfq-iosched.c (ffffffff81453924)
Location: include/linux/blkdev.h:790
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_allow_bio_merge
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
Location: include/linux/blkdev.h:810
Inline: True
Inline callers:
  - block/elevator.c:elv_completed_request
  - block/elevator.c:elv_requeue_request
```
```
In block/blk-core.c (ffffffff8144cc33)
Location: include/linux/blkdev.h:810
Inline: True
Inline callers:
  - block/blk-core.c:blk_start_request
```
```
In block/blk-tag.c (ffffffff81452455)
Location: include/linux/blkdev.h:810
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_start_tag
```
```
In block/blk-mq.c (ffffffff8145ac40)
Location: include/linux/blkdev.h:810
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/cfq-iosched.c (ffffffff8147e5bc)
Location: include/linux/blkdev.h:810
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_allow_bio_merge
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
Location: include/linux/blkdev.h:824
Inline: True
Inline callers:
  - block/elevator.c:elv_completed_request
  - block/elevator.c:elv_requeue_request
```
```
In block/blk-core.c (ffffffff8147fec2)
Location: include/linux/blkdev.h:824
Inline: True
Inline callers:
  - block/blk-core.c:blk_start_request
```
```
In block/blk-tag.c (ffffffff814858c6)
Location: include/linux/blkdev.h:824
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_start_tag
```
```
In block/blk-mq.c (ffffffff8148dcf3)
Location: include/linux/blkdev.h:824
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/cfq-iosched.c (ffffffff814b259a)
Location: include/linux/blkdev.h:824
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_allow_bio_merge
  - block/cfq-iosched.c:cfq_remove_request
  - block/cfq-iosched.c:cfq_add_rq_rb
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
In block/blk-mq.c (ffffffff814a75d1)
Location: include/linux/blkdev.h:710
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
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
In block/blk-mq.c (ffffffff814d5525)
Location: include/linux/blkdev.h:722
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
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
In block/blk-mq.c (ffffffff814ee805)
Location: include/linux/blkdev.h:739
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
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
In block/blk-mq.c (ffffffff8154f480)
Location: include/linux/blkdev.h:752
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
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
In block/blk-mq.c (ffffffff8156b7c0)
Location: include/linux/blkdev.h:801
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
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
In block/blk-mq.c (ffffffff81573490)
Location: include/linux/blkdev.h:803
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
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
In block/blk-mq.c (ffffffff815d7a30)
Location: include/linux/blkdev.h:769
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105ee4f0)
Location: include/linux/blkdev.h:739
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
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
In block/blk-mq.c (c0799970)
Location: include/linux/blkdev.h:739
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
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
In block/blk-mq.c (c0000000007832d8)
Location: include/linux/blkdev.h:739
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
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
In block/blk-mq.c (ffffffe00042ce02)
Location: include/linux/blkdev.h:739
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
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
In block/blk-mq.c (ffffffff814e6de5)
Location: include/linux/blkdev.h:739
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
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
In block/blk-mq.c (ffffffff814d7355)
Location: include/linux/blkdev.h:739
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
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
In block/blk-mq.c (ffffffff814e2e75)
Location: include/linux/blkdev.h:739
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
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
In block/blk-mq.c (ffffffff814fbcf5)
Location: include/linux/blkdev.h:739
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
</details>
</li>
</ul>

## Differences
