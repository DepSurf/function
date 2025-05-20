# Function: <code>blk_rq_map_kern</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blk_rq_map_kern(struct request_queue *q, struct request *rq, void *kbuf, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff813bf750)
Location: block/blk-map.c:203
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_lib.c:scsi_execute
```
**Symbols:**

```
ffffffff813bf750-ffffffff813bf889: blk_rq_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blk_rq_map_kern(struct request_queue *q, struct request *rq, void *kbuf, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81403690)
Location: block/blk-map.c:208
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/block/virtio_blk.c:virtblk_serial_show
  - drivers/scsi/scsi_lib.c:scsi_execute
```
**Symbols:**

```
ffffffff81403690-ffffffff814037c9: blk_rq_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blk_rq_map_kern(struct request_queue *q, struct request *rq, void *kbuf, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8141d400)
Location: block/blk-map.c:214
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
```
**Symbols:**

```
ffffffff8141d400-ffffffff8141d52d: blk_rq_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blk_rq_map_kern(struct request_queue *q, struct request *rq, void *kbuf, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8142b460)
Location: block/blk-map.c:216
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_lib.c:scsi_execute
```
**Symbols:**

```
ffffffff8142b460-ffffffff8142b57f: blk_rq_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_rq_map_kern(struct request_queue *q, struct request *rq, void *kbuf, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81456650)
Location: block/blk-map.c:215
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_lib.c:scsi_execute
```
**Symbols:**

```
ffffffff81456650-ffffffff81456784: blk_rq_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blk_rq_map_kern(struct request_queue *q, struct request *rq, void *kbuf, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81489a90)
Location: block/blk-map.c:215
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_lib.c:scsi_execute
```
**Symbols:**

```
ffffffff81489a90-ffffffff81489bcb: blk_rq_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blk_rq_map_kern(struct request_queue *q, struct request *rq, void *kbuf, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814a38d0)
Location: block/blk-map.c:215
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_lib.c:__scsi_execute
```
**Symbols:**

```
ffffffff814a38d0-ffffffff814a3a0b: blk_rq_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blk_rq_map_kern(struct request_queue *q, struct request *rq, void *kbuf, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814d1ad0)
Location: block/blk-map.c:221
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_lib.c:__scsi_execute
```
**Symbols:**

```
ffffffff814d1ad0-ffffffff814d1c15: blk_rq_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blk_rq_map_kern(struct request_queue *q, struct request *rq, void *kbuf, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814eae80)
Location: block/blk-map.c:221
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_lib.c:__scsi_execute
```
**Symbols:**

```
ffffffff814eae80-ffffffff814eafc5: blk_rq_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blk_rq_map_kern(struct request_queue *q, struct request *rq, void *kbuf, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81549e70)
Location: block/blk-map.c:729
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_lib.c:__scsi_execute
```
**Symbols:**

```
ffffffff81549e70-ffffffff8154a139: blk_rq_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blk_rq_map_kern(struct request_queue *q, struct request *rq, void *kbuf, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81565c20)
Location: block/blk-map.c:684
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_lib.c:__scsi_execute
```
**Symbols:**

```
ffffffff81565c20-ffffffff81565ee9: blk_rq_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blk_rq_map_kern(struct request_queue *q, struct request *rq, void *kbuf, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8156e0e0)
Location: block/blk-map.c:625
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_lib.c:__scsi_execute
```
**Symbols:**

```
ffffffff8156e0e0-ffffffff8156e4b4: blk_rq_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blk_rq_map_kern(struct request_queue *q, struct request *rq, void *kbuf, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff815d25a0)
Location: block/blk-map.c:625
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_lib.c:__scsi_execute
```
**Symbols:**

```
ffffffff815d25a0-ffffffff815d2974: blk_rq_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blk_rq_map_kern(struct request_queue *q, struct request *rq, void *kbuf, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8167e2c0)
Location: block/blk-map.c:634
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_lib.c:__scsi_execute
```
**Symbols:**

```
ffffffff8167e2c0-ffffffff8167e70d: blk_rq_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blk_rq_map_kern(struct request_queue *q, struct request *rq, void *kbuf, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8173afa0)
Location: block/blk-map.c:777
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_lib.c:__scsi_execute
```
**Symbols:**

```
ffffffff8173afa0-ffffffff8173b3ed: blk_rq_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blk_rq_map_kern(struct request_queue *q, struct request *rq, void *kbuf, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81777850)
Location: block/blk-map.c:775
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_lib.c:scsi_execute_cmd
```
**Symbols:**

```
ffffffff81777850-ffffffff81777af5: blk_rq_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blk_rq_map_kern(struct request_queue *q, struct request *rq, void *kbuf, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff817b9a70)
Location: block/blk-map.c:782
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_lib.c:scsi_execute_cmd
```
**Symbols:**

```
ffffffff817b9a70-ffffffff817b9d15: blk_rq_map_kern (STB_GLOBAL)
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
int blk_rq_map_kern(struct request_queue *q, struct request *rq, void *kbuf, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffff8000105e95a8)
Location: block/blk-map.c:221
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_lib.c:__scsi_execute
```
**Symbols:**

```
ffff8000105e95a8-ffff8000105e9740: blk_rq_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blk_rq_map_kern(struct request_queue *q, struct request *rq, void *kbuf, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (c0795cd4)
Location: block/blk-map.c:221
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_lib.c:__scsi_execute
```
**Symbols:**

```
c0795cd4-c0795e4c: blk_rq_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blk_rq_map_kern(struct request_queue *q, struct request *rq, void *kbuf, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (c00000000077e5b0)
Location: block/blk-map.c:221
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_lib.c:__scsi_execute
```
**Symbols:**

```
c00000000077e5b0-c00000000077e7ac: blk_rq_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blk_rq_map_kern(struct request_queue *q, struct request *rq, void *kbuf, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffe000429e0a)
Location: block/blk-map.c:221
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_lib.c:__scsi_execute
```
**Symbols:**

```
ffffffe000429e0a-ffffffe000429f24: blk_rq_map_kern (STB_GLOBAL)
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
int blk_rq_map_kern(struct request_queue *q, struct request *rq, void *kbuf, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814e3460)
Location: block/blk-map.c:221
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/nvme/host/core.c:__nvme_submit_sync_cmd
  - drivers/nvme/host/lightnvm.c:nvme_nvm_submit_io
```
**Symbols:**

```
ffffffff814e3460-ffffffff814e35a5: blk_rq_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blk_rq_map_kern(struct request_queue *q, struct request *rq, void *kbuf, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814d3de0)
Location: block/blk-map.c:221
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/nvme/host/core.c:__nvme_submit_sync_cmd
```
**Symbols:**

```
ffffffff814d3de0-ffffffff814d3f25: blk_rq_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blk_rq_map_kern(struct request_queue *q, struct request *rq, void *kbuf, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814df4f0)
Location: block/blk-map.c:221
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_lib.c:__scsi_execute
```
**Symbols:**

```
ffffffff814df4f0-ffffffff814df635: blk_rq_map_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blk_rq_map_kern(struct request_queue *q, struct request *rq, void *kbuf, unsigned int len, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814f8360)
Location: block/blk-map.c:221
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_lib.c:__scsi_execute
```
**Symbols:**

```
ffffffff814f8360-ffffffff814f84a5: blk_rq_map_kern (STB_GLOBAL)
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
