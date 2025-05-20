# Function: <code>blk_queue_logical_block_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue *q, short unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff813be090)
Location: block/blk-settings.c:352
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sr.c:sr_block_revalidate_disk
```
**Symbols:**

```
ffffffff813be090-ffffffff813be0c5: blk_queue_logical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue *q, short unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81401ff0)
Location: block/blk-settings.c:352
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sr.c:sr_block_revalidate_disk
```
**Symbols:**

```
ffffffff81401ff0-ffffffff81402025: blk_queue_logical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue *q, short unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8141bca0)
Location: block/blk-settings.c:370
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_register
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sr.c:sr_block_revalidate_disk
```
**Symbols:**

```
ffffffff8141bca0-ffffffff8141bcd5: blk_queue_logical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue *q, short unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81429c60)
Location: block/blk-settings.c:381
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_register
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sr.c:sr_block_revalidate_disk
```
**Symbols:**

```
ffffffff81429c60-ffffffff81429c95: blk_queue_logical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue *q, short unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81454e20)
Location: block/blk-settings.c:382
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_register
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sr.c:sr_block_revalidate_disk
```
**Symbols:**

```
ffffffff81454e20-ffffffff81454e55: blk_queue_logical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue *q, short unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81488290)
Location: block/blk-settings.c:382
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sr.c:sr_block_revalidate_disk
```
**Symbols:**

```
ffffffff81488290-ffffffff814882c5: blk_queue_logical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue *q, short unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814a22b0)
Location: block/blk-settings.c:326
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sr.c:sr_block_revalidate_disk
```
**Symbols:**

```
ffffffff814a22b0-ffffffff814a22e5: blk_queue_logical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue *q, short unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814d0390)
Location: block/blk-settings.c:330
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sr.c:sr_block_revalidate_disk
```
**Symbols:**

```
ffffffff814d0390-ffffffff814d03c5: blk_queue_logical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814e96f0)
Location: block/blk-settings.c:331
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sr.c:sr_block_revalidate_disk
```
**Symbols:**

```
ffffffff814e96f0-ffffffff814e9721: blk_queue_logical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81548580)
Location: block/blk-settings.c:324
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sr.c:get_sectorsize
```
**Symbols:**

```
ffffffff81548580-ffffffff815485b1: blk_queue_logical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff815642e0)
Location: block/blk-settings.c:328
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sr.c:get_sectorsize
```
**Symbols:**

```
ffffffff815642e0-ffffffff81564322: blk_queue_logical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8156ca60)
Location: block/blk-settings.c:301
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sr.c:get_sectorsize
```
**Symbols:**

```
ffffffff8156ca60-ffffffff8156caa2: blk_queue_logical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff815d0f80)
Location: block/blk-settings.c:304
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sr.c:get_sectorsize
```
**Symbols:**

```
ffffffff815d0f80-ffffffff815d0fc2: blk_queue_logical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8167c860)
Location: block/blk-settings.c:303
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sr.c:get_sectorsize
```
**Symbols:**

```
ffffffff8167c860-ffffffff8167c8ac: blk_queue_logical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff817390f0)
Location: block/blk-settings.c:303
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sr.c:get_sectorsize
```
**Symbols:**

```
ffffffff817390f0-ffffffff8173913c: blk_queue_logical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff817757c0)
Location: block/blk-settings.c:309
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sr.c:get_sectorsize
```
**Symbols:**

```
ffffffff817757c0-ffffffff8177580c: blk_queue_logical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff817b7a70)
Location: block/blk-settings.c:306
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sr.c:get_sectorsize
```
**Symbols:**

```
ffffffff817b7a70-ffffffff817b7aca: blk_queue_logical_block_size (STB_GLOBAL)
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
void blk_queue_logical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffff8000105e7848)
Location: block/blk-settings.c:331
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
ffff8000105e7848-ffff8000105e7898: blk_queue_logical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c07942c8)
Location: block/blk-settings.c:331
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
c07942c8-c0794300: blk_queue_logical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c00000000077c160)
Location: block/blk-settings.c:331
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sr.c:sr_block_revalidate_disk
```
**Symbols:**

```
c00000000077c160-c00000000077c194: blk_queue_logical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffe0004285ce)
Location: block/blk-settings.c:331
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
ffffffe0004285ce-ffffffe000428612: blk_queue_logical_block_size (STB_GLOBAL)
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
void blk_queue_logical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814e1cd0)
Location: block/blk-settings.c:331
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_update_disk_info
  - drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk
```
**Symbols:**

```
ffffffff814e1cd0-ffffffff814e1d01: blk_queue_logical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814d2660)
Location: block/blk-settings.c:331
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/nvdimm/blk.c:nd_blk_probe
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_update_disk_info
  - drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk
```
**Symbols:**

```
ffffffff814d2660-ffffffff814d2691: blk_queue_logical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814ddd60)
Location: block/blk-settings.c:331
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sr.c:sr_block_revalidate_disk
```
**Symbols:**

```
ffffffff814ddd60-ffffffff814ddd91: blk_queue_logical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814f6bc0)
Location: block/blk-settings.c:331
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sr.c:sr_block_revalidate_disk
```
**Symbols:**

```
ffffffff814f6bc0-ffffffff814f6bf1: blk_queue_logical_block_size (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>short unsigned int size</code> ➡️ <code>unsigned int size</code>
</li>
</ul>
</details>
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
