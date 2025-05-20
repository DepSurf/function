# Function: <code>blk_queue_virt_boundary</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_queue_virt_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff813be220)
Location: block/blk-settings.c:778
Inline: False
```
**Symbols:**

```
ffffffff813be220-ffffffff813be232: blk_queue_virt_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_queue_virt_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81402180)
Location: block/blk-settings.c:778
Inline: False
```
**Symbols:**

```
ffffffff81402180-ffffffff81402192: blk_queue_virt_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_queue_virt_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8141be30)
Location: block/blk-settings.c:802
Inline: False
```
**Symbols:**

```
ffffffff8141be30-ffffffff8141be42: blk_queue_virt_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_queue_virt_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81429e30)
Location: block/blk-settings.c:814
Inline: False
```
**Symbols:**

```
ffffffff81429e30-ffffffff81429e42: blk_queue_virt_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_queue_virt_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81454ff0)
Location: block/blk-settings.c:815
Inline: False
```
**Symbols:**

```
ffffffff81454ff0-ffffffff81455002: blk_queue_virt_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_queue_virt_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81488460)
Location: block/blk-settings.c:815
Inline: False
```
**Symbols:**

```
ffffffff81488460-ffffffff81488472: blk_queue_virt_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_queue_virt_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814a2480)
Location: block/blk-settings.c:757
Inline: False
```
**Symbols:**

```
ffffffff814a2480-ffffffff814a2492: blk_queue_virt_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_queue_virt_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814d0540)
Location: block/blk-settings.c:745
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814d0540-ffffffff814d0561: blk_queue_virt_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_virt_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814e9fdd)
Location: block/blk-settings.c:746
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_can_use_dma_map_merging
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814e98a0-ffffffff814e98c1: blk_queue_virt_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_virt_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81548e8d)
Location: block/blk-settings.c:707
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_can_use_dma_map_merging
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff815486f0-ffffffff81548711: blk_queue_virt_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_virt_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81564dfd)
Location: block/blk-settings.c:720
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_can_use_dma_map_merging
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff815644c0-ffffffff815644e1: blk_queue_virt_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_virt_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8156d44d)
Location: block/blk-settings.c:717
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_can_use_dma_map_merging
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff8156cc00-ffffffff8156cc21: blk_queue_virt_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_virt_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff815d18ed)
Location: block/blk-settings.c:717
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_can_use_dma_map_merging
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff815d1140-ffffffff815d1161: blk_queue_virt_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_virt_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8167ce9c)
Location: block/blk-settings.c:749
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_can_use_dma_map_merging
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff8167ca90-ffffffff8167cab9: blk_queue_virt_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_virt_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8173992c)
Location: block/blk-settings.c:750
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_can_use_dma_map_merging
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff817393b0-ffffffff817393d9: blk_queue_virt_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_virt_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8177600c)
Location: block/blk-settings.c:756
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_can_use_dma_map_merging
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff81775a80-ffffffff81775aa9: blk_queue_virt_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_virt_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff817b816c)
Location: block/blk-settings.c:758
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_can_use_dma_map_merging
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff817b7d50-ffffffff817b7d79: blk_queue_virt_boundary (STB_GLOBAL)
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
void blk_queue_virt_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffff8000105e8350)
Location: block/blk-settings.c:746
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_can_use_dma_map_merging
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffff8000105e7ad0-ffff8000105e7b08: blk_queue_virt_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_virt_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c0794820)
Location: block/blk-settings.c:746
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_can_use_dma_map_merging
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
c0794478-c07944a0: blk_queue_virt_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_virt_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c00000000077cf88)
Location: block/blk-settings.c:746
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_can_use_dma_map_merging
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
c00000000077c310-c00000000077c330: blk_queue_virt_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_virt_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffe000428fdc)
Location: block/blk-settings.c:746
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_can_use_dma_map_merging
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffe0004287e8-ffffffe00042881a: blk_queue_virt_boundary (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_virt_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814e25bd)
Location: block/blk-settings.c:746
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_can_use_dma_map_merging
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/nvme/host/core.c:nvme_set_queue_limits
```
**Symbols:**

```
ffffffff814e1e80-ffffffff814e1ea1: blk_queue_virt_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_virt_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814d2f4d)
Location: block/blk-settings.c:746
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_can_use_dma_map_merging
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/nvme/host/core.c:nvme_set_queue_limits
```
**Symbols:**

```
ffffffff814d2810-ffffffff814d2831: blk_queue_virt_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_virt_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814de64d)
Location: block/blk-settings.c:746
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_can_use_dma_map_merging
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814ddf10-ffffffff814ddf31: blk_queue_virt_boundary (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_virt_boundary(struct request_queue *q, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814f74ad)
Location: block/blk-settings.c:746
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_can_use_dma_map_merging
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
**Symbols:**

```
ffffffff814f6d70-ffffffff814f6d91: blk_queue_virt_boundary (STB_GLOBAL)
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
