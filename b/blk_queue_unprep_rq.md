# Function: <code>blk_queue_unprep_rq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_queue_unprep_rq(struct request_queue *q, unprep_rq_fn *ufn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff813bde30)
Location: block/blk-settings.c:50
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_queue
```
**Symbols:**

```
ffffffff813bde30-ffffffff813bde42: blk_queue_unprep_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_queue_unprep_rq(struct request_queue *q, unprep_rq_fn *ufn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81401d90)
Location: block/blk-settings.c:50
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_queue
```
**Symbols:**

```
ffffffff81401d90-ffffffff81401da2: blk_queue_unprep_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_queue_unprep_rq(struct request_queue *q, unprep_rq_fn *ufn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8141ba00)
Location: block/blk-settings.c:51
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_queue
```
**Symbols:**

```
ffffffff8141ba00-ffffffff8141ba12: blk_queue_unprep_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_queue_unprep_rq(struct request_queue *q, unprep_rq_fn *ufn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81429a00)
Location: block/blk-settings.c:51
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_queue
```
**Symbols:**

```
ffffffff81429a00-ffffffff81429a12: blk_queue_unprep_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_queue_unprep_rq(struct request_queue *q, unprep_rq_fn *ufn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81454be0)
Location: block/blk-settings.c:51
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_old_alloc_queue
```
**Symbols:**

```
ffffffff81454be0-ffffffff81454bf2: blk_queue_unprep_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_queue_unprep_rq(struct request_queue *q, unprep_rq_fn *ufn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81488020)
Location: block/blk-settings.c:51
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_old_alloc_queue
```
**Symbols:**

```
ffffffff81488020-ffffffff81488032: blk_queue_unprep_rq (STB_GLOBAL)
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
