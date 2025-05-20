# Function: <code>queue_max_discard_segments</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (0)
Location: include/linux/blkdev.h:1412
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/blkdev.h:1412
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:1412
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
In block/blk-core.c (0)
Location: include/linux/blkdev.h:1427
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/blkdev.h:1427
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:1427
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
In block/blk-core.c (0)
Location: include/linux/blkdev.h:1467
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/blkdev.h:1467
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:1467
Inline: True
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
In block/blk-core.c (0)
Location: include/linux/blkdev.h:1246
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/blkdev.h:1246
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:1246
Inline: True
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
In block/blk-core.c (0)
Location: include/linux/blkdev.h:1260
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/blkdev.h:1260
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:1260
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
In block/blk-core.c (0)
Location: include/linux/blkdev.h:1287
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/blkdev.h:1287
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:1287
Inline: True
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
In block/blk-core.c (ffffffff81545b29)
Location: include/linux/blkdev.h:1316
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-sysfs.c (ffffffff81546cc5)
Location: include/linux/blkdev.h:1316
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_max_discard_segments_show
```
```
In block/blk-merge.c (ffffffff8154cf6b)
Location: include/linux/blkdev.h:1316
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
  - block/blk-merge.c:ll_merge_requests_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
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
In block/blk-sysfs.c (ffffffff815629b9)
Location: include/linux/blkdev.h:1414
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_max_discard_segments_show
```
```
In block/blk-merge.c (ffffffff8156773a)
Location: include/linux/blkdev.h:1414
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:ll_merge_requests_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:blk_recalc_rq_segments
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
In block/blk-sysfs.c (ffffffff8156b069)
Location: include/linux/blkdev.h:1399
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_max_discard_segments_show
```
```
In block/blk-merge.c (ffffffff8156fdd0)
Location: include/linux/blkdev.h:1399
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:blk_recalc_rq_segments
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
In block/elevator.c (ffffffff815c9917)
Location: include/linux/blkdev.h:1374
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-sysfs.c (ffffffff815cf2d9)
Location: include/linux/blkdev.h:1374
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_max_discard_segments_show
```
```
In block/blk-merge.c (ffffffff815d446e)
Location: include/linux/blkdev.h:1374
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:blk_recalc_rq_segments
```
```
In block/mq-deadline.c (ffffffff8160150d)
Location: include/linux/blkdev.h:1374
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_request_merge
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
In block/elevator.c (ffffffff81674bf5)
Location: include/linux/blkdev.h:1185
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-sysfs.c (ffffffff8167a899)
Location: include/linux/blkdev.h:1185
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_max_discard_segments_show
```
```
In block/blk-merge.c (ffffffff816802ba)
Location: include/linux/blkdev.h:1185
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:blk_recalc_rq_segments
```
```
In block/mq-deadline.c (ffffffff816b3db9)
Location: include/linux/blkdev.h:1185
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_request_merge
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
In block/elevator.c (ffffffff81730945)
Location: include/linux/blkdev.h:1133
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-sysfs.c (ffffffff81736e59)
Location: include/linux/blkdev.h:1133
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_max_discard_segments_show
```
```
In block/blk-merge.c (ffffffff8173d686)
Location: include/linux/blkdev.h:1133
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:blk_recalc_rq_segments
```
```
In block/mq-deadline.c (ffffffff817734f7)
Location: include/linux/blkdev.h:1133
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_request_merge
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
In block/elevator.c (ffffffff8176cbab)
Location: include/linux/blkdev.h:1114
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-sysfs.c (ffffffff81773619)
Location: include/linux/blkdev.h:1114
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_max_discard_segments_show
```
```
In block/blk-merge.c (ffffffff81779c06)
Location: include/linux/blkdev.h:1114
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:blk_recalc_rq_segments
```
```
In block/blk-mq.c (ffffffff8178392b)
Location: include/linux/blkdev.h:1114
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
```
```
In block/mq-deadline.c (ffffffff817b2397)
Location: include/linux/blkdev.h:1114
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_request_merge
```
```
In drivers/block/virtio_blk.c (ffffffff81b7ec4a)
Location: include/linux/blkdev.h:1114
Inline: True
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
In block/elevator.c (ffffffff817aedd8)
Location: include/linux/blkdev.h:1099
Inline: True
Inline callers:
  - block/elevator.c:elv_merge
```
```
In block/blk-sysfs.c (ffffffff817b58f9)
Location: include/linux/blkdev.h:1099
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_max_discard_segments_show
```
```
In block/blk-merge.c (ffffffff817bbfd6)
Location: include/linux/blkdev.h:1099
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:blk_recalc_rq_segments
```
```
In block/blk-mq.c (ffffffff817c5c9b)
Location: include/linux/blkdev.h:1099
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
```
```
In block/mq-deadline.c (ffffffff817f61a7)
Location: include/linux/blkdev.h:1099
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_request_merge
```
```
In drivers/block/virtio_blk.c (ffffffff81bd3349)
Location: include/linux/blkdev.h:1099
Inline: True
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
In block/blk-core.c (0)
Location: include/linux/blkdev.h:1287
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/blkdev.h:1287
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:1287
Inline: True
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
In block/blk-core.c (c0791920)
Location: include/linux/blkdev.h:1287
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-sysfs.c (c0792998)
Location: include/linux/blkdev.h:1287
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_max_discard_segments_show
```
```
In block/blk-merge.c (c07983c8)
Location: include/linux/blkdev.h:1287
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
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
In block/blk-core.c (c0000000007784b0)
Location: include/linux/blkdev.h:1287
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-sysfs.c (c000000000779cbc)
Location: include/linux/blkdev.h:1287
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_max_discard_segments_show
```
```
In block/blk-merge.c (c0000000007813d0)
Location: include/linux/blkdev.h:1287
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
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
In block/blk-core.c (ffffffe000425e2e)
Location: include/linux/blkdev.h:1287
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
```
In block/blk-sysfs.c (ffffffe000426dee)
Location: include/linux/blkdev.h:1287
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_max_discard_segments_show
```
```
In block/blk-merge.c (ffffffe00042bbc2)
Location: include/linux/blkdev.h:1287
Inline: True
Inline callers:
  - block/blk-merge.c:blk_try_merge
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
In block/blk-core.c (0)
Location: include/linux/blkdev.h:1287
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/blkdev.h:1287
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:1287
Inline: True
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
In block/blk-core.c (0)
Location: include/linux/blkdev.h:1287
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/blkdev.h:1287
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:1287
Inline: True
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
In block/blk-core.c (0)
Location: include/linux/blkdev.h:1287
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/blkdev.h:1287
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:1287
Inline: True
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
In block/blk-core.c (0)
Location: include/linux/blkdev.h:1287
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/blkdev.h:1287
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/blkdev.h:1287
Inline: True
```
</details>
</li>
</ul>

## Differences
