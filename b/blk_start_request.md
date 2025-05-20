# Function: <code>blk_start_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_start_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813baff0)
Location: block/blk-core.c:2502
Inline: True
Direct callers:
  - block/blk-core.c:blk_peek_request
  - block/blk-core.c:blk_fetch_request
  - block/blk-tag.c:blk_queue_start_tag
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/md/dm.c:dm_start_request
```
**Symbols:**

```
ffffffff813baff0-ffffffff813bb03d: blk_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void blk_start_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fedb0)
Location: block/blk-core.c:2474
Inline: True
Direct callers:
  - block/blk-core.c:blk_fetch_request
  - block/blk-core.c:blk_peek_request
  - block/blk-tag.c:blk_queue_start_tag
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/md/dm-rq.c:dm_start_request
```
**Symbols:**

```
ffffffff813fedb0-ffffffff813fedfd: blk_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_start_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814187a0)
Location: block/blk-core.c:2457
Inline: True
Direct callers:
  - block/blk-core.c:blk_fetch_request
  - block/blk-core.c:blk_peek_request
  - block/blk-tag.c:blk_queue_start_tag
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/md/dm-rq.c:dm_start_request
```
**Symbols:**

```
ffffffff814187a0-ffffffff81418825: blk_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_start_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81426790)
Location: block/blk-core.c:2642
Inline: False
Direct callers:
  - block/blk-core.c:blk_fetch_request
  - block/blk-core.c:blk_peek_request
  - block/blk-tag.c:blk_queue_start_tag
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/md/dm-rq.c:dm_start_request
```
**Symbols:**

```
ffffffff81426790-ffffffff81426859: blk_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_start_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144cbd0)
Location: block/blk-core.c:2845
Inline: False
Direct callers:
  - block/blk-core.c:blk_fetch_request
  - block/blk-core.c:blk_peek_request
  - block/blk-tag.c:blk_queue_start_tag
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/md/dm-rq.c:dm_start_request
```
**Symbols:**

```
ffffffff8144cbd0-ffffffff8144ccfe: blk_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_start_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8147fe60)
Location: block/blk-core.c:2986
Inline: False
Direct callers:
  - block/blk-core.c:blk_fetch_request
  - block/blk-core.c:blk_peek_request
  - block/blk-tag.c:blk_queue_start_tag
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/md/dm-rq.c:dm_start_request
```
**Symbols:**

```
ffffffff8147fe60-ffffffff8147ff39: blk_start_request (STB_GLOBAL)
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
