# Function: <code>blk_execute_rq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blk_execute_rq(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff813bfa20)
Location: block/blk-exec.c:99
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_io
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/bsg.c:bsg_ioctl
  - drivers/block/virtio_blk.c:virtblk_serial_show
  - drivers/scsi/scsi_lib.c:scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff813bfa20-ffffffff813bfb57: blk_execute_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blk_execute_rq(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff81403960)
Location: block/blk-exec.c:99
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_ioctl
  - drivers/block/virtio_blk.c:virtblk_serial_show
  - drivers/scsi/scsi_lib.c:scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff81403960-ffffffff81403a99: blk_execute_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blk_execute_rq(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff8141d6c0)
Location: block/blk-exec.c:99
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff8141d6c0-ffffffff8141d7f9: blk_execute_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_execute_rq(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff8142b6b0)
Location: block/blk-exec.c:94
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_ioctl
  - drivers/scsi/scsi_lib.c:scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff8142b6b0-ffffffff8142b751: blk_execute_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_execute_rq(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff814568c0)
Location: block/blk-exec.c:94
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_ioctl
  - drivers/scsi/scsi_lib.c:scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814568c0-ffffffff81456961: blk_execute_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_execute_rq(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff81489d00)
Location: block/blk-exec.c:94
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_ioctl
  - drivers/scsi/scsi_lib.c:scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff81489d00-ffffffff81489da1: blk_execute_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_execute_rq(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff814a3a60)
Location: block/blk-exec.c:76
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_ioctl
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814a3a60-ffffffff814a3b01: blk_execute_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_execute_rq(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff814d1c90)
Location: block/blk-exec.c:77
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814d1c90-ffffffff814d1d31: blk_execute_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_execute_rq(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff814eb020)
Location: block/blk-exec.c:77
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814eb020-ffffffff814eb0c1: blk_execute_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_execute_rq(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff8154ad60)
Location: block/blk-exec.c:79
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc
```
**Symbols:**

```
ffffffff8154ad60-ffffffff8154ae01: blk_execute_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_execute_rq(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff81566b20)
Location: block/blk-exec.c:79
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc
```
**Symbols:**

```
ffffffff81566b20-ffffffff81566bc1: blk_execute_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_execute_rq(struct gendisk *bd_disk, struct request *rq, int at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff8156f060)
Location: block/blk-exec.c:76
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc
```
**Symbols:**

```
ffffffff8156f060-ffffffff8156f101: blk_execute_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
blk_status_t blk_execute_rq(struct gendisk *bd_disk, struct request *rq, int at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff815d36e0)
Location: block/blk-exec.c:90
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
  - drivers/scsi/sr.c:sr_read_cdda_bpc
```
**Symbols:**

```
ffffffff815d36e0-ffffffff815d37e2: blk_execute_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
blk_status_t blk_execute_rq(struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81684940)
Location: block/blk-mq.c:1258
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
  - drivers/scsi/sr.c:sr_read_cdda_bpc
```
**Symbols:**

```
ffffffff81684940-ffffffff81684b0f: blk_execute_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
blk_status_t blk_execute_rq(struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81742cd0)
Location: block/blk-mq.c:1386
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
  - drivers/scsi/sr.c:sr_read_cdda_bpc
```
**Symbols:**

```
ffffffff81742cd0-ffffffff81742e9f: blk_execute_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
blk_status_t blk_execute_rq(struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817804c0)
Location: block/blk-mq.c:1392
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_lib.c:scsi_execute_cmd
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
  - drivers/scsi/sr.c:sr_read_cdda_bpc
```
**Symbols:**

```
ffffffff817804c0-ffffffff817806e7: blk_execute_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
blk_status_t blk_execute_rq(struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c2a90)
Location: block/blk-mq.c:1395
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_lib.c:scsi_execute_cmd
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
  - drivers/scsi/sr.c:sr_read_cdda_bpc
```
**Symbols:**

```
ffffffff817c2a90-ffffffff817c2cad: blk_execute_rq (STB_GLOBAL)
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
void blk_execute_rq(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffff8000105e9a88)
Location: block/blk-exec.c:77
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/mmc/core/block.c:mmc_ext_csd_open
  - drivers/mmc/core/block.c:mmc_dbg_card_status_get
  - drivers/mmc/core/block.c:mmc_blk_ioctl_multi_cmd
  - drivers/mmc/core/block.c:mmc_blk_ioctl_cmd
```
**Symbols:**

```
ffff8000105e9a88-ffff8000105e9b58: blk_execute_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_execute_rq(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (c0795ee4)
Location: block/blk-exec.c:77
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/mmc/core/block.c:mmc_ext_csd_open
  - drivers/mmc/core/block.c:mmc_dbg_card_status_get
  - drivers/mmc/core/block.c:mmc_blk_ioctl_multi_cmd
  - drivers/mmc/core/block.c:mmc_blk_ioctl_cmd
```
**Symbols:**

```
c0795ee4-c0795fa0: blk_execute_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_execute_rq(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (c00000000077e830)
Location: block/blk-exec.c:77
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
c00000000077e830-c00000000077e918: blk_execute_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_execute_rq(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffe000429f8a)
Location: block/blk-exec.c:77
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/mmc/core/block.c:mmc_ext_csd_open
  - drivers/mmc/core/block.c:mmc_dbg_card_status_get
  - drivers/mmc/core/block.c:mmc_blk_ioctl_multi_cmd
  - drivers/mmc/core/block.c:mmc_blk_ioctl_cmd
```
**Symbols:**

```
ffffffe000429f8a-ffffffe00042a022: blk_execute_rq (STB_GLOBAL)
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
void blk_execute_rq(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff814e3600)
Location: block/blk-exec.c:77
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/nvme/host/core.c:nvme_submit_user_cmd
  - drivers/nvme/host/core.c:__nvme_submit_sync_cmd
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814e3600-ffffffff814e36a1: blk_execute_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_execute_rq(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff814d3f80)
Location: block/blk-exec.c:77
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/nvme/host/core.c:nvme_submit_user_cmd
  - drivers/nvme/host/core.c:__nvme_submit_sync_cmd
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814d3f80-ffffffff814d4021: blk_execute_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_execute_rq(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff814df690)
Location: block/blk-exec.c:77
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814df690-ffffffff814df731: blk_execute_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_execute_rq(struct request_queue *q, struct gendisk *bd_disk, struct request *rq, int at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-exec.c (ffffffff814f8500)
Location: block/blk-exec.c:77
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814f8500-ffffffff814f859a: blk_execute_rq (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct request_queue *q</code>
</li>
<li>
<b>Param reordered. </b>
<code>q, bd_disk, rq, at_head</code> ➡️ <code>bd_disk, rq, at_head</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>blk_status_t</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct gendisk *bd_disk</code>
</li>
<li>
<b>Param reordered. </b>
<code>bd_disk, rq, at_head</code> ➡️ <code>rq, at_head</code>
</li>
<li>
<b>Param type changed. </b>
<code>int at_head</code> ➡️ <code>bool at_head</code>
</li>
</ul>
</details>
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
