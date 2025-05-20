# Function: <code>blk_queue_max_segments</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_max_segments(struct request_queue *q, short unsigned int max_segments);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff813be4e0)
Location: block/blk-settings.c:309
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_dma_drain
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/block/xen-blkfront.c:blkif_recover
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff813be4e0-ffffffff813be51d: blk_queue_max_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_max_segments(struct request_queue *q, short unsigned int max_segments);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81402460)
Location: block/blk-settings.c:309
Inline: True
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81402460-ffffffff8140249d: blk_queue_max_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_max_segments(struct request_queue *q, short unsigned int max_segments);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8141c0e0)
Location: block/blk-settings.c:327
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff8141c0e0-ffffffff8141c11d: blk_queue_max_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_max_segments(struct request_queue *q, short unsigned int max_segments);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8142a070)
Location: block/blk-settings.c:322
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff8142a070-ffffffff8142a0ad: blk_queue_max_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_max_segments(struct request_queue *q, short unsigned int max_segments);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814552b0)
Location: block/blk-settings.c:323
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814552b0-ffffffff814552ed: blk_queue_max_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_queue_max_segments(struct request_queue *q, short unsigned int max_segments);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (ffffffff81488436)
Location: block/blk-settings.c:323
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_dma_drain
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81488dcb-ffffffff81488ded: blk_queue_max_segments.cold.8 (STB_LOCAL)
ffffffff81488670-ffffffff81488692: blk_queue_max_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_queue_max_segments(struct request_queue *q, short unsigned int max_segments);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (ffffffff814a2456)
Location: block/blk-settings.c:267
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_dma_drain
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814a2ccb-ffffffff814a2ced: blk_queue_max_segments.cold.7 (STB_LOCAL)
ffffffff814a2590-ffffffff814a25b2: blk_queue_max_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_queue_max_segments(struct request_queue *q, short unsigned int max_segments);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (ffffffff814d0516)
Location: block/blk-settings.c:268
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_dma_drain
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814d0d7d-ffffffff814d0d9f: blk_queue_max_segments.cold (STB_LOCAL)
ffffffff814d0660-ffffffff814d0682: blk_queue_max_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_queue_max_segments(struct request_queue *q, short unsigned int max_segments);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (ffffffff814e9876)
Location: block/blk-settings.c:269
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_dma_drain
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814ea13d-ffffffff814ea15f: blk_queue_max_segments.cold (STB_LOCAL)
ffffffff814e99e0-ffffffff814e9a02: blk_queue_max_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_segments(struct request_queue *q, short unsigned int max_segments);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:262
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff815490df-ffffffff81549101: blk_queue_max_segments.cold (STB_LOCAL)
ffffffff81548830-ffffffff81548855: blk_queue_max_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_segments(struct request_queue *q, short unsigned int max_segments);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:266
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff81bf2711-ffffffff81bf2733: blk_queue_max_segments.cold (STB_LOCAL)
ffffffff81564610-ffffffff81564635: blk_queue_max_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_segments(struct request_queue *q, short unsigned int max_segments);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:239
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff81be46d8-ffffffff81be46fa: blk_queue_max_segments.cold (STB_LOCAL)
ffffffff8156cce0-ffffffff8156cd05: blk_queue_max_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_segments(struct request_queue *q, short unsigned int max_segments);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:242
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff81cd817b-ffffffff81cd819d: blk_queue_max_segments.cold (STB_LOCAL)
ffffffff815d1230-ffffffff815d1255: blk_queue_max_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_segments(struct request_queue *q, short unsigned int max_segments);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:241
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff81e8b541-ffffffff81e8b563: blk_queue_max_segments.cold (STB_LOCAL)
ffffffff8167cc10-ffffffff8167cc41: blk_queue_max_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_queue_max_segments(struct request_queue *q, short unsigned int max_segments);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff817395a0)
Location: block/blk-settings.c:241
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff817395a0-ffffffff81739603: blk_queue_max_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_queue_max_segments(struct request_queue *q, short unsigned int max_segments);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81775c70)
Location: block/blk-settings.c:247
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff81775c70-ffffffff81775cd3: blk_queue_max_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_queue_max_segments(struct request_queue *q, short unsigned int max_segments);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff817b7f40)
Location: block/blk-settings.c:246
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff817b7f40-ffffffff817b7fa3: blk_queue_max_segments (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_max_segments(struct request_queue *q, short unsigned int max_segments);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffff8000105e7a9c)
Location: block/blk-settings.c:269
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_dma_drain
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
ffff8000105e7c10-ffff8000105e7c64: blk_queue_max_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_max_segments(struct request_queue *q, short unsigned int max_segments);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c0794458)
Location: block/blk-settings.c:269
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_dma_drain
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
c07945bc-c0794608: blk_queue_max_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_max_segments(struct request_queue *q, short unsigned int max_segments);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c00000000077c2e8)
Location: block/blk-settings.c:269
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_dma_drain
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
c00000000077c430-c00000000077c498: blk_queue_max_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_max_segments(struct request_queue *q, short unsigned int max_segments);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffe0004287c0)
Location: block/blk-settings.c:269
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_dma_drain
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
ffffffe000428904-ffffffe00042894e: blk_queue_max_segments (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_queue_max_segments(struct request_queue *q, short unsigned int max_segments);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (ffffffff814e1e56)
Location: block/blk-settings.c:269
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_dma_drain
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/nvme/host/core.c:nvme_set_queue_limits
```
**Symbols:**

```
ffffffff814e271d-ffffffff814e273f: blk_queue_max_segments.cold (STB_LOCAL)
ffffffff814e1fc0-ffffffff814e1fe2: blk_queue_max_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_queue_max_segments(struct request_queue *q, short unsigned int max_segments);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (ffffffff814d27e6)
Location: block/blk-settings.c:269
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_dma_drain
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/nvme/host/core.c:nvme_set_queue_limits
```
**Symbols:**

```
ffffffff814d30ad-ffffffff814d30cf: blk_queue_max_segments.cold (STB_LOCAL)
ffffffff814d2950-ffffffff814d2972: blk_queue_max_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_queue_max_segments(struct request_queue *q, short unsigned int max_segments);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (ffffffff814ddee6)
Location: block/blk-settings.c:269
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_dma_drain
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814de7ad-ffffffff814de7cf: blk_queue_max_segments.cold (STB_LOCAL)
ffffffff814de050-ffffffff814de072: blk_queue_max_segments (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_queue_max_segments(struct request_queue *q, short unsigned int max_segments);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (ffffffff814f6d46)
Location: block/blk-settings.c:269
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_dma_drain
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814f760d-ffffffff814f762f: blk_queue_max_segments.cold (STB_LOCAL)
ffffffff814f6eb0-ffffffff814f6ed2: blk_queue_max_segments (STB_GLOBAL)
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
