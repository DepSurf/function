# Function: <code>blk_mq_map_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct blk_mq_hw_ctx *blk_mq_map_queue(struct request_queue *q, const int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c2d10)
Location: block/blk-mq.c:1410
Inline: False
```
**Symbols:**

```
ffffffff813c2d10-ffffffff813c2d33: blk_mq_map_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct blk_mq_hw_ctx *blk_mq_map_queue(struct request_queue *q, const int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81406910)
Location: block/blk-mq.c:1476
Inline: False
```
**Symbols:**

```
ffffffff81406910-ffffffff81406933: blk_mq_map_queue (STB_GLOBAL)
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
In block/blk-core.c (ffffffff814189af)
Location: block/blk-mq.h:47
Inline: True
Inline callers:
  - block/blk-core.c:blk_peek_request
  - block/blk-core.c:__blk_drain_queue
```
```
In block/blk-flush.c (ffffffff8141b702)
Location: block/blk-mq.h:47
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-mq.c (ffffffff81423e05)
Location: block/blk-mq.h:47
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_map_request
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_request
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-mq-tag.c (ffffffff8142592c)
Location: block/blk-mq.h:47
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_unique_tag
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
In block/blk-core.c (ffffffff8142688a)
Location: block/blk-mq.h:66
Inline: True
Inline callers:
  - block/blk-core.c:blk_peek_request
  - block/blk-core.c:__blk_drain_queue
```
```
In block/blk-flush.c (ffffffff8142975a)
Location: block/blk-mq.h:66
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-mq.c (ffffffff81432e69)
Location: block/blk-mq.h:66
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_request_bypass_insert
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_get_driver_tag
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff8143365d)
Location: block/blk-mq.h:66
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_unique_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff81435ccf)
Location: block/blk-mq.h:66
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
```
In block/blk-mq-debugfs.c (ffffffff8145a0ed)
Location: block/blk-mq.h:66
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
In block/blk-core.c (ffffffff814511c7)
Location: block/blk-mq.h:68
Inline: True
Inline callers:
  - block/blk-core.c:blk_peek_request
  - block/blk-core.c:__blk_drain_queue
```
```
In block/blk-flush.c (ffffffff8145493a)
Location: block/blk-mq.h:68
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-mq.c (ffffffff8145ea24)
Location: block/blk-mq.h:68
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_request_bypass_insert
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_get_driver_tag
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff8145f24d)
Location: block/blk-mq.h:68
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_unique_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff81461a3f)
Location: block/blk-mq.h:68
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
```
In block/blk-mq-debugfs.c (ffffffff81485e6d)
Location: block/blk-mq.h:68
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
In block/blk-core.c (ffffffff81484437)
Location: block/blk-mq.h:74
Inline: True
Inline callers:
  - block/blk-core.c:blk_peek_request
