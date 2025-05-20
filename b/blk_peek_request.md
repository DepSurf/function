# Function: <code>blk_peek_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct request *blk_peek_request(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813bb180)
Location: block/blk-core.c:2379
Inline: False
Direct callers:
  - block/blk-core.c:blk_fetch_request
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/md/dm.c:dm_request_fn
```
**Symbols:**

```
ffffffff813bb180-ffffffff813bb402: blk_peek_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct request *blk_peek_request(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fef50)
Location: block/blk-core.c:2349
Inline: False
Direct callers:
  - block/blk-core.c:blk_fetch_request
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff813fef50-ffffffff813ff1fa: blk_peek_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct request *blk_peek_request(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81418980)
Location: block/blk-core.c:2332
Inline: False
Direct callers:
  - block/blk-core.c:blk_fetch_request
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff81418980-ffffffff81418c38: blk_peek_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct request *blk_peek_request(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81426860)
Location: block/blk-core.c:2518
Inline: False
Direct callers:
  - block/blk-core.c:blk_fetch_request
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff81426860-ffffffff81426b0e: blk_peek_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct request *blk_peek_request(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814510a0)
Location: block/blk-core.c:2729
Inline: False
Direct callers:
  - block/blk-core.c:blk_fetch_request
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff814510a0-ffffffff81451360: blk_peek_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct request *blk_peek_request(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:2872
Inline: False
Direct callers:
  - block/blk-core.c:blk_fetch_request
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff814857d7-ffffffff814857f2: blk_peek_request.cold.102 (STB_LOCAL)
ffffffff81484310-ffffffff814845c1: blk_peek_request (STB_GLOBAL)
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
