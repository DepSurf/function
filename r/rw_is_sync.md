# Function: <code>rw_is_sync</code>

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
Location: include/linux/blkdev.h:615
Inline: True
```
```
In block/blk-core.c (ffffffff813b5e38)
Location: include/linux/blkdev.h:615
Inline: True
Inline callers:
  - block/blk-core.c:freed_request
  - block/blk-core.c:get_request
```
```
In block/blk-tag.c (0)
Location: include/linux/blkdev.h:615
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/blkdev.h:615
Inline: True
```
```
In block/cfq-iosched.c (ffffffff813e44fa)
Location: include/linux/blkdev.h:615
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
In block/elevator.c (ffffffff813f80e9)
Location: include/linux/blkdev.h:633
Inline: True
Inline callers:
  - block/elevator.c:elv_completed_request
  - block/elevator.c:elv_requeue_request
```
```
In block/blk-core.c (ffffffff813fed70)
Location: include/linux/blkdev.h:633
Inline: True
Inline callers:
  - block/blk-core.c:blk_dequeue_request
  - block/blk-core.c:get_request
  - block/blk-core.c:freed_request
```
```
In block/blk-tag.c (ffffffff813ffc7f)
Location: include/linux/blkdev.h:633
Inline: True
Inline callers:
  - block/blk-tag.c:blk_queue_start_tag
```
```
In block/blk-mq.c (ffffffff81409b8f)
Location: include/linux/blkdev.h:633
Inline: True
Inline callers:
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_map_request
  - block/blk-mq.c:blk_mq_free_hctx_request
  - block/blk-mq.c:__blk_mq_alloc_request
```
```
In block/cfq-iosched.c (ffffffff8142a75d)
Location: include/linux/blkdev.h:633
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_may_queue
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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
