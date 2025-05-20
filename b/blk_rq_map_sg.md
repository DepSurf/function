# Function: <code>blk_rq_map_sg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blk_rq_map_sg(struct request_queue *q, struct request *rq, struct scatterlist *sglist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff813bfef0)
Location: block/blk-merge.c:424
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtio_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff813bfef0-ffffffff813c0458: blk_rq_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blk_rq_map_sg(struct request_queue *q, struct request *rq, struct scatterlist *sglist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81403f70)
Location: block/blk-merge.c:450
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtio_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff81403f70-ffffffff814044ca: blk_rq_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blk_rq_map_sg(struct request_queue *q, struct request *rq, struct scatterlist *sglist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8141e430)
Location: block/blk-merge.c:436
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff8141e430-ffffffff8141e9b0: blk_rq_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blk_rq_map_sg(struct request_queue *q, struct request *rq, struct scatterlist *sglist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8142bc30)
Location: block/blk-merge.c:426
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff8142bc30-ffffffff8142c161: blk_rq_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_rq_map_sg(struct request_queue *q, struct request *rq, struct scatterlist *sglist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81456e40)
Location: block/blk-merge.c:427
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff81456e40-ffffffff81457377: blk_rq_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blk_rq_map_sg(struct request_queue *q, struct request *rq, struct scatterlist *sglist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8148a8d0)
Location: block/blk-merge.c:436
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff8148a8d0-ffffffff8148ae64: blk_rq_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blk_rq_map_sg(struct request_queue *q, struct request *rq, struct scatterlist *sglist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814a44a0)
Location: block/blk-merge.c:478
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff814a44a0-ffffffff814a4a09: blk_rq_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int blk_rq_map_sg(struct request_queue *q, struct request *rq, struct scatterlist *sglist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-merge.c (0)
Location: block/blk-merge.c:449
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
ffffffff814d40c1-ffffffff814d40d4: blk_rq_map_sg.cold (STB_LOCAL)
ffffffff814d2320-ffffffff814d2595: blk_rq_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blk_rq_map_sg(struct request_queue *q, struct request *rq, struct scatterlist *sglist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814eb6a0)
Location: block/blk-merge.c:502
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
ffffffff814eb6a0-ffffffff814eb91c: blk_rq_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81569660)
Location: include/linux/blkdev.h:1163
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_map_buffer
```
```
In drivers/block/xen-blkfront.c (ffffffff817ee47d)
Location: include/linux/blkdev.h:1163
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81583db3)
Location: include/linux/blkdev.h:1217
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_map_buffer
```
```
In drivers/block/xen-blkfront.c (ffffffff81802d84)
Location: include/linux/blkdev.h:1217
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff8158abb3)
Location: include/linux/blkdev.h:1202
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_map_buffer
```
```
In drivers/block/xen-blkfront.c (ffffffff817e7404)
Location: include/linux/blkdev.h:1202
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff815efc83)
Location: include/linux/blkdev.h:1176
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_map_buffer
```
```
In drivers/block/xen-blkfront.c (ffffffff8187344a)
Location: include/linux/blkdev.h:1176
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff816a0c1d)
Location: include/linux/blk-mq.h:1112
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_map_buffer
```
```
In drivers/block/xen-blkfront.c (ffffffff819bd39f)
Location: include/linux/blk-mq.h:1112
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff8175f7ad)
Location: include/linux/blk-mq.h:1143
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_map_buffer
```
```
In drivers/block/xen-blkfront.c (ffffffff81b32a6f)
Location: include/linux/blk-mq.h:1143
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff8179e68d)
Location: include/linux/blk-mq.h:1143
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_map_buffer
```
```
In drivers/block/virtio_blk.c (ffffffff81b7eb44)
Location: include/linux/blk-mq.h:1143
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff81b85f41)
Location: include/linux/blk-mq.h:1143
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff817e210d)
Location: include/linux/blk-mq.h:1140
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_map_buffer
```
```
In drivers/block/virtio_blk.c (ffffffff81bd31f7)
Location: include/linux/blk-mq.h:1140
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd9e3f)
Location: include/linux/blk-mq.h:1140
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
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
int blk_rq_map_sg(struct request_queue *q, struct request *rq, struct scatterlist *sglist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffff8000105ea0e0)
Location: block/blk-merge.c:502
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/mmc/core/queue.c:mmc_queue_map_sg
```
**Symbols:**

```
ffff8000105ea0e0-ffff8000105ea340: blk_rq_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blk_rq_map_sg(struct request_queue *q, struct request *rq, struct scatterlist *sglist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c0796694)
Location: block/blk-merge.c:502
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/mmc/core/queue.c:mmc_queue_map_sg
```
**Symbols:**

```
c0796694-c0796934: blk_rq_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blk_rq_map_sg(struct request_queue *q, struct request *rq, struct scatterlist *sglist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c00000000077efe0)
Location: block/blk-merge.c:502
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_map_buffer
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
c00000000077efe0-c00000000077f2f8: blk_rq_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blk_rq_map_sg(struct request_queue *q, struct request *rq, struct scatterlist *sglist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffe00042a53a)
Location: block/blk-merge.c:502
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/mmc/core/queue.c:mmc_queue_map_sg
```
**Symbols:**

```
ffffffe00042a53a-ffffffe00042a70e: blk_rq_map_sg (STB_GLOBAL)
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
int blk_rq_map_sg(struct request_queue *q, struct request *rq, struct scatterlist *sglist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814e3c80)
Location: block/blk-merge.c:502
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/nvme/host/pci.c:nvme_map_data
```
**Symbols:**

```
ffffffff814e3c80-ffffffff814e3efc: blk_rq_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blk_rq_map_sg(struct request_queue *q, struct request *rq, struct scatterlist *sglist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d4560)
Location: block/blk-merge.c:502
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/nvme/host/pci.c:nvme_map_data
```
**Symbols:**

```
ffffffff814d4560-ffffffff814d47dc: blk_rq_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blk_rq_map_sg(struct request_queue *q, struct request *rq, struct scatterlist *sglist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814dfd10)
Location: block/blk-merge.c:502
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
ffffffff814dfd10-ffffffff814dff8c: blk_rq_map_sg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blk_rq_map_sg(struct request_queue *q, struct request *rq, struct scatterlist *sglist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814f8b70)
Location: block/blk-merge.c:502
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
ffffffff814f8b70-ffffffff814f8dec: blk_rq_map_sg (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
