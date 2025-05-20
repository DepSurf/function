# Function: <code>blk_queue_softirq_done</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_queue_softirq_done(struct request_queue *q, softirq_done_fn *fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff813bde50)
Location: block/blk-settings.c:56
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/scsi/scsi_lib.c:scsi_alloc_queue
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff813bde50-ffffffff813bde62: blk_queue_softirq_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_queue_softirq_done(struct request_queue *q, softirq_done_fn *fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81401db0)
Location: block/blk-settings.c:56
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/scsi/scsi_lib.c:scsi_alloc_queue
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff81401db0-ffffffff81401dc2: blk_queue_softirq_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_queue_softirq_done(struct request_queue *q, softirq_done_fn *fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8141ba20)
Location: block/blk-settings.c:57
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/scsi/scsi_lib.c:scsi_alloc_queue
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff8141ba20-ffffffff8141ba32: blk_queue_softirq_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_queue_softirq_done(struct request_queue *q, softirq_done_fn *fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81429a20)
Location: block/blk-settings.c:57
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/scsi/scsi_lib.c:scsi_alloc_queue
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff81429a20-ffffffff81429a32: blk_queue_softirq_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_queue_softirq_done(struct request_queue *q, softirq_done_fn *fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81454c00)
Location: block/blk-settings.c:57
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/scsi/scsi_lib.c:scsi_old_alloc_queue
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff81454c00-ffffffff81454c12: blk_queue_softirq_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_queue_softirq_done(struct request_queue *q, softirq_done_fn *fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81488040)
Location: block/blk-settings.c:57
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/scsi/scsi_lib.c:scsi_old_alloc_queue
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff81488040-ffffffff81488052: blk_queue_softirq_done (STB_GLOBAL)
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
