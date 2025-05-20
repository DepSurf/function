# Function: <code>blk_queue_max_segment_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_queue_max_segment_size(struct request_queue *q, unsigned int max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff813be560)
Location: block/blk-settings.c:330
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff813be560-ffffffff813be59d: blk_queue_max_segment_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_queue_max_segment_size(struct request_queue *q, unsigned int max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814024e0)
Location: block/blk-settings.c:330
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814024e0-ffffffff8140251d: blk_queue_max_segment_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_queue_max_segment_size(struct request_queue *q, unsigned int max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8141c160)
Location: block/blk-settings.c:348
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff8141c160-ffffffff8141c19d: blk_queue_max_segment_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_queue_max_segment_size(struct request_queue *q, unsigned int max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8142a0b0)
Location: block/blk-settings.c:359
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff8142a0b0-ffffffff8142a0ed: blk_queue_max_segment_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_queue_max_segment_size(struct request_queue *q, unsigned int max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814552f0)
Location: block/blk-settings.c:360
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814552f0-ffffffff8145532d: blk_queue_max_segment_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_segment_size(struct request_queue *q, unsigned int max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:360
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81488ded-ffffffff81488e0f: blk_queue_max_segment_size.cold.9 (STB_LOCAL)
ffffffff814886a0-ffffffff814886c2: blk_queue_max_segment_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_segment_size(struct request_queue *q, unsigned int max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:304
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814a2ced-ffffffff814a2d0f: blk_queue_max_segment_size.cold.8 (STB_LOCAL)
ffffffff814a25c0-ffffffff814a25e2: blk_queue_max_segment_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_segment_size(struct request_queue *q, unsigned int max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:305
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814d0dc1-ffffffff814d0de3: blk_queue_max_segment_size.cold (STB_LOCAL)
ffffffff814d06c0-ffffffff814d06f7: blk_queue_max_segment_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_segment_size(struct request_queue *q, unsigned int max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:306
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814ea181-ffffffff814ea1a3: blk_queue_max_segment_size.cold (STB_LOCAL)
ffffffff814e9a40-ffffffff814e9a77: blk_queue_max_segment_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_segment_size(struct request_queue *q, unsigned int max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:299
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81549123-ffffffff81549145: blk_queue_max_segment_size.cold (STB_LOCAL)
ffffffff815488e0-ffffffff8154891d: blk_queue_max_segment_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_segment_size(struct request_queue *q, unsigned int max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:303
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81bf2755-ffffffff81bf2777: blk_queue_max_segment_size.cold (STB_LOCAL)
ffffffff815646c0-ffffffff815646fd: blk_queue_max_segment_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_segment_size(struct request_queue *q, unsigned int max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:276
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81be471c-ffffffff81be473e: blk_queue_max_segment_size.cold (STB_LOCAL)
ffffffff8156cd90-ffffffff8156cdcd: blk_queue_max_segment_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_segment_size(struct request_queue *q, unsigned int max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:279
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81cd81bf-ffffffff81cd81e1: blk_queue_max_segment_size.cold (STB_LOCAL)
ffffffff815d12e0-ffffffff815d131d: blk_queue_max_segment_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_segment_size(struct request_queue *q, unsigned int max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:278
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81e8b585-ffffffff81e8b5a7: blk_queue_max_segment_size.cold (STB_LOCAL)
ffffffff8167ccf0-ffffffff8167cd45: blk_queue_max_segment_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_queue_max_segment_size(struct request_queue *q, unsigned int max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81739710)
Location: block/blk-settings.c:278
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81739710-ffffffff81739788: blk_queue_max_segment_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_queue_max_segment_size(struct request_queue *q, unsigned int max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81775de0)
Location: block/blk-settings.c:284
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81775de0-ffffffff81775e58: blk_queue_max_segment_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_queue_max_segment_size(struct request_queue *q, unsigned int max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff817b8040)
Location: block/blk-settings.c:282
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff817b8040-ffffffff817b80b8: blk_queue_max_segment_size (STB_GLOBAL)
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
void blk_queue_max_segment_size(struct request_queue *q, unsigned int max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffff8000105e7cc0)
Location: block/blk-settings.c:306
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
ffff8000105e7cc0-ffff8000105e7d34: blk_queue_max_segment_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_queue_max_segment_size(struct request_queue *q, unsigned int max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c0794654)
Location: block/blk-settings.c:306
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
c0794654-c07946e0: blk_queue_max_segment_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_queue_max_segment_size(struct request_queue *q, unsigned int max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c00000000077c580)
Location: block/blk-settings.c:306
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
c00000000077c580-c00000000077c608: blk_queue_max_segment_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_queue_max_segment_size(struct request_queue *q, unsigned int max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffe0004289a8)
Location: block/blk-settings.c:306
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
ffffffe0004289a8-ffffffe000428a0e: blk_queue_max_segment_size (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_segment_size(struct request_queue *q, unsigned int max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:306
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814e2761-ffffffff814e2783: blk_queue_max_segment_size.cold (STB_LOCAL)
ffffffff814e2020-ffffffff814e2057: blk_queue_max_segment_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_segment_size(struct request_queue *q, unsigned int max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:306
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814d30f1-ffffffff814d3113: blk_queue_max_segment_size.cold (STB_LOCAL)
ffffffff814d29b0-ffffffff814d29e7: blk_queue_max_segment_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_segment_size(struct request_queue *q, unsigned int max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:306
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814de7f1-ffffffff814de813: blk_queue_max_segment_size.cold (STB_LOCAL)
ffffffff814de0b0-ffffffff814de0e7: blk_queue_max_segment_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_segment_size(struct request_queue *q, unsigned int max_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:306
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814f7651-ffffffff814f7673: blk_queue_max_segment_size.cold (STB_LOCAL)
ffffffff814f6f10-ffffffff814f6f47: blk_queue_max_segment_size (STB_GLOBAL)
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
