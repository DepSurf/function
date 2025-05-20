# Function: <code>blk_run_queue_async</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_run_queue_async(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b5690)
Location: block/blk-core.c:354
Inline: False
Direct callers:
  - block/blk-core.c:blk_start_queue_async
  - block/blk-core.c:queue_unplugged
  - block/blk-flush.c:flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - drivers/md/dm.c:rq_completed
  - drivers/md/dm.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff813b5690-ffffffff813b56cf: blk_run_queue_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_run_queue_async(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fa510)
Location: block/blk-core.c:354
Inline: False
Direct callers:
  - block/blk-core.c:queue_unplugged
  - block/blk-core.c:blk_start_queue_async
  - block/blk-flush.c:flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - drivers/md/dm-rq.c:dm_requeue_original_request
  - drivers/md/dm-rq.c:rq_completed
```
**Symbols:**

```
ffffffff813fa510-ffffffff813fa54f: blk_run_queue_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_run_queue_async(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81413e90)
Location: block/blk-core.c:355
Inline: False
Direct callers:
  - block/blk-core.c:queue_unplugged
  - block/blk-core.c:blk_start_queue_async
  - block/blk-flush.c:flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - drivers/md/dm-rq.c:dm_requeue_original_request
  - drivers/md/dm-rq.c:rq_completed
```
**Symbols:**

```
ffffffff81413e90-ffffffff81413ecf: blk_run_queue_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_run_queue_async(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814218d0)
Location: block/blk-core.c:413
Inline: False
Direct callers:
  - block/blk-core.c:queue_unplugged
  - block/blk-core.c:blk_start_queue_async
  - block/blk-flush.c:flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - drivers/md/dm-rq.c:dm_requeue_original_request
  - drivers/md/dm-rq.c:rq_completed
```
**Symbols:**

```
ffffffff814218d0-ffffffff81421927: blk_run_queue_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_run_queue_async(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144c420)
Location: block/blk-core.c:446
Inline: False
Direct callers:
  - block/blk-core.c:queue_unplugged
  - block/blk-core.c:blk_start_queue_async
  - block/blk-flush.c:flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - drivers/md/dm-rq.c:rq_completed
```
**Symbols:**

```
ffffffff8144c420-ffffffff8144c46c: blk_run_queue_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_run_queue_async(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8147f6c0)
Location: block/blk-core.c:507
Inline: False
Direct callers:
  - block/blk-core.c:queue_unplugged
  - block/blk-core.c:blk_start_queue_async
  - block/blk-flush.c:flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - drivers/md/dm-rq.c:rq_completed
```
**Symbols:**

```
ffffffff8147f6c0-ffffffff8147f70c: blk_run_queue_async (STB_GLOBAL)
```
</details>
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
