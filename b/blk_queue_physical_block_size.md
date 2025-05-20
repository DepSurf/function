# Function: <code>blk_queue_physical_block_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_queue_physical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff813be0d0)
Location: block/blk-settings.c:374
Inline: False
Direct callers:
  - drivers/block/brd.c:brd_alloc
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff813be0d0-ffffffff813be104: blk_queue_physical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_queue_physical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81402030)
Location: block/blk-settings.c:374
Inline: False
Direct callers:
  - drivers/block/brd.c:brd_alloc
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff81402030-ffffffff81402062: blk_queue_physical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_queue_physical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8141bce0)
Location: block/blk-settings.c:392
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff8141bce0-ffffffff8141bd12: blk_queue_physical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_queue_physical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81429ca0)
Location: block/blk-settings.c:403
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff81429ca0-ffffffff81429cd2: blk_queue_physical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_queue_physical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81454e60)
Location: block/blk-settings.c:404
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff81454e60-ffffffff81454e92: blk_queue_physical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_queue_physical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814882d0)
Location: block/blk-settings.c:404
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff814882d0-ffffffff81488302: blk_queue_physical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_queue_physical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814a22f0)
Location: block/blk-settings.c:348
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff814a22f0-ffffffff814a2322: blk_queue_physical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_queue_physical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814d03d0)
Location: block/blk-settings.c:352
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffff814d03d0-ffffffff814d0402: blk_queue_physical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_queue_physical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814e9730)
Location: block/blk-settings.c:353
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffff814e9730-ffffffff814e9761: blk_queue_physical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_queue_physical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff815485c0)
Location: block/blk-settings.c:346
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffff815485c0-ffffffff815485f1: blk_queue_physical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_queue_physical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81564330)
Location: block/blk-settings.c:357
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffff81564330-ffffffff81564361: blk_queue_physical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_queue_physical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8156cab0)
Location: block/blk-settings.c:330
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffff8156cab0-ffffffff8156cada: blk_queue_physical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_queue_physical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff815d0fd0)
Location: block/blk-settings.c:333
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffff815d0fd0-ffffffff815d0ffa: blk_queue_physical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_queue_physical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8167c8b0)
Location: block/blk-settings.c:332
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffff8167c8b0-ffffffff8167c8e4: blk_queue_physical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_queue_physical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81739150)
Location: block/blk-settings.c:332
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffff81739150-ffffffff81739184: blk_queue_physical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_queue_physical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81775820)
Location: block/blk-settings.c:338
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffff81775820-ffffffff81775854: blk_queue_physical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_queue_physical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff817b7ae0)
Location: block/blk-settings.c:338
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffff817b7ae0-ffffffff817b7b22: blk_queue_physical_block_size (STB_GLOBAL)
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
void blk_queue_physical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffff8000105e7898)
Location: block/blk-settings.c:353
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffff8000105e7898-ffff8000105e78e8: blk_queue_physical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_queue_physical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c0794300)
Location: block/blk-settings.c:353
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
c0794300-c0794338: blk_queue_physical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_queue_physical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c00000000077c1a0)
Location: block/blk-settings.c:353
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
c00000000077c1a0-c00000000077c1d4: blk_queue_physical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_queue_physical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffe000428612)
Location: block/blk-settings.c:353
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffe000428612-ffffffe000428656: blk_queue_physical_block_size (STB_GLOBAL)
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
void blk_queue_physical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814e1d10)
Location: block/blk-settings.c:353
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/nvme/host/core.c:nvme_update_disk_info
```
**Symbols:**

```
ffffffff814e1d10-ffffffff814e1d41: blk_queue_physical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_queue_physical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814d26a0)
Location: block/blk-settings.c:353
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/nvme/host/core.c:nvme_update_disk_info
```
**Symbols:**

```
ffffffff814d26a0-ffffffff814d26d1: blk_queue_physical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_queue_physical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814ddda0)
Location: block/blk-settings.c:353
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffff814ddda0-ffffffff814dddd1: blk_queue_physical_block_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_queue_physical_block_size(struct request_queue *q, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814f6c00)
Location: block/blk-settings.c:353
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_capacity
```
**Symbols:**

```
ffffffff814f6c00-ffffffff814f6c31: blk_queue_physical_block_size (STB_GLOBAL)
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
