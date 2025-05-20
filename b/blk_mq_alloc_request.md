# Function: <code>blk_mq_alloc_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request(struct request_queue *q, int rw, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c4a70)
Location: block/blk-mq.c:232
Inline: False
Direct callers:
  - block/blk-core.c:blk_get_request
```
**Symbols:**

```
ffffffff813c4a70-ffffffff813c4b9a: blk_mq_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request(struct request_queue *q, int rw, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81408c10)
Location: block/blk-mq.c:233
Inline: False
Direct callers:
  - block/blk-core.c:blk_get_request
```
**Symbols:**

```
ffffffff81408c10-ffffffff81408d62: blk_mq_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct request *blk_mq_alloc_request(struct request_queue *q, int rw, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81421620)
Location: block/blk-mq.c:240
Inline: True
Direct callers:
  - block/blk-core.c:blk_get_request
```
**Symbols:**

```
ffffffff81421620-ffffffff81421707: blk_mq_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request(struct request_queue *q, unsigned int op, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8142f460)
Location: block/blk-mq.c:351
Inline: False
```
**Symbols:**

```
ffffffff8142f460-ffffffff8142f525: blk_mq_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145a9b0)
Location: block/blk-mq.c:387
Inline: False
Direct callers:
  - block/blk-core.c:blk_get_request_flags
```
**Symbols:**

```
ffffffff8145a9b0-ffffffff8145aa72: blk_mq_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148ef40)
Location: block/blk-mq.c:399
Inline: False
Direct callers:
  - block/blk-core.c:blk_get_request
```
**Symbols:**

```
ffffffff8148ef40-ffffffff8148efff: blk_mq_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a89c0)
Location: block/blk-mq.c:412
Inline: False
Direct callers:
  - block/blk-core.c:blk_get_request
```
**Symbols:**

```
ffffffff814a89c0-ffffffff814a8a86: blk_mq_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d63a0)
Location: block/blk-mq.c:411
Inline: False
Direct callers:
  - block/blk-core.c:blk_get_request
```
**Symbols:**

```
ffffffff814d63a0-ffffffff814d6471: blk_mq_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ef710)
Location: block/blk-mq.c:422
Inline: False
Direct callers:
  - block/blk-core.c:blk_get_request
```
**Symbols:**

```
ffffffff814ef710-ffffffff814ef7e1: blk_mq_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8154eda0)
Location: block/blk-mq.c:405
Inline: False
Direct callers:
  - block/blk-core.c:blk_get_request
```
**Symbols:**

```
ffffffff8154eda0-ffffffff8154ee56: blk_mq_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156b4c0)
Location: block/blk-mq.c:401
Inline: False
Direct callers:
  - block/blk-core.c:blk_get_request
```
**Symbols:**

```
ffffffff8156b4c0-ffffffff8156b576: blk_mq_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81573120)
Location: block/blk-mq.c:402
Inline: False
Direct callers:
  - block/blk-core.c:blk_get_request
```
**Symbols:**

```
ffffffff81573120-ffffffff815731d6: blk_mq_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d78d0)
Location: block/blk-mq.c:409
Inline: False
Direct callers:
  - block/blk-core.c:blk_get_request
```
**Symbols:**

```
ffffffff815d78d0-ffffffff815d7986: blk_mq_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81684040)
Location: block/blk-mq.c:510
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - drivers/scsi/scsi_lib.c:__scsi_execute
```
**Symbols:**

```
ffffffff81684040-ffffffff8168410a: blk_mq_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request(struct request_queue *q, blk_opf_t opf, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817416b0)
Location: block/blk-mq.c:603
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - drivers/scsi/scsi_lib.c:__scsi_execute
```
**Symbols:**

```
ffffffff817416b0-ffffffff817418d6: blk_mq_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request(struct request_queue *q, blk_opf_t opf, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81781b80)
Location: block/blk-mq.c:577
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/scsi/scsi_lib.c:scsi_execute_cmd
```
**Symbols:**

```
ffffffff81781b80-ffffffff81781df2: blk_mq_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request(struct request_queue *q, blk_opf_t opf, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c4060)
Location: block/blk-mq.c:581
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/scsi/scsi_lib.c:scsi_execute_cmd
```
**Symbols:**

```
ffffffff817c4060-ffffffff817c42e3: blk_mq_alloc_request (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105efb48)
Location: block/blk-mq.c:422
Inline: False
Direct callers:
  - block/blk-core.c:blk_get_request
```
**Symbols:**

```
ffff8000105efb48-ffff8000105efc0c: blk_mq_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079ac48)
Location: block/blk-mq.c:422
Inline: False
Direct callers:
  - block/blk-core.c:blk_get_request
```
**Symbols:**

```
c079ac48-c079ad18: blk_mq_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000784a70)
Location: block/blk-mq.c:422
Inline: False
Direct callers:
  - block/blk-core.c:blk_get_request
```
**Symbols:**

```
c000000000784a70-c000000000784b70: blk_mq_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042dbde)
Location: block/blk-mq.c:422
Inline: False
Direct callers:
  - block/blk-core.c:blk_get_request
```
**Symbols:**

```
ffffffe00042dbde-ffffffe00042dc7a: blk_mq_alloc_request (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e7cf0)
Location: block/blk-mq.c:422
Inline: False
Direct callers:
  - block/blk-core.c:blk_get_request
  - drivers/nvme/host/core.c:nvme_alloc_request
```
**Symbols:**

```
ffffffff814e7cf0-ffffffff814e7dc1: blk_mq_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d8260)
Location: block/blk-mq.c:422
Inline: False
Direct callers:
  - block/blk-core.c:blk_get_request
  - drivers/nvme/host/core.c:nvme_alloc_request
```
**Symbols:**

```
ffffffff814d8260-ffffffff814d8331: blk_mq_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e3d80)
Location: block/blk-mq.c:422
Inline: False
Direct callers:
  - block/blk-core.c:blk_get_request
```
**Symbols:**

```
ffffffff814e3d80-ffffffff814e3e51: blk_mq_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fd2e0)
Location: block/blk-mq.c:422
Inline: False
Direct callers:
  - block/blk-core.c:blk_get_request
```
**Symbols:**

```
ffffffff814fd2e0-ffffffff814fd3b1: blk_mq_alloc_request (STB_GLOBAL)
```
</details>
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int op</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int flags</code> ➡️ <code>blk_mq_req_flags_t flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>blk_opf_t opf</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int op</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
