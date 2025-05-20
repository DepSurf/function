# Function: <code>blk_requeue_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_requeue_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b5f10)
Location: block/blk-core.c:1385
Inline: True
Direct callers:
  - block/blk-tag.c:blk_queue_invalidate_tags
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/md/dm.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff813b5f10-ffffffff813b5fb4: blk_requeue_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void blk_requeue_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fad60)
Location: block/blk-core.c:1344
Inline: True
Direct callers:
  - block/blk-tag.c:blk_queue_invalidate_tags
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff813fad60-ffffffff813fae03: blk_requeue_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_requeue_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814146a0)
Location: block/blk-core.c:1345
Inline: True
Direct callers:
  - block/blk-tag.c:blk_queue_invalidate_tags
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff814146a0-ffffffff8141474e: blk_requeue_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_requeue_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81421dd0)
Location: block/blk-core.c:1446
Inline: False
Direct callers:
  - block/blk-tag.c:blk_queue_invalidate_tags
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81421dd0-ffffffff81421e8f: blk_requeue_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_requeue_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144c900)
Location: block/blk-core.c:1551
Inline: False
Direct callers:
  - block/blk-tag.c:blk_queue_invalidate_tags
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff8144c900-ffffffff8144c9c2: blk_requeue_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_requeue_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8147fc10)
Location: block/blk-core.c:1647
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff8147fc10-ffffffff8147fcdb: blk_requeue_request (STB_GLOBAL)
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
