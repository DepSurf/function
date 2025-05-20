# Function: <code>__blk_put_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __blk_put_request(struct request_queue *q, struct request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b65d0)
Location: block/blk-core.c:1463
Inline: True
Direct callers:
  - block/blk-core.c:blk_put_request
  - block/blk-core.c:blk_finish_request
  - block/blk-core.c:blk_finish_request
  - block/blk-merge.c:attempt_merge
  - drivers/scsi/scsi_error.c:eh_lock_door_done
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/md/dm.c:end_clone_request
```
**Symbols:**

```
ffffffff813b65d0-ffffffff813b6768: __blk_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __blk_put_request(struct request_queue *q, struct request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fb420)
Location: block/blk-core.c:1422
Inline: True
Direct callers:
  - block/blk-core.c:blk_finish_request
  - block/blk-core.c:blk_finish_request
  - block/blk-core.c:blk_put_request
  - drivers/scsi/scsi_error.c:eh_lock_door_done
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/md/dm-rq.c:end_clone_request
```
**Symbols:**

```
ffffffff813fb420-ffffffff813fb5c2: __blk_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __blk_put_request(struct request_queue *q, struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81414ed0)
Location: block/blk-core.c:1424
Inline: False
Direct callers:
  - block/blk-core.c:blk_finish_request
  - block/blk-core.c:blk_finish_request
  - block/blk-core.c:blk_put_request
  - drivers/scsi/scsi_error.c:eh_lock_door_done
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/md/dm-rq.c:end_clone_request
```
**Symbols:**

```
ffffffff81414ed0-ffffffff814150b3: __blk_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __blk_put_request(struct request_queue *q, struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81423480)
Location: block/blk-core.c:1525
Inline: False
Direct callers:
  - block/blk-core.c:blk_finish_request
  - block/blk-core.c:blk_finish_request
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_put_request
  - block/blk-merge.c:blk_attempt_req_merge
  - drivers/scsi/scsi_error.c:eh_lock_door_done
  - drivers/scsi/sg.c:sg_rq_end_io
```
**Symbols:**

```
ffffffff81423480-ffffffff8142361c: __blk_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __blk_put_request(struct request_queue *q, struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144ee20)
Location: block/blk-core.c:1644
Inline: False
Direct callers:
  - block/blk-core.c:blk_finish_request
  - block/blk-core.c:blk_finish_request
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_put_request
  - block/blk-merge.c:blk_attempt_req_merge
  - drivers/scsi/scsi_error.c:eh_lock_door_done
  - drivers/scsi/sg.c:sg_rq_end_io
```
**Symbols:**

```
ffffffff8144ee20-ffffffff8144f004: __blk_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __blk_put_request(struct request_queue *q, struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814819c0)
Location: block/blk-core.c:1740
Inline: False
Direct callers:
  - block/blk-core.c:blk_finish_request
  - block/blk-core.c:blk_finish_request
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_put_request
  - block/blk-merge.c:blk_attempt_req_merge
  - drivers/scsi/scsi_error.c:eh_lock_door_done
  - drivers/scsi/sg.c:sg_rq_end_io
```
**Symbols:**

```
ffffffff814819c0-ffffffff81481bc3: __blk_put_request (STB_GLOBAL)
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
