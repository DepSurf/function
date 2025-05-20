# Function: <code>blk_get_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct request *blk_get_request(struct request_queue *q, int rw, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b9530)
Location: block/blk-core.c:1292
Inline: False
Direct callers:
  - block/blk-core.c:blk_make_request
  - block/scsi_ioctl.c:sg_io
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_lib.c:scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff813b9530-ffffffff813b9615: blk_get_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct request *blk_get_request(struct request_queue *q, int rw, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fd3a0)
Location: block/blk-core.c:1311
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - drivers/block/virtio_blk.c:virtblk_serial_show
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_lib.c:scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff813fd3a0-ffffffff813fd4c4: blk_get_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct request *blk_get_request(struct request_queue *q, int rw, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81416d00)
Location: block/blk-core.c:1312
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff81416d00-ffffffff81416e1d: blk_get_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct request *blk_get_request(struct request_queue *q, unsigned int op, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81424400)
Location: block/blk-core.c:1415
Inline: True
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_lib.c:scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff81424400-ffffffff81424502: blk_get_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct request *blk_get_request(struct request_queue *q, unsigned int op, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81450070)
Location: block/blk-core.c:1533
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff81450070-ffffffff81450089: blk_get_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct request *blk_get_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814830b0)
Location: block/blk-core.c:1615
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_lib.c:scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814830b0-ffffffff81483268: blk_get_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct request *blk_get_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149cf60)
Location: block/blk-core.c:575
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_ioctl
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff8149cf60-ffffffff8149cfbd: blk_get_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct request *blk_get_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cb0f0)
Location: block/blk-core.c:573
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814cb0f0-ffffffff814cb14d: blk_get_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct request *blk_get_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e42e0)
Location: block/blk-core.c:577
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814e42e0-ffffffff814e433d: blk_get_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct request *blk_get_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81542a10)
Location: block/blk-core.c:619
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/scsi_error.c:scsi_eh_lock_door
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/scsi/sg.c:sg_start_req
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc
```
**Symbols:**

```
ffffffff81542a10-ffffffff81542a6d: blk_get_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct request *blk_get_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155f370)
Location: block/blk-core.c:628
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/scsi_error.c:scsi_eh_lock_door
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/scsi/sg.c:sg_start_req
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc
```
**Symbols:**

```
ffffffff8155f370-ffffffff8155f3cd: blk_get_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct request *blk_get_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81567be0)
Location: block/blk-core.c:629
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/scsi/sg.c:sg_start_req
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc
```
**Symbols:**

```
ffffffff81567be0-ffffffff81567c3d: blk_get_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct request *blk_get_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815cc210)
Location: block/blk-core.c:627
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
  - drivers/scsi/sr.c:sr_read_cdda_bpc
  - drivers/scsi/sg.c:sg_start_req
```
**Symbols:**

```
ffffffff815cc210-ffffffff815cc26d: blk_get_request (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct request *blk_get_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e04e8)
Location: block/blk-core.c:577
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/mmc/core/block.c:mmc_ext_csd_open
  - drivers/mmc/core/block.c:mmc_dbg_card_status_get
  - drivers/mmc/core/block.c:mmc_blk_ioctl_multi_cmd
  - drivers/mmc/core/block.c:mmc_blk_ioctl_cmd
```
**Symbols:**

```
ffff8000105e04e8-ffff8000105e0578: blk_get_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct request *blk_get_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c078e744)
Location: block/blk-core.c:577
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/mmc/core/block.c:mmc_ext_csd_open
  - drivers/mmc/core/block.c:mmc_dbg_card_status_get
  - drivers/mmc/core/block.c:mmc_blk_ioctl_multi_cmd
  - drivers/mmc/core/block.c:mmc_blk_ioctl_cmd
```
**Symbols:**

```
c078e744-c078e814: blk_get_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct request *blk_get_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000774760)
Location: block/blk-core.c:577
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
c000000000774760-c000000000774828: blk_get_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct request *blk_get_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe0004239fe)
Location: block/blk-core.c:577
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/mmc/core/block.c:mmc_ext_csd_open
  - drivers/mmc/core/block.c:mmc_dbg_card_status_get
  - drivers/mmc/core/block.c:mmc_blk_ioctl_multi_cmd
  - drivers/mmc/core/block.c:mmc_blk_ioctl_cmd
```
**Symbols:**

```
ffffffe0004239fe-ffffffe000423a66: blk_get_request (STB_GLOBAL)
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
struct request *blk_get_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814dc8c0)
Location: block/blk-core.c:577
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814dc8c0-ffffffff814dc91d: blk_get_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct request *blk_get_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cd270)
Location: block/blk-core.c:577
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814cd270-ffffffff814cd2cd: blk_get_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct request *blk_get_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d8950)
Location: block/blk-core.c:577
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814d8950-ffffffff814d89ad: blk_get_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct request *blk_get_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f1560)
Location: block/blk-core.c:577
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814f1560-ffffffff814f15bd: blk_get_request (STB_GLOBAL)
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
<b>Param added. </b>
<code>unsigned int op</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>blk_mq_req_flags_t flags</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
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
