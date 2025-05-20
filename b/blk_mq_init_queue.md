# Function: <code>blk_mq_init_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct request_queue *blk_mq_init_queue(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c5800)
Location: block/blk-mq.c:1963
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
ffffffff813c5800-ffffffff813c585d: blk_mq_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct request_queue *blk_mq_init_queue(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814095b0)
Location: block/blk-mq.c:1987
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
ffffffff814095b0-ffffffff8140960d: blk_mq_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct request_queue *blk_mq_init_queue(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81423fb0)
Location: block/blk-mq.c:2033
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
ffffffff81423fb0-ffffffff8142400d: blk_mq_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct request_queue *blk_mq_init_queue(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81432f90)
Location: block/blk-mq.c:2232
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
ffffffff81432f90-ffffffff81432fed: blk_mq_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct request_queue *blk_mq_init_queue(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145eb50)
Location: block/blk-mq.c:2373
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
ffffffff8145eb50-ffffffff8145ebad: blk_mq_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct request_queue *blk_mq_init_queue(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81492490)
Location: block/blk-mq.c:2435
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
ffffffff81492490-ffffffff814924f6: blk_mq_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct request_queue *blk_mq_init_queue(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ac010)
Location: block/blk-mq.c:2637
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
ffffffff814ac010-ffffffff814ac074: blk_mq_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct request_queue *blk_mq_init_queue(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814da260)
Location: block/blk-mq.c:2683
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
ffffffff814da260-ffffffff814da2bf: blk_mq_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct request_queue *blk_mq_init_queue(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f3610)
Location: block/blk-mq.c:2702
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
ffffffff814f3610-ffffffff814f3671: blk_mq_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct request_queue *blk_mq_init_queue(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81554318)
Location: block/blk-mq.c:2916
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_sq_queue
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
ffffffff81553bb0-ffffffff81553c15: blk_mq_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct request_queue *blk_mq_init_queue(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81570a28)
Location: block/blk-mq.c:3021
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_sq_queue
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_init_blk_queue
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
ffffffff81570270-ffffffff815702d5: blk_mq_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct request_queue *blk_mq_init_queue(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81578988)
Location: block/blk-mq.c:3081
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_sq_queue
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_init_blk_queue
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
ffffffff815781d0-ffffffff81578235: blk_mq_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct request_queue *blk_mq_init_queue(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815dd2c0)
Location: block/blk-mq.c:3135
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff815dd2c0-ffffffff815dd31e: blk_mq_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct request_queue *blk_mq_init_queue(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8168ae50)
Location: block/blk-mq.c:3905
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff8168ae50-ffffffff8168aec4: blk_mq_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct request_queue *blk_mq_init_queue(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81749fa0)
Location: block/blk-mq.c:4069
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff81749fa0-ffffffff8174a00b: blk_mq_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct request_queue *blk_mq_init_queue(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817866a0)
Location: block/blk-mq.c:4081
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff817866a0-ffffffff8178670e: blk_mq_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct request_queue *blk_mq_init_queue(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c8d80)
Location: block/blk-mq.c:4097
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff817c8d80-ffffffff817c8dea: blk_mq_init_queue (STB_GLOBAL)
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
struct request_queue *blk_mq_init_queue(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f2e50)
Location: block/blk-mq.c:2702
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
ffff8000105f2e50-ffff8000105f2ec8: blk_mq_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct request_queue *blk_mq_init_queue(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079ef5c)
Location: block/blk-mq.c:2702
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
c079ef5c-c079efbc: blk_mq_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct request_queue *blk_mq_init_queue(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c00000000078a4a0)
Location: block/blk-mq.c:2702
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
c00000000078a4a0-c00000000078a550: blk_mq_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct request_queue *blk_mq_init_queue(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe000431646)
Location: block/blk-mq.c:2702
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
ffffffe000431646-ffffffe0004316b4: blk_mq_init_queue (STB_GLOBAL)
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
struct request_queue *blk_mq_init_queue(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ebbf0)
Location: block/blk-mq.c:2702
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/pci.c:nvme_reset_work
```
**Symbols:**

```
ffffffff814ebbf0-ffffffff814ebc51: blk_mq_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct request_queue *blk_mq_init_queue(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814dc140)
Location: block/blk-mq.c:2702
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/pci.c:nvme_reset_work
```
**Symbols:**

```
ffffffff814dc140-ffffffff814dc1a1: blk_mq_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct request_queue *blk_mq_init_queue(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e7c80)
Location: block/blk-mq.c:2702
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
ffffffff814e7c80-ffffffff814e7ce1: blk_mq_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct request_queue *blk_mq_init_queue(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81500c20)
Location: block/blk-mq.c:2702
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
ffffffff81500c20-ffffffff81500c81: blk_mq_init_queue (STB_GLOBAL)
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
