# Function: <code>op_needs_zoned_write_locking</code>

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
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8177b53a)
Location: include/linux/blkdev.h:1277
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_plug_merge
```
```
In block/blk-mq.c (ffffffff817845d3)
Location: include/linux/blkdev.h:1277
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In block/mq-deadline.c (ffffffff817b3ea1)
Location: include/linux/blkdev.h:1277
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_write2_next_rq_show
  - block/mq-deadline.c:deadline_read2_next_rq_show
  - block/mq-deadline.c:deadline_write1_next_rq_show
  - block/mq-deadline.c:deadline_read1_next_rq_show
  - block/mq-deadline.c:deadline_write0_next_rq_show
  - block/mq-deadline.c:deadline_read0_next_rq_show
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff817b787b)
Location: include/linux/blkdev.h:1277
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
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
In block/blk-merge.c (ffffffff817bd89d)
Location: include/linux/blkdev.h:1257
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_plug_merge
```
```
In block/blk-mq.c (ffffffff817c65d5)
Location: include/linux/blkdev.h:1257
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In block/mq-deadline.c (ffffffff817f7a1a)
Location: include/linux/blkdev.h:1257
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_write2_next_rq_show
  - block/mq-deadline.c:deadline_read2_next_rq_show
  - block/mq-deadline.c:deadline_write1_next_rq_show
  - block/mq-deadline.c:deadline_read1_next_rq_show
  - block/mq-deadline.c:deadline_write0_next_rq_show
  - block/mq-deadline.c:deadline_read0_next_rq_show
  - block/mq-deadline.c:deadline_next_request
```
```
In block/blk-zoned.c (ffffffff817fc0d7)
Location: include/linux/blkdev.h:1257
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_req_needs_zone_write_lock
```
</details>
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
