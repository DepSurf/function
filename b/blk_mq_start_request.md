# Function: <code>blk_mq_start_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_mq_start_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c3090)
Location: block/blk-mq.c:396
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/virtio_blk.c:virtio_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/md/dm.c:dm_start_request
```
**Symbols:**

```
ffffffff813c3090-ffffffff813c316d: blk_mq_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_mq_start_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81406cb0)
Location: block/blk-mq.c:452
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/virtio_blk.c:virtio_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/md/dm-rq.c:dm_start_request
```
**Symbols:**

```
ffffffff81406cb0-ffffffff81406d82: blk_mq_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_mq_start_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814210c0)
Location: block/blk-mq.c:466
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/md/dm-rq.c:dm_start_request
```
**Symbols:**

```
ffffffff814210c0-ffffffff814211c3: blk_mq_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_mq_start_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8142f940)
Location: block/blk-mq.c:545
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/md/dm-rq.c:dm_start_request
```
**Symbols:**

```
ffffffff8142f940-ffffffff8142fa81: blk_mq_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_start_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145aec0)
Location: block/blk-mq.c:587
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/md/dm-rq.c:dm_start_request
```
**Symbols:**

```
ffffffff8145aec0-ffffffff8145b021: blk_mq_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_start_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148def0)
Location: block/blk-mq.c:630
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/md/dm-rq.c:dm_start_request
```
**Symbols:**

```
ffffffff8148def0-ffffffff8148dfff: blk_mq_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_start_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a7780)
Location: block/blk-mq.c:666
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff814a7780-ffffffff814a7892: blk_mq_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_start_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d57e0)
Location: block/blk-mq.c:668
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff814d57e0-ffffffff814d58d5: blk_mq_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_start_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814eeac0)
Location: block/blk-mq.c:678
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff814eeac0-ffffffff814eec04: blk_mq_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_start_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8154fbd0)
Location: block/blk-mq.c:688
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_prep_fn
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff8154fbd0-ffffffff8154fcf0: blk_mq_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_start_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156c010)
Location: block/blk-mq.c:738
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff8156c010-ffffffff8156c110: blk_mq_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_start_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81573890)
Location: block/blk-mq.c:712
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81573890-ffffffff81573990: blk_mq_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_start_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d7e90)
Location: block/blk-mq.c:719
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff815d7e90-ffffffff815d7f8d: blk_mq_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_start_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81685420)
Location: block/blk-mq.c:1130
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81685420-ffffffff81685569: blk_mq_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_start_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81743220)
Location: block/blk-mq.c:1249
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81743220-ffffffff81743369: blk_mq_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_start_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177e860)
Location: block/blk-mq.c:1248
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff8177e860-ffffffff8177e991: blk_mq_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_start_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c12c0)
Location: block/blk-mq.c:1249
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff817c12c0-ffffffff817c1416: blk_mq_start_request (STB_GLOBAL)
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
void blk_mq_start_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105ee988)
Location: block/blk-mq.c:678
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/mmc/core/queue.c:mmc_mq_queue_rq
```
**Symbols:**

```
ffff8000105ee988-ffff8000105eeae8: blk_mq_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_start_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c0799ca8)
Location: block/blk-mq.c:678
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/block/loop.c:loop_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/mtd/mtd_blkdevs.c:mtd_queue_rq
  - drivers/mtd/mtd_blkdevs.c:mtd_blktrans_work
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/mmc/core/queue.c:mmc_mq_queue_rq
```
**Symbols:**

```
c0799ca8-c0799e2c: blk_mq_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_start_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000783750)
Location: block/blk-mq.c:678
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/block/loop.c:loop_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
c000000000783750-c000000000783910: blk_mq_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_start_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042d082)
Location: block/blk-mq.c:678
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/block/loop.c:loop_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/mmc/core/queue.c:mmc_mq_queue_rq
```
**Symbols:**

```
ffffffe00042d082-ffffffe00042d1a6: blk_mq_start_request (STB_GLOBAL)
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
void blk_mq_start_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e70a0)
Location: block/blk-mq.c:678
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/nvme/host/pci.c:nvme_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff814e70a0-ffffffff814e71e4: blk_mq_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_start_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d7610)
Location: block/blk-mq.c:678
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/block/loop.c:loop_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/nvme/host/pci.c:nvme_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff814d7610-ffffffff814d7754: blk_mq_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_start_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e3130)
Location: block/blk-mq.c:678
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff814e3130-ffffffff814e3274: blk_mq_start_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_start_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fbfc0)
Location: block/blk-mq.c:678
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_queue_rq
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff814fbfc0-ffffffff814fc113: blk_mq_start_request (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
