# Function: <code>blk_queue_segment_boundary</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_queue_segment_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff813be5a0)
Location: block/blk-settings.c:761
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff813be5a0-ffffffff813be5df: blk_queue_segment_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_queue_segment_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81402520)
Location: block/blk-settings.c:761
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81402520-ffffffff8140255f: blk_queue_segment_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_queue_segment_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8141c1a0)
Location: block/blk-settings.c:785
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff8141c1a0-ffffffff8141c1df: blk_queue_segment_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_queue_segment_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8142a0f0)
Location: block/blk-settings.c:797
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff8142a0f0-ffffffff8142a12f: blk_queue_segment_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_queue_segment_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81455330)
Location: block/blk-settings.c:798
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81455330-ffffffff8145536f: blk_queue_segment_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void blk_queue_segment_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:798
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81488e0f-ffffffff81488e31: blk_queue_segment_boundary.cold.10 (STB_LOCAL)
ffffffff814886d0-ffffffff814886f4: blk_queue_segment_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void blk_queue_segment_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:740
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814a2d0f-ffffffff814a2d31: blk_queue_segment_boundary.cold.9 (STB_LOCAL)
ffffffff814a25f0-ffffffff814a2614: blk_queue_segment_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void blk_queue_segment_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:728
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814d0d9f-ffffffff814d0dc1: blk_queue_segment_boundary.cold (STB_LOCAL)
ffffffff814d0690-ffffffff814d06b4: blk_queue_segment_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void blk_queue_segment_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:729
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814ea15f-ffffffff814ea181: blk_queue_segment_boundary.cold (STB_LOCAL)
ffffffff814e9a10-ffffffff814e9a34: blk_queue_segment_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void blk_queue_segment_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:690
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81549101-ffffffff81549123: blk_queue_segment_boundary.cold (STB_LOCAL)
ffffffff81548860-ffffffff81548887: blk_queue_segment_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void blk_queue_segment_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:703
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81bf2733-ffffffff81bf2755: blk_queue_segment_boundary.cold (STB_LOCAL)
ffffffff81564640-ffffffff81564667: blk_queue_segment_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void blk_queue_segment_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:700
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81be46fa-ffffffff81be471c: blk_queue_segment_boundary.cold (STB_LOCAL)
ffffffff8156cd10-ffffffff8156cd37: blk_queue_segment_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void blk_queue_segment_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:700
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81cd819d-ffffffff81cd81bf: blk_queue_segment_boundary.cold (STB_LOCAL)
ffffffff815d1260-ffffffff815d1287: blk_queue_segment_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void blk_queue_segment_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:732
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81e8b563-ffffffff81e8b585: blk_queue_segment_boundary.cold (STB_LOCAL)
ffffffff8167cc50-ffffffff8167cc83: blk_queue_segment_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_queue_segment_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81739620)
Location: block/blk-settings.c:733
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81739620-ffffffff81739685: blk_queue_segment_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_queue_segment_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81775cf0)
Location: block/blk-settings.c:739
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81775cf0-ffffffff81775d55: blk_queue_segment_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_queue_segment_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff817b7fc0)
Location: block/blk-settings.c:742
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff817b7fc0-ffffffff817b8025: blk_queue_segment_boundary (STB_GLOBAL)
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
void blk_queue_segment_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffff8000105e7c68)
Location: block/blk-settings.c:729
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffff8000105e7c68-ffff8000105e7cc0: blk_queue_segment_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_queue_segment_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c0794608)
Location: block/blk-settings.c:729
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
c0794608-c0794654: blk_queue_segment_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_queue_segment_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c00000000077c4a0)
Location: block/blk-settings.c:729
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
c00000000077c4a0-c00000000077c510: blk_queue_segment_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_queue_segment_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffe00042894e)
Location: block/blk-settings.c:729
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffe00042894e-ffffffe0004289a8: blk_queue_segment_boundary (STB_GLOBAL)
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
void blk_queue_segment_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:729
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814e273f-ffffffff814e2761: blk_queue_segment_boundary.cold (STB_LOCAL)
ffffffff814e1ff0-ffffffff814e2014: blk_queue_segment_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void blk_queue_segment_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:729
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814d30cf-ffffffff814d30f1: blk_queue_segment_boundary.cold (STB_LOCAL)
ffffffff814d2980-ffffffff814d29a4: blk_queue_segment_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void blk_queue_segment_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:729
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814de7cf-ffffffff814de7f1: blk_queue_segment_boundary.cold (STB_LOCAL)
ffffffff814de080-ffffffff814de0a4: blk_queue_segment_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void blk_queue_segment_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:729
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814f762f-ffffffff814f7651: blk_queue_segment_boundary.cold (STB_LOCAL)
ffffffff814f6ee0-ffffffff814f6f04: blk_queue_segment_boundary (STB_GLOBAL)
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
