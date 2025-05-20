# Function: <code>blk_mq_is_sbitmap_shared</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81563c37)
Location: block/blk-mq.h:162
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff81570dda)
Location: block/blk-mq.h:162
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_get_driver_tag
  - block/blk-mq.c:__blk_mq_get_driver_tag
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff81570f7f)
Location: block/blk-mq.h:162
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_busy
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
In block/elevator.c (ffffffff81565cb0)
Location: block/blk-mq.h:163
Inline: True
Inline callers:
  - block/elevator.c:elevator_init_mq
```
```
In block/blk-flush.c (ffffffff8156c3b7)
Location: block/blk-mq.h:163
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff81578d1e)
Location: block/blk-mq.h:163
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_get_driver_tag
  - block/blk-mq.c:blk_mq_get_driver_tag
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff81579ed5)
Location: block/blk-mq.h:163
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:__blk_mq_get_tag
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_busy
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
In block/elevator.c (ffffffff815ca0ba)
Location: block/blk-mq.h:165
Inline: True
Inline callers:
  - block/elevator.c:elevator_init_mq
```
```
In block/blk-flush.c (ffffffff815d0857)
Location: block/blk-mq.h:165
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff815dddea)
Location: block/blk-mq.h:165
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_get_driver_tag
  - block/blk-mq.c:blk_mq_get_driver_tag
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff815df1f5)
Location: block/blk-mq.h:165
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_free_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:__blk_mq_get_tag
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-mq-sched.c (ffffffff815e1169)
Location: block/blk-mq.h:165
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_exit_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
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
