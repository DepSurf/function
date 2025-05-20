# Function: <code>blk_queue_io_min</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_queue_io_min(struct request_queue *q, unsigned int min);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff813be170)
Location: block/blk-settings.c:442
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff813be170-ffffffff813be1a6: blk_queue_io_min (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_queue_io_min(struct request_queue *q, unsigned int min);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814020d0)
Location: block/blk-settings.c:442
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff814020d0-ffffffff81402104: blk_queue_io_min (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_queue_io_min(struct request_queue *q, unsigned int min);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8141bd80)
Location: block/blk-settings.c:460
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff8141bd80-ffffffff8141bdb4: blk_queue_io_min (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_queue_io_min(struct request_queue *q, unsigned int min);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81429d40)
Location: block/blk-settings.c:471
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff81429d40-ffffffff81429d74: blk_queue_io_min (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_queue_io_min(struct request_queue *q, unsigned int min);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81454f00)
Location: block/blk-settings.c:472
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff81454f00-ffffffff81454f34: blk_queue_io_min (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_queue_io_min(struct request_queue *q, unsigned int min);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81488370)
Location: block/blk-settings.c:472
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff81488370-ffffffff814883a4: blk_queue_io_min (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_queue_io_min(struct request_queue *q, unsigned int min);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814a2390)
Location: block/blk-settings.c:416
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff814a2390-ffffffff814a23c4: blk_queue_io_min (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_queue_io_min(struct request_queue *q, unsigned int min);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814d0470)
Location: block/blk-settings.c:420
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff814d0470-ffffffff814d04a4: blk_queue_io_min (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_queue_io_min(struct request_queue *q, unsigned int min);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814e97d0)
Location: block/blk-settings.c:421
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff814e97d0-ffffffff814e9803: blk_queue_io_min (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_queue_io_min(struct request_queue *q, unsigned int min);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81548660)
Location: block/blk-settings.c:414
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/scsi/sd.c:sd_read_block_limits
```
**Symbols:**

```
ffffffff81548660-ffffffff81548693: blk_queue_io_min (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_queue_io_min(struct request_queue *q, unsigned int min);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81564420)
Location: block/blk-settings.c:438
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/scsi/sd.c:sd_read_block_limits
```
**Symbols:**

```
ffffffff81564420-ffffffff81564453: blk_queue_io_min (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_queue_io_min(struct request_queue *q, unsigned int min);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8156cb70)
Location: block/blk-settings.c:433
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/scsi/sd.c:sd_read_block_limits
```
**Symbols:**

```
ffffffff8156cb70-ffffffff8156cb97: blk_queue_io_min (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_queue_io_min(struct request_queue *q, unsigned int min);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff815d10a0)
Location: block/blk-settings.c:437
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/scsi/sd.c:sd_read_block_limits
```
**Symbols:**

```
ffffffff815d10a0-ffffffff815d10c7: blk_queue_io_min (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_queue_io_min(struct request_queue *q, unsigned int min);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8167c9b0)
Location: block/blk-settings.c:436
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff8167c9b0-ffffffff8167c9e3: blk_queue_io_min (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_queue_io_min(struct request_queue *q, unsigned int min);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81739290)
Location: block/blk-settings.c:436
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff81739290-ffffffff817392c3: blk_queue_io_min (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_queue_io_min(struct request_queue *q, unsigned int min);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81775960)
Location: block/blk-settings.c:442
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
```
**Symbols:**

```
ffffffff81775960-ffffffff81775993: blk_queue_io_min (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_queue_io_min(struct request_queue *q, unsigned int min);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff817b7c30)
Location: block/blk-settings.c:445
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
```
**Symbols:**

```
ffffffff817b7c30-ffffffff817b7c63: blk_queue_io_min (STB_GLOBAL)
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
void blk_queue_io_min(struct request_queue *q, unsigned int min);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffff8000105e7978)
Location: block/blk-settings.c:421
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sd.c:sd_read_block_limits
```
**Symbols:**

```
ffff8000105e7978-ffff8000105e79cc: blk_queue_io_min (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_queue_io_min(struct request_queue *q, unsigned int min);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c07943a0)
Location: block/blk-settings.c:421
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
c07943a0-c07943d8: blk_queue_io_min (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_queue_io_min(struct request_queue *q, unsigned int min);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c00000000077c250)
Location: block/blk-settings.c:421
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
c00000000077c250-c00000000077c284: blk_queue_io_min (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_queue_io_min(struct request_queue *q, unsigned int min);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffe0004286ca)
Location: block/blk-settings.c:421
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffe0004286ca-ffffffe00042870e: blk_queue_io_min (STB_GLOBAL)
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
void blk_queue_io_min(struct request_queue *q, unsigned int min);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814e1db0)
Location: block/blk-settings.c:421
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_update_disk_info
```
**Symbols:**

```
ffffffff814e1db0-ffffffff814e1de3: blk_queue_io_min (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_queue_io_min(struct request_queue *q, unsigned int min);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814d2740)
Location: block/blk-settings.c:421
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_update_disk_info
```
**Symbols:**

```
ffffffff814d2740-ffffffff814d2773: blk_queue_io_min (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_queue_io_min(struct request_queue *q, unsigned int min);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814dde40)
Location: block/blk-settings.c:421
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff814dde40-ffffffff814dde73: blk_queue_io_min (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_queue_io_min(struct request_queue *q, unsigned int min);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814f6ca0)
Location: block/blk-settings.c:421
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff814f6ca0-ffffffff814f6cd3: blk_queue_io_min (STB_GLOBAL)
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
