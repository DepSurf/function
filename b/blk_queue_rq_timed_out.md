# Function: <code>blk_queue_rq_timed_out</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_queue_rq_timed_out(struct request_queue *q, rq_timed_out_fn *fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff813bde90)
Location: block/blk-settings.c:68
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_queue
```
**Symbols:**

```
ffffffff813bde90-ffffffff813bdea2: blk_queue_rq_timed_out (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_queue_rq_timed_out(struct request_queue *q, rq_timed_out_fn *fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81401df0)
Location: block/blk-settings.c:68
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_queue
```
**Symbols:**

```
ffffffff81401df0-ffffffff81401e02: blk_queue_rq_timed_out (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_queue_rq_timed_out(struct request_queue *q, rq_timed_out_fn *fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8141ba60)
Location: block/blk-settings.c:69
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_queue
```
**Symbols:**

```
ffffffff8141ba60-ffffffff8141ba72: blk_queue_rq_timed_out (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_queue_rq_timed_out(struct request_queue *q, rq_timed_out_fn *fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81429a60)
Location: block/blk-settings.c:69
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_queue
```
**Symbols:**

```
ffffffff81429a60-ffffffff81429a72: blk_queue_rq_timed_out (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_queue_rq_timed_out(struct request_queue *q, rq_timed_out_fn *fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81455080)
Location: block/blk-settings.c:69
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_old_alloc_queue
```
**Symbols:**

```
ffffffff81455080-ffffffff814550a6: blk_queue_rq_timed_out (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_queue_rq_timed_out(struct request_queue *q, rq_timed_out_fn *fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81488080)
Location: block/blk-settings.c:69
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_old_alloc_queue
```
**Symbols:**

```
ffffffff81488080-ffffffff814880a6: blk_queue_rq_timed_out (STB_GLOBAL)
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
