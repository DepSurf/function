# Function: <code>blk_mq_is_shared_tags</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81675453)
Location: block/blk-mq.h:166
Inline: True
Inline callers:
  - block/elevator.c:elevator_init_mq
```
```
In block/blk-flush.c (ffffffff8167c084)
Location: block/blk-mq.h:166
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff8168bcc7)
Location: block/blk-mq.h:166
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_free_map_and_rqs
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:__blk_mq_get_driver_tag
  - block/blk-mq.c:__blk_mq_get_driver_tag
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff8168d911)
Location: block/blk-mq.h:166
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:bt_iter
  - block/blk-mq-tag.c:__blk_mq_get_tag
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-mq-sched.c (ffffffff8168fcb1)
Location: block/blk-mq.h:166
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_free_rqs
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_sched_tags_teardown
```
```
In block/blk-mq-debugfs.c (ffffffff816bb279)
Location: block/blk-mq.h:166
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:hctx_active_show
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
In block/elevator.c (ffffffff81730e83)
Location: block/blk-mq.h:167
Inline: True
Inline callers:
  - block/elevator.c:elevator_init_mq
```
```
In block/blk-flush.c (ffffffff817388e9)
Location: block/blk-mq.h:167
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff8174a3a5)
Location: block/blk-mq.h:167
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_free_map_and_rqs
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:__blk_mq_get_driver_tag
  - block/blk-mq.c:__blk_mq_get_driver_tag
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff8174c151)
Location: block/blk-mq.h:167
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:bt_iter
  - block/blk-mq-tag.c:__blk_mq_get_tag
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-mq-sched.c (ffffffff8174e851)
Location: block/blk-mq.h:167
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_free_rqs
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_sched_tags_teardown
```
```
In block/blk-mq-debugfs.c (ffffffff8177b9b9)
Location: block/blk-mq.h:167
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:hctx_active_show
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
In block/elevator.c (ffffffff8176d0e6)
Location: block/blk-mq.h:217
Inline: True
Inline callers:
  - block/elevator.c:elevator_init_mq
```
```
In block/blk-flush.c (ffffffff81774f29)
Location: block/blk-mq.h:217
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff81786aa8)
Location: block/blk-mq.h:217
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:__blk_mq_free_map_and_rqs
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:__blk_mq_get_driver_tag
  - block/blk-mq.c:__blk_mq_get_driver_tag
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:__blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff81788871)
Location: block/blk-mq.h:217
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:bt_iter
  - block/blk-mq-tag.c:__blk_mq_get_tag
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-mq-sched.c (ffffffff8178aad1)
Location: block/blk-mq.h:217
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_free_rqs
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_sched_tags_teardown
```
```
In block/blk-mq-debugfs.c (ffffffff817bb4c9)
Location: block/blk-mq.h:217
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:hctx_active_show
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
In block/elevator.c (ffffffff817af313)
Location: block/blk-mq.h:217
Inline: True
Inline callers:
  - block/elevator.c:elevator_init_mq
```
```
In block/blk-flush.c (ffffffff817b7256)
Location: block/blk-mq.h:217
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff817c917f)
Location: block/blk-mq.h:217
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:__blk_mq_free_map_and_rqs
  - block/blk-mq.c:blk_mq_free_rqs
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:__blk_mq_alloc_driver_tag
  - block/blk-mq.c:__blk_mq_alloc_driver_tag
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:__blk_mq_alloc_requests_batch
```
```
In block/blk-mq-tag.c (ffffffff817caf71)
Location: block/blk-mq.h:217
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:bt_iter
  - block/blk-mq-tag.c:__blk_mq_get_tag
  - block/blk-mq-tag.c:__blk_mq_tag_idle
  - block/blk-mq-tag.c:__blk_mq_tag_busy
```
```
In block/blk-mq-sched.c (ffffffff817cd221)
Location: block/blk-mq.h:217
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_free_rqs
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_sched_tags_teardown
```
```
In block/blk-mq-debugfs.c (ffffffff817ffbc9)
Location: block/blk-mq.h:217
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:hctx_active_show
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