```
```
In block/blk-flush.c (ffffffff81487d73)
Location: block/blk-mq.h:74
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-mq.c (ffffffff81492367)
Location: block/blk-mq.h:74
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_request_bypass_insert
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_get_driver_tag
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff81492b78)
Location: block/blk-mq.h:74
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_unique_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff81495395)
Location: block/blk-mq.h:74
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
```
In block/blk-mq-debugfs.c (ffffffff814bad78)
Location: block/blk-mq.h:74
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
In block/blk-flush.c (ffffffff814a1daa)
Location: block/blk-mq.h:101
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff814a85fe)
Location: block/blk-mq.h:101
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814ad05e)
Location: block/blk-mq.h:101
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff814af08d)
Location: block/blk-mq.h:101
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-flush.c (0)
Location: block/blk-mq.h:102
Inline: True
```
```
In block/blk-mq.c (ffffffff814d602e)
Location: block/blk-mq.h:102
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814db34a)
Location: block/blk-mq.h:102
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff814dd34b)
Location: block/blk-mq.h:102
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-flush.c (0)
Location: block/blk-mq.h:103
Inline: True
```
```
In block/blk-mq.c (ffffffff814ef373)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814f477a)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff814f67bb)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-flush.c (ffffffff815482fb)
Location: block/blk-mq.h:102
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff8154ed37)
Location: block/blk-mq.h:102
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_request
```
```
In block/blk-mq-tag.c (ffffffff81554f49)
Location: block/blk-mq.h:102
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff8155726e)
Location: block/blk-mq.h:102
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-flush.c (ffffffff8156403b)
Location: block/blk-mq.h:104
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff8156b45a)
Location: block/blk-mq.h:104
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_request
```
```
In block/blk-mq-tag.c (ffffffff815715fe)
Location: block/blk-mq.h:104
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff815738f7)
Location: block/blk-mq.h:104
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-flush.c (ffffffff8156c7aa)
Location: block/blk-mq.h:105
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff815730c6)
Location: block/blk-mq.h:105
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_request
```
```
In block/blk-mq-tag.c (ffffffff8157962e)
Location: block/blk-mq.h:105
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff8157b9af)
Location: block/blk-mq.h:105
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-flush.c (ffffffff815d0c8a)
Location: block/blk-mq.h:105
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff815d7826)
Location: block/blk-mq.h:105
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_request
```
```
In block/blk-mq-tag.c (ffffffff815de83c)
Location: block/blk-mq.h:105
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff815e0d1f)
Location: block/blk-mq.h:105
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-flush.c (ffffffff8167c418)
Location: block/blk-mq.h:109
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff81684ddd)
Location: block/blk-mq.h:109
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:__blk_mq_alloc_requests
```
```
In block/blk-mq-tag.c (ffffffff8168ca97)
Location: block/blk-mq.h:109
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff8168f8b7)
Location: block/blk-mq.h:109
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_bio_merge
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
In block/blk-flush.c (ffffffff81738ca8)
Location: block/blk-mq.h:109
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff817415cb)
Location: block/blk-mq.h:109
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_requests
```
```
In block/blk-mq-tag.c (ffffffff8174b287)
Location: block/blk-mq.h:109
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff8174e407)
Location: block/blk-mq.h:109
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_bio_merge
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
In block/blk-flush.c (ffffffff817752d1)
Location: block/blk-mq.h:105
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff8178187d)
Location: block/blk-mq.h:105
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_requests
```
```
In block/blk-mq-tag.c (ffffffff817879a7)
Location: block/blk-mq.h:105
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff8178a947)
Location: block/blk-mq.h:105
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_bio_merge
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
In block/blk-flush.c (ffffffff817b75dc)
Location: block/blk-mq.h:105
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff817c3edd)
Location: block/blk-mq.h:105
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_requests
```
```
In block/blk-mq-tag.c (ffffffff817ca077)
Location: block/blk-mq.h:105
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff817cd097)
Location: block/blk-mq.h:105
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_bio_merge
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
In block/blk-flush.c (0)
Location: block/blk-mq.h:103
Inline: True
```
```
In block/blk-mq.c (ffff8000105ef848)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffff8000105f4554)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffff8000105f6dc8)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-flush.c (c0793bd4)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (c079a910)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (c07a01bc)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (c07a258c)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-flush.c (c00000000077ba8c)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (c00000000078466c)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (c00000000078bd6c)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (c00000000078f25c)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-flush.c (ffffffe00042803e)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffe00042d952)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffe0004324dc)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffe000434598)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-flush.c (0)
Location: block/blk-mq.h:103
Inline: True
```
```
In block/blk-mq.c (ffffffff814e7953)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814ecd5a)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff814eed9b)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-flush.c (0)
Location: block/blk-mq.h:103
Inline: True
```
```
In block/blk-mq.c (ffffffff814d7ec3)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814dd2aa)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff814df2db)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-flush.c (0)
Location: block/blk-mq.h:103
Inline: True
```
```
In block/blk-mq.c (ffffffff814e39e3)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff814e8dea)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff814eae2b)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
In block/blk-flush.c (0)
Location: block/blk-mq.h:103
Inline: True
```
```
In block/blk-mq.c (ffffffff814fcf47)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff81501d8a)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
```
```
In block/blk-mq-sched.c (ffffffff81503e0c)
Location: block/blk-mq.h:103
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
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
</ul>
