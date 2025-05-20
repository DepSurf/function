# Function: <code>__blk_rq_map_sg</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __blk_rq_map_sg(struct request_queue *q, struct request *rq, struct scatterlist *sglist, struct scatterlist **last_sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8154b4f0)
Location: block/blk-merge.c:512
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_map_buffer
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
ffffffff8154b4f0-ffffffff8154b653: __blk_rq_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __blk_rq_map_sg(struct request_queue *q, struct request *rq, struct scatterlist *sglist, struct scatterlist **last_sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815675a0)
Location: block/blk-merge.c:528
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_map_buffer
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
**Symbols:**

```
ffffffff815675a0-ffffffff81567703: __blk_rq_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __blk_rq_map_sg(struct request_queue *q, struct request *rq, struct scatterlist *sglist, struct scatterlist **last_sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8156f990)
Location: block/blk-merge.c:527
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_map_buffer
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
**Symbols:**

```
ffffffff8156f990-ffffffff8156fae9: __blk_rq_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __blk_rq_map_sg(struct request_queue *q, struct request *rq, struct scatterlist *sglist, struct scatterlist **last_sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815d4030)
Location: block/blk-merge.c:529
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_map_buffer
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
**Symbols:**

```
ffffffff815d4030-ffffffff815d4189: __blk_rq_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __blk_rq_map_sg(struct request_queue *q, struct request *rq, struct scatterlist *sglist, struct scatterlist **last_sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8167fe90)
Location: block/blk-merge.c:529
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_map_buffer
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
**Symbols:**

```
ffffffff8167fe90-ffffffff8167ff65: __blk_rq_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __blk_rq_map_sg(struct request_queue *q, struct request *rq, struct scatterlist *sglist, struct scatterlist **last_sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8173d230)
Location: block/blk-merge.c:566
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_map_buffer
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
**Symbols:**

```
ffffffff8173d230-ffffffff8173d305: __blk_rq_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __blk_rq_map_sg(struct request_queue *q, struct request *rq, struct scatterlist *sglist, struct scatterlist **last_sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff817797d0)
Location: block/blk-merge.c:567
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_map_buffer
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
**Symbols:**

```
ffffffff817797d0-ffffffff817798a5: __blk_rq_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __blk_rq_map_sg(struct request_queue *q, struct request *rq, struct scatterlist *sglist, struct scatterlist **last_sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff817bbba0)
Location: block/blk-merge.c:563
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_map_buffer
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
**Symbols:**

```
ffffffff817bbba0-ffffffff817bbc75: __blk_rq_map_sg (STB_GLOBAL)
```
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
