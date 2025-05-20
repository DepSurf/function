# Function: <code>blk_rq_map_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blk_rq_map_user(struct request_queue *q, struct request *rq, struct rq_map_data *map_data, void *ubuf, long unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff813bf610)
Location: block/blk-map.c:143
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_io
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff813bf610-ffffffff813bf692: blk_rq_map_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blk_rq_map_user(struct request_queue *q, struct request *rq, struct rq_map_data *map_data, void *ubuf, long unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81403600)
Location: block/blk-map.c:148
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_io
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff81403600-ffffffff8140368c: blk_rq_map_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blk_rq_map_user(struct request_queue *q, struct request *rq, struct rq_map_data *map_data, void *ubuf, long unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8141d370)
Location: block/blk-map.c:154
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_io
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff8141d370-ffffffff8141d3f2: blk_rq_map_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blk_rq_map_user(struct request_queue *q, struct request *rq, struct rq_map_data *map_data, void *ubuf, long unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8142b3d0)
Location: block/blk-map.c:156
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_io
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff8142b3d0-ffffffff8142b452: blk_rq_map_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_rq_map_user(struct request_queue *q, struct request *rq, struct rq_map_data *map_data, void *ubuf, long unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814565c0)
Location: block/blk-map.c:155
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_io
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814565c0-ffffffff81456642: blk_rq_map_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blk_rq_map_user(struct request_queue *q, struct request *rq, struct rq_map_data *map_data, void *ubuf, long unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81489a00)
Location: block/blk-map.c:155
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_io
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff81489a00-ffffffff81489a82: blk_rq_map_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blk_rq_map_user(struct request_queue *q, struct request *rq, struct rq_map_data *map_data, void *ubuf, long unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814a3840)
Location: block/blk-map.c:155
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814a3840-ffffffff814a38c2: blk_rq_map_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blk_rq_map_user(struct request_queue *q, struct request *rq, struct rq_map_data *map_data, void *ubuf, long unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814d1a40)
Location: block/blk-map.c:161
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814d1a40-ffffffff814d1ac4: blk_rq_map_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blk_rq_map_user(struct request_queue *q, struct request *rq, struct rq_map_data *map_data, void *ubuf, long unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814eadf0)
Location: block/blk-map.c:161
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814eadf0-ffffffff814eae74: blk_rq_map_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blk_rq_map_user(struct request_queue *q, struct request *rq, struct rq_map_data *map_data, void *ubuf, long unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8154ac60)
Location: block/blk-map.c:669
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_start_req
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc
```
**Symbols:**

```
ffffffff8154ac60-ffffffff8154ace4: blk_rq_map_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blk_rq_map_user(struct request_queue *q, struct request *rq, struct rq_map_data *map_data, void *ubuf, long unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81566a20)
Location: block/blk-map.c:620
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_start_req
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc
```
**Symbols:**

```
ffffffff81566a20-ffffffff81566aa4: blk_rq_map_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blk_rq_map_user(struct request_queue *q, struct request *rq, struct rq_map_data *map_data, void *ubuf, long unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8156ef60)
Location: block/blk-map.c:565
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_start_req
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc
```
**Symbols:**

```
ffffffff8156ef60-ffffffff8156efe4: blk_rq_map_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blk_rq_map_user(struct request_queue *q, struct request *rq, struct rq_map_data *map_data, void *ubuf, long unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff815d35a0)
Location: block/blk-map.c:565
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
  - drivers/scsi/sr.c:sr_read_cdda_bpc
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_start_req
```
**Symbols:**

```
ffffffff815d35a0-ffffffff815d3624: blk_rq_map_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blk_rq_map_user(struct request_queue *q, struct request *rq, struct rq_map_data *map_data, void *ubuf, long unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8167f370)
Location: block/blk-map.c:573
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
  - drivers/scsi/sr.c:sr_read_cdda_bpc
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_start_req
```
**Symbols:**

```
ffffffff8167f370-ffffffff8167f43d: blk_rq_map_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int blk_rq_map_user(struct request_queue *q, struct request *rq, struct rq_map_data *map_data, void *ubuf, long unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8173c5f0)
Location: block/blk-map.c:681
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
  - drivers/scsi/sr.c:sr_read_cdda_bpc
```
**Symbols:**

```
ffffffff8173c5f0-ffffffff8173c6bd: blk_rq_map_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int blk_rq_map_user(struct request_queue *q, struct request *rq, struct rq_map_data *map_data, void *ubuf, long unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81778ba0)
Location: block/blk-map.c:680
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
  - drivers/scsi/sr.c:sr_read_cdda_bpc
```
**Symbols:**

```
ffffffff81778ba0-ffffffff81778c58: blk_rq_map_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int blk_rq_map_user(struct request_queue *q, struct request *rq, struct rq_map_data *map_data, void *ubuf, long unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff817baf70)
Location: block/blk-map.c:687
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
  - drivers/scsi/sr.c:sr_read_cdda_bpc
```
**Symbols:**

```
ffffffff817baf70-ffffffff817bb028: blk_rq_map_user (STB_GLOBAL)
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
int blk_rq_map_user(struct request_queue *q, struct request *rq, struct rq_map_data *map_data, void *ubuf, long unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffff8000105e9940)
Location: block/blk-map.c:161
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffff8000105e9940-ffff8000105e99f0: blk_rq_map_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blk_rq_map_user(struct request_queue *q, struct request *rq, struct rq_map_data *map_data, void *ubuf, long unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (c0795c34)
Location: block/blk-map.c:161
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
c0795c34-c0795cd4: blk_rq_map_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blk_rq_map_user(struct request_queue *q, struct request *rq, struct rq_map_data *map_data, void *ubuf, long unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (c00000000077e4e0)
Location: block/blk-map.c:161
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
c00000000077e4e0-c00000000077e5a4: blk_rq_map_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blk_rq_map_user(struct request_queue *q, struct request *rq, struct rq_map_data *map_data, void *ubuf, long unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffe000429d9c)
Location: block/blk-map.c:161
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffe000429d9c-ffffffe000429e0a: blk_rq_map_user (STB_GLOBAL)
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
int blk_rq_map_user(struct request_queue *q, struct request *rq, struct rq_map_data *map_data, void *ubuf, long unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814e33d0)
Location: block/blk-map.c:161
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/nvme/host/core.c:nvme_submit_user_cmd
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814e33d0-ffffffff814e3454: blk_rq_map_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blk_rq_map_user(struct request_queue *q, struct request *rq, struct rq_map_data *map_data, void *ubuf, long unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814d3d50)
Location: block/blk-map.c:161
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/nvme/host/core.c:nvme_submit_user_cmd
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814d3d50-ffffffff814d3dd4: blk_rq_map_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blk_rq_map_user(struct request_queue *q, struct request *rq, struct rq_map_data *map_data, void *ubuf, long unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814df460)
Location: block/blk-map.c:161
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814df460-ffffffff814df4e4: blk_rq_map_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blk_rq_map_user(struct request_queue *q, struct request *rq, struct rq_map_data *map_data, void *ubuf, long unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814f82d0)
Location: block/blk-map.c:161
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814f82d0-ffffffff814f8354: blk_rq_map_user (STB_GLOBAL)
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
