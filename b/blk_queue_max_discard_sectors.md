# Function: <code>blk_queue_max_discard_sectors</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue *q, unsigned int max_discard_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff813be050)
Location: block/blk-settings.c:280
Inline: False
Direct callers:
  - drivers/block/brd.c:brd_alloc
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd.c:sd_config_discard
```
**Symbols:**

```
ffffffff813be050-ffffffff813be067: blk_queue_max_discard_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue *q, unsigned int max_discard_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81401fb0)
Location: block/blk-settings.c:280
Inline: False
Direct callers:
  - drivers/block/brd.c:brd_alloc
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd.c:sd_config_discard
```
**Symbols:**

```
ffffffff81401fb0-ffffffff81401fc7: blk_queue_max_discard_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue *q, unsigned int max_discard_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8141bc40)
Location: block/blk-settings.c:285
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd.c:sd_config_discard
```
**Symbols:**

```
ffffffff8141bc40-ffffffff8141bc57: blk_queue_max_discard_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue *q, unsigned int max_discard_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81429be0)
Location: block/blk-settings.c:280
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd.c:sd_config_discard
```
**Symbols:**

```
ffffffff81429be0-ffffffff81429bf7: blk_queue_max_discard_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue *q, unsigned int max_discard_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81454da0)
Location: block/blk-settings.c:281
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd.c:sd_config_discard
```
**Symbols:**

```
ffffffff81454da0-ffffffff81454db7: blk_queue_max_discard_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue *q, unsigned int max_discard_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81488210)
Location: block/blk-settings.c:281
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd.c:sd_config_discard
```
**Symbols:**

```
ffffffff81488210-ffffffff81488227: blk_queue_max_discard_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue *q, unsigned int max_discard_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814a2230)
Location: block/blk-settings.c:225
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd.c:sd_config_discard
```
**Symbols:**

```
ffffffff814a2230-ffffffff814a2247: blk_queue_max_discard_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue *q, unsigned int max_discard_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814d0310)
Location: block/blk-settings.c:226
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd.c:sd_config_discard
```
**Symbols:**

```
ffffffff814d0310-ffffffff814d0327: blk_queue_max_discard_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue *q, unsigned int max_discard_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814e9670)
Location: block/blk-settings.c:227
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd.c:sd_config_discard
```
**Symbols:**

```
ffffffff814e9670-ffffffff814e9687: blk_queue_max_discard_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue *q, unsigned int max_discard_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81548500)
Location: block/blk-settings.c:193
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
```
**Symbols:**

```
ffffffff81548500-ffffffff81548517: blk_queue_max_discard_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue *q, unsigned int max_discard_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81564260)
Location: block/blk-settings.c:197
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
```
**Symbols:**

```
ffffffff81564260-ffffffff81564277: blk_queue_max_discard_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue *q, unsigned int max_discard_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8156c9e0)
Location: block/blk-settings.c:170
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_config_discard
  - drivers/block/loop.c:loop_config_discard
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
```
**Symbols:**

```
ffffffff8156c9e0-ffffffff8156c9f7: blk_queue_max_discard_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue *q, unsigned int max_discard_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff815d0f00)
Location: block/blk-settings.c:173
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_config_discard
  - drivers/block/loop.c:loop_config_discard
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
```
**Symbols:**

```
ffffffff815d0f00-ffffffff815d0f17: blk_queue_max_discard_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue *q, unsigned int max_discard_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8167c7d0)
Location: block/blk-settings.c:172
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
```
**Symbols:**

```
ffffffff8167c7d0-ffffffff8167c7f5: blk_queue_max_discard_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue *q, unsigned int max_discard_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81739020)
Location: block/blk-settings.c:172
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
```
**Symbols:**

```
ffffffff81739020-ffffffff81739045: blk_queue_max_discard_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue *q, unsigned int max_discard_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81775700)
Location: block/blk-settings.c:178
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
```
**Symbols:**

```
ffffffff81775700-ffffffff8177571f: blk_queue_max_discard_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue *q, unsigned int max_discard_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff817b79b0)
Location: block/blk-settings.c:177
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:provisioning_mode_store
```
**Symbols:**

```
ffffffff817b79b0-ffffffff817b79cf: blk_queue_max_discard_sectors (STB_GLOBAL)
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
void blk_queue_max_discard_sectors(struct request_queue *q, unsigned int max_discard_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffff8000105e7788)
Location: block/blk-settings.c:227
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
ffff8000105e7788-ffff8000105e77b8: blk_queue_max_discard_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue *q, unsigned int max_discard_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c0794250)
Location: block/blk-settings.c:227
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
c0794250-c0794270: blk_queue_max_discard_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue *q, unsigned int max_discard_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c00000000077c110)
Location: block/blk-settings.c:227
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd.c:sd_config_discard
```
**Symbols:**

```
c00000000077c110-c00000000077c124: blk_queue_max_discard_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue *q, unsigned int max_discard_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffe000428522)
Location: block/blk-settings.c:227
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
ffffffe000428522-ffffffe000428550: blk_queue_max_discard_sectors (STB_GLOBAL)
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
void blk_queue_max_discard_sectors(struct request_queue *q, unsigned int max_discard_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814e1c50)
Location: block/blk-settings.c:227
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/nvme/host/core.c:nvme_update_disk_info
```
**Symbols:**

```
ffffffff814e1c50-ffffffff814e1c67: blk_queue_max_discard_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue *q, unsigned int max_discard_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814d25e0)
Location: block/blk-settings.c:227
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/nvme/host/core.c:nvme_update_disk_info
```
**Symbols:**

```
ffffffff814d25e0-ffffffff814d25f7: blk_queue_max_discard_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue *q, unsigned int max_discard_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814ddce0)
Location: block/blk-settings.c:227
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd.c:sd_config_discard
```
**Symbols:**

```
ffffffff814ddce0-ffffffff814ddcf7: blk_queue_max_discard_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_queue_max_discard_sectors(struct request_queue *q, unsigned int max_discard_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814f6b40)
Location: block/blk-settings.c:227
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/sd.c:sd_config_discard
  - drivers/scsi/sd.c:sd_config_discard
```
**Symbols:**

```
ffffffff814f6b40-ffffffff814f6b57: blk_queue_max_discard_sectors (STB_GLOBAL)
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
