# Function: <code>blk_queue_prep_rq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_queue_prep_rq(struct request_queue *q, prep_rq_fn *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff813bde10)
Location: block/blk-settings.c:33
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_queue
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff813bde10-ffffffff813bde22: blk_queue_prep_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_queue_prep_rq(struct request_queue *q, prep_rq_fn *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81401d70)
Location: block/blk-settings.c:33
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_queue
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff81401d70-ffffffff81401d82: blk_queue_prep_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_queue_prep_rq(struct request_queue *q, prep_rq_fn *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8141b9e0)
Location: block/blk-settings.c:34
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_queue
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff8141b9e0-ffffffff8141b9f2: blk_queue_prep_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_queue_prep_rq(struct request_queue *q, prep_rq_fn *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814299e0)
Location: block/blk-settings.c:34
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_queue
```
**Symbols:**

```
ffffffff814299e0-ffffffff814299f2: blk_queue_prep_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_queue_prep_rq(struct request_queue *q, prep_rq_fn *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81454bc0)
Location: block/blk-settings.c:34
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_old_alloc_queue
```
**Symbols:**

```
ffffffff81454bc0-ffffffff81454bd2: blk_queue_prep_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_queue_prep_rq(struct request_queue *q, prep_rq_fn *pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81488000)
Location: block/blk-settings.c:34
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_old_alloc_queue
```
**Symbols:**

```
ffffffff81488000-ffffffff81488012: blk_queue_prep_rq (STB_GLOBAL)
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
