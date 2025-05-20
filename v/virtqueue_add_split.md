# Function: <code>virtqueue_add_split</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816064d2)
Location: drivers/virtio/virtio_ring.c:417
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int virtqueue_add_split(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8163a308)
Location: drivers/virtio/virtio_ring.c:415
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
**Symbols:**

```
ffffffff81638d90-ffffffff8163923b: virtqueue_add_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int virtqueue_add_split(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8165c564)
Location: drivers/virtio/virtio_ring.c:415
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
**Symbols:**

```
ffffffff8165aaf0-ffffffff8165afb3: virtqueue_add_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int virtqueue_add_split(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170ab70)
Location: drivers/virtio/virtio_ring.c:415
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
**Symbols:**

```
ffffffff8170ab70-ffffffff8170b051: virtqueue_add_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int virtqueue_add_split(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff817279c0)
Location: drivers/virtio/virtio_ring.c:415
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
**Symbols:**

```
ffffffff817279c0-ffffffff81727ea1: virtqueue_add_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int virtqueue_add_split(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170b480)
Location: drivers/virtio/virtio_ring.c:415
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
**Symbols:**

```
ffffffff8170b480-ffffffff8170b919: virtqueue_add_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_split(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:478
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
**Symbols:**

```
ffffffff81787560-ffffffff81787b58: virtqueue_add_split (STB_LOCAL)
ffffffff81cf4a19-ffffffff81cf4b28: virtqueue_add_split.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_split(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:470
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
**Symbols:**

```
ffffffff818be700-ffffffff818bed75: virtqueue_add_split (STB_LOCAL)
ffffffff81ebcae8-ffffffff81ebcc47: virtqueue_add_split.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_split(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:517
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
**Symbols:**

```
ffffffff81a0dcd0-ffffffff81a0e35e: virtqueue_add_split (STB_LOCAL)
ffffffff82093f7b-ffffffff820940da: virtqueue_add_split.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_split(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:523
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
**Symbols:**

```
ffffffff81a56c20-ffffffff81a572a1: virtqueue_add_split (STB_LOCAL)
ffffffff82114cc4-ffffffff82114e2c: virtqueue_add_split.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_split(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:544
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
**Symbols:**

```
ffffffff81aa8010-ffffffff81aa86d2: virtqueue_add_split (STB_LOCAL)
ffffffff821f2958-ffffffff821f2a9f: virtqueue_add_split.cold (STB_LOCAL)
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
int virtqueue_add_split(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff8000108254cc)
Location: drivers/virtio/virtio_ring.c:415
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
**Symbols:**

```
ffff8000108227d8-ffff800010822cfc: virtqueue_add_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int virtqueue_add_split(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c094201c)
Location: drivers/virtio/virtio_ring.c:415
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
**Symbols:**

```
c09417c8-c0941d44: virtqueue_add_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int virtqueue_add_split(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008cfd10)
Location: drivers/virtio/virtio_ring.c:415
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
**Symbols:**

```
c0000000008cd720-c0000000008cdd08: virtqueue_add_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int virtqueue_add_split(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe00051a4dc)
Location: drivers/virtio/virtio_ring.c:415
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
**Symbols:**

```
ffffffe00051bc08-ffffffe00051bff0: virtqueue_add_split (STB_LOCAL)
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
int virtqueue_add_split(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81622404)
Location: drivers/virtio/virtio_ring.c:415
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
**Symbols:**

```
ffffffff81620990-ffffffff81620e53: virtqueue_add_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int virtqueue_add_split(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81616a54)
Location: drivers/virtio/virtio_ring.c:415
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
**Symbols:**

```
ffffffff81614fe0-ffffffff816154a3: virtqueue_add_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int virtqueue_add_split(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816503a4)
Location: drivers/virtio/virtio_ring.c:415
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
**Symbols:**

```
ffffffff8164e930-ffffffff8164edf3: virtqueue_add_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int virtqueue_add_split(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8166aa34)
Location: drivers/virtio/virtio_ring.c:415
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
**Symbols:**

```
ffffffff81668fc0-ffffffff81669483: virtqueue_add_split (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
