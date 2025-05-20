# Function: <code>blk_start_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_start_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b55a0)
Location: block/blk-core.c:234
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock
  - drivers/md/dm.c:start_queue
```
**Symbols:**

```
ffffffff813b55a0-ffffffff813b55df: blk_start_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_start_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fa420)
Location: block/blk-core.c:234
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff813fa420-ffffffff813fa45f: blk_start_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_start_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81413da0)
Location: block/blk-core.c:235
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff81413da0-ffffffff81413ddf: blk_start_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_start_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814223f0)
Location: block/blk-core.c:280
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_start_queue
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff814223f0-ffffffff8142243c: blk_start_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_start_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144d4d0)
Location: block/blk-core.c:280
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_start_queue
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff8144d4d0-ffffffff8144d51c: blk_start_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_start_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81480780)
Location: block/blk-core.c:353
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_start_queue
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff81480780-ffffffff814807a7: blk_start_queue (STB_GLOBAL)
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
